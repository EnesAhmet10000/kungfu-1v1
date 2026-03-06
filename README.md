# 🐼 Kung Fu Panda Reflex Challenge - 1v1 Arena

Selamlar! 👋 Bilgisayarlı Görü (Computer Vision) ve yapay zeka kullanarak tarayıcı üzerinden oynanabilen, refleksleri test eden bir oyun geliştirdim. Kameranın karşısına geçip ekrandaki hedefleri vurmaya çalışıyorsunuz.

## Neler Var Bu Oyunda?
* **Kamera ile Kontrol:** Klavyeye veya fareye gerek yok, MediaPipe sayesinde oyun el hareketlerinizi anlık takip ediyor.
* **1v1 Kapışma Modu:** Ekran ikiye bölünüyor. Arkadaşınızla kameranın karşısına geçip aynı hedefleri kim daha hızlı vuracak kapışabiliyorsunuz. Tamamen adil bir sistem kurdum, ikinize de aynı anda aynı hedefler çıkıyor.
* **Her Cihazda Çalışır:** Kodu bayağı bir optimize ettim. Sadece bilgisayarda değil, telefonda da (yan çevirerek) sorunsuz oynayabilirsiniz.

## Nasıl Başladı, Nereye Geldi?
Aslında bu projeye Tinkercad üzerinde Arduino, fiziksel butonlar ve LED'ler kullanarak başlamıştım. Ama donanım sınırlarına takılınca işi tamamen yazılıma dökmeye karar verdim. Butonların yerini kamera aldı, kabloların yerini de yapay zeka algoritmaları :) Benim için fiziksel donanımdan yazılıma geçişte çok güzel bir problem çözme tecrübesi oldu.

## Hangi Teknolojileri Kullandım?
* **React.js:** Arayüz ve oyun durumunu (state) yönetmek için. (Hızlıca test edebilmek için direkt CDN üzerinden projeye dahil ettim).
* **Google MediaPipe:** El takibi ve yapay zeka kısmı tamamen bununla çalışıyor.
* **HTML5 Canvas:** Görüntüyü ve hedefleri ekrana basmak için.
* **Tailwind CSS:** Tasarımı hızlıca toparlamak için.

## Nasıl Oynarsınız?
Hiçbir şey indirmenize veya kurmanıza gerek yok. Sadece tarayıcınızın olması yeterli.
1. Projenin linkine tıklayın (veya projeyi indirip `index.html` dosyasını açın).
2. Tarayıcıda kameraya izin verin.
3. Telefondaysanız cihazı yan çevirin.
4. Menüden "Başla"ya basıp hedeflere ellerinizle dokunun!

## Geliştirici
**Enes** - iESÜ Bilişim Sistemleri ve Teknolojileri 1. Sınıf. 
Yazılım ve yapay zekayı birleştirip interaktif şeyler üretmeyi seviyorum.
