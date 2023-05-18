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


  Makine öğrenmesi, bilgisayarların verilerden öğrenme ve tahmin yapma yeteneğine sahip olmasını sağlayan bir alan olarak büyük ilgi görmektedir. İşte makine öğrenmesi için bir yol haritası:

  1. Temel Matematik ve İstatistik: Makine öğrenmesi için matematiksel ve istatistiksel temelleri anlamak önemlidir. Lineer cebir, olasılık teorisi, istatistiksel çıkarım gibi konulara hakim olmanızı öneririm.

  2. Programlama Becerileri: Makine öğrenmesi için programlama dillerini öğrenmek önemlidir. Python, bu alanda yaygın olarak kullanılan bir dil olarak öne çıkmaktadır. Python'da veri manipülasyonu, veri analizi ve makine öğrenmesi kütüphanelerini kullanmayı öğrenmelisiniz.

  3. Veri Manipülasyonu ve Veri Görselleştirme: Veri manipülasyonu, veri ön işleme ve veri görselleştirme becerilerini geliştirmek, makine öğrenmesi projelerinde veriye ilişkin anlayışınızı artıracaktır. Pandas ve Matplotlib gibi Python kütüphanelerini öğrenmek bu aşamada faydalı olacaktır.

  4. Makine Öğrenmesi Temelleri: Makine öğrenmesi algoritmalarını ve temel kavramları öğrenmeye başlamalısınız. Denetimli ve denetimsiz öğrenme, sınıflandırma, regresyon, kümeleme gibi kavramlar üzerinde çalışmalısınız. Scikit-learn gibi Python kütüphaneleri, bu alanda kullanılan algoritmalara erişmenizi sağlayacaktır.

  5. Derin Öğrenme: Derin öğrenme, karmaşık yapılara sahip veriler üzerinde etkili olan bir makine öğrenme yöntemidir. Derin öğrenme için temel sinir ağı kavramlarını öğrenmelisiniz. TensorFlow ve Keras gibi kütüphaneler, derin öğrenme projelerinde kullanılan araçlardır.

  6. Model Değerlendirme ve Hata Analizi: Makine öğrenmesi modellerinin performansını değerlendirmek ve hataları analiz etmek önemlidir. Doğrulama kavramları, hata metrikleri ve hiperparametre ayarlaması gibi konular üzerinde çalışmalısınız.

  7. Uygulama ve Proje Geliştirme: Makine öğrenmesi uygulamaları ve projeleri geliştirmek, gerçek dünya verileri üzerinde pratik yapmanızı sağlar. Bu süreçte yeni veri setleriyle çalışmak, algoritmaları uygulamak ve sonuçları analiz etmek önemlidir.

  8. Güncel Gelişmeleri Takip Etmek: Makine öğrenmesi

## Dokümantasyonlar
* [Numpy Dokümanstasyon](https://numpy.org/doc/)
* [Pandas Dokümanstasyon](https://pandas.pydata.org/pandas-docs/stable/)
* [Scikit-learn Dokümanstasyon](https://scikit-learn.org/stable/index.html)
* [TensorFlow Dokümanstasyon](https://www.tensorflow.org/api_docs)
* [Keras Dokümanstasyon](https://keras.io/)
* [PyTorch Dokümanstasyon](https://pytorch.org/docs/stable/index.html)
* [Matplotlib Dokümanstasyon](https://matplotlib.org/stable/index.html)
* [Seaborn Dokümanstasyon](https://seaborn.pydata.org/tutorial.html)
* [XGBoost Dokümanstasyon](https://xgboost.readthedocs.io/en/stable/)
* [OpenCV Dokümanstasyon](https://docs.opencv.org/4.x/d9/df8/tutorial_root.html)

