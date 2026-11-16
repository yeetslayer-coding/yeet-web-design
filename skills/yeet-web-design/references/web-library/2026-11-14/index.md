# Web skill panosu — 14 Kasım 2026

Bu dosya ilk 7 pinlik incelemenin kaydıdır. Sonraki 18 pin için [ikinci incelemeyi](../2026-11-14-update-02/index.md), bütün kapsam için [ana dizini](../index.md) aç.

Kaynak: [lilyeet00 / web skill](https://tr.pinterest.com/lilyeet00/web-skill/). Kullanıcının gönderdiği kısa bağlantı bu panoya açıldı. Davet ve takip parametreleri arşive alınmadı.

**Kapsam: 7 pin / 7 farklı statik kaynak dosya / 7 ayrı prompt kaydı.** Panonun sonuna kadar gidildi ve yedi pinin ayrıntı sayfası açıldı. İncelenen ana pin içeriklerinde video veya ek slayt denetimi görülmedi. Pinterest'in önerileri, reklamları, avatarları ve aynı görseli yineleyen DOM öğeleri kaynak sayısına katılmadı. Karusel görünümünü çağrıştıran web bileşenleri, Pinterest'te ayrı slayt olduğu anlamına gelmez.

Kaynak görseller indirildi ve dosyalar doğrudan açılarak incelendi. İndirilen gerçek piksel ölçüleri aşağıdadır; bunlar önerilen web viewport ölçüleri değildir. Pinterest sunumları incelendi, örneklerin çalışan web siteleri test edilmedi. W006'da masaüstü ve telefon tasarımı aynı kaynakta görünür; diğer kayıtlardaki mobil/etkileşim tarifleri açıkça uyarlama önerisidir.

| Kimlik | Görseldeki çalışma | Dosya ölçüsü | Seçim amacı | Prompt ve inceleme |
|---|---|---|---|---|
| W001 | Business Alliance | 736 × 1472 | Kurumsal hizmet, katalog ve süreç anlatımı | [Kaydı aç](W001-business-alliance.md) |
| W002 | Jolt Sport | 752 × 2314 | Yaşam sahnesi → ürün ızgarası → koleksiyon akışı | [Kaydı aç](W002-jolt-sport.md) |
| W003 | MetaLeaf / VR konsepti | 1200 × 1666 | Ürün portresiyle katmanlı lansman ilk ekranı | [Kaydı aç](W003-vr-concept.md) |
| W004 | BOTANY | 736 × 1104 | Organik malzeme, büyük harf ve seçili iş ilişkisi | [Kaydı aç](W004-botany.md) |
| W005 | form&wood | 736 × 1230 | Ürün kesiti, işçilik fotoğrafı ve açık/koyu bölüm ritmi | [Kaydı aç](W005-form-and-wood.md) |
| W006 | OOMPH | 736 × 1104 | Masaüstü/mobil katalog, kategori şeridi ve yeniden sıralama | [Kaydı aç](W006-furniture-catalog.md) |
| W007 | WEAVE hava temizleyici | 564 × 1873 | Tek ürünün sahne, kullanım, özellik, teknik bilgi ve SSS akışı | [Kaydı aç](W007-weave.md) |

## Nasıl kullanılır?

1. Brief'in gerektirdiği bilgi yapısına göre kayıt seç; bütün örnekleri tek sayfaya karıştırma.
2. Seçilen kaydı ve bağlantılı kaynak görseli aç. [Sentezdeki](analysis.md) ortak ilişkileri ve karşı örnekleri gerektiğinde kullan.
3. Prompt'taki `[BRAND]`, `[AUDIENCE]`, `[PRIMARY_ACTION]`, `[VERIFIED_CONTENT]` ve `[APPROVED_ASSETS]` alanlarını güncel brief ile doldur. Metin dilini brief belirler; İngilizce prompt İngilizce site zorunluluğu değildir.
4. “Kaynakta görülen” ile “yeni uygulama önerisi” ayrımını koru. CSS ölçülerini, font adını ve animasyonu görselden kesinleşmiş sayma.
5. Prompt'u önce tasarım planına girdi yap. Kütüphane kaydı, yeni tasarım için plan onayının yerine geçmez. Onaydan sonra ilgili uygulama ve doğrulamayı tamamla.

Her kaydın İngilizce çekirdek prompt'u Türkçe gözlem ve uygulama notlarıyla birlikte kullanılmalıdır. Yalnız görsel konsept istenirse kod teslimini kapsamdan çıkar; hedef viewport'u belirt ve arayüzü gerçek bir ekran olarak tasarla. Sunum afişinin dış çerçevesini çalışan siteye taşıma.

## Kanıt ve sınırlar

- W004 tek dosyada bir web ilk ekranı ve iki dikey grafik uygulama; W006 tek dosyada masaüstü ve telefon görünümü içerir. Bunlar ek indirilmiş slayt olarak sayılmadı.
- W003'ün pin sayfasında “Yapay zeka ile değiştirildi” etiketi görüldü. Küçük yazı ve ürün geometrisi uygulamaya doğrudan aktarılabilecek doğruluk kanıtı değildir.
- W007'nin Pinterest başlığı “UX Marathon: Master the Platform”; görseldeki gerçek konu WEAVE hava temizleyici sayfasıdır. Sınıflandırma görsele göre yapıldı.
- W005 ve W006 aynı Pinterest yayıncısından iki farklı marka sunumudur; benzer öğeleri iki bağımsız kişisel tercih oyu olarak yorumlama.
- Tam dosya özeti ve kaynak URL'leri [manifest.json](manifest.json) içindedir. Birebir dosya tekrarı yoktur. Kaynak görsellerin marka, fotoğraf ve font hakları yeni işe devredilmiş sayılmaz.
- Bu çalışma kaynak incelemesi, prompt yazımı ve skill güncellemesidir. Yeni site/görsel üretimi veya bu prompt'lardan çıkan sonuçların kalite testi yapılmadı.
