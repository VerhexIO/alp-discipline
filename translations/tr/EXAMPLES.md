# İşlenmiş örnekler

Disiplin, hiçbir alana bağımlı olmadığını iddia eder — bu iddia beyan edilerek değil,
kanıtlanarak durur (kendi İlke-1'i). O yüzden aşağıdaki örnekler bilerek birden fazla alandan
seçilmiştir; yazılım, örneklerden yalnız biridir. Tüm isim ve mekânlar bilinçli olarak
jeneriktir.

## 1 — Araştırma (yazılım-dışı)

Bir doktora araştırmacısı, yaşlı hastalarda ilaç uyumunu çalışıyor. Etik kurul **sert bir
sınır** koymuş: bakım-tesisi sakinleriyle doğrudan görüşme yok. Planlanan yöntem ise doğrudan
görüşmeydi.

- **Negatif alan (İ1).** Sınır taşıyıcı; araştırmacı gerçekçi bir ihlal hayal ederek anladığını
  kanıtlar: *"Ziyaret saatlerinde sakinlerle gayriresmî sohbet edip notlarımı veri olarak
  kullanabilirdim."* Bunu adlandırmak, sınırın gerçekte neyi yasakladığını gösterir — yalnız
  resmî görüşmeyi değil, gayriresmî toplamayı da.
- **Hedef mi yaklaşım mı (İ2).** Sınır *yaklaşımı* (doğrudan görüşme) engelliyor, *hedefi*
  (uyumu anlamak) değil. Sınır-içi alternatifler var: bakıcı görüşmeleri, anonimleştirilmiş
  eczane yenileme kayıtları, tesis-personeli anketleri. Alternatifler tüketilmemiş — yani
  ortada gereksinim yok, kurula taşınacak bir şey de yok. Vaka sınırın içinde biter; vakaların
  çoğu orada biter.
- **Kayba giden rota (İ3).** Aylar sonra doğrulanmış katılım-kaybı verisi, yalnız-bakıcı
  örnekleminin ailesi olmayan sakinleri sistematik dışladığını gösterir — beyan edilmiş
  araştırma-sorusuna karşı doğrulanabilir bir kötüleşme, bir his değil. Araştırmacı veri
  toplamayı sürdürmeden durur; kanıtı ve en küçük karşı-öneriyi (eczane-kayıtları kolu ekle)
  danışmana ve kurula taşır. Karar onlarda kalır.
- **İrtifa (İ4).** Kayıt-kolu eklemek, çalışma tasarımına bir *dilim* (sınırlı ama bütünlüklü
  değişiklik) olarak beyan edilir — örnekleme bölümüne sessiz yama olarak sokulmaz.

## 2 — Operasyon (yazılım-dışı)

Bir tıbbi dağıtımcının bölge-depo koordinatörü. **Sert sınır:** soğuk-zincir ürünleri yalnız
valide edilmiş soğutmalı araçlarla taşınır. Sıcak hava dalgası talebi patlatır, valide filo
tamamen dolu, bir klinik ilaçsız kalmak üzere.

- **Yasak soru:** "soğuk-zincir kuralını nasıl aşarım?" — normal minibüste yalıtımlı kutular,
  "yalnız bu seferlik". **Zorunlu soru:** hedef — kliniğin hastalarını tedavi etmeyi
  sürdürmesi — tam olarak neyi gerektiriyor? Sınır-içi alternatifler: bir sonraki valide
  seferle kısmî sevkiyat, daha yakın depodan stok transferi, kliniğe *bugün* hangi kalemlerin
  kritik olduğunu sormak.
- **Emsal (İ2).** Bir meslektaş hatırlatır: "iki yaz önce minibüsü bir kez yapmıştık." Bu
  emsaldir, gerekçe değil — ve emsal-zinciri, bir soğuk zincirin tam olarak nasıl çürüdüğüdür.
- **Tek-seferlik mi yapısal mı (İ2).** Her sıcak dalga aynı sıkışmayı üretiyorsa gereksinim
  yapısaldır. Çözüm birikip duran istisnalar değil, sınırın kendisinin doğru irtifada, sahibine
  taşınmış değişikliğidir: valide filoyu genişletmek ya da tahsis kurallarını revize etmek — bu
  operasyon için anayasa-seviyesi iş; kararı baskı altındaki koordinatör değil, soğuk-zincir
  kuralının sahibi verir.

## 3 — Yazılım: bir AI ajanı

Bir AI kod ajanının yazma-kapsamı yalnız `billing/`. Görevin ortasında gerçek hatanın kökünü
`auth/` içinde bulur.

- **Önce tabanlar.** Kendine genişleme vermez — kapsam sınırı *yaklaşımını* (hatayı doğrudan
  düzeltmek) engelliyor, *hedefini* (hatanın çözülmesi) değil.
- **Ses kanalı (İ2/İ3).** Kanıtı — başarısız test ve kök-neden izini — ve en küçük
  karşı-öneriyi (*"kapsamımı yalnız `auth/session.ts` ile genişlet ya da düzeltmeyi yeniden
  ata"*) sahibe taşır; o soruda güvenli-durur, kalan sınır-içi işi varsa sürdürür.
- **Karşı-örnek (İ4).** Testleri geçirmek için `billing/` içinde bir belirtiyi sessizce
  yamasaydı, bu geçiştirme olurdu — yanlış irtifada sahte tamamlanma ve kayıt-dışı açık
  bırakılmış tehlikeli bir yol.
