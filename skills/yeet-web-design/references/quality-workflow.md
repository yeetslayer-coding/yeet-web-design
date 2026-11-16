# Web tasarımında erken karşılaştırma ve düzeltme

Yeni tasarım planından önce oku; onaydan sonra uygula. Küçük bir revizyonda yalnız değişen bileşen ve etkilediği durumlar için kullan. Bu süreç ayrıca görsel konsept, yeni araç veya kullanıcı onay aşaması gerektirmez.

## Kararı ve kanıtı aynı kayıtta tut

Mevcut DESIGN.md/proje planı veya çalışma klasöründeki kısa bir kaydı kullan. Küçük revizyonda birkaç satır yeterlidir; gereksiz belge üretme.

- **Brief ve sınır:** kullanıcı görevi, gerçek içerik, değişen/korunacak parçalar, sayfa/işlev kapsamı, yayın yetkisi.
- **Tasarım kararı:** seçilmiş kaynak dosyası → gözlenen ilişki → uygulanacak bölüm/durum → kabul ölçütü. Yeni önerileri kaynak gözleminden ayır.
- **Temsilî uygulama:** onaylı kapsamın hangi bölümleri ve mobil durumuyla ilk kontrol yapılacak?
- **İnceleme kanıtı:** gerçek ekran görüntüsü/durum ve ekran genişliği → gözlem → geçti/düzeltilecek/doğrulanamadı → düzeltme ve yeniden kontrol.

Gerçek dosya veya tarayıcı durumu görülmeden kontrol sonucu yazma. “Poppins, cam, doku mevcut” yalnız tercihlerin varlığına kanıttır; hiyerarşi ve kompozisyon ayrıca değerlendirilir. Kullanıcıya kısa plan ve sonuç ver; iç kaydı uzun teknik tutanak olarak dayatma.

## Onaylı örneğe göre karşılaştır

Yeni web işinde [Alfa Invest / Best Aroma örneklerinden](approved-web-2026-11-15/index.md) ilgili ekranı aç; planın uyarlamasını görsel hiyerarşi, yüzey okunurluğu, simetri, ana eylem ve markaya özgü hareket bakımından karşılaştır. Yalnız dosya/komut kontrolüyle bu karşılaştırmayı atlama. Mevcut onaylı işte kabul edilmiş fotoğraf, kimlik ve davranışları koru. Bu örneklerin kullanıcı beğenisi kaydedilmiştir; yeni sonucun beğenisi ayrıca değerlendirilir.

## 1. Temsilî bölümü önce çalıştır

Onaylı kapsamdan ilk ekran, görsel ritmi sınayan bir içerik bölümü ve ana eylem/geniş-dar gezinme ilişkisiyle başla. İş yalnız bir bileşense o bileşenin ilgili durumlarını kullan. Bunlar bitmiş kapsamın parçalarıdır; ek seçenekler veya sadece hero teslimi değildir.

Gerçek font ve metinle, kullanılacak gerçek varlık veya açıkça geçici olduğu belirtilmiş varlıkla çalıştır. Yer tutucu varlıkla yapılan kontrol onun yerleşimini sınar; final fotoğraf, okunurluk ve kadraj kontrolünün yerine geçmez. Final varlık geldiğinde etkilediği görünümü tekrar incele.

Masaüstü ve mobilde tarayıcıda aç, ekran görüntülerini görsel olarak incele. Seçilen kaynak görseli ve onaylı kararlarla karşılaştır:

| Kontrol | Görünür kanıt | Başarısızsa düzelt |
|---|---|---|
| İlk ekran | Mesaj, ürün/iş görseli ve ana eylemin okuma sırası | Başlık ölçeği, sütun ilişkisi, görsel alanı veya içerik sırası |
| Simetri | Aynı sırada eşit görsel ölçüsü/oranı, ortak üst-alt hizalar ve dengeli aralık; mobilde tutarlı sıra | Basamaklı ofsetleri kaldır; grid ve çerçeveleri eşitle, uygun kadraj seç |
| Yüzey ve etiket | Her kutunun gruplama, okunurluk veya etkileşim görevi var; hero ve yardımcı bilgiler otomatik kutulanmamış; dekoratif 01/02/03 yok | Gereksiz dış/iç çerçeveleri ve güncelleme/sonuç sayısı bantlarını kaldır; kontrastı koru. Gerçek kartları, kontrolleri, sayısal bilgileri ve mevcut footer düzenini koru |
| Renk ve boşluk | Büyük renk kütleleri, görsel/metin payı, sakin/yoğun alan ilişkisi | Alan dağılımı ve boşluk; yalnız gölge veya renk kodu değiştirme |
| Bölüm ritmi | Farklı soruları yanıtlayan bölümlerin farklı bilgi yoğunluğu | Tekrarlanan kart düzeni yerine göreve uygun düzen |
| Mobil | Başlık kırılımı, odak noktası/kadraj, sıra ve ana eyleme erişim | Dar ekrana özel düzen; masaüstünü yalnız küçültme |
| Cam/doku/hareket | Yerleri planla uyumlu; içerik okunuyor, etkileşim çalışıyor | Yüzey/kontrast, doku yoğunluğu veya hareket aralığı |

Kaynak piksel kopyası veya evrensel “8/10 estetik” puanı arama. Uyarlama onaylı brief'e hizmet etmeli. Görsel uyuşmazlık varsa ortak düzen/token/varlık kararını düzeltip temsilî bölümde yeniden bak; ardından tüm sayfaları tamamla. Bu kontrol için kullanıcıdan yeniden onay isteme.

Tarayıcı erişilemiyorsa mevcut alternatiflerle yapılabilen kod/kapsam işini sürdür; ara görsel kontrolü **doğrulanamadı** olarak bırak. Tarayıcı çalışmış gibi davranma veya görsel kaliteyi geçti sayma.

## 2. Kusurun nedenini düzelt

“Modern görünmüyor” yerine “ilk ekranın üçte ikisi genel başlık, ürünü anlatan görsel çok küçük” gibi gözlem yaz. Düzeltmeyi etkili değişkene bağla: içerik, düzen, dizgi, varlık, hareket veya işlev. Kullanıcının kabul ettiği özellikleri koru.

Aynı kusur hedefli düzeltmeden sonra sürerse aynı CSS değerlerini rastgele değiştirmeyi bırak; DOM/yerleşim ilişkisini, metnin uzunluğunu, kullanılan fontu veya varlık kadrajını incele. Yöntemi neden değiştiğini belirterek seç. Marka yönü ve kapsam aynı kaldıkça olağan düzeltmeyi tamamla.

Çözüm yeni görsel yön, zorunlu içerik değişikliği veya eksik harici yetki gerektiriyorsa o somut kararı kullanıcıya sun; bağımsız işleri sürdür. Kullanılabilir yöntemlerle doğrulanamayan kısmı açıkça ayır. Sonsuz kozmetik revizyon döngüsü veya bilinen kusura “tamamlandı” etiketi kullanma.

## 3. Temsilî bölümden tüm kapsama geç

İlk kontrol yalnız ortak tasarım kararlarının erken sınamasıdır. Son incelemede tüm değişen rotaları/bölümleri ve ana akış durumlarını [uygulama rehberine](implementation-and-review.md) göre dene. Alt bölümlerdeki tekrar, uzun metin, menü/form durumları ve gerçek varlık yüklemesini atlama.

- Tasarım/referans sonucu ekran görüntüsü ve gözlenen ilişkiye dayanır.
- Akış sonucu gerçek tıklama, gezinme, klavye/dokunma ve gerekiyorsa yetkili entegrasyon sonucuna dayanır.
- Teknik sonuç gerçekten çalıştırılmış uygun kontrole dayanır.

Değişen ortak bileşen veya token için etkilenen ekranları yeniden incele. Testi yapılmayan cihaz, entegrasyon veya durum için kanıt iddia etme. Yeni skill metninin geçerli olması yeni sitenin daha güzel çıktığını kanıtlamaz; bunu gerçek uygulama ve kullanıcı geri bildirimi sınar.
