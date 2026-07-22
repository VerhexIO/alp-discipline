# Alp Discipline

*Bir sınırla karşılaştığın an için bir karar disiplini.*

> **Kaynak dil notu:** Türkçe, disiplinin kaynak dilidir; v1.0 çekirdeği bu dilde yazıldı ve
> donduruldu (2026-07-18). Yayın kanonu kök dizindeki İngilizce metindir. Bir fark görürseniz
> lütfen issue açın.

## Nedir

Alp Discipline'in tek işi vardır: bir insanın ya da bir AI ajanının bir sınırla karşılaştığı
anda daha doğru karar vermesini sağlamak. Bir proje yönetimi metodu, zanaat kılavuzu veya
uyum standardı **değildir.** Seremoni, araç ya da checklist dayatmaz; karar yetkisini
sahipten uygulayıcıya taşımaz. İyi niyetli, yetkin bir uygulayıcının kendi kendine
çıkaramayacağı tek şeyi öğretir; gerisini onun yargısına bırakır.

## Kimin için

Alan, sektör ve rol fark etmeksizin herkes için: mühendis, araştırmacı, operasyon
koordinatörü, solo kurucu ya da bir AI ajanı. Teknik geçmiş gerektirmez.

## Nasıl okunur (5 dakika)

| Dosya | Nedir | Süre |
|---|---|---|
| [ESSENCE.md](ESSENCE.md) | Tek sıkıştırılmış yüzey: dört ilke, beş soru, dört taban | 1 dk |
| [DISCIPLINE.md](DISCIPLINE.md) | Kanon: amaç, yedi tanım, dört ilke ve disiplinin kendi non-goal'leri | 5 ila 8 dk |
| [APPLYING.md](APPLYING.md) | İsteğe bağlı mekanikler; hiçbiri zorunlu değildir | gerektiğinde |
| [EXAMPLES.md](EXAMPLES.md) | Alanlar arası işlenmiş örnekler: araştırma, operasyon, gazetecilik, yazılım | gerektiğinde |

## Dört ilke tek bakışta

*(Bu bir tanıtım özetidir. Tek yetkili sıkıştırılmış yüzey [ESSENCE.md](ESSENCE.md)'dir.)*

1. **Önce negatif alanı çiz.** Ne *yapmayacağını* adlandır ve taşıyıcı sınırları, ihlallerini
   hayal ederek anladığını kanıtla.
2. **Genişleme gereksinime verilir, yaklaşıma değil.** Yaklaşımını engelleyen sınır işini
   yapıyordur. Gereksinimi yalnız tükenmiş alternatifler kanıtlar ve genişlemeyi asla kendine
   vermezsin.
3. **Kayba giden rotada dürüst duruş.** Doğrulanmış kanıtı ve en küçük karşı öneriyi karar
   sahibine taşı. Sessiz uygulama asla kabul edilmez.
4. **Doğru irtifa, kalıcı adım.** İşin bir yama mı, dilim mi (sınırlı ama bütünlüklü bir
   değişiklik), tasarım mı yoksa anayasa işi mi olduğunu beyan et. Her adım kalıcı olarak
   ilerletir ve geçiştirme hiçbir irtifada meşru değildir.

## AI ajanları için

Ajanına **ESSENCE.md'yi bütün ve değiştirilmemiş** ver. ESSENCE, ajanın tek kanonik Alp
Discipline yüzeyidir ve ajanın zaten sahip olduğu daha öncelikli bütün kısıtların içinde
çalışır: sistem ve güvenlik politikaları, hukuk ve açıkça verilmiş yetki. Beş soru ajana
*nasıl düşüneceğini*, dört taban *neyi asla yapmayacağını* söyler. Tam olarak tek bir
sıkıştırılmış yüzey tut, çünkü paralel varyantlar birbirinden uzaklaşır.

## Uygulamalar (implementations)

Disiplin tek ve basit kalır; uygulamaları sınırsız olabilir. Entegrasyonlar, ajan prompt
şablonları, şemalar ve kurumsal benimseme modelleri ayrı repolara aittir, bu repoya değil.
Bu repo hiçbir aracı, ürünü veya organizasyonu adlandırmaz, çünkü disiplin her ortama
uyarlanabilir kalmalıdır.

## Durum

**v1.0.2.** Çekirdek 2026-07-18'de donduruldu; kullanım kanıtına dayanan ilk değişiklik
2026-07-22'de onaylandı. Metin yalnız kullanım kanıtıyla yeniden açılır; bu, disiplinin kendi
İlke 2'sinin kendine uygulanmasıdır. Metne yapılan her değişiklik
[AMENDMENTS.md](../../AMENDMENTS.md) dosyasına kaydedilir; değişiklik prosedürü
[GOVERNANCE.md](../../GOVERNANCE.md) dosyasında tanımlıdır.

## Lisans ve atıf

[MIT](../../LICENSE). Alperen Sartacoglu tarafından oluşturuldu; bkz.
[ACKNOWLEDGEMENTS.md](../../ACKNOWLEDGEMENTS.md). ESSENCE.md'yi makine tarafından tüketilen
bir prompt'a gömerken atıf gösterimi aranmaz.
