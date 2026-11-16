# Yedi web referansının tasarım ilişkileri

Bu dosya [7 pinlik ilk incelemenin](index.md) sentezidir. Kullanıcı bu panonun skill'e kaynak olmasını istedi; her öğesini ayrı ayrı onayladığını söylemedi. Aşağıdaki ilişkiler görsel gözlem ve çalışma yorumudur, değişmez kişisel stil kuralları değildir.

## Brief'e göre kaynak seçimi

| İhtiyaç | Kaynak | Aktarılabilecek ilişki |
|---|---|---|
| Hizmeti ve çalışma sürecini açıklama | W001 | Fotoğrafla ana vaat → açıklama/doğrulanmış kanıt → kategori → adım listesi |
| Çok ürünlü mağaza | W002 | Kullanım sahnesi → karşılaştırılabilir ürün görselleri → fiziksel bağlam → kategori keşfi |
| Tek güçlü lansman ilk ekranı | W003 | Büyük ürün/insan kesiti ile iki yana ayrılan başlık ve yerel açıklamalar |
| Doğal malzemeden kavramsal marka dili | W004 | Malzemenin konturu, harf ölçeği ve açık/koyu alanın aynı kompozisyonda çalışması |
| İşçilik ve ürün kalitesi | W005 | Genel ürün → mekân → malzeme detayı → satın alınabilir seri |
| Responsive ürün kataloğu | W006 | Dört kolonun ikiye dönüşmesi, kategori düğmelerinin satıra yayılması, hikâye sırasının değişmesi |
| Bir ürünün ayrıntılı açıklaması | W007 | Yaşam sahnesi → özellik bağlantıları → teknik karşılaştırma → SSS |

## Tekrarlanan kararlar ve sınırları

### 1. Büyük yazı tek başına tasarım fikri değil

W003'te başlık ürün portresinin iki yanına bölünür; W004'te kelime organik yüzeyle katmanlanır; W005'te marka yazısı ürün kesitiyle aynı alanı paylaşır; W006'da marka ve kategori başlıkları boşluğu düzenler. Ortak ilişki harf ölçeği ile nesnenin birlikte kompozisyon kurmasıdır. W001'in daha ölçülü hizmet başlığı bu havuzun karşı örneğidir.

**Uygulama:** Planda başlığın satırlarını, görselin taşıdığı alanı ve örtüşme sınırını belirt. Ana mesajı gizleyecek rastgele kesme/maskeleme kullanma. Kaynakta yazı kesiliyorsa okunur alternatif hiyerarşiyi ve mobil davranışı ayrıca çöz.

### 2. Arayüz rengi ile içerik rengi farklı görevlerde

W001, W002 ve W006 nötr yüzey üzerinde fotoğraf/ürün renklerini taşır. W005 ahşap tonunu işçilik fikrine bağlar. W003'te soğuk mavi geniş alanı kaplar; W004'te yeşil, malzemenin kendisinden gelir. Bu nedenle “her web sitesi krem ve siyah olmalı” sonucu çıkarılamaz.

**Uygulama:** Paletten önce geniş yüzey, yazı, vurgu ve fotoğrafın renk payını planla. Ürün renklerini zorunlu monokroma dönüştürme. W005/W007'de koyu bölüm içerik grubunu ayırır; ayrı bir dark-mode teslimi değildir.

### 3. Aynı ürün farklı bilgi taşıyan kadrajlarla anlatılıyor

W005'in tek sandalye kesiti, iç mekânı ve örgü detayı farklı görevler taşır. W007'de ilk sahne, masadaki kullanım, iç yapı ve teknik sunum sıralanır. W002 ürün ızgarasını büyük mağaza fotoğrafı ve giyim koleksiyonlarıyla keser.

**Uygulama:** Ana ürün, bağlam ve detay için varlık listesini baştan çıkar. Tek packshot'ı tekrar büyütmek bilgi çeşitliliği değildir. Mekanik/geometrik tutarlılığı koru; gerçek ürün iç yapısı yoksa hayalî kesit üretme.

### 4. Bölüm ritmi içerik görevine göre değişiyor

W001'in katalog ve süreç bölümleri aynı kart şablonunu kullanmaz. W002'nin düzenli ürün ızgarasını asimetrik koleksiyon alanı izler. W005/W007'de açık/koyu kütleler bölümlerin işlevini değiştirir.

**Uygulama:** Her bölüm için “hangi soruyu yanıtlıyor?” sorusunu çöz. Görsel çeşitlilik uğruna sırayı rastgeleleştirme; benzer ürün karşılaştırmasını tutarlı ızgarada tut. Her bölüme ayrı efekt eklemek bu ritmin karşılığı değildir.

### 5. Mobil kanıt yalnız W006'da açık

W006'da masaüstünün dört ürün kolonu telefonda iki olur; kategori şeridi satırlara ayrılır; hikâye görselleri ve metin yeniden sıralanır. Bu statik ekranların varlığı gerçek responsive CSS veya çalışan telefon deneyimi kanıtı değildir. W004'teki iki dikey grafik paneli mobil site sanma.

**Uygulama:** Genişlik, içerik sırası, ürün ölçeği ve dokunma hedeflerini birlikte çöz. W001–W005/W007 için mobil öneriyi yeni tasarım kararı olarak planla; kaynakta gözlenmiş davranış diye sunma.

### 6. Sunum grafiği ile uygulama yüzeyi ayrılmalı

W003'ün dev dış portresi, ajans etiketi ve iletişim rozeti sunumun parçasıdır. W004'ün üst sosyal medya etiketi ve alttaki iki grafik paneli web ekranının dışında kalır. W006'da iki ekranın yan yana sunulması ve ayrı büyük logo, canlı sayfa yerleşimi değildir. W007'nin dış gri zemini de bu gruptadır.

**Uygulama:** Önce hangi sınırın gerçek web ekranını gösterdiğini tanımla. Sunum istenmemişse çerçeve, ajans kredisi ve mockup gölgesini siteye kopyalama. Kaynak görseli tek parça site olarak yerleştirme.

### 7. Kaynak hatası tasarım kuralı değildir

W001'de örnek logo/sayılar ve farklı dilde rozet; W002'de ürün görüntüsüyle uyuşmayan bazı ürün adları ve güzellik içeriğine kayan bülten metni; W003'te bozuk küçük yazılar; W005/W006'da yazım/dil kusurları görülür. W007'nin pin başlığı da konuyu yanlış sınıflandırır.

**Uygulama:** Hiyerarşi ve ilişkileri aktar; yabancı marka, fiyat, metrik, performans vaadi, yanlış ürün etiketi ve bozuk metni taşıma. Gerçek içerik tasarımın parçasıdır. Kaynaktaki estetik değer, her ayrıntının doğru olduğu anlamına gelmez.

## Skill'e etkisi

Yeni brief'te önce uygun bilgi yapısını seç, sonra gözlenen düzen/renk/kadraj ilkesini somutlaştır. Büyük yazı, nötr yüzey ve yuvarlak köşe bu yedi kayıtta sık görünür; bunlar açık kullanıcı emri olarak genellenmez. Kaynaklara dayalı öneri, plan onayı ve çıktı beğenisi ayrı kaydedilir. Gerçek web uygulaması yapılmadan bu kütüphanenin çıktı başarısı doğrulanmış sayılmaz.
