# Alp Discipline

> **Kaynak-dil notu:** Türkçe, disiplinin kaynak dilidir — v1.0 çekirdeği bu dilde yazıldı ve
> donduruldu (Alperen-onayı, 2026-07-18). Yayın-kanonu kök dizindeki İngilizce metindir
> (`/DISCIPLINE.md`); iki metin arasında bir fark görürseniz bu bir çatal değil, bir hatadır —
> lütfen issue açın.

## Amaç

Bu bir karar disiplinidir — proje-yönetim metodu, zanaat kılavuzu veya uyum-standardı değil.
Tek işi vardır: **bir insanın ya da bir AI ajanının bir sınırla karşılaştığı anda daha doğru
karar vermesini sağlamak.** Nasıl uygulanacağını okuyucuya bırakır; kendi bürokrasisini
üretmez. **Alan, sektör ve rol fark etmeksizin** — bir insan da, bir AI ajanı da — aynı dört
ilkeyi okuyup kendi bağlamında ne yapacağını çıkarabilmelidir.

## Yedi taşıyıcı tanım

- **Sınır** — geçilmemesi kararlaştırılmış çizgi. Yumuşak (gerekçeyle sapılabilir), sert
  (yalnız gereksinim açar) veya temel/değişimi-özel-sürece-bağlı olabilir.
- **Sahip** — bir sınır üzerinde *bugün* yorumlama ve değiştirme yetkisi olan taraf; sınırı ilk
  koyanla aynı olmak zorunda değildir (**köken ≠ yetki**). Bağlama göre değişir: amir, müşteri,
  etik-kurul, fon-veren — ya da solo çalışmada bir başka anki *sen* (bkz. İlke 2).
- **Hedef ≠ yaklaşım** — hedef *ne* başarmak istediğin; yaklaşım *nasıl* denediğin. İkisini
  ayırmak bu disiplinin en çok işe yarayan tek hamlesidir.
- **Gereksinim** — hedefin nesnel olarak *zorunlu* kıldığı şey. Tercih değildir; rahatsızlık
  değildir; "başka yol yok" demek değildir — tükenmiş alternatiflerle *kanıtlanan* şeydir.
- **Kayıp** — bilinçli-yetkili bir ödünleşme *değil*, **beyan edilmiş hedefe veya kabul edilmiş
  ölçüte** karşı doğrulanabilir bir kötüleşme (başta öngörülmemiş olabilir; süreç içinde görünür
  hale gelmesi yeter). Kabul edilmiş trade-off'u "kayıp" diye işaretlemek disiplinin
  suistimalidir. Hedef beyan edilmemiş ve ölçüt kabul edilmemişse kayıp doğrulanamaz ve İlke 3
  ateşlenemez — ilk hamle hedefi beyan ettirmektir.
- **İrtifa** — kararın *ne kadar büyük* olduğu değil, **hangi seviyedeki gerçeği değiştirdiği:**
  yerel müdahale (*yama*) · sınırlı ama bütünlüklü değişiklik (*dilim*) · sistem-düzeyi değişiklik
  (*tasarım*) · kural/yönetişim değişikliği (*anayasa*).
- **Non-goal** — bilinçli olarak *yapmayacağın* şey. Geçerli bir non-goal'un çekim kuvveti
  vardır (söylenmeseydi biri yapardı); onu adlandırmak gerçek bir karardır.

---

## İlke 1 — Önce negatif alanı çiz

Pozitif tasarım sonsuz yöne açılabilir; onu işe dönüştüren negatif alandır. Ve bir sınırı
*listelemek* ile *anlamak* aynı şey değildir: **hayalinde ihlal edemediğin bir sınırı
anlamamışsındır.** O yüzden ne yapacağını tasarlamadan önce ne yapmayacağını adlandır — ve
taşıyıcı/en-riskli sınırlar için gerçekçi bir ihlal örneği vererek anladığını kanıtla.

Bir non-goal'un geçerli olup olmadığını üç soru söyler: **çekim kuvveti** (söylenmeseydi yetkin
uygulayıcı yapar mıydı?) · **karar bilgisi** (dışarıda bırakmak gerçek bir karar mıydı?) ·
**gözlemlenebilir ihlal** (gerçekleşse fark edilir miydi?). Bir non-goal'ü kaldırmak da bir
sınır-değişikliğidir; sessizce düşürülmez.

*Anti-pattern:* boş non-goal · ihlal-koşulsuz liste · ritüel doldurma.

## İlke 2 — Genişleme gereksinime verilir, yaklaşıma değil

Resmî bir istisna yolu var olduğu anda sınırın psikolojisi değişir — duvar müzakere masasına
dönebilir. Bu yüzden mekanizmanın nesnesi **ihlal değil, gereksinimdir.** **Sınırın canını
acıtması, yanlışlığının kanıtı değildir; çoğunlukla çalıştığının kanıtıdır** — *ama yalnız
çoğunlukla:* bazen acı, sınırın yanlış kurulduğunu gösterir, ve o vaka İlke 3'ün konusudur.

Sınır seni engellediğinde sırayla:

1. **Neyi engelliyor — yaklaşımını mı, hedefi mi?** Yasak soru "*bu sınırı nasıl aşarım?*";
   zorunlu soru "*hedef tam olarak neyi gerektiriyor?*". Sınır yaklaşımını engelliyorsa işini
   yapıyordur; tek meşru hamle sınır içinde başka yaklaşım aramaktır — vakaların çoğu burada
   biter.
2. **Gereksinim, tükenmiş alternatiflerle kanıtlanır** — tercih değil, tükenme. Arama derinliği
   kararın etkisine ve geri-döndürülebilirliğine orantılıdır (sonsuz araştırma da karar-felci
   de kaçıştır).
3. **Tek-seferliği yapısaldan ayır.** Tek-seferlik gereksinim gerekçelendirilir ve **emsal
   oluşturmaz** — "geçen sefer verilmişti" bir gerekçe değildir; emsal-zinciri sınır-çürümesinin
   ta kendisidir. Yapısal (tekrarlayan) gereksinim istisna biriktirmez; **sınırın kendisini
   değiştirir.**

**Kendine genişleme verme.** Kararı sınırın sahibi verir; sen yalnız taşırsın — mekanizma bir
yetki değil, bir *ses kanalıdır.* **Sahip sensen ayrım zamansaldır** (solo çalışmanın çoğunluk
vakası): karar-veren-sen ile uygulayan-sen aynı an değildir; kaydı bırakmak, uygulama-kipindeki
seni karar-kipindeki sana taşır — bu yüzden *"ben sahibim, o hâlde serbestim"* bu ilkeyi ters
okumaktır. (Kayıt alanları, süre-dolumu, tekrar-eşiği gibi mekanikler zorunlu değildir; isteyen
için APPLYING.md'de.)

*Anti-pattern:* emsal göstermek · yaklaşımın acısını gereksinim diye anlatmak · tüketim-kanıtı
olmadan "başka yol yok" demek.

## İlke 3 — Kayba giden rotada dürüst duruş

En pahalı kayıplar, birilerinin gördüğü ama söylemediği kayıplardır. Bu ilke **yukarı-yönlü
dürüstlüğü lisanslar:** yön-koyana kanıtlı itiraz, sadakatin en yüksek biçimidir.

Ayrım önce yapılır: *yaklaşımının* engellenmesi İlke 2'dir; **rotanın/hedefin kendisinin**
kayba gitmesi İlke 3'tür. Duruş kanıt-kapılıdır — **rahatsızlık kanıt değildir, doğrulama
kanıttır.** Doğrulanmış kanıt mevcut rotanın kayba gittiğini gösteriyorsa, rotayı kim koymuş
olursa olsun (süreç sahibi, müşteri, amir, kullanıcı dahil) **uygulamadan önce dur**; kanıtı ve
**en küçük karşı-öneriyi** karar sahibine ilet — ve *"hiç yapmama"* geçerli bir karşı-öneridir.

**Karar sahibinde kalır.** **Yetki alanı içinde**, bilgilendirilmiş ısrar sahibin hakkıdır;
disiplinin garantisi itaatsizlik değil, **kanıtın karardan önce sahibine ulaşmış olmasıdır.**
Sonrası: uygula (kayıt düşerek) ya da resmî çekil — bir AI ajanı için çekilmenin karşılığı
güvenli-durup konuyu sahibine bırakmaktır. **Asla** sessiz uygulama, sessiz sabotaj, gizli
yavaşlatma.

**Üstün normlar (tek hüküm):** Hiçbir karar sahibi; hukuka aykırılığı, insan güvenliğine açık
zararı, temel hak ihlalini veya bilerek yanıltmayı yalnızca **ısrar ederek** meşru kılamaz —
bu dört norm disiplinin taşınmaz zeminidir. Disiplin bu noktada saf-prosedür değildir.

**Zararı sınırlama (tek hüküm):** Aktif ve geri-döndürülemez zarar ilerliyorsa (çöken sistem,
ilerleyen veri kaybı, istismar edilen açık), yetkini genişletmeden önce **zararı en dar ve
güvenli biçimde sınırla**, sonra kararı yetkiliye taşı. Bu bir genişleme değil, triyajdır. Bir
AI ajanı için varsayılan **güvenli-durmadır**; ötesi ancak açıkça verilmişse. (Mekanik ve
eskalasyon-kanalları: APPLYING.md.)

*Anti-pattern:* bilinen-kötüyü sessizce uygulamak · his-temelli itiraz · karşı-önerisiz ret ·
İlke-3'ü İlke-2'nin kanıt-yükünden kaçış-kapısı yapmak.

## İlke 4 — Doğru irtifa, kalıcı adım

Yanlış-irtifa birinci-sınıf hatadır: anayasa-işini yama diye yapmak felaket, yamayı anayasa-işi
diye yapmak felçtir. **İrtifa "ne kadar iş", kalıcılık "hangi dürüstlükte iş" sorusudur — bu iki
şey tek ilkede birleşir, çünkü geçiştirmenin en verimli üreteci yanlış-irtifadır.** O yüzden işe
başlamadan **irtifanı beyan et** — yama · dilim · tasarım · anayasa. Adım boyunu bilinçli seç;
ve **karar-olgunluğunu çift yönlü sor:** *"Bu karar şimdi olgun mu? Beklemek hangi kanıtı satın
alır; gecikmek hangi kaybı yaratır?"* — bu soru **kanıt-yeterliliği** hakkındadır, takvim
hakkında değil.

İrtifa değişiyorsa yeniden beyan et; **sessiz irtifa-kayması yasaktır.** Ve düşük irtifa, üst
sınıf bir sınırı aşma yetkisi üretmez: **"bu yalnız küçük bir yama" bir yetki cümlesi
değildir** — iş temel bir sınıra dokunduğu anda yeniden sınıflandırılır ya da durur.

Her adım **kalıcı olarak ilerletmeli:** sessiz borç yok, sahte tamamlanma yok, kalan iş
adlandırılmış. Kalıcı ilerleme yalnız çalışan-çıktı değildir — **belirsizliğin azalması, yanlış
hipotezin elenmesi, tehlikeli yolun kayıtla kapanması da kalıcı ilerlemedir.** Geçiştirmek
hiçbir irtifada meşru değildir.

*Anti-pattern:* süresiz "geçici" çözüm · tamamlanma tiyatrosu · beyansız irtifa-kayması ·
"küçük yama" diyerek temel sınıra dokunmak.

---

## Disiplinin kendi non-goal'leri

*(kendi İlke-1'ini uyguluyor — davranış-tabanlı ihlal göstergeleriyle:)*

- **Proje-yönetim metodu değildir** — *ihlal:* seremoni/rol/kadans zorunlu kılan hüküm.
- **Zanaat disiplini değildir** — *ihlal:* araç/teknoloji/üslubu evrensel ilke diye dayatmak.
- **Uyum-checklist'i değildir** — *ihlal:* anlama-testlerini kutucuğa indirmek.
- **Yetki devri değildir** — *ihlal:* karar yetkisini sahipten uygulayıcıya taşıyan okuma.
- **Zamanlama/önceliklendirme yönetimi değildir** — *ihlal:* metne takvim/kadans/öncelik kuralı.

## AI ve özet yüzeyi

Bir AI ajanının (veya hızlı-hatırlamanın) tüketeceği yüzey **tektir** ve ayrı tutulur:
dört-madde çapa + beş yönlendirme-sorusu + **dört taban-kısıt**, hepsi tek yerde → **ESSENCE.md**.
Bu dosya (DISCIPLINE.md) kanondur; ESSENCE onun daima-mevcut, kayıpsız-olmayan çapasıdır —
paralel sıkıştırılmış yüzey tutmayız (drift kaynağı). Ajanın gördüğü yüzey onun tek yasasıdır: o
yüzden yönlendirme-soruları *nasıl düşüneceğini*, taban-kısıtlar *neyi asla yapmayacağını* söyler.

---

*Alp Discipline v1.0 — çekirdek 2026-07-18'de donduruldu · ilk kullanım-kanıtı değişikliği
2026-07-22 (Alperen-onaylı). Bu metne değişiklik yalnız kullanım-kanıtıyla açılır — dokümanın
kendi İlke-2'si kendine uygulanmıştır. Created by Alperen Sartacoglu · Lisans: CC BY 4.0.*
