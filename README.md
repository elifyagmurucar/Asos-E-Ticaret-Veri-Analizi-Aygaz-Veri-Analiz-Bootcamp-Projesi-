**Asos E-Ticaret  Veri Analizi**

Bu proje ile bir Asos e-ticaret sitesindeki ürünlerin detaylarını analiz edeceğim ve önemli çıkarımlar yapmayı hedefleyorum. Örneğin, hangi kategorilerdeki ürünlerin daha popüler olduğunu, fiyat dağılımlarını ve stok durumlarını inceleyeceğim.


Veri Setim: https://www.kaggle.com/datasets/trainingdatapro/asos-e-commerce-dataset-30845-products

**Adım 1: Veri Setinin İncelenmesi ve Yüklenmesi**

Veri Setindeki Değişkenler:

- •	`product_name:` Ürünün adı
- •	`brand:`Marka adı
- •	`price:` Fiyat
- •	`category:`Ürünün kategorisi
- •    ` stock:` Stok durumu
- •	`rating:` Ürün derecelendirmesi 
- •	`product_code:`Ürün kodu
- •	`color:` Ürünün rengi

Hedef: Bu verilerden hangi ürünlerin ve kategorilerin en popüler olduğunu anlamak, fiyat dağılımlarını analiz etmek ve stok yönetimiyle ilgili çıkarımlar yapmak.


**Kütüphanelerin ve Veri Setinin Yüklenmesi**



**Adım 2: Veri Keşfi (EDA)**

**2.1 Veri seti hakkında genel bilgi:**
Veri setinde eksik veri olup olmadığını ve genel istatistikleri inceleyelim.




**2.2 Eksik değerlerin doldurulması:**
Eksik değerlerin olduğu durumlarda bu değerleri doldurabiliriz ya da gerekirse o satırları çıkarabiliriz.

**Adım 3: Veri Görselleştirme**

3.1 Fiyat dağılımı:
Ürünlerin fiyat dağılımını histogram ile görselleştirelim.

3.2 Kategorilere göre ürün sayısı:
Hangi kategoride daha fazla ürün olduğunu inceleyelim.

3.3 Fiyat ve derecelendirme ilişkisi:
Fiyatın, ürün derecelendirmesi ile ilişkisini scatter plot ile inceleyelim.

**Adım 4: İstatistiksel Analiz**

4.1 Fiyat istatistikleri:
Hangi kategorinin ortalama fiyatının daha yüksek olduğunu inceleyelim.

4.2 Stok yönetimi:
Stok durumunu inceleyerek hangi kategorilerde stokların daha fazla olduğunu gözlemleyebiliriz.

**Adım 5: Sonuçlar ve Öneriler**

**Sonuçlar:**

`Fiyat Dağılımı:` Çoğu ürün düşük fiyat aralığında yoğunlaşmış. Ancak, bazı kategorilerde fiyatlar oldukça yüksek.

`Popüler Kategoriler:` en fazla ürün sayısına sahip ve müşterilerin ilgisini çeken bir alan olabilir.

`Fiyat ve Derecelendirme:` Daha yüksek fiyatlı ürünlerin derecelendirmelerinin biraz daha düşük olduğu gözleniyor.

`Stok Yönetimi: [Kategori Adı] `stok açısından zenginken, bazı kategorilerde stoklar kritik düzeyde.

**Öneriler:**
Stok Yönetimi: Stokların yoğun olduğu kategorilerde kampanyalar düzenlenebilir. Az stoklu kategoriler için tedarik artırılabilir.
Fiyat Stratejisi: Orta fiyat segmentindeki ürünler daha fazla talep görüyor gibi gözüküyor; bu alana odaklanılabilir.
Kategori Geliştirme: Popüler kategorilere daha fazla ürün eklenebilir.
