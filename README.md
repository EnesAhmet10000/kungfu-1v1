# 🐼 Kung Fu Panda Reflex Challenge - Yapay Zeka (AI) Destekli Görüntü İşleme Oyunu

![Oyun Görseli](https://via.placeholder.com/800x400?text=Kung+Fu+Panda+Reflex+Challenge) Bilgisayarlı Görü (Computer Vision) ve Yapay Zeka (AI) kullanılarak geliştirilmiş, refleksleri ve el-göz koordinasyonunu test eden etkileşimli bir web oyunudur. Oyuncular, ekrandaki sanal hedefleri vurmak için kameranın önünde ellerini hareket ettirerek puan toplarlar.

## ✨ Özellikler

* **Hassas El Takibi (Hand Tracking):** El eklemlerinin hareketlerini gerçek zamanlı ve yüksek hassasiyetle yakalamak için Google'ın `MediaPipe Hands` makine öğrenimi modelini kullanır.
* **1v1 Çift Oyuncu Modu (Split-Screen):** İki oyuncunun aynı anda, bölünmüş ekranda rekabet etmesini sağlayan kapışma arenası.
* **Adalet Algoritması (Fair-Play Engine):** 1v1 modunda, her iki oyuncu için de aynı rastgele hedef dizilimini önceden üreterek adil bir rekabet ortamı sunar. Sadece gerçekten hızlı olan kazanır!
* **Duyarlı Tasarım (Responsive Design):** Hem bilgisayarlarda (geniş ekran) hem de mobil cihazlarda (yatay modda) sorunsuz çalışacak şekilde tasarlanmıştır. Mobil cihazlarda otomatik olarak ön kamerayı kullanır.
* **Görsel ve İşitsel Geri Bildirimler:** Hedef vurulduğunda anında görsel tepkiler ve her oyuncu için özel olarak ayarlanmış ses efektleri (Osilatör kullanılarak oluşturulmuştur).

## 🚀 Geliştirme Serüveni (The Pivot)

Bu proje başlangıçta **Tinkercad** ve **Arduino** kartları (fiziksel butonlar, kablolar ve LED'ler) kullanılarak donanım tabanlı basit bir donanım projesi olarak yola çıktı. Ancak fiziksel donanımların getirdiği kısıtlamaları aşmak ve kullanıcılara çok daha etkileşimli, özgür bir oyun deneyimi sunmak için projeyi tamamen bir yazılım (Software) ortamına taşıma kararı aldım. 

Fiziksel butonların yerini web kamerası, kabloların yerini ise Yapay Zeka algoritmaları aldı. Bu süreç, donanımdan yazılıma geçişte harika bir problem çözme deneyimi oldu.

## 🛠️ Kullanılan Teknolojiler

* **React.js:** Oyun durumunu (state) yönetmek ve kullanıcı arayüzünü akıcı bir şekilde (Virtual DOM) güncellemek için kullanıldı (CDN üzerinden projeye dahil edildi).
* **MediaPipe by Google:** El hareketlerini ve eklemleri (landmarks) takip eden ana yapay zeka/bilgisayarlı görü modeli.
* **HTML5 Canvas & JavaScript:** Ekrandaki dinamik etkileşimleri, hedefleri ve ayna efektini oluşturmak için.
* **Tailwind CSS:** Modern ve duyarlı (responsive) UI tasarımını hızlıca kurgulamak için.

## 🎮 Nasıl Oynanır?

1. Oyun bağlantısını açın (GitHub Pages üzerinden veya projeyi indirip `index.html` dosyasını çalıştırarak).
2. Tarayıcının **Kamera** erişimine izin verin.
3. **Mobilde oynuyorsanız:** En iyi deneyim için telefonunuzu yatay konuma (Landscape) çevirin.
4. Ekranda beliren hedefleri vurmak için elinizi kameranın önünde hareket ettirin. Süre bitmeden en yüksek puanı toplamaya çalışın!

## ⚙️ Kurulum (Local Setup)

Bu proje doğrudan CDN bağlantıları kullandığı için karmaşık Node.js kurulumları veya arka plan sunucuları (örn. `npm install`) gerektirmez. Sadece tarayıcınızın olması yeterlidir.

1. Repoyu bilgisayarınıza klonlayın:
   ```bash
   git clone [https://github.com/KullaniciAdiniz/RepoAdiniz.git](https://github.com/KullaniciAdiniz/RepoAdiniz.git)
