# 🍔 Restaurant Web Site (HTML & CSS)

Modern, responsive ve tamamen **HTML + CSS** ile geliştirilmiş tek sayfalık restoran web sitesi. Minimal ve performanslı bir yapıyla menü, ürünler, müşteri yorumları, blog ve iletişim bölümlerini içerir.

## ✨ Özellikler
- **Hero** alanı: Büyük arka plan görseli ve “Order Now” CTA butonu
- **Menu**: Ürün kartları, indirimli fiyat gösterimi, sepete ekleme butonları (UI)
- **Products**: Öne çıkan ürünler, fiyat/gramaj bilgisi
- **About**: Kısa tanıtım ve “Learn More” CTA
- **Reviews**: Müşteri yorum kartları, yıldız derecelendirme
- **Blogs**: Kart yapısı ile son yazılar
- **Contact**: Gömülü **Google Map** ve iletişim formu (UI)
- **Responsive**: Mobil, tablet ve masaüstü için akışkan grid ve tipografi

## 🖼️ Ekran Görüntüleri
> Aşağıdaki görseller canlı demodan alınmıştır.

![Hero](/screens/hero.png)
![Menu](/screens/menu.png)
![Products](/screens/products.png)
![About](/screens/about.png)
![Reviews](/screens/review.png)
![Contact](/screens/contact.png)
![Blogs](/screens/blog.png)

## 🧱 Teknolojiler
- **HTML5** – semantic markup
- **CSS3** – flexbox & grid, custom variables, responsive helpers
- (İsteğe bağlı) **Google Fonts** ve **Font Awesome** ikonlar


## 🚀 Yerelde Çalıştırma
1. Bu repo’yu indir/clonela.
2. Bir **Live Server** (VS Code eklentisi) ile `index.html` dosyasını çalıştır.
3. Alternatif: Dosyayı tarayıcıda çift tıklayarak da açabilirsin.

> Geliştirme sırasında görsel yollarının (`/assets/images/...`) doğru olduğundan emin ol.

## 🧩 Özelleştirme İpuçları
- Renk paletini `:root { --primary: ... }` değişkenleri ile yönet.
- Kart boşlukları ve radius değerlerini `--radius`, `--gap` gibi değişkenlerle ayarla.
- Menü/ürün kartlarını JSON’a taşımayı planlıyorsan küçük bir JS ile **template render** ekleyebilirsin.

## 🔒 Lisans
Bu proje kişisel portföy ve eğitim amaçlıdır. Ticari kullanımda telif hakkı içeren görsellerinizi kontrol etmeyi unutmayın.

## 👩‍💻 İletişim
- **İsim:** İrem Tokuş  
- LinkedIn / GitHub linklerinizi `Contact` alanında ve README’de paylaşabilirsiniz.

---

> Not: Bu proje şu an **saf HTML & CSS**’tir. Sepete ekleme, form gönderimi gibi işlemler **UI gösterimidir**. Gerçek işlevsellik için arka uç (Node/ASP.NET vb.) veya basit bir form endpoint’i eklenebilir.