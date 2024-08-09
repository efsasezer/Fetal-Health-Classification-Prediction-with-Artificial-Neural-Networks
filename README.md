Fetal Health Classification with Autoencoder and SVM

Bu proje, fetal sağlık verilerini kullanarak bir sınıflandırma modeli geliştirmeyi amaçlamaktadır. Model, veri ön işleme, özellik seçimi, normalizasyon, otomatik kodlayıcı (autoencoder) ve Destek Vektör Makineleri (SVM) kullanılarak eğitilmektedir.

Proje İçeriği

Veri Yükleme ve Ön İşleme:

fetal_health.csv dosyasından veri yüklenir ve giriş (X) ve çıkış (y) değişkenlerine ayrılır.

Türkçe karakterlerin doğru işlenmesi için veri okuma ayarları yapılır.

Veri Görselleştirme:

Verinin korelasyon matrisini ve kutu grafiğini oluşturur.

Çıkış değişkeni ile giriş değişkenleri arasındaki korelasyon katsayılarını hesaplar ve görselleştirir.

Veri Normalizasyonu:

Giriş verileri min-max normalizasyonu ile ölçeklendirilir.

Eğitim ve test veri setleri oluşturulur.

Model Eğitimi:

Autoencoder kullanılarak verinin kodlanması sağlanır.

Kodlanmış verilerle Destek Vektör Makineleri (SVM) sınıflandırıcı eğitilir.

Sonuçların Değerlendirilmesi:

Eğitim ve test veri setleri için modelin performansı confusion matrix ve doğruluk (accuracy) hesaplamaları ile değerlendirilir.

Ortalama Kare Hata (MSE) hesaplanır ve sonuçlar raporlanır.

Kurulum ve Çalıştırma
Gereksinimler:

MATLAB
Veri Seti:

fetal_health.csv dosyasının projeye dahil edilmesi gerekmektedir.
Adımlar:

Veriyi yükleyin ve işleyin.
Veriyi görselleştirin ve normalizasyon işlemlerini gerçekleştirin.
Autoencoder ve SVM modellerini eğitin.
Sonuçları değerlendirin ve raporlayın.
Kullanım
Proje, veri analizi ve makine öğrenmesi teknikleri kullanılarak fetal sağlık durumlarının sınıflandırılmasını amaçlar. Eğitim ve test aşamalarında elde edilen sonuçlar, modelin genel başarısını gösterir.
