# Genetik Algoritma ile Web Sunucusu Optimizasyonu

Bu proje, **Yapay Zeka Sistemleri** dersi kapsamında, Genetik Algoritma kullanılarak bir web sunucusunun performans ayarlarının (CPU ve RAM) optimize edilmesi amacıyla geliştirilmiştir.

##  Problem Tanımı
Bir yazılım şirketi, sunucu ayarlarını maksimum performans için optimize etmek istemektedir.
* **Amaç Fonksiyonu (Maximize):** y = 5*x1 + 7*x2 - 0.1*x1^2 - 0.2*x2^2`
* **Değişkenler:**
  * `x1` (CPU Çekirdeği): [2, 12] aralığında tamsayı.
  * `x2` (RAM Miktarı): [4, 64] aralığında tamsayı (GB).
* **Kısıtlar:**
  1. `x1 * x2 <= 512` (Donanım/Lisans limiti)
  2. `x1 >= 4` (Minimum çekirdek sayısı)

##  Algoritma Parametreleri
Projede aşağıdaki Genetik Algoritma parametreleri kullanılmıştır:
* **Popülasyon Büyüklüğü:** 50
* **Jenerasyon Sayısı:** 100
* **Mutasyon Oranı:** 0.1
* **Çaprazlama (Crossover) Oranı:** 0.8
* **Seçilim Yöntemi:** Turnuva Seçimi (Tournament Selection)

##  Kurulum ve Çalıştırma
Bu projeyi kendi bilgisayarınızda çalıştırmak için aşağıdaki adımları izleyebilirsiniz:

1. Bu repoyu klonlayın veya zip olarak indirin.
2. Gerekli kütüphanelerin yüklü olduğundan emin olun:
   pip install numpy matplotlib
