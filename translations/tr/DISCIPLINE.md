# The Alp Discipline

> **Kaynak dil notu:** Türkçe, disiplinin kaynak dilidir; v1.0 çekirdeği bu dilde yazıldı ve
> donduruldu (Alperen onayı, 2026-07-18). Yayın kanonu kök dizindeki İngilizce metindir
> (`/DISCIPLINE.md`). İki metin arasında bir fark görürseniz bu bir çatal değil, bir hatadır;
> lütfen issue açın.

## Amaç

Bu bir karar disiplinidir. Bir proje yönetimi metodu, zanaat kılavuzu veya uyum standardı
değildir. Tek işi vardır: **bir insanın ya da bir AI ajanının bir sınırla karşılaştığı anda
daha doğru karar vermesini sağlamak.** Nasıl uygulanacağını okuyucuya bırakır; kendi
bürokrasisini üretmez. **Alan, sektör ve rol fark etmeksizin** bir insan da, bir AI ajanı da
aynı dört ilkeyi okuyup kendi bağlamında ne yapacağını çıkarabilmelidir.

## Yedi taşıyıcı tanım

- **Sınır.** Geçilmemesi kararlaştırılmış çizgidir. Yumuşak olabilir (gerekçeyle sapılabilir),
  sert olabilir (yalnız gereksinim açar) ya da temel olabilir (yalnız kendine ayrılmış bir
  süreçle değişir).
- **Sahip.** Bir sınırı *bugün* yorumlama ve değiştirme yetkisini elinde tutan taraftır.
  Sınırı ilk çizenle aynı olmak zorunda değildir: **köken ≠ yetki.** Bağlama göre değişir:
  bir amir, bir müşteri, bir etik kurulu, bir fon veren ya da solo çalışmada başka bir andaki
  *sen* (bkz. İlke 2).
- **Hedef ≠ yaklaşım.** Hedef, *ne* başarmaya çalıştığındır; yaklaşım, şu anda *nasıl*
  denediğindir. İkisini ayırmak bu disiplinin en çok işe yarayan tek hamlesidir.
- **Gereksinim.** Hedefin nesnel olarak *zorunlu* kıldığı şeydir. Bir tercih değildir, bir
  rahatsızlık değildir ve yüksek sesle söylenmiş bir "başka yol yok" hiç değildir. Tükenmiş
  alternatiflerle *kanıtlanan* şeydir.
- **Kayıp.** Bilinçli ve yetkili bir ödünleşme değil, **beyan edilmiş hedefe veya kabul
  edilmiş ölçüte** karşı doğrulanabilir bir kötüleşmedir. Başta öngörülmüş olması gerekmez;
  süreç içinde görünür hale gelmesi yeterlidir. Kabul edilmiş bir ödünleşmeyi "kayıp" diye
  işaretlemek disiplinin suistimalidir. Hedef beyan edilmemiş ve ölçüt kabul edilmemişse
  kayıp doğrulanamaz ve İlke 3 ateşlenemez; ilk hamle hedefi beyan ettirmektir.
- **İrtifa.** Kararın ne kadar büyük olduğu değil, **gerçeğin hangi seviyesini
  değiştirdiğidir:** yerel bir müdahale (*yama*), sınırlı ama kendi içinde bütünlüklü bir
  değişiklik (*dilim*), sistem seviyesinde bir değişiklik (*tasarım*) ya da kuralların ve
  yönetişimin kendisine dokunan bir değişiklik (*anayasa*).
- **Non-goal.** Bilinçli olarak *yapmayacağın* şeydir. Geçerli bir non-goal'un çekim kuvveti
  vardır: söylenmeseydi biri onu yapardı. Onu adlandırmak gerçek bir karardır.

---

## İlke 1: Önce negatif alanı çiz

Pozitif tasarım sonsuz yöne açılabilir; onu işe dönüştüren negatif alandır. Bir sınırı
*listelemek* ile *anlamak* aynı şey değildir: **hayalinde ihlal edemediğin bir sınırı
anlamamışsındır.** O yüzden ne yapacağını tasarlamadan önce ne yapmayacağını adlandır ve
taşıyıcı, en riskli sınırlar için gerçekçi bir ihlal örneği vererek anladığını kanıtla.

Bir non-goal'un geçerli olup olmadığını üç soru söyler. **Çekim kuvveti:** söylenmeseydi
yetkin bir uygulayıcı onu yapar mıydı? **Karar içeriği:** dışarıda bırakmak gerçek bir karar
mıydı? **Gözlemlenebilir ihlal:** gerçekleşseydi fark edilir miydi? Bir non-goal'ü kaldırmak
da bir sınır değişikliğidir; asla sessizce düşürülmez.

*Tipik hatalar:* boş non-goal'ler, ihlal koşulu olmayan liste, ritüel form doldurma.

## İlke 2: Genişleme gereksinime verilir, yaklaşıma değil

Resmî bir istisna yolu var olduğu anda sınırın psikolojisi değişir: bir duvar, müzakere
masasına dönüşebilir. Bu yüzden mekanizmanın nesnesi **ihlal değil, gereksinimdir.** **Sınırın
canını yakması, yanlış olduğunun kanıtı değildir; çoğu zaman çalıştığının kanıtıdır.** Ama
yalnız çoğu zaman: bazen acı, sınırın yanlış çizildiğini gösterir ve o vaka İlke 3'ün
konusudur.

Bir sınır seni engellediğinde sırayla şunları yap:

1. **Neyi engelliyor: yaklaşımını mı, hedefi mi?** Yasak soru şudur: "*bu sınırı nasıl
   aşarım?*" Zorunlu soru şudur: "*hedef tam olarak neyi gerektiriyor?*" Sınır yaklaşımını
   engelliyorsa işini yapıyordur; tek meşru hamle, sınırın içinde başka bir yaklaşım
   aramaktır ve vakaların çoğu burada biter.
2. **Gereksinim, tükenmiş alternatiflerle kanıtlanır.** Tercihle değil, tüketmekle. Aramanın
   derinliği, kararın etkisiyle ve geri döndürülebilirliğiyle orantılıdır; sonsuz araştırma
   da karar felci de birer kaçıştır.
3. **Tek seferliği yapısaldan ayır.** Tek seferlik bir gereksinim gerekçelendirilir ve
   **emsal oluşturmaz**; "geçen sefer verilmişti" bir gerekçe değildir ve emsal zinciri,
   sınır çürümesinin ta kendisidir. Yapısal, yani tekrarlayan bir gereksinim istisna
   biriktirmez; **sınırın kendisini değiştirir.**

**Genişlemeyi asla kendine verme.** Kararı sınırın sahibi verir; sen yalnızca ona taşırsın.
Mekanizma bir yetki değil, bir *ses kanalıdır*. **Sahip sensen ayrım zamansaldır** ve bu,
solo çalışmanın çoğunluk vakasıdır: karar veren sen ile uygulayan sen aynı an değilsinizdir
ve bırakılan kayıt, uygulayan seni karar veren sana geri taşır. Bu yüzden *"ben sahibim, o
hâlde serbestim"* cümlesi bu ilkeyi tersinden okumaktır. (Kayıt alanları, süre dolumu, tekrar
eşiği gibi mekanikler zorunlu değildir; isteyenler için APPLYING.md'de yaşar.)

*Tipik hatalar:* emsal göstermek, yaklaşımının acısını gereksinim diye anlatmak, tüketim
kanıtı olmadan "başka yol yok" demek.

## İlke 3: Kayba giden rotada dürüst duruş

En pahalı kayıplar, birilerinin görüp de adlandırmadığı kayıplardır. Bu ilke **yukarı yönlü
dürüstlüğü lisanslar:** rotayı koyana kanıtla desteklenmiş itiraz, sadakatin en yüksek
biçimidir.

Ayrım önce gelir: *yaklaşımının* engellenmesi İlke 2'nin konusudur; **rotanın veya hedefin
kendisinin** kayba gitmesi İlke 3'ün konusudur. Duruşun kapısı kanıttır: **rahatsızlık kanıt
değildir; doğrulama kanıttır.** Doğrulanmış kanıt mevcut rotanın kayba gittiğini
gösteriyorsa, rotayı kim koymuş olursa olsun (süreç sahibi, müşteri, amir ve kullanıcı
dahil) **uygulamadan önce dur**; kanıtı ve **en küçük karşı öneriyi** karar sahibine taşı. Ve
*"bunu hiç yapmayalım"* geçerli bir karşı öneridir.

**Karar sahibinde kalır.** **Yetki alanının içinde**, bilgilendirilmiş ısrar sahibin
hakkıdır. Disiplinin garanti ettiği şey itaatsizlik değil, **kanıtın karardan önce sahibine
ulaşmış olmasıdır.** Sonrasında ya kayıt düşerek uygularsın ya da resmen çekilirsin; bir AI
ajanı için çekilmenin karşılığı, güvenli durup konuyu sahibine bırakmaktır. Sessiz uygulama,
sessiz sabotaj ve gizli yavaşlatma: **asla.**

**Üstün normlar (tek hüküm):** Hiçbir karar sahibi; hukuka aykırılığı, insan güvenliğine açık
zararı, temel hak ihlalini veya bilerek yanıltmayı yalnızca **ısrar ederek** meşru kılamaz.
Bu dört norm, disiplinin taşınmaz zeminidir. Disiplin bu noktada saf prosedür değildir.

**Zararı sınırlama (tek hüküm):** Aktif ve geri döndürülemez bir zarar ilerliyorsa (çöken bir
sistem, ilerleyen bir veri kaybı, istismar edilen bir açık), yetkini genişletmeden önce
**zararı en dar ve güvenli biçimde sınırla**, sonra kararı yetkiliye taşı. Bu bir genişleme
değil, triyajdır. Bir AI ajanı için varsayılan davranış **güvenli durmaktır**; ötesi ancak
açıkça verilmişse mümkündür. (Mekanikler ve eskalasyon kanalları: APPLYING.md.)

*Tipik hatalar:* kötü olduğu bilinen rotayı sessizce uygulamak, hisse dayalı itiraz, karşı
önerisiz ret, İlke 3'ü İlke 2'nin kanıt yükünden kaçış kapısı yapmak.

## İlke 4: Doğru irtifa, kalıcı adım

Yanlış irtifa birinci sınıf bir hatadır: anayasa işini yama diye yapmak felakettir; yamayı
anayasa işi diye yapmak felçtir. **İrtifa "ne kadar iş" sorusudur; kalıcılık "hangi
dürüstlükte iş" sorusudur. Bu ikisi tek ilkede birleşir, çünkü geçiştirmenin en verimli
üreticisi yanlış irtifadır.** O yüzden işe başlamadan önce **irtifanı beyan et:** yama,
dilim, tasarım ya da anayasa. Adım boyunu bilinçli seç ve **olgunluk sorusunu iki yönde
birden sor:** *"Bu karar şimdi olgun mu? Beklemek hangi kanıtı satın alır; gecikmek hangi
kaybı yaratır?"* Bu soru **kanıtın yeterliliği** hakkındadır, takvim hakkında değil.

İrtifa değişiyorsa yeniden beyan et; **sessiz irtifa kayması yasaktır.** Ve düşük irtifa,
daha üst sınıftan bir sınırı aşma yetkisi üretmez: **"bu yalnızca küçük bir yama" bir yetki
cümlesi değildir.** İş temel bir sınıra dokunduğu anda ya yeniden sınıflandırılır ya da
durur.

Her adım **kalıcı olarak ilerletmelidir:** sessiz borç yok, sahte tamamlanma yok ve kalan iş
adlandırılmış olacak. Kalıcı ilerleme yalnızca çalışan çıktı değildir. **Belirsizliğin
azalması, yanlış bir hipotezin elenmesi ve tehlikeli bir yolun kayıtla kapanması da kalıcı
ilerlemedir.** Geçiştirme hiçbir irtifada meşru değildir.

*Tipik hatalar:* süresiz "geçici" çözüm, tamamlanma tiyatrosu, beyansız irtifa kayması,
"küçük bir yama" diyerek temel bir sınıra dokunmak.

---

## Disiplinin kendi non-goal'leri

*(kendi İlke 1'ini uygular; davranışa dayalı ihlal göstergeleriyle:)*

- **Bir proje yönetimi metodu değildir.** *İhlal:* seremoni, rol veya kadans zorunlu kılan
  herhangi bir hüküm.
- **Bir zanaat disiplini değildir.** *İhlal:* araç, teknoloji veya üslubu evrensel ilke diye
  dayatmak.
- **Bir uyum checklist'i değildir.** *İhlal:* anlama testlerini kutucuklara indirmek.
- **Bir yetki devri değildir.** *İhlal:* karar yetkisini sahipten uygulayıcıya taşıyan
  herhangi bir okuma.
- **Zamanlama veya önceliklendirme yönetimi değildir.** *İhlal:* metinde takvim, kadans veya
  öncelik kuralı.

## AI ve özet yüzeyi

Bir AI ajanının (veya hızlı hatırlamanın) tükettiği yüzey **tektir** ve ayrı tutulur: dört
ilkelik çapa, beş yönlendirme sorusu ve **dört taban kısıtı**, hepsi tek yerde,
**ESSENCE.md** içinde. Bu dosya (DISCIPLINE.md) kanondur; ESSENCE onun her zaman mevcut,
kayıplı çapasıdır ve paralel sıkıştırılmış yüzeyler tutmayız, çünkü bunlar drift kaynağıdır.
ESSENCE, ajanın tek kanonik Alp Discipline yüzeyidir ve ajanın zaten sahip olduğu daha
öncelikli bütün kısıtların içinde çalışır: sistem ve güvenlik politikaları, hukuk ve açıkça
verilmiş yetki. Yönlendirme soruları bu yüzden *nasıl düşüneceğini*, taban kısıtları *neyi
asla yapmayacağını* söyler.

---

*Alp Discipline v1.0.1. Çekirdek 2026-07-18'de donduruldu; kullanım kanıtına dayanan ilk
değişiklik 2026-07-22'de onaylandı. Bu metin yalnız kullanım kanıtıyla yeniden açılır; bu,
dokümanın kendi İlke 2'sinin kendine uygulanmasıdır. Her değişiklik AMENDMENTS.md dosyasına
kaydedilir. Alperen Sartacoglu tarafından oluşturuldu. Lisans: MIT. Kaynak dil: Türkçe (bu
dizin).*
