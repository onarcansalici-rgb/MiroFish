# 🖨️ 3D BASKI İŞİ — BAŞLANGIÇ BRİFİNGİ (Claude'a Yükle)

> **Bu dosya nedir?**
> Bu, yeni bir oturuma başladığında bana (Claude) ilk yükleyeceğin "hafıza / brifing" dosyasıdır.
> Amacı: Konuştuğumuz her şeyi sıfırdan anlatmadan, projenin neresinde olduğumuzu ve nasıl
> çalışacağımızı hatırlatmaktır. Yeni bir oturum açtığında **önce bu dosyayı bana ver**, sonra
> "Kaldığımız yerden devam" de. Proje ilerledikçe bu dosyayı birlikte güncelleyeceğiz.

---

## 1. PROJENİN ÖZETİ

- **Ne yapıyoruz:** 3D yazıcı(lar) ile ürün basıp Türkiye'de online satacağız.
- **Kimim ben (kullanıcı):** 3D yazıcı konusunda sıfır bilgim var. Sen bana öncülük edeceksin,
  adım adım öğreteceksin ve karar süreçlerini benim için kolaylaştıracaksın.
- **Hedef:** Para kazandıran, talebi olan modelleri bulmak; üretip stoklu/talebe göre satmak;
  bunu birden fazla "temalı satış hesabı/markası" ile ölçeklemek.
- **Bütçe:** (Buraya yazılacak — henüz netleşmedi. Belirleyince güncelleyeceğiz.)
- **Mevcut ekipman:** (Buraya yazılacak — yazıcı modeli, malzeme tipi vs.)
- **Mevcut durum/aşama:** (Buraya yazılacak — örn. "henüz yazıcı almadık", "araştırma aşaması")

---

## 2. BEN (CLAUDE) NELER YAPABİLİRİM — GERÇEKÇİ KAPABİLİTELER

### ✅ Yapabildiklerim
1. **Pazar & trend analizi (web erişimi açıkken):**
   - Etsy, Trendyol, Hepsiburada, Instagram, Pinterest, Amazon, Cults3D, MyMiniFactory,
     Thingiverse, Printables gibi platformlarda neyin satıldığını/trend olduğunu araştırmak.
   - "Şu an Türkiye'de ne satıyor?" sorusuna kaynaklı, gerekçeli cevaplar üretmek.
   - Rakip ürün/fiyat/yorum analizi yapıp raporlamak.

2. **Niche & hesap konsept stratejisi:**
   - "Sadece spor", "Formula 1 / araba", "anime figür", "ev-organizasyon", "hediyelik" gibi
     temalı 10+ hesap konsepti tasarlamak, her birine isim/kimlik/içerik planı çıkarmak.

3. **Model bulma & seçim mantığı:**
   - Hangi modeli basmaya değer? Lisans (ticari kullanım izni) uygun mu? Baskı süresi/maliyeti
     mantıklı mı? Talep var mı? Bunları skorlayan bir karar çerçevesi kurmak.

4. **Maliyet & fiyatlandırma:**
   - Filament maliyeti + baskı süresi + elektrik + işçilik + kargo + platform komisyonu +
     kar marjını hesaplayan bir **fiyat hesaplama tablosu/script'i** yazmak.

5. **Satış metni & SEO:**
   - Türkçe ürün başlığı, açıklaması, etiketleri (Etsy/Trendyol SEO'su) yazmak.
   - Instagram/TikTok için içerik, reels senaryosu, hashtag stratejisi üretmek.

6. **Otomasyon (kod yazarak):**
   - Fiyat/rakip takip script'leri, maliyet hesaplayıcılar, model seçim skorlama araçları,
     satış kayıt tabloları, içerik takvimi üreticileri — bunları bu repo içine kod olarak yazarım.

7. **Operasyon planı:**
   - Üretim akışı, stok yönetimi, kargo, müşteri mesajlaşma şablonları, iade politikası taslakları.

### ❌ Yapamadıklarım / Sınırlarım (Dürüst olmak gerekirse)
- **Fiziksel hiçbir şey yapamam:** Yazıcıyı ben çalıştıramam, dilimleme (slicing) için yazıcının
  başında olamam, ürünü basamam/kargolayamam. Bunları sen yaparsın, ben yönlendiririm.
- **Otomatik ilan yayınlayamam:** Senin hesabına girip Trendyol/Etsy'ye ürün koyamam veya
  Instagram'da otomatik paylaşım yapamam (özel API/erişim kurmadıkça). İçeriği hazırlarım,
  yayınlamayı sen yaparsın.
- **Canlı/anlık veri garantisi yok:** Web erişimi bu ortamın ağ politikasına bağlı. Açıksa
  güncel araştırma yaparım; kapalıysa bilgimle ve senin getirdiğin verilerle çalışırım.
- **3D model tasarımı (CAD) üretemem:** STL/3MF dosyası çizemem. Ama nereden bulacağını,
  hangisini seçeceğini, nasıl modifiye ettireceğini söylerim ve gerekirse tasarım brief'i yazarım.
- **Yatırım/finans tavsiyesi değil:** Tahminler kurarım ama gerçek satış rakamlarını piyasa belirler.

---

## 3. HESAP / MARKA KONSEPT STRATEJİSİ (Çok Hesaplı Model)

Mantık: **Tek bir karışık mağaza yerine, her biri belirli bir kitleye hitap eden niş hesaplar.**
Niş hesaplar daha kolay büyür, takipçi daha sadıktır, SEO daha nettir.

Örnek 10 konsept (proje ilerledikçe netleştireceğiz):

| # | Konsept | Hedef Kitle | Örnek Ürünler |
|---|---------|-------------|----------------|
| 1 | Formula 1 / Motorsport | Yarış hayranları, erkek 18-40 | F1 araba modelleri, kask standı, anahtarlık |
| 2 | Futbol / Spor takımları | Taraftarlar | Takım logolu eşyalar, kupa replikaları |
| 3 | Anime & Oyun figürleri | Genç, koleksiyoncu | Karakter figürleri, masaüstü standlar |
| 4 | Ev & Organizasyon | 25-45 ev sahipleri | Kablo düzenleyici, kulaklık standı, saksı |
| 5 | Hediyelik & Kişiye özel | Geniş kitle | İsimli ürünler, sevgili/yıldönümü hediyeleri |
| 6 | Masaüstü oyun (D&D) | Hobi oyuncular | Minyatürler, zar kuleleri |
| 7 | Çocuk & Eğitici | Ebeveynler | Eğitici oyuncaklar, puzzle |
| 8 | Gadget & Tech aksesuar | Teknoloji meraklısı | Telefon standı, VESA mount, kontrolcü tutucu |
| 9 | Dekoratif & Aydınlatma | Estetik odaklı | Litofan lamba, vazo, geometrik dekor |
| 10 | Otomotiv aksesuar | Araç sahipleri | Araç içi tutucular, logo, organizer |

Her hesap için birlikte şunları çıkaracağız: marka adı, görsel kimlik notları, ilk 10 ürün listesi,
fiyat aralığı, içerik takvimi.

---

## 4. ÇALIŞMA YÖNTEMİMİZ (İŞ AKIŞI)

**Faz 0 — Kurulum & Öğrenme**
1. Bütçe + ekipman + hedef pazar netleştirme.
2. Bana sıfırdan 3D baskı temellerini öğret (filament tipleri PLA/PETG/ABS, yazıcı seçimi, slicer).

**Faz 1 — Araştırma**
3. Niş seçimi + ilk hesap konsepti.
4. O niş için pazar/rakip/trend analizi → "basılacak ilk modeller" listesi.

**Faz 2 — Test Üretimi**
5. 3-5 model seç, lisans + maliyet + fiyat kontrolü, küçük üretim.
6. İlanları hazırla (görsel brief + metin + SEO), sen yayınla.

**Faz 3 — Ölçekleme**
7. Satılanı analiz et, ölçek, yeni hesap aç, otomasyon araçlarını devreye al.

---

## 5. BU REPO İÇİNDE NE TUTACAĞIZ (Otomasyon & Dosya Yapısı)

```
3D_BASKI_PROJESI/
├── 00_BASLANGIC_BRIFING.md   ← bu dosya (her oturumda yükle)
├── 01_pazar_arastirmalari/   ← analiz raporları
├── 02_hesap_konseptleri/     ← her markanın planı
├── 03_modeller/              ← model seçim listeleri, lisans notları
├── 04_maliyet_fiyat/         ← hesap tabloları / script'ler
├── 05_satis_metinleri/       ← ilan başlık/açıklama/SEO
└── 06_otomasyon/             ← takip ve hesaplama script'leri
```

---

## 6. HER OTURUMDA BANA NE SÖYLE (Hızlı Başlangıç)

Yeni oturum açtığında şu kalıbı kullan:
> "3D baskı projesi. Brifing dosyasını yükledim. Şu an [X aşamasındayız].
> Bugün [şunu] yapmak istiyorum."

Ben de güncel duruma göre nereden devam edeceğimizi söyleyeceğim.

---

## 7. AÇIK KARARLAR / BEKLEYENLER
- [ ] Bütçe netleştirilecek
- [ ] İlk yazıcı ve malzeme kararı
- [ ] İlk niş/hesap seçimi
- [ ] Satış platformu önceliği (Etsy mi, Trendyol mu, Instagram mı?)

*(Bu listeyi ilerledikçe güncelleyeceğiz.)*
