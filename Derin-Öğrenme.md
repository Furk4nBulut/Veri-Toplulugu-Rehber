![logo](https://i.hizliresim.com/i7pztue.jpg)
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
* **[Video Dersler](#Video-Dersler)**
* **[Kitaplar](#kitaplar)**

 ##  Genel Bilgi
  Derin öğrenme, yapay sinir ağları ve büyük veri setlerini kullanarak karmaşık problemleri çözmek için kullanılan bir makine öğrenme yöntemidir. Derin öğrenme, sinir ağlarının çok katmanlı yapısını kullanır ve veriye dayalı özelliklerin otomatik olarak öğrenilmesine odaklanır.

  Derin öğrenme, birçok farklı uygulama alanında etkili olmuştur, özellikle görüntü ve ses tanıma, doğal dil işleme, otomatik sürüş, oyun oynama ve tıp gibi alanlarda büyük başarı elde etmiştir.

  Derin öğrenme algoritmaları, veri setlerinden örneklerle beslenir ve bu örnekleri analiz ederek veri içindeki desenleri ve ilişkileri algılamaya çalışır. Bu işlem, ağın birçok katmanında gerçekleştirilir ve her bir katman, önceki katmanın çıktılarından yeni özellikler öğrenir. Bu sayede, derin öğrenme modelleri, karmaşık ve soyut kavramları algılayabilme yeteneğine sahiptir.

  Derin öğrenme modelleri, genellikle büyük veri setleri üzerinde eğitilir. Bu veri setleri, genellikle insan uzmanları tarafından etiketlenmiş veya kategorize edilmiş veriler içerir. Eğitim süreci, ağırlık değerlerini güncelleyerek ve hata fonksiyonunu minimize ederek gerçekleştirilir. Daha sonra eğitilen model, yeni girdileri analiz ederek tahminlerde bulunabilir veya problemleri çözebilir.

  Derin öğrenme, geleneksel makine öğrenme yöntemlerine göre daha yüksek düzeyde otomatiklik ve veriye dayalı özellik öğrenimi sağlar. Ancak derin öğrenme modelleri, büyük miktarda veri ve hesaplama gücü gerektirebilir. Ayrıca, bu modellerin eğitim süreci karmaşık ve zaman alıcı olabilir.

## Yol Haritası
### Frameworks
* **[TensorFlow:](#TensorFlow)** Derin öğrenme için en popüler açık kaynaklı kütüphanelerden biridir. Çok sayıda önceden eğitilmiş model ve   derin öğrenme araçları sunar.

* **[Keras:](#Keras)** TensorFlow'un üzerine inşa edilen yüksek seviyeli bir derin öğrenme kütüphanesidir. Kullanımı kolay ve hızlı prototipler  oluşturmanıza olanak tanır.

* **[PyTorch:](#PyTorch)** Yine açık kaynaklı bir derin öğrenme kütüphanesidir. Dinamik grafikler kullanarak esnek bir şekilde model oluşturmanıza olanak sağlar.

* **[scikit-learn:](#scikit-learn)** Genel amaçlı bir makine öğrenimi kütüphanesidir. Derin öğrenme için önceden işleme, model seçimi ve   değerlendirme gibi bir dizi yardımcı işlev sunar.

* **[Theano:](#Theano)** Yüksek performanslı matematiksel işlemler yapabilen bir derin öğrenme kütüphanesidir. Biraz daha düşük seviyeli bir API'ye sahiptir ve TensorFlow ve Keras ile karşılaştırıldığında daha az popüler hale gelmiştir.

* **[Caffe:](#Caffe)** Hızlı ve etkili bir derin öğrenme kütüphanesidir. Özellikle görüntü sınıflandırma ve tanıma gibi görsel işleme problemlerinde yaygın olarak kullanılır.

### Lineer Cebir
* **[Vektörler ve Matrisler:]** Lineer cebirde, vektörler ve matrisler temel yapı taşlarıdır. Vektörler, tek bir boyutlu verileri temsil ederken, matrisler iki boyutlu veri tablolarını temsil eder. Derin öğrenme uygulamalarında, genellikle ağırlıklar, özellikler ve gradyanlar gibi bilgileri temsil etmek için vektörler ve matrisler kullanılır.

* **[Doğrusal Bağımlılık:]** Bir vektörün diğer vektörler tarafından doğrusal bir kombinasyonu olarak ifade edilebilmesine doğrusal bağımlılık denir. Derin öğrenme uygulamalarında, özelliklerin doğrusal bağımlılığını analiz etmek, aşırı uyum (overfitting) veya özellik seçimi gibi sorunları ele almak için önemlidir.

* **[Matris Çarpımı:]** Matrislerin çarpılması, bir matrisi diğerine dönüştüren temel bir işlemdir. Derin öğrenme modellerinde, ağırlıkların ve özelliklerin matris çarpımı yoluyla hesaplanması yaygındır. Matris çarpımı, katmanlar arasındaki bağlantıları ve veri işleme süreçlerini temsil eder.

* **[Transpoz:]** Bir matrisin transpozu, matrisin satırlarını sütunlara ve sütunları satırlara dönüştüren işlemdir. Transpoz, matris çarpımında ve model parametrelerini güncellemede önemli bir rol oynar.

* **[Lineer Denklem Sistemleri:]** Derin öğrenme modelleri genellikle lineer denklem sistemlerini çözmek için kullanılır. Bu denklemler, verileri temsil eden matrisler ve hedef değerleri temsil eden vektörler arasında bir ilişkiyi ifade eder. Modellerin eğitimi, bu denklem sistemlerini çözmeyi ve model parametrelerini ayarlamayı içerir.

* **[Eigenvektörler ve Eigendeğerler:]** Bir matrisin eigenvektörleri, matrisin çarpımı sonucunda yalnızca bir ölçek faktörüyle değişmeyen vektörlerdir. Eigenvektörler ve eigendeğerler, derin öğrenme modellerinde boyut indirgeme, veri dönüşümü ve matrislerin özelliklerini anlamak için kullanılır.
### Olasılık-İstatistik
* **[Olasılık Dağılımları:]** Derin öğrenme modellerinde genellikle olasılık dağılımları kullanılır. Örneğin, sınıflandırma problemlerinde sınıflar arasındaki olasılık dağılımlarını tahmin etmek için kullanılır. En yaygın olarak kullanılan olasılık dağılımları arasında normal dağılım, Bernoulli dağılımı, çoknomiyal dağılım ve kategorik dağılım bulunur.

* **[En olası tahmin (Maximum Likelihood):]** Derin öğrenme modellerinde, veriye dayalı en olası tahmini yapmak için maksimum olabilirlik (maximum likelihood) yöntemi kullanılır. Bu, veriyi en iyi açıklayan model parametrelerini seçmek için kullanılan bir istatistiksel tahminleme yöntemidir.

* **[Örnekleme (Sampling):]** Derin öğrenme modelleri genellikle örnekleme işlemine dayalıdır. Örnekleme, olasılık dağılımlarına dayalı olarak yeni örnekler oluşturma sürecidir. Örneğin, jeneratif modeller, yeni görüntüler, metinler veya sesler oluşturmak için örnekleme işlemi kullanır.

* **[İstatistiksel Testler:]** Derin öğrenme modelleri geliştirirken, modelin performansını değerlendirmek için istatistiksel testler kullanılabilir. Örneğin, hipotez testleri veya çapraz doğrulama (cross-validation) gibi yöntemlerle modelin doğruluğunu, hatayı veya performansını istatistiksel olarak analiz etmek mümkündür.

* **[Bayes Teorisi:]** Bayes teorisi, derin öğrenme modellerinde istatistiksel çıkarımlar yapmak için kullanılan bir yöntemdir. Bayes teoremi, öncül bilgiyi ve veriyi birleştirerek sonuçları güncellemeyi sağlar. Bu, özellikle belirsizliklerin olduğu durumlarda model tahminlerini iyileştirmek için kullanılır.

* **[Veri Ön İşleme ve Normalleştirme:]** Derin öğrenme modelleri, veri ön işleme adımlarını içerir. Bu adımlar arasında veri normalleştirme, veri temizleme, boyut indirgeme, veri standartlaştırma gibi istatistiksel yöntemler yer alır. Bu işlemler, verinin modele daha iyi uymasını sağlar ve eğitim sürecini iyileştirir.

## Dokümantasyonlar

* [TenserFlow Documentaion](https://www.tensorflow.org/api_docs)
* [Keras Documentation](https://keras.io/getting_started/)
* [PyTorch Documentation](https://pytorch.org/docs/stable/index.html)
* [scikit-learn Documentation](https://scikit-learn.org/stable/index.html)
* [Theano Documentation](https://theano.readthedocs.io/en/0.8.x/)
* [Caffe Documentation](http://caffe.berkeleyvision.org/tutorial/)

## Kütüphaneler

### TensorFlow
* [TenserFlow Documentaion](https://www.tensorflow.org/api_docs)

### Keras
* [Keras Documentation](https://keras.io/getting_started/)

### PyTorch
* [PyTorch Documentation](https://pytorch.org/docs/stable/index.html)
* [Deep Learning with PyTorrch](https://drive.google.com/file/d/1BIqGpwNqS9pipQ_hxRXiGXTT-5jcmp3m/view?usp=share_link)

### scikit-learn
* [scikit-learn Documentation](https://scikit-learn.org/stable/index.html)

### Theano
* [Theano Documentation](https://theano.readthedocs.io/en/0.8.x/)


### Caffe
* [Caffe Documentation](http://caffe.berkeleyvision.org/tutorial/)

## Video Dersler
* [Derin Öğrenme (Mustafa Selçuk Çağlar)](https://youtube.com/playlist?list=PLrPKUEV0N1BRO8uli-5-XysJSXcsl-nMM)
* [Keras İle Derin Öğrenme (Makine Öğrenmesi)](https://youtube.com/playlist?list=PLRRY18KNZTgUyaxSRvExF7zNsIpaehl5e)
* [Python ile Derin Öğrenme Yapay Zeka Dersleri (Tirendaz Akademi)](https://youtube.com/playlist?list=PLfMRLSpipmftdjM4l9u7adgDZGDM7vNLE)
* [6.S191: Introduction to Deep Learning Massachusetts Institute of Technology via Independent](https://www.classcentral.com/course/independent-6-s191-introduction-to-deep-learning-8083)
* [Deep Learning at Oxford 2015](https://youtube.com/playlist?list=PLE6Wd9FR--EfW8dtjAuPoTuPcqmOV53Fu)


## Kitaplar
* [Statistics The Art and Science of Learning from Data 4th edition](https://drive.google.com/file/d/1CVGQBlWLVsAmirdD6I6tRleIFuE-s_0k/view?usp=share_link)
* [Deep Learning For Python(François Chollet)](https://drive.google.com/file/d/1_YzIFKzHRFutZ0hEeuoykCO-ORiAWI9E/view?usp=share_link)
* [Grokking Deep Learning - Meap](https://drive.google.com/file/d/1DO25smHOFW300OZ6CaCrO6yfJLSgO9qW/view?usp=share_link) 
* [Deep Learning For Computer Vision (Muhommed Elgendy)](https://drive.google.com/file/d/1tRUFxXMsCj2XCPPu8HoFBIuMcoKhuN18/view?usp=share_link)
* [Deep Learning An MIT Press Book](https://www.deeplearningbook.org/)
* [Neural Networks and Deep Learning free online book](http://neuralnetworksanddeeplearning.com/)




