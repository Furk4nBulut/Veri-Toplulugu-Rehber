![logo](https://i.hizliresim.com/i7pztue.jpg)
# Manisa Celal Bayar Üniversitesi Veri Bilimi Topluluğu #
Bu sayfa Manisa Celal Bayar Üniversitesi **Veri Bilimi Topluluğu** üyeleri için hazırlanmış **Derin Öğrenme(Deep Learning)** rehberidir.
Veriye ilgi duyuyorsanız Veri Bilimi topluluğuna katılmak için [aktif üye formu](https://docs.google.com/forms/d/e/1FAIpQLSczMPDGLATvOFSniiMnODwOjb_2Io8aiC6PEPW_t3K88UR5bA/alreadyresponded) doldurabilirsiniz.

**Sosyal Medya Hesaplarımız**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?&style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/company/verimcbu/)
[![Github Badge](https://img.shields.io/badge/-Github-000?style=quare&labelColor=000&logo=Github&logoColor=white&link=link)](https://github.com/Veri-Web)
[![Instagram Badge](https://img.shields.io/badge/-Instagram-C13584?style=flat-quare&labelColor=C13584&logo=instagram&logoColor=white&link=link)](https://www.instagram.com/verimcbu/)    [![Twitter](https://img.shields.io/badge/Twitter-%231DA1F2.svg?&style=flat-square&logo=twitter&logoColor=white)](https://twitter.com/verimcbu)
[![Microsoft Teams](https://img.shields.io/badge/%20-Microsoft%20Teams-blue)](https://teams.microsoft.com/l/team/19%3a1CRwwN4CIxhszcmwMP21pOHAIIfz5NqqpnHvzTpdggI1%40thread.tacv2/conversations?groupId=43c41ff4-f472-4916-9b28-08e813dc9ed1&tenantId=e21375a3-27e8-43e1-9c27-82155d13eb80)


# İçindekiler

* **[Genel Bilgi](#genel-bilgi)** 
* **[Yol Haritası](#yol-haritası)**
* **[Algoritmalar](#algoritmalar)**
* **[Kullanım Alanları](#kullanım-alanları)**
* **[Kütüphaneler](#kütüphaneler)**
* **[Video Dersler](#Video-Dersler)**
* **[Kitaplar](#kitaplar)**
*  **[Bloglar](#bloglar)**
*  **[Bilimsel Makalaler](#bilimsel-makaleler)**
*  **[Google Colab](#google-colab)**

 ##  Genel Bilgi
  Derin öğrenme, yapay sinir ağları ve büyük veri setlerini kullanarak karmaşık problemleri çözmek için kullanılan bir makine öğrenme yöntemidir. Derin öğrenme, sinir ağlarının çok katmanlı yapısını kullanır ve veriye dayalı özelliklerin otomatik olarak öğrenilmesine odaklanır.

## Yol Haritası
### Temel Konular
* [Motivasyon: Yapay Zeka ve Derin Öğrenmenin Hikayesi](https://medium.com/deep-learning-turkiye/motivasyon-yapay-zeka-ve-derin-%C3%B6%C4%9Frenme-48d09355388d) (Merve Ayyüce Kızrak)
* [Derin Öğrenme Başlangıç Seti - Donanım Ve Yazılım](http://www.ardamavi.com/2017/10/derin-ogrenme-baslangic-seti.html) (Arda Mavi)
* [Derin Öğrenme 1](http://derindelimavi.blogspot.com.tr/2015/10/derin-ogrenme-1.html) (Birol Kuyumcu)
* [Derin Öğrenme 2](http://derindelimavi.blogspot.com.tr/2015/11/derin-ogrenme-2.html) (Birol Kuyumcu)
* [Derin Öğrenme 3](http://derindelimavi.blogspot.com.tr/2015/11/derin-ogrenme-3.html) (Birol Kuyumcu)
* [Derin Öğrenme , Yapay Zeka ve Bilgisayar Bilim](http://sayilarvekuramlar.blogspot.com/2015/12/bilgisayar-bilim-yapay-zeka.html) (Burak Bayramlı)
### Frameworks
* **[TensorFlow:](#TensorFlow)** Derin öğrenme için en popüler açık kaynaklı kütüphanelerden biridir. Çok sayıda önceden eğitilmiş model ve   derin öğrenme araçları sunar.
* **[Keras:](#Keras)** TensorFlow'un üzerine inşa edilen yüksek seviyeli bir derin öğrenme kütüphanesidir. Kullanımı kolay ve hızlı prototipler  oluşturmanıza olanak tanır.
* **[PyTorch:](#PyTorch)** Yine açık kaynaklı bir derin öğrenme kütüphanesidir. Dinamik grafikler kullanarak esnek bir şekilde model oluşturmanıza olanak sağlar.
* **[scikit-learn:](#scikit-learn)** Genel amaçlı bir makine öğrenimi kütüphanesidir. Derin öğrenme için önceden işleme, model seçimi ve   değerlendirme gibi bir dizi yardımcı işlev sunar.
* **[Theano:](#Theano)** Yüksek performanslı matematiksel işlemler yapabilen bir derin öğrenme kütüphanesidir. Biraz daha düşük seviyeli bir API'ye sahiptir ve TensorFlow ve Keras ile karşılaştırıldığında daha az popüler hale gelmiştir.
* **[Caffe:](#Caffe)** Hızlı ve etkili bir derin öğrenme kütüphanesidir. Özellikle görüntü sınıflandırma ve tanıma gibi görsel işleme problemlerinde yaygın olarak kullanılır.
* **[Julia:](#Julia)** Julia, açık kaynak kodlu, yüksek performanslı ve yüksek seviyede programlanabilen bir dil olarak derin öğrenmeye giriş için uygun bir platform oluşturmaktadır. Knet.j ise Julia üzerinde Deniz Yüret ve ortakları tarafından uygulanan derin öğrenme çerçevesidir. Knet.jl derin öğrenme modellerinin program fonksiyonlarına yakın bir dille tanımlanmasına izin vermekte, alt fonksiyonlar kullanarak kompleks modellerin kolaylıkla geliştirilmesine olanak sağlamakta, model eğitimi için gerekli türev ve güncelleştirme işlemlerini otomatikleştirerek kullanıcının model yapısına konsantre olmasını kolaylaştırmaktadır
*  **[MatConvNet:](#MatConvNet)** MatConvNet, derin öğrenme platformları ve kütüphanelerinden biridir. Derin öğrenme, yapay zekâ alanında çığır açmıştır. Derin Öğrenmeyle birlikte makineler ses, görüntü, sinyal, metin gibi verileri kullanarak sınıflandırma, nesne tanıma, ses tanıma ya da dil çevirileri gibi özelleşmiş görevleri en az hatayla yerine getirirler.


### Lineer Cebir
* **Vektörler ve Matrisler:** Lineer cebirde, vektörler ve matrisler temel yapı taşlarıdır. Vektörler, tek bir boyutlu verileri temsil ederken, matrisler iki boyutlu veri tablolarını temsil eder. Derin öğrenme uygulamalarında, genellikle ağırlıklar, özellikler ve gradyanlar gibi bilgileri temsil etmek için vektörler ve matrisler kullanılır.
* **Doğrusal Bağımlılık:** Bir vektörün diğer vektörler tarafından doğrusal bir kombinasyonu olarak ifade edilebilmesine doğrusal bağımlılık denir. Derin öğrenme uygulamalarında, özelliklerin doğrusal bağımlılığını analiz etmek, aşırı uyum (overfitting) veya özellik seçimi gibi sorunları ele almak için önemlidir.
* **Matris Çarpımı:** Matrislerin çarpılması, bir matrisi diğerine dönüştüren temel bir işlemdir. Derin öğrenme modellerinde, ağırlıkların ve özelliklerin matris çarpımı yoluyla hesaplanması yaygındır. Matris çarpımı, katmanlar arasındaki bağlantıları ve veri işleme süreçlerini temsil eder.
* **Transpoz:** Bir matrisin transpozu, matrisin satırlarını sütunlara ve sütunları satırlara dönüştüren işlemdir. Transpoz, matris çarpımında ve model parametrelerini güncellemede önemli bir rol oynar.
* **Lineer Denklem Sistemleri:** Derin öğrenme modelleri genellikle lineer denklem sistemlerini çözmek için kullanılır. Bu denklemler, verileri temsil eden matrisler ve hedef değerleri temsil eden vektörler arasında bir ilişkiyi ifade eder. Modellerin eğitimi, bu denklem sistemlerini çözmeyi ve model parametrelerini ayarlamayı içerir.
* **Eigenvektörler ve Eigendeğerler:** Bir matrisin eigenvektörleri, matrisin çarpımı sonucunda yalnızca bir ölçek faktörüyle değişmeyen vektörlerdir. Eigenvektörler ve eigendeğerler, derin öğrenme modellerinde boyut indirgeme, veri dönüşümü ve matrislerin özelliklerini anlamak için kullanılır.


### Olasılık-İstatistik
* **Olasılık Dağılımları:** Derin öğrenme modellerinde genellikle olasılık dağılımları kullanılır. Örneğin, sınıflandırma problemlerinde sınıflar arasındaki olasılık dağılımlarını tahmin etmek için kullanılır. En yaygın olarak kullanılan olasılık dağılımları arasında normal dağılım, Bernoulli dağılımı, çoknomiyal dağılım ve kategorik dağılım bulunur.
* **En olası tahmin (Maximum Likelihood):** Derin öğrenme modellerinde, veriye dayalı en olası tahmini yapmak için maksimum olabilirlik (maximum likelihood) yöntemi kullanılır. Bu, veriyi en iyi açıklayan model parametrelerini seçmek için kullanılan bir istatistiksel tahminleme yöntemidir.
* **Örnekleme (Sampling):** Derin öğrenme modelleri genellikle örnekleme işlemine dayalıdır. Örnekleme, olasılık dağılımlarına dayalı olarak yeni örnekler oluşturma sürecidir. Örneğin, jeneratif modeller, yeni görüntüler, metinler veya sesler oluşturmak için örnekleme işlemi kullanır.
* **İstatistiksel Testler:** Derin öğrenme modelleri geliştirirken, modelin performansını değerlendirmek için istatistiksel testler kullanılabilir. Örneğin, hipotez testleri veya çapraz doğrulama (cross-validation) gibi yöntemlerle modelin doğruluğunu, hatayı veya performansını istatistiksel olarak analiz etmek mümkündür.
* **Bayes Teorisi:** Bayes teorisi, derin öğrenme modellerinde istatistiksel çıkarımlar yapmak için kullanılan bir yöntemdir. Bayes teoremi, öncül bilgiyi ve veriyi birleştirerek sonuçları güncellemeyi sağlar. Bu, özellikle belirsizliklerin olduğu durumlarda model tahminlerini iyileştirmek için kullanılır.
* **Veri Ön İşleme ve Normalleştirme:** Derin öğrenme modelleri, veri ön işleme adımlarını içerir. Bu adımlar arasında veri normalleştirme, veri temizleme, boyut indirgeme, veri standartlaştırma gibi istatistiksel yöntemler yer alır. Bu işlemler, verinin modele daha iyi uymasını sağlar ve eğitim sürecini iyileştirir.

## Algoritmalar

### Algoritmalar için Püf Noktaları
* [Derin Öğrenme Uygulamalarında En Sık kullanılan Hiper-parametreler](https://medium.com/deep-learning-turkiye/derin-ogrenme-uygulamalarinda-en-sik-kullanilan-hiper-parametreler-ece8e9125c4) (Necmettin Çarkacı)
* [Derin Öğrenme Uygulamalarında Başarım İyileştirme (Regularization) Yöntemleri](https://medium.com/@necmettin.carkaci/derin-öğrenme-uygulamalarında-başarım-iyileştirme-yöntemleri-regularization-fb521e64c30f) (Necmettin Çarkacı)


### Yapay Sinir Ağları (Artificial Neural Networks)
* [Yapay Sinir Ağlarına Giriş](http://www.ardamavi.com/2017/07/sinir-aglari.html) (Arda Mavi)
* [Yapay Sinir Ağları](http://www.akanesen.com/2017/09/yapay-sinir-aglar.html) (Birol Akan Esen)
* [Yapay Sinir Ağları Temel Kavramlar: Perceptron, Skor fonksiyonu ve Hata hesaplaması(loss function)](https://www.linkedin.com/pulse/derin-öğrenme-uygulamalarında-temel-kavramlar-skor-ve-çarkacı/) (Necmettin Çarkacı)

### Evrişimli Sinir Ağları (Convolutional Neural Networks)
* [Derine Daha Derine: Evrişimli Sinir Ağları](https://medium.com/deep-learning-turkiye/deri%CC%87ne-daha-deri%CC%87ne-evri%C5%9Fimli-sinir-a%C4%9Flar%C4%B1-2813a2c8b2a9) (Merve Ayyüce Kızrak)
* [Evrişimli Sinir Ağlarına Giriş](http://www.ardamavi.com/2017/07/convolutional-networks.html) (Arda Mavi)
* [Tensorflow Tabanlı Keras ile MNIST Veriseti Üzerinde Çalışma](http://erdoganb.com/2017/04/kerastensorflow-ile-rakamlari-tanima-mnist-dataset/) (Erdoğan Bavaş)

### Kapsül Ağları (Capsule Networks)
* [Yapay Zekada Büyük Yenilik: Kapsül Ağları (Capsule Networks)](https://medium.com/deep-learning-turkiye/yapay-zekan%C4%B1n-yeni-ve-%C3%A7ekici-mimarisi-kaps%C3%BCl-a%C4%9F%C4%B1na-uygulamal%C4%B1-bir-bak%C4%B1%C5%9F-ef7310e3d847) (Merve Ayyüce Kızrak)

### Çekişmeli Üretici Ağlar (Generative Adversarial Networks)
* [Generative Adversarial Networks — GAN nedir ? ( Türkçe )](https://medium.com/@mubuyuk51/generative-adversarial-networks-gan-nedir-t%C3%BCrk%C3%A7e-5819fe9c1fa7) (Muhammed Buyukkınacı)




## Kullanım Alanları
### Doğal Dil İşleme (Natural Language Processing)
* [Keras ile Duygu Analizi](http://derindelimavi.blogspot.com.tr/2017/10/keras-ile-duygu-analizi.html) (Birol Kuyumcu)
* [Türkçe Metin İşlemede İlk Adımlar](http://www.veridefteri.com/2017/11/20/turkce-metin-islemede-ilk-adimlar/) (İlker Birbil)


### Bilgisayarlı Görü (Computer Vision)
* [10 Dakikada Görüntü Sınıflandıran Mobil Uygulama Geliştirin](https://medium.com/nsistanbul/10-dakikada-g%C3%B6r%C3%BCnt%C3%BC-s%C4%B1n%C4%B1fland%C4%B1ran-mobil-uygulama-geli%C5%9Ftirin-7567371839b0) (Özgür Şahin)

## Kütüphaneler
### TensorFlow
* [TenserFlow Documentaion](https://www.tensorflow.org/api_docs)

### Keras
* [Keras'a Giriş-1](http://derindelimavi.blogspot.com.tr/2017/01/keras-giris-1.html) (Birol Kuyumcu)
* [Keras'a Giriş-2 ( LSTM )](http://derindelimavi.blogspot.com.tr/2017/03/kerasa-giris-2-lstm.html) (Birol Kuyumcu)
* [Keras Türkçe Dokümantasyon](https://github.com/kemalcanbora/keras_turkish_doc) (Kemalcan Bora)
* [Keras Kurulumu](http://ibrahimdelibasoglu.blogspot.com.tr/2017/08/python-tensorflow-ile-keras-derin.html) (İbrahim Delibaşoğlu)
* [Keras ile Sonar Verisi Sınıflandırma](http://ibrahimdelibasoglu.blogspot.com.tr/2017/09/keras-ile-derin-ogrenmeye-giris-snflama.html) (İbrahim Delibaşoğlu)
* [Keras Documentation](https://keras.io/getting_started/)

### PyTorch
* [PyTorch ile Derin Öğrenmeye Giriş: Kurulum](https://medium.com/@ozgungenc/pytorch-ile-derin-%C3%B6%C4%9Frenmeye-giri%C5%9F-kurulum-2194a06ce0c) (Özgün Genç)
* [PyTorch Documentation](https://pytorch.org/docs/stable/index.html)

### Caffe
* [Caffe Kılavuzu - Tüm detaylarıyla Caffe ile çalışma rehberi](https://www.slideshare.net/bluekid/caffe-klavuzu) (Birol Kuyumcu)
* [Pratik Caffe Kullanımı](https://www.slideshare.net/bluekid/pratik-caffe) (Birol Kuyumcu)
* [Caffe Fine Tuning: Caffe'yi Kendi Verisetiniz ile Kullanma](http://blog.yavuzz.com/post/caffe-fine-tuning) (Yavuz Kömeçoğlu)
* [Windows İşletim Sistemi için Caffe Kurulumu](http://mesutpiskin.com/blog/windows-icin-caffe-kurulumu.html) (Mesut Pişkin)
* [Caffe Documentation](http://caffe.berkeleyvision.org/tutorial/)

### Scikit-learn
* [scikit-learn Documentation](https://scikit-learn.org/stable/index.html)

### Theano 
* [Theano Documentation](https://theano.readthedocs.io/en/0.8.x/)

### Julia
* [Julia Dokümantasyon](https://docs.julialang.org/en/v1/)
* [Julia ve Knet ile Derin Öğrenmeye Giriş](https://youtu.be/3TR3Rx-Esis) (Doç. Dr. Deniz Yuret) {104 dakika}

### MatConvNet
* [MatConvNet Dokümantasyon](https://www.vlfeat.org/matconvnet/#documentation)-
* [MatConvNet ve Matlab ile Derin Öğrenmeye Giriş](https://www.youtube.com/watch?v=nRVQQNw4Kh4&t=8s) (Ahmet Gökhan POYRAZ) {5 Video, eklemeler yapılacaktır}


## Video Dersler
* [Derin Öğrenme (Mustafa Selçuk Çağlar)](https://youtube.com/playlist?list=PLrPKUEV0N1BRO8uli-5-XysJSXcsl-nMM)
* [Keras İle Derin Öğrenme (Makine Öğrenmesi)](https://youtube.com/playlist?list=PLRRY18KNZTgUyaxSRvExF7zNsIpaehl5e)
* [Python ile Derin Öğrenme Yapay Zeka Dersleri (Tirendaz Akademi)](https://youtube.com/playlist?list=PLfMRLSpipmftdjM4l9u7adgDZGDM7vNLE)
* [6.S191: Introduction to Deep Learning Massachusetts Institute of Technology via Independent](https://www.classcentral.com/course/independent-6-s191-introduction-to-deep-learning-8083)
* [Deep Learning at Oxford 2015](https://youtube.com/playlist?list=PLE6Wd9FR--EfW8dtjAuPoTuPcqmOV53Fu)
* [Keras ile Derin Öğrenmeye Giriş (BTK Akademi)](https://www.btkakademi.gov.tr/portal/course/keras-ile-derin-ogrenmeye-giris-10599)
* [Ankara Deep Learning - Derin Öğrenme Etkinliği 1](https://youtu.be/K74rzKSsGs8) (Ferhat Kurt) {96 dakika}
* [Derin Öğrenmeye Derinlemesine Dalış](https://www.youtube.com/watch?v=zJPW6Lyf_Xs) (Şefik İlkin Serengil @Softtech Sahnesi) {52 dakika}
* [Derin Öğrenme: Dünü, Bugünü, Yarını](https://www.youtube.com/watch?v=ITCD2Z4jT8w) (Şefik İlkin Serengil @Bilgisayar Mühendisleri Odası) {100 dakika}
* [IoT ve Derin Öğrenme Etkinliği](https://youtu.be/fqf6m3R4psQ) (Ferhat Kurt) {82 dakika}
* [Keras Video Eğitim Serisi](https://www.youtube.com/watch?v=RNWjwdEQHOQ&list=PLRRY18KNZTgUyaxSRvExF7zNsIpaehl5e) (Mehmet Burak Sayıcı) {21 video, artmakta}
* [Julia ve Knet ile Derin Öğrenmeye Giriş](https://youtu.be/3TR3Rx-Esis) (Doç. Dr. Deniz Yuret) {104 dakika},
* [MatConvNet ve Matlab ile Derin Öğrenmeye Giriş](https://www.youtube.com/watch?v=nRVQQNw4Kh4&t=8s) (Ahmet Gökhan POYRAZ) {5 Video, eklemeler yapılacaktır}



## Kitaplar
* [Deep Learning An MIT Press Book](https://www.deeplearningbook.org/)
* [Neural Networks and Deep Learning free online book](http://neuralnetworksanddeeplearning.com/)
* [MIT Deep Learning Book]( https://github.com/janishar/mit-deep-learning-book-pdf/tree/master/complete-book-pdf)
#### Ücretli Kitaplar
* [Yapay Öğrenme - Ethem Alpaydın](http://www.idefix.com/Kitap/Yapay-Ogrenme/Ethem-Alpaydin/Bilim/Populer-Bilim/urunno=0000000362293)
* [Derin Öğrenme - Ian Goodfellow, Yoshua Bengio, Aaron Courville](https://www.kitapyurdu.com/kitap/derin-ogrenme-ciltli/480279.html)
* [OpenCv Görüntü İşleme ve Yapay Öğrenme - Birol Kuyumcu](http://www.kitapyurdu.com/kitap/opencv-goruntu-isleme-ve-yapay-ogrenme/376463.html)
* [Yapay Zeka - Vasif Vagifoğlu Nabiyev](http://www.dr.com.tr/Kitap/Yapay-Zeka-Problemler-Yontemler-Algoritma-/Vasif-Vagifoglu-Nabiyev/Bilim/Populer-Bilim/urunno=0000000435115)
* [Derin Öğrenme - Ian Goodfellow, Yoshua Bengio, Aaron Courville](https://www.kitapyurdu.com/kitap/derin-ogrenme-ciltli/480279.html)


## Bloglar
* [Deep Learning Türkiye Blog](http://medium.com/deep-learning-turkiye)
* [veridefteri.com](http://veridefteri.com/)
* [alpslabel.wordpress.com](https://alpslabel.wordpress.com//)
* [makineogrenimi.wordpress.com](https://makineogrenimi.wordpress.com)
* [devhunteryz.wordpress.com](https://devhunteryz.wordpress.com)

## Bilimsel Makaleler
### Genel (Review/Survey)
* [Derin Öğrenme Yöntemleri ve Uygulamaları Hakkında Bir İnceleme](https://dergipark.org.tr/tr/pub/gmbd/issue/31064/372661) (Abdulkadir Şeker, Banu Diri, Hasan Hüseyin Balık )
### Bilgisayarlı Görü (Computer Vision)
* [Face Recognition Classifier Based on Dimension Reduction in Deep Learning Properties](http://ieeexplore.ieee.org/document/7960368/) (Ahmet Bilgiç, Onur Can Kurban, Tülay Yıldırım)
* [Signature recognition application based on deep learning](http://ieeexplore.ieee.org/abstract/document/7960454/) (Nurullah Çalık, 
Onur Can Kurban, Ali Rıza Yılmaz, Lütfiye Durak Ata, Tülay Yıldırım)

## Google Colab
* [Kapsamlı Derin Öğrenme Rehberi](https://colab.research.google.com/github/ayyucekizrak/Kapsamli_Derin_Ogrenme_Rehberi/blob/master/Kapsaml%C4%B1_Derin_%C3%96%C4%9Frenme_Rehberi.ipynb)
* [Google Colab ile Ücretsiz GPU Kullanımı](https://medium.com/deep-learning-turkiye/google-colab-ile-%C3%BCcretsiz-gpu-kullan%C4%B1m%C4%B1-30fdb7dd822e) (Fuat)

## Github
* [Python ve Derin Öğrenme Pytorch ile Derin Öğrenme (5.3)](https://github.com/dataiteam/7-ADIMLIK-YAPAY-ZEKA-YOLCULUGU/tree/master/Python%20ve%20Derin%20%C3%96%C4%9Frenme%20Pytorch%20ile%20Derin%20%C3%96%C4%9Frenme%20(5.3))

### [Sayfa Başına Dönmek için Tıkla](#İçindekiler)
### [Anasayfaya Dönüş için Tıkla](https://github.com/Furk4nBulut/Veri-Billimi-Toplulugu-Rehber)

