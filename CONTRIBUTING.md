# Katkı Sağlama Rehberi

**Awesome Güvenli Bilgi** listesine katkıda bulunmak istediğiniz için teşekkürler! Bu rehber, katkınızın hızlıca kabul edilmesi için izlemeniz gereken kuralları açıklar.

## Nasıl katkı sağlayabilirim?

- Yeni bir kaynak (platform, araç, veri tabanı, eğitim kaynağı) önerebilirsiniz.
- Kırık ya da güncel olmayan bağlantıları düzeltebilirsiniz.
- Mevcut açıklamalardaki hataları giderebilir ya da açıklamaları iyileştirebilirsiniz.
- Bir kaynağın durumu değiştiyse (kapandı, ücretli oldu, arşiv moduna geçti vb.) durum notu ekleyebilirsiniz.

Katkılar **pull request (PR)** ile yapılır. Küçük öneriler için issue açmanız da yeterlidir.

## Kaynak ekleme formatı

Her kaynak, README.md'deki ilgili kategorinin altına şu formatta tek satır olarak eklenir:

```
- [İsim](URL) — Açıklama
```

- **İsim:** Kaynağın resmî adı (kısa parantezli ekler kabul edilir, örn. `OSoMeNet (Hoaxy'nin devamı)`).
- **URL:** Kaynağın resmî ve çalışan adresi; mümkünse HTTPS kullanın.
- **Açıklama:** Türkçe, bir cümle; kaynağın ne işe yaradığını ve öne çıkan özelliğini anlatsın. Nokta ile bitirin.
- İsim ile URL arasında boşluk yok; URL'den sonra ` — ` (boşluk + uzun çizgi + boşluk) kullanın.
- Kaynağın bilinen bir sınırlaması veya durum değişikliği varsa açıklamanın sonuna parantezle not düşün, örn. `(2024'te kapandı; arşiv erişilebilir)`.
- Yeni eklenen kaynağı kategori içinde alfabetik sıraya uygun yere yerleştirin.

## Kalite kriterleri

Önerilen her kaynak şu ölçütleri sağlamalıdır:

1. **Aktif olmalı:** Kaynak hâlâ yayında ve bakımı yapılıyor olmalı. Kapanmış ama tarihî/arşiv değeri taşıyan kaynaklar ancak durum notu ile kabul edilir.
2. **Resmî URL:** Yalnızca kaynağın resmî sitesine bağlantı verin; ayna, kopya ya da üçüncü taraf tanıtım sayfaları kabul edilmez.
3. **Ücretsiz veya ücretsiz katmanı olmalı (tercihen):** Tamamen ücretli araçlar ancak alanında gerçekten benzersizse ve ücretsiz deneme/katman sunuyorsa değerlendirilir.
4. **Reklam ve spam içermemeli:** Tanıtım amaçlı, düşük kaliteli veya spam bağlantılar kabul edilmez.
5. **Konuyla ilgili olmalı:** Kaynak; dezenformasyonla mücadele, doğrulama, güvenilir bilgiye erişim veya medya okuryazarlığı temasına doğrudan hizmet etmeli.
6. **Yasal olmalı:** Telif hakkı ihlali barındıran ya da yasa dışı erişim sağlayan kaynaklar (örn. Sci-Hub) listeye alınmaz.

## Pull request süreci

1. Depoyu fork'layın ve değişikliğinizi ayrı bir branch'te yapın.
2. Tek bir PR'da tek bir mantıksal değişiklik yapın (örn. bir kaynak ekleme veya bir bağlantı düzeltme).
3. PR başlığını net yazın: `Ekle: Kaynak Adı (Kategori)` ya da `Düzelt: Kaynak Adı bağlantısı`.
4. PR açıklamasında şunları belirtin:
   - Eklediğiniz kaynağın bu listede neden yer alması gerektiği (1-2 cümle),
   - Bağlantının çalıştığını doğruladığınızı,
   - Varsa ücretsiz katman / dil desteği bilgisi.
5. PR gönderilmeden önce kontrol listesi:
   - [ ] Format `- [İsim](URL) — Açıklama` şablonuna uyuyor.
   - [ ] Bağlantı çalışıyor ve resmî siteye gidiyor.
   - [ ] Açıklama Türkçe, bir cümle ve nokta ile bitiyor.
   - [ ] Kaynak doğru kategoriye ve alfabetik sıraya eklendi.
   - [ ] Kaynak listede zaten yok (tekrar kontrol edildi).

PR'lar en geç makul bir süre içinde incelenir; değişiklik istenirse lütfen aynı PR üzerinde güncelleme yapın.

## Yeni kategori önerisi

Mevcut kategorilere uymayan bir kaynak grubu için yeni kategori önerebilirsiniz:

1. Önce bir **issue** açın ve önerdiğiniz kategoriyi gerekçelendirin.
2. Yeni bir kategorinin kabul edilmesi için genellikle **en az 3 uygun kaynak** önerilmiş olması beklenir.
3. Kategori kabul edilirse; `##` başlık, açıklayıcı bir emoji ve İçindekiler (TOC) güncellemesi ile birlikte eklenir.

## Davranış kuralları

- Saygılı ve yapıcı bir dil kullanın.
- Tartışmaları kaynakların kalitesi ve liste kriterleri çerçevesinde yürütün; siyasi veya kişisel tartışmalardan kaçının.
- Bu liste tarafsızlığı esas alır; belirli bir görüşü öne çıkarma amaçlı katkılar kabul edilmez.

Sorularınız için issue açmaktan çekinmeyin. Katkınız için şimdiden teşekkürler!
