# W007 — WEAVE / tek ürün anlatımı

- Kaynak: [761600987041761751](https://tr.pinterest.com/pin/761600987041761751/)
- Pinterest başlığı: **UX Marathon: Master the Platform**. Bu başlık görselin konusuyla uyuşmuyor; görsel WEAVE hava temizleyici sayfasıdır.
- Pin üzerinde bir Behance portfolyo derlemesi bağlantısı vardır; bu dış derleme ayrıca incelenmedi ve görselin özgün yaratıcısı doğrulanmadı.
- İnceleme: 14 Kasım 2026; 1 statik uzun sayfa, **564 × 1873 px**.
- [Kaynak görsel](images/W007-weave.jpg). İlk ekran, bütün ara bölümler ve footer incelendi.

## Kaynakta görülen

İlk ekranda büyük beyaz marka yazısının önünde açık renk hava temizleyici, mimari bir iç mekânda keskin pencere ışığıyla sunulur. Küçük bilgi kutuları ve ince çizgiler ürüne bağlanır; üst gezinme fotoğrafın içindedir. Sonraki açık bölümün üst sınırı yuvarlak ve ortası küçük kavisli bir çıkıntıyla ilk ekrana bağlanır.

Hakkında bölümü solda başlık/küçük sahne, sağda daha büyük kullanım fotoğrafı kullanır. Arkadaki çok açık marka yazısı düşük öncelikli dokudur. Özellik alanında ürünün kesit benzeri görünümü, çevresinde küçük açıklama kapsülleri ve sağda ikincil bağlam görseli vardır. Koyu ürün bölümünde başlık, kısa açıklama, açık teknik tablo, büyük ürün sahnesi, renk örnekleri ve satın alma çağrısı birlikte sunulur. SSS alanında solda soruya ait küçük fotoğraf/açıklama, sağda çizgili soru listesi; en altta büyük marka yazılı koyu footer bulunur.

| Gözlem | Uyarlama | Yer |
|---|---|---|
| Mekân ışığında tek ürün ve dev yazı | Kullanım bağlamını ilk ekranda görünür kıl | Hero |
| Bağlam → kesit → teknik tablo | Aynı ürünü farklı bilgi düzeylerinde açıkla | Sayfa akışı |
| Koyu bölümde teknik sunum | Karar anındaki bilgileri tek yerde topla | Ürün/teknik bölüm |
| Seçili soruyla ilişkili görsel | Soru yanıtını görsel bağlamla destekle | SSS |

## Yeniden kullanılabilir prompt

```text
Design a single-product explanatory website for [BRAND], aimed at [AUDIENCE] and leading to [PRIMARY_ACTION]. Use [VERIFIED_CONTENT] and [APPROVED_ASSETS]. Adapt W007's sequence of use context, product understanding, technical detail and questions; do not use the unrelated Pinterest title as the subject.

Build a spacious photographic hero with the actual product in a credible interior or relevant environment. Use directional natural-looking light, a large typographic anchor and compact navigation. Place only a small number of factual annotations near the product, connected to real features. Preserve product geometry, materials and scale across every image.

Move into a light editorial section with an asymmetric pairing of contextual photographs and concise explanation. Use an optional oversized low-contrast brand word as background hierarchy only if it does not impair reading. Follow with a feature explanation that relates labels to observable product details. Use an internal or exploded view only when accurate approved product information is available; otherwise use an external detail photograph.

Create a contrasting dark product section that groups the buying decision: product name, truthful summary, verified specifications, available variants and the primary action. Arrange a readable technical table beside a substantial product view on wide screens. Keep every value and claim grounded in the brief, and omit unavailable data rather than inventing it.

Close with a question section whose selected answer can be supported by a relevant detail image, then a compact dark footer. The source suggests selected question states but does not demonstrate working interactions. Design an accessible accordion or tabbed explanation appropriate to the actual content, without requiring every site to use the same mechanism.

For mobile, propose a new linear reading order, readable specification rows, larger annotation text and a usable question list. Reduce decorative overlap and do not shrink a long desktop screenshot into the viewport. No mobile or animation evidence is present in the source. After plan approval, implement and verify the actual product action, variants where required, question states and responsive composition.
```

## Uygulama önerisi ve kontrol

Kaynak üründe aynı geometrinin genel, kullanım ve teknik görünümde sürmesi hedeflenir. Kesit benzeri görsel bir mühendislik belgesi değildir. Gerçek ürün iç yapısı bulunmuyorsa görselin iddiasını kopyalama. SSS listesindeki seçili satır ve yandaki yanıt görseli aynı duruma bağlanmalı; kart yalnız süs olarak kalmamalı.

Kaynak dosyanın eni 564 px; küçük teknik yazıdan kesin ürün değeri veya font ölçüsü çıkarma. Fiyat, yorum sayısı, enerji/filtreleme iddiası, ölçü, güç ve garanti yeni ürün bilgisi değildir. Dış gri sunum çerçevesi siteye taşınmaz. Pin başlığı ve açıklamasındaki eğitim platformu/katılımcı bilgileri bu görsele ait doğrulanmış veri sayılmaz. Mobil ve canlı ürün akışı incelenmedi; yeni çıktı üretilmedi.
