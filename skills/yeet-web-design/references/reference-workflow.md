# Web referansını incele ve uygulanabilir karara dönüştür

Bu rehberi yeni web bağlantısı, pano, ekran görüntüsü veya referans arşivi güncellemesinde kullan. İncelenmiş kaynak yoksa arşiv oluşturulmuş gibi davranma; gerekli kayıtları ilk gerçek incelemede oluştur.

## Kaynağı gerçekten incele

- Mevcut kaydı kontrol et. Aynı siteye ait ekranlar, karusel slaytları ve mobil varyasyonlar tek tasarım ailesine bağlansın; bağımsız beğeni oyları olarak sayılmasın.
- Canlı sitede ilgili sayfayı üstten alta incele. Görevin gerektirdiği menü, hover/odak, kaydırma ve geçişleri gözle; mobil görünümü ayrıca aç. Yalnız ilk ekranı görüp tüm siteyi veya bütün akışı incelemiş sayma.
- Statik görselde yalnız görüneni kaydet. Responsive davranış, tıklama sonucu veya animasyon hakkında öneri geliştirilebilir; bunlar kaynakta gözlenmiş davranış değildir.
- Pinterest/Behance gibi çoklu içerikte istenen kapsamı sonuna kadar yükle, ilgili karuselleri aç. Video incelemesinde yalnız kapağı davranış kanıtı sayma; izlenen bölüm ve süreyi belirt.
- Erişim sınırını görünür kapsamdan ayır. Önceki tarihli kayıt canlı sitenin bugünkü davranışını kanıtlamaz. Kaynak HTML'i veya başlığı tek başına görsel inceleme yerine geçmez.

## Her kaynak için kayıt

Arşiv güncellemesi istendiğinde `references/web-library/YYYY-MM-DD/` altında bir `index.md` ve kaynak başına okunur kayıt oluştur. Aynı günün sonraki incelemesinde `YYYY-MM-DD-update-02` gibi ayrı dizin kullan; eski envanteri ezme. Kaynak görselleri yalnız erişim ve kullanım koşulları izin veriyorsa sakla; dosyası bulunmayan kayda sahte yerel bağlantı yazma. [Ana kaynak dizinini](web-library/index.md) ve gerektiğinde [tasarım dili profilini](design-language.md) güncelle. İlgili kayıt seçilebilsin; her işte tüm arşivi yükleme.

| Alan | İçerik |
|---|---|
| Kimlik | Sabit kaynak kimliği, temiz URL/dosya yolu, gözlem tarihi, sayfa/slayt adı |
| Kapsam | Canlı site/statik/video, gerçekten incelenen sayfalar, ekran boyutları, durumlar ve erişilemeyen alanlar |
| Düzen | Hizalar, sütun oranı, içerik genişliği, boşluk, metin/görsel ölçeği, bölüm sırası |
| Tipografi | Gözlenen harf karakteri, görevler, ağırlık ve satır ilişkisi; doğrulanmayan font adı veya piksel değerine kesinlik verme |
| Renk ve varlık | Yüzey/metin/vurgu dağılımı, görüntü kadrajı, doku, ikon ve logo görevleri |
| Davranış | Gerçekten görülen tetikleyici, durum değişimi, mobil uyarlama ve hareket; bilinmeyenleri ayrı işaretle |
| Uyarlama | Bu karar hangi içerikte işe yarar, yeni brief'te nerede kullanılabilir, ne taşınmamalı? |
| Kanıt türü | Kullanıcının açık tercihi / görsel gözlem / yorum / uygulanacak öneri |

Uygulama kararını **gözlem → karşılık → sayfa/durum** olarak yaz. Kesin ölçü alınamadıysa oran veya yaklaşık gözlem kullan; tahmini CSS değerini kaynakta ölçülmüş veri gibi gösterme.

## Prompt veya uygulama tarifi istendiğinde

Her istenen kaynak/slayt için kaynak bağlantılı ayrı kayıt üret. Bir kolajın panellerini indirilen ayrı görseller gibi sayma. Birebir tekrarları ortak kaynağa bağla; mevcut kimlikleri yeniden numaralama.

Kaynak gözlemi ile güncel uygulama talimatını ayır. 15 Kasım 2026 son düzeltmesi gereği yeni uygulama prompt'larında simetrik/eşit ölçülü yerleşim, dekoratif numarasız etiketler ve yalnız işlevi olan yüzeyler belirt. Okunur hero başlığına, güncelleme notuna veya sonuç sayısına otomatik kutu ekleme; kısa yardımcı bilgiler doğal akışta kalabilir. Marka/iletişim/telif footer'ının mevcut düzenini sırf kutu eklemek ya da kaldırmak için değiştirme. Eski arşivdeki asimetri, numaralı süreç veya kutu kullanımı kaynak betimlemesi olarak korunabilir; seçilen prompt'u kullanırken güncel simetri, okunurluk ve yüzey ihtiyacına göre uyarla.

Tarifin sırası:

1. Yeni işin amacı, gerçek içerik ve marka kısıtları.
2. Hangi sayfa veya ekranın kurulacağı; bilgi ve okuma sırası.
3. Düzen, tipografi, renk rolleri, varlık/kadraj ve boşluk kararları.
4. Masaüstünden mobile geçiş ve gerekli etkileşim durumları.
5. Kaynaktan taşınmayacak marka, fotoğraf, metin, iddia ve dekorasyon.
6. Gözlenenler ile yeni öneriler; uygulanınca kontrol edilecek karşılıklar.

Raster tasarım prompt'u isteniyorsa hedef ekran boyutunu ve birebir metni ekle. Kod uygulama tarifi isteniyorsa bileşen/durum ilişkisini ve gerçek varlık kaynaklarını ekle. Bir statik ekranın prompt'u, canlı sitenin bütün davranışları çıkarılmış anlamına gelmez.

## Güncelleme ve sınırlar

Yeni kaynakları önceki URL/kimliklerle karşılaştır; aynı sayfadaki değişen düzeni de izle. Kaybolan referansı otomatik olarak reddedilmiş stil sayma. Tekrarlanan ilişkiyi çıkarım olarak kaydet, farklı davranan örnekleri silme. Kullanıcı bir bölümü özellikle seçtiyse o tercih tüm sitenin onayı değildir.

Dosya özeti aynı olan birebir tekrar ile farklı kırpım/çözünürlükte aynı tasarımı ayır. İkinci durumda her pinin kaynak kaydı korunsun, fakat ortak tasarım ailesine bağlansın. Yeni analiz profilin bir kuralını daraltıyorsa ilgili kuralı güncelle; eski tek örneği evrensel kural olarak bırakma. İncelemeyi yalnız prompt sayısını artırmakla bitirme: yeni kaynak ilişkisinin sonraki plan ve uygulamaya etkisini belirt.

İncelenen site/pin sayısı, açılan sayfa/slayt sayısı, gözlenen mobil/etkileşim kapsamı ve yazılan tarif sayısını ayrı raporla. Prompt yazımı, kod uygulanması ve sonucun doğrulanması farklı tamamlanma durumlarıdır. Arka planda takip veya model eğitimi iddiasında bulunma.
