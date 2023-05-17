![logo](https://i.hizliresim.com/2qlnhq0.jpg)
# Manisa Celal Bayar Üniversitesi Veri Bilimi Topluluğu #
Bu sayfa Manisa Celal Bayar Üniversitesi **Veri Bilimi Topluluğu** üyeleri için hazırlanmış **Derin Öğrenme(Deep Learning)** rehberidir.
Veriye ilgi duyuyorsanız Veri Bilimi topluluğuna katılmak için [aktif üye formu](https://docs.google.com/forms/d/e/1FAIpQLSczMPDGLATvOFSniiMnODwOjb_2Io8aiC6PEPW_t3K88UR5bA/alreadyresponded) doldurabilirsiniz.

**Sosyal Medya Hesaplarımız**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?&style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/company/verimcbu/)
[![Github Badge](https://img.shields.io/badge/-Github-000?style=quare&labelColor=000&logo=Github&logoColor=white&link=link)](https://github.com/Veri-Web)
[![Instagram Badge](https://img.shields.io/badge/-Instagram-C13584?style=flat-quare&labelColor=C13584&logo=instagram&logoColor=white&link=link)](https://www.instagram.com/verimcbu/)    [![Twitter](https://img.shields.io/badge/Twitter-%231DA1F2.svg?&style=flat-square&logo=twitter&logoColor=white)](https://twitter.com/verimcbu)


# İçindekiler

* **[Genel Bilgi](#genel-bilgi)** 
* **[Yol Haritası](#yol-haritası)**
* **[Dokümantasyonlar](#Dokümantasyonlar)**
* **[Kütüphaneler](#Kütüphaneler)**
* **[Kitaplar](#kitaplar)**

## Genel Bilgi
  Makine öğrenmesi (Machine Learning), bilgisayar sistemlerinin veriye dayalı deneyimlerden öğrenerek, belirli görevleri gerçekleştirebilmelerini sağlayan bir yapay zeka dalıdır. Makine öğrenmesi algoritmaları, veriler üzerinde istatistiksel analizler yaparak desenler, ilişkiler ve trendler bulmayı hedefler. Bu desenler ve ilişkiler kullanılarak gelecekteki verileri tahmin etme, sınıflandırma, gruplandırma, öneri sistemleri oluşturma gibi birçok görev gerçekleştirilebilir.

  Makine öğrenmesi genellikle iki ana kategoriye ayrılır:

  1. İz supervised learning): İzlenen öğrenme, giriş verileriyle birlikte hedef çıktı verilerini kullanarak bir modelin eğitildiği bir öğrenme yöntemidir. Bu yöntemde, model, giriş verilerini analiz ederek belirli bir hedefe ulaşmak için desenleri tanımayı öğrenir. Örneğin, bir evin özelliklerine dayanarak evin fiyatını tahmin etmek gibi bir problemde, model, evin özelliklerini (odaların sayısı, metrekare, konum vb.) kullanarak fiyatı tahmin etmeyi öğrenir.

  2. İzlenmeyen öğrenme (unsupervised learning): İzlenmeyen öğrenme, hedef çıktı verilerinin olmadığı, yani sadece giriş verilerinin bulunduğu bir öğrenme yöntemidir. Bu yöntemde, model, veriler arasındaki desenleri ve yapıları keşfetmeye çalışır. Kümeleme (clustering) veya boyut indirgeme (dimensionality reduction) gibi tekniklerle veri setini analiz eder. Örneğin, bir müşteri veri setinde, müşterilerin benzerliklerine dayanarak gruplara ayırma gibi bir problemde, model benzer özelliklere sahip müşterileri gruplandırabilir.

  Makine öğrenmesinde kullanılan algoritmalar çeşitlilik gösterir. Bunlar arasında en yaygın olanları karar ağaçları (decision trees), destek vektör makineleri (support vector machines), doğrusal regresyon (linear regression), lojistik regresyon (logistic regression), yapay sinir ağları (artificial neural networks), derin öğrenme (deep learning) gibi yöntemlerdir.

  Makine öğrenmesi uygulamaları birçok alanda kullanılmaktadır, örneğin:
  - Görüntü ve ses tanıma
  - Doğal dil işleme
  - Otomatik araç kontrolü
  - Finansal piyasa analizi ve tahminleri
  - Sağlık sektöründe hastalık teşhisi

## Yol Haritası
* **[NumPy:]()** Sayısal hesaplamalar ve çok boyutlu diziler için temel bir kütüphane. Makine öğrenmesi için veri manipülasyonu için sıklıkla kullanılır.
* **[Pandas:]()** Veri analizi ve manipülasyonu için kullanılan bir kütüphane. Tablo verileriyle çalışmak için etkili bir araçtır.
* **[Scikit-learn:]()** Python'da en popüler makine öğrenmesi kütüphanelerinden biridir. Çeşitli makine öğrenmesi algoritmaları, model seçimi, veri ön işleme ve değerlendirme araçları sunar.
* **[TensorFlow:]()** Açık kaynaklı bir makine öğrenmesi kütüphanesidir. Derin öğrenme için özellikle popülerdir ve nesne tanıma, doğal dil işleme, ses işleme gibi uygulamalarda kullanılır.
* **[Keras:]()** Yüksek seviyeli bir yapay sinir ağı kütüphanesidir ve TensorFlow üzerinde çalışır. Kolay kullanımı ve hızlı prototipleme yetenekleri nedeniyle tercih edilir.
* **[PyTorch:]()** Yine derin öğrenme için popüler bir açık kaynaklı kütüphanedir. Dinamik grafik hesaplama özelliğine sahip olmasıyla dikkat çeker.
* **[Matplotlib:]()** Görselleştirme aracıdır. Veri görselleştirmesi ve grafik oluşturmak için kullanılır.
* **[Seaborn:]()** Matplotlib'e dayalı bir istatistiksel veri görselleştirme kütüphanesidir. Veri keşfi ve görselleştirme için daha yüksek seviye bir arayüz sunar.
* **[XGBoost:]()** Gradient boosting yöntemini uygulayan etkili bir makine öğrenmesi kütüphanesidir. Özellikle yapılandırılmış verilerle çalışmak için kullanılır.
* **[OpenCV:]()** Bilgisayarlı görü ve görüntü işleme için kullanılan açık kaynaklı bir kütüphanedir. Nesne tanıma, yüz tanıma, görüntü işleme gibi uygulamalarda yaygın olarak kullanılır.
