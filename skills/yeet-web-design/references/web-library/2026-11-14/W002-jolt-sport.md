# W002 — Jolt Sport / outdoor mağaza

- Kaynak: [761600987041761759](https://tr.pinterest.com/pin/761600987041761759/)
- Pinterest başlığı: Başlıksız pin.
- İnceleme: 14 Kasım 2026; 1 statik uzun sayfa, **752 × 2314 px**.
- [Kaynak görsel](images/W002-jolt-sport.jpg). İlk ekrandan footer'a kadar incelendi.

## Kaynakta görülen

Dar duyuru şeridinin altında karlı spor sahnesi, fotoğraf üstüne yerleşen gezinme, ortalanmış başlık/açıklama ve aşağıda beyaz kapsül düğme bulunur. Ardından beyaz yüzeyde başlığı ortalanmış yeni ürünler alanı gelir: dört sütun, iki satır; açık gri yuvarlatılmış görsel yüzeyleri, kesilmiş ürün fotoğrafları, kalp/çanta ikonları, ad ve fiyatlar.

Orta bölüm solda büyük mağaza fotoğrafı, sağda daha dar metin/teklif alanıyla simetriyi kırar. Koleksiyon alanı eş genişlikli üç sütunda farklı yüksekliklere sahip altı fotoğraf kullanır; geniş başlıklar görüntü üzerine oturur. Koyu fotoğraflı bülten bandını siyah, çok sütunlu footer izler. Arayüz büyük ölçüde nötr kalırken mavi, yeşil ve sıcak ürün tonları fotoğraflardan gelir. Ürün karşılaştırma alanı düzenli, keşif alanı daha serbesttir.

| Gözlem | Uyarlama | Yer |
|---|---|---|
| Kullanım sahnesinden temiz packshot'a geçiş | Önce yaşam bağlamı, sonra ürün karşılaştırması | İlk ekran → ürün ızgarası |
| Eş ürün kutuları, değişken koleksiyon kadrajı | Satın alma ve keşif için farklı düzen kullan | Ürünler / koleksiyonlar |
| Büyük mağaza fotoğrafı + dar metin | Gerçek fiziksel bağlamla ritmi değiştir | Marka/mağaza bölümü |
| Nötr UI, ürünün kendi rengi | Ürün ayrımını dekoratif arayüz renklerine boğma | Katalog genelinde |

## Yeniden kullanılabilir prompt

```text
Design a responsive multi-product storefront for [BRAND] and [AUDIENCE], with [PRIMARY_ACTION], using [VERIFIED_CONTENT] and [APPROVED_ASSETS]. Adapt W002's transition from outdoor context to clear shopping and editorial discovery.

Start with a real use-context photograph carrying compact navigation and a centered, short campaign message with a single action. Use a readable tonal overlay only as needed. Include an announcement strip only for an actual, current announcement; do not invent urgency or a countdown.

Create a new-products section with a consistent four-column desktop grid. Give each item a quiet light-neutral image field, consistent product scale, accurate name, actual price when provided, and clearly separate product navigation from favorite or cart actions. Do not add fake shopping functionality. Preserve meaningful product colors while keeping the surrounding interface restrained.

Interrupt the product rhythm with a large real location or brand-context image paired with a narrower editorial text column. Use a factual story or real destination instead of fabricated discounts or locations. Follow with category discovery arranged as three balanced desktop columns with varied photographic heights. Each category tile must remain a clear link with a readable label, not an arbitrary decorative collage.

Close with an optional newsletter area and a compact dark footer when those functions belong to the brief. Keep body copy and merchandise information in actual interface elements. Distinguish catalog consistency from editorial image variation; do not turn every section into the same card row.

Propose mobile behavior explicitly: simplify navigation, recompose the campaign image, reduce the product grid to two readable columns or one where the content requires it, stack the brand story, and reorder category tiles in a clear reading sequence. These are new responsive decisions, not observed source states. After plan approval, implement the agreed interactions and verify the catalog, category destinations, keyboard focus and any connected form.
```

## Uygulama önerisi ve kontrol

Ürün görseli, adı ve varyantının eşleşmesini tek tek kontrol et. Favori ve sepet işlevi kapsamda değilse işlev varmış izlenimi veren ikon ekleme. Bülten başarı durumu gerçek gönderime dayansın. Kaynakta farklı yükseklikli koleksiyonlar görünüyor; animasyonlu masonry davranışı gözlenmedi.

Bazı ürün etiketleri görüntüyle uyuşmuyor: bir giyim ürünü “Carabiner Set”, sandalye “Beanie” olarak etiketlenmiş. Bülten metni spor bağlamından güzellik içeriğine kayıyor. Bu kusurları kopyalama. Fiyat, %50 indirim, mağaza konumu, sayaç, marka ve tarih kaynak içeriğidir; yeni işin verisi değildir. Mobil ve canlı e-ticaret akışı incelenmedi; yeni çıktı üretilmedi.
