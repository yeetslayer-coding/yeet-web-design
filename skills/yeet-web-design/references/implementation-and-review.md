# Onaylı web tasarımını uygula ve doğrula

Tasarım + çalışan arayüz kapsamındaki plan onayından sonra kullan. Bu rehber sabit teknoloji veya her işte aynı test paketini zorunlu kılmaz; onaylı tasarım ve kullanıcı akışı için gereken kanıtı ister.

Önce [kalite akışındaki](quality-workflow.md) temsilî uygulamayı denetle; ardından burada tanımlanan kontrolleri bütün değişen kapsama uygula. Ekran/durum kanıtını mevcut proje kaydına bağla. Bu ara kontrol yeni bir kullanıcı onayı gerektirmez.

## Mevcut projeye oturt

- Proje yönergelerini, paket/çalıştırma komutlarını, mevcut bileşenleri ve değişiklik durumunu incele. Kullanıcının ilgisiz düzenlemelerini koru; sadece görünümü değiştirmek için çalışan yönlendirme veya veri katmanını yeniden yazma.
- Onaylı renk, tipografi, içerik genişliği, boşluk ve köşe kararlarını mevcut token/sistem yapısına taşı. Tek sayfalık iş için kullanılmayan kapsamlı tasarım sistemi üretme.
- Gerçek metinle çalış. İçeriğe göre bölüm yüksekliğini ve kırılma noktalarını belirle; masaüstü ekran görüntüsündeki koordinatları bütün sayfaya sabit konumlandırmayla kopyalama.
- Doğru semantik öğeleri kullan: gezinme için bağlantı, eylem için düğme. Form alanını etiketiyle, açılır öğeyi durumu ve odağıyla, görseli anlamına uygun alternatif metinle birlikte kur.
- Varlıkların en-boy alanını ayır; font/görsel yüklenince düzenin beklenmedik kaymasını kontrol et. Ana görselin kalitesini korurken gereksiz video, ağır efekt ve kütüphane yükünü azalt. Ölçülmemiş performans skoru veya SEO sonucu vaat etme.

## İşlev gerçekten çalışsın

Planlanan ana eylemi baştan sona uygula. Menü kapansın/açılsın, sekme içeriği değişsin, filtre gerçekten filtrelesin, bağlantı doğru hedefe gitsin. Görünür bir kontrolü sessizce etkisiz bırakma.

Formun başarı durumu gerçek gönderim sonucuna dayansın. Backend yokken sahte “gönderildi” bildirimi gösterme. Açıkça prototip istenmişse simülasyonu belirt; çalışan entegrasyon istenmişse eksik erişimi doğru noktada bildir ve bağımsız arayüz işlerini tamamla. Yüklenme, doğrulama hatası ve gönderim hatasını ilgili akışta ele al.

Ürün akışı gerçek ödeme, mesaj veya başka dış etki oluşturuyorsa doğrulama yöntemini mevcut yetkiye göre seç; sırf tasarım kontrolü için gereksiz gerçek işlem yapma. Yerel tasarım işi bu sistemlere otomatik yetki vermez.

## Görsel ve davranış kontrolü

Onaylı kaydırma efektlerini ve arayüz animasyonlarını gerçek tarayıcı etkileşimiyle dene. Kaydırmayı ileri/geri ve hızlı/yavaş kullan; öğeler yarım durumda veya görünmez kalmasın. Sabitlenen bölüm varsa doğru noktada serbest kaldığını, yeniden boyutlandırmada ve mobilde içerik sırasının korunduğunu doğrula. Cam, doku ve hareketin birlikte kullanıldığı alanlarda okunurluk ile kaydırma akıcılığını gözle. Ekran görüntüsü tek başına animasyonun çalıştığını kanıtlamaz.

Build/typecheck gibi proje kontrolleriyle tarayıcı kontrolünü birbirinin yerine koyma. Değişikliğe uygun mevcut kontrolleri çalıştır; yalnız biçimsel bir düzenleme için yeni test altyapısı kurma. Yeni davranış veya düzeltmenin anlamlı regresyon riski varsa ilgili akışı test et.

Tarayıcıda onaylı kapsamı aç; yalnız kahraman alanını değil sayfanın altını ve değişen ekranları da incele. Uygun başlangıç örnekleri geniş masaüstü için 1440 px, telefon için 390 px ve kritik ara kırılım için 768 px'tir; bunlar çıktı dosyası ölçüsü veya sabit CSS kırılma noktası şartı değildir. İçerik gerektiriyorsa daha dar/geniş sınırları da dene.

| Kontrol | Görünür kanıt |
|---|---|
| Planla uyum | Ana hizalar, metin ölçeği, boşluk, renk alanı, görsel kadraj ve bölüm ritmi karşılaştırıldı |
| Simetri ve etiket | Görseller aynı sırada eşit boyut/oran ve ortak üst-alt hizada; boşluklar dengeli; dekoratif sıra numaraları yok |
| Yüzey ihtiyacı | Kutuların gruplama/okunurluk/etkileşim amacı açık; okunur hero başlığı, güncelleme notu ve sonuç sayısı gereksiz panel içinde değil. Doğrudan zemindeki metinler yeterli kontrastta; gerçek kartlar/kontroller korunmuş, dar ekranda taşmıyor; footer sırf kutu eklemek/kaldırmak için değiştirilmemiş |
| Cam ve sektörel doku | Başlangıç tercihleri görünür biçimde uygulandı veya sonraki açık brief ile değişti; dokunun sektör ilişkisi somut, metin ve kontrol okunurluğu masaüstü/mobilde korundu |
| Metin ve özgünlük | Boş sloganlar ve tekrarlar çıkarıldı; içerik, bölüm görevleri ve görsel/doku seçimi gerçek markaya özgü; cam efekti okunurluk veya kaydırma akıcılığını bozmuyor |
| Responsive | Dar ve geniş görünümde taşma, kesilme, çakışma, yanlış sıra ve sabit öğenin içeriği kapatması kontrol edildi |
| Tipografi | Gerçek font yüklendi; Türkçe karakter, uzun başlık, düğme metni ve küçük yazı okunuyor |
| Gezinme/eylem | İlgili rotalar, ana çağrı, mobil menü, sekme/diyalog ve geri dönüş yolu denendi |
| Klavye/dokunma | Odak görünür; kontrol erişilebilir; açılır öğeden çıkış ve odak dönüşü çalışıyor; hover tek erişim yolu değil |
| Durumlar | İlgili boş, yüklenme, hata ve başarı durumları dürüst içerikle kontrol edildi |
| Hareket | Planlanan kaydırma ve arayüz animasyonları oynatıldı; başlangıç/bitiş, geri kaydırma ve mobil davranış kontrol edildi; azaltılmış harekette içerik ve ana işlev kullanılabilir |
| Teknik | İlgili proje kontrolleri geçti; gözlenen konsol/ağ/varlık yükleme hataları incelendi |

Tarayıcı aracı yoksa mevcut alternatiflerle doğrulanabileni tamamla ve kalan görsel/etkileşim kontrolünü açık bırak. Bir komutu çalıştırmadan geçti, tek ekranı görüp tüm siteyi test edildi, emülasyonla gerçek cihazda doğrulandı deme.

## Teslim kanıtı

İşin boyutuna göre kaynak kodu ve gerekli varlıkları, çalışan yerel/önizleme adresini veya çalıştırma komutunu, incelenmiş masaüstü/mobil ekran görüntülerini paylaş. Önemli akış veya çok sayfalı işte yalnız ana sayfa görüntüsünü kapsam kanıtı sayma. Kullanıcıya kısa sonuç ve gerçek sınırları anlat; uzun teknik tutanağı zorunlu teslim haline getirme.

Tamamlanan tasarımı kullanıcının beğenmiş olduğunu varsayma. Tasarım karşılaştırması, işlev doğrulaması ve kullanıcı estetik onayı ayrı durumlardır. Gerçek entegrasyon veya yayın kapsamda olup engelliyse engeli belirt; sadece arayüz bitti diye bütün görevi tamamlanmış sayma.
