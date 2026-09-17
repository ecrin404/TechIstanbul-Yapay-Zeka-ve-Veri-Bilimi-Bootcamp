# Tech Istanbul - Python ile Veri Bilimi ve Yapay Zeka Bootcamp

Bu repository, **Tech Istanbul Veri Bilimi ve Yapay Zeka Bootcamp** süresince gerçekleştirilen Python temelleri, makine öğrenmesi algoritmaları, derin öğrenme ve nesne tespiti projelerini içermektedir. 

Eğitim boyunca temel programlama kavramlarından başlayarak uçtan uca veri bilimi ve yapay zeka modellerinin geliştirilmesi, Colab ortamında test edilmesi ve konsol tabanlı bütünleşik projelere dönüştürülmesi sağlanmıştır.

---

## 📂 Repo İçeriği

Repoda yer alan temel notebook ve proje dosyaları şu şekildedir:

1. **Temel Python ve Veri Yapıları:**
   - Değişkenler, tipler, koleksiyonlar (list, dict, set, tuple) ve kontrol akışı (`if`, `for`, `while`).
   - Fonksiyonlar, hata yönetimi (`try-except`) ve dosya işlemleri.

2. **Makine Öğrenmesi & Regresyon Modelleri:**
   - Doğrusal Regresyon, Ridge, PCR (Principal Component Regression) ve PLS (Partial Least Squares) analizleri.
   - Reklam ve ev fiyatları veri setleri üzerinde modelleme ve hata optimizasyonu.

3. **Doğrusal Olmayan Modeller ve Sınıflandırma:**
   - KNN, SVR, Karar Ağaçları (CART), Random Forest, AdaBoost, Lojistik Regresyon ve Destek Vektör Makineleri (SVM) uygulamaları.

4. **Yapay Sinir Ağları ve Derin Öğrenme:**
   - Sıfırdan gradyan inişi (`gradient descent`) hesaplamaları.
   - Keras/TensorFlow ile Yapay Sinir Ağları (YSA) ve **Fashion-MNIST** veri seti ile Görüntü Sınıflandırma (**CNN**).
   - **IMDB Dataset** üzerinde **SimpleRNN** ile Metin Duygu Analizi (NLP).

5. **Nesne Tespiti (Object Detection):**
   - Detectron2 ve Faster R-CNN altyapısı kullanılarak özel veri setlerinde nesne tespiti ve çıkarımı.

6. **Bitirme Projesi (Bütünleşik Konsol Uygulaması):**
   - Regresyon, kümeleme, metin duygu analizi ve görüntü sınıflandırma yöntemlerini menü tabanlı tek bir yapıda birleştiren, sonuçları otomatik olarak `.txt` dosyasına kaydeden kapsamlı bir bitirme uygulaması (`bitirme_projesi_butunlesik_ml.ipynb`).

---

## 🛠️ Kullanılan Teknolojiler ve Kütüphaneler

* **Dil:** Python
* **Ortam:** Google Colab / Jupyter Notebook
* **Veri Analizi & Manipülasyon:** Pandas, NumPy
* **Görselleştirme:** Matplotlib, Seaborn
* **Makine Öğrenmesi:** Scikit-Learn
* **Derin Öğrenme:** TensorFlow, Keras, Detectron2 (PyTorch tabanlı)

---

## 🚀 Çalıştırma Rehberi

Projeleri incelemek veya Google Colab üzerinde çalıştırmak için ilgili `.ipynb` uzantılı notebook dosyasını açabilir ya da GitHub üzerindeyken **"Open in Colab"** rozetini kullanabilirsiniz. 

Harici veri seti gerektiren projelerde (örneğin bitirme projesi), kod bloğu içerisindeki `gdown` komutları ilgili verileri Google Drive üzerinden otomatik olarak indirecektir.

---

* **Program:** Tech Istanbul Veri Bilimi ve Yapay Zeka Bootcamp
* **Eğitmen:** Battal Koç
