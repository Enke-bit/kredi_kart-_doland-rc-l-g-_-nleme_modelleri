# Kredi Kartı Dolandırıcılığı Tespiti için Sinir Ağı Modelleri
Bu proje, kredi kartı dolandırıcılığını tespit etmek amacıyla çeşitli sinir ağı modelleri geliştirmeyi hedeflemektedir. Model performansını değerlendirirken basit sinir ağı, konvolüsyonel sinir ağı (CNN) ve derin sinir ağı (Deep NN) modelleri kullanılmıştır. Bu README dosyası, projenin amacını, veri setini, kullanılan modelleri ve sonuçları açıklar.

## İçindekiler
- Proje Amacı
- Veri Seti
- Kullanılan Modeller
- Sonuçlar ve Görselleştirme
- Geleceğe Yönelik Çalışmalar
- Kurulum ve Çalıştırma
## Lisans
Proje Amacı
Bu projede, kredi kartı dolandırıcılığı tespiti için çeşitli sinir ağı modelleri geliştirilmiş ve performansları karşılaştırılmıştır. Modellerin doğruluk oranlarını ve kayıplarını analiz ederek, dolandırıcılık tespitinde en etkili yaklaşım belirlenmiştir.

## Veri Seti
Kaynak: [Veri Seti Bağlantısı]
Açıklama: Veri seti, kredi kartı işlemleri ile ilgili çeşitli özellikleri içerir ve dolandırıcılık işlemlerini sınıflandırmak için kullanılır.
Sütunlar: İşlem ID, İşlem Türü, İşlem Tutarı, Zaman Damgası, Etiket (Dolandırıcılık / Normal)
## Kullanılan Modeller
Basit Sinir Ağı (Simple NN)

- Yapı: Tek gizli katman
- Aktivasyon Fonksiyonu: ReLU
- Çıkış Katmanı: Sigmoid
- Konvolüsyonel Sinir Ağı (CNN)

Yapı: 1D Konvolüsyon katmanı, MaxPooling katmanı, Düzleştirme (Flatten) katmanı, Yoğun (Dense) katman
Aktivasyon Fonksiyonları: ReLU, Sigmoid
Derin Sinir Ağı (Deep NN)

Yapı: Birden fazla gizli katman, Dropout katmanları
Aktivasyon Fonksiyonları: ReLU, Sigmoid
## Sonuçlar ve Görselleştirme
Model performansları, eğitim ve doğrulama kayıpları ile doğruluk metrikleri kullanılarak analiz edilmiştir. Eğitim süreçlerinin sonuçları, aşağıdaki grafiklerde görselleştirilmiştir:

- Eğitim ve doğrulama kayıpları grafiği
- Eğitim ve doğrulama doğrulukları grafiği
- Grafikler, her modelin eğitim sürecindeki performansını karşılaştırmak amacıyla hazırlanmıştır.

## Geleceğe Yönelik Çalışmalar
- Model Performansının İyileştirilmesi: Daha karmaşık model mimarileri ve hiperparametre optimizasyonları ile performans artırılabilir.
- Veri Çeşitliliği ve Zenginleştirilmesi: Yeni özellikler ve veri kaynakları eklenerek modelin doğruluğu geliştirilebilir.
- Gerçek Zamanlı Uygulama: Modellerin gerçek zamanlı veri akışları üzerinde çalışması ve otomatik dolandırıcılık tespiti sağlanabilir.
- Model Güvenliği ve Adalet: Model güvenliği ve tarafsızlık konularında çalışmalar yapılabilir.
## Kurulum ve Çalıştırma
Gereksinimler:

- Python 3.x
- TensorFlow
- Keras
- Pandas
- Matplotlib
- Seaborn

## Lisans
Bu proje MIT Lisansı altında lisanslanmıştır. Daha fazla bilgi için LICENSE dosyasına bakabilirsiniz.
  
