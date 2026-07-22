# Disiplini Uygulamak — isteğe bağlı mekanikler

**Bu dosyadaki hiçbir şey zorunlu değildir.** [DISCIPLINE.md](DISCIPLINE.md) bu dosya olmadan
da tamdır. Bu dosya, somut mekanik *isteyen* uygulayıcılar içindir; herhangi bir maddeyi al,
uyarla ya da tümüyle yok say.

> **Büyüme kuralı (v1):** bu dosya en çok 3–4 madde tutar. Yeni madde yalnız **kanıtlanmış
> gereksinimle** girer — gerçek kullanımda fiilen sorulmuş bir soru. Hayal-edilen-suistimalden
> doğan mekanikler (sahte-acil, gamed-tetik, sabotaj-semantiği) bu dosyaya girmez; o iş
> denetimin ve güvenliğin işidir, disiplinin değil.

## 1. Gereksinim kayıtları

Bir gereksinim bir sınırı açtığında (İlke 2) kayıt bırak. İşe yarayan alanlar:

- **Sınır** — hangi çizgi açıldı.
- **Beyan edilmiş hedef** — hedefin nesnel olarak zorunlu kıldığı şey.
- **Tüketilen alternatifler** — denenen/değerlendirilen her sınır-içi alternatif ve *hedefe
  karşı* neden başarısız olduğu (rahatına karşı değil).
- **Tek-seferlik mi, yapısal mı** — tek-seferlik emsal oluşturmaz; yapısal gereksinim, sahibe
  sınır-değişikliği önerisi olarak gider.
- **Süre-dolumu / gözden-geçirme tarihi** — bu kaydın tek başına geçerli olmayı bıraktığı an.

**Tekrar eşiği:** "aynı tek-seferlik" üçüncü kez göründüğünde onu yapısal say — istisna
kaydetmeyi bırak, sınır-değişikliğini sahibine taşı. Solo çalışmada kayıt, karar-veren-sen ile
uygulayan-sen arasındaki ses kanalıdır.

## 2. Zararı sınırlama ve eskalasyon

İlke 3'ün sınırlama hükmünün pratiği. Bunları bağlam başına *önceden* kararlaştır:

- **Her sert/temel sınırın sahibi kim** — muhatapsız eskalasyon boşluğa bağırmaktır.
- **Eskalasyonla ne taşınır** — doğrulama (his değil), etki ve en küçük karşı-öneri.
- **Sahibe ulaşılamıyorsa ne olur** — varsayılan güvenli-durma olarak kalır; sınırlama yalnız
  mevcut yetki içinde, en dar güvenli biçimde eyler ve karar sonrasında yine sahibe taşınır.
  Bir AI ajanı için güvenli-durmanın ötesi **önceden ve açıkça** verilmiş olmalıdır — anlık
  çıkarımla asla.

## 3. Orantılı tüketim

"Gereksinim kanıtlandı" diyebilmek için alternatif araması ne kadar derin olmalı? **Etki ×
geri-döndürülebilirlik ile orantılı.**

- Geri-döndürülebilir + düşük-etkili: dakikalarca düşünmek ve tek dürüst cümle yeter.
- Geri-döndürülemez veya yüksek-etkili: yazılı bir arama — ne denendi/değerlendirildi, her
  alternatif hedefe karşı neden başarısız.

Sonsuz araştırma da anlık "başka yol yok" da kaçıştır; orantılılık kuralı, tüketimi slogandan
pratiğe çeviren şeydir.
