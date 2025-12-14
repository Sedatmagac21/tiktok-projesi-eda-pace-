# 🤳 TikTok Veri Analizi: İkili Sınıflandırma Modeli

### 📌 Giriş, Proje Amacı ve Önemi

Günümüzde sosyal medya platformlarındaki içerik akışı, doğru bilgiye ulaşmayı zorlaştırmakta ve içerik denetimi (content moderation) kritik bir öneme sahip olmaktadır. Bu proje, TikTok platformundan elde edilen gerçek dünya verilerini kullanarak, bir video içeriğinin içerdiği iddiaların **doğru (verify)** ya da **iddia (claim)** statüsünde olup olmadığını yüksek doğrulukla tahmin edebilen güçlü bir **ikili sınıflandırma modeli** geliştirmeyi amaçlamaktadır.

Geleneksel içerik denetimi süreçlerinin hızı ve ölçeği yetersiz kaldığından, bu proje, makine öğrenmesi yeteneklerini kullanarak sürece hız, tutarlılık ve nesnellik katmayı hedeflemektedir. Uygulanan analiz; Keşifçi Veri Analizi (EDA) ile veri setinin derinlemesine anlaşılmasını, Veri Mühendisliği ile model için en uygun özelliklerin hazırlanmasını ve son olarak, sağlam bir modelin eğitilmesi, test edilmesi ve performansının kapsamlı bir şekilde değerlendirilmesini içermektedir.

Bu çalışma, sadece teknik bir başarı değil, aynı zamanda büyük ölçekli içerik platformlarında bilgi doğruluğunu artırma potansiyeli taşıyan, iş kararlarını doğrudan etkileyebilecek değerli bir analiz sunmaktadır. Proje sonuçları ve model önerileri, iş paydaşlarına Yönetici Özeti (Executive Summary) formatında sunulmuştur.

### 🎯 Proje Hedefleri

Proje, Dördüncü Aşama (PACE) stratejisi çerçevesinde aşağıdaki hedeflere odaklanmıştır:

* **Planlama (Plan):** Proje strateji belgesindeki soruları tamamlamak.
* **Analiz (Analyze) & İnşa Etme (Construct):** Jupyter Notebook proje dosyasındaki soruları yanıtlamak.
* **Model Geliştirme:** İkili sınıflandırma görevini yerine getirecek en uygun makine öğrenmesi modelinin seçilmesi ve eğitilmesi.
* **Uygulama (Execute):** Modelin performans metriklerini (Doğruluk, Kesinlik, vb.) değerlendirmek ve sonuçları Yönetici Özeti olarak sunmak.

### 🧪 Metodoloji ve Teknik Adımlar

Bu proje, güçlü ve güvenilir bir model elde etmek için standart ML geliştirme adımlarını izlemiştir. [cite_start]Proje akışı dört ana göreve bölünmüştür:

1. **Görev 1:** Imports & data loading (İçe aktarmalar ve veri yükleme)].
2.  **Görev 2:** Data exploration (Veri keşfi).
3.  **Görev 3:** Statistical test(s) (İstatistiksel testler ve model oluşturma).
4.  **Görev 4:** Communicate insights with stakeholders (Paydaşlarla içgörülerin iletişimini sağlama).

### 📊 Veri Seti ve Model Seçimi

* **Veri Seti:** TikTok platformundan elde edilen `tiktok_dataset.csv` kullanılmıştır.
* **Hedef Değişken:** `claim_status` (Klaim durumu).
* **Model Tipi:** İkili Sınıflandırma (Binary Classification).

### 🛠️ Kullanılan Teknolojiler

* **Diller:** Python
* **Ortam:** Jupyter Notebook (`Exemplar_Course_3_TikTok_project_lab.ipynb`)
* **Veri Seti Dosyası:** `tiktok_dataset.csv`
* **Kütüphaneler:** `pandas`, `numpy`, `scikit-learn` (Modelleme), `matplotlib`/`seaborn` (EDA için varsayılmıştır).

### 🚀 Çalıştırma

Projenin analitik akışını ve model geliştirme adımlarını incelemek için ana Jupyter Notebook dosyasını çalıştırmanız gerekmektedir.

#### 1. Gerekli Kütüphaneleri Yükleme

```bash
# Gerekli temel kütüphaneleri yükleyin
pip install pandas numpy scikit-learn jupyter
```
### 2. Notebook'u Başlatma

jupyter notebook
