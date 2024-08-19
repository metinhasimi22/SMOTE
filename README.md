# SMOTE
SMOTE Analysis
![awan_introduction_smote_2](https://github.com/user-attachments/assets/1bd054ff-3c03-4620-92ef-42c8b56aab41)


### 🔍 SMOTE Analysis: Balancing Imbalanced Datasets 🔍

**SMOTE (Synthetic Minority Over-sampling Technique)**, imbalanced veri setlerinde azınlık sınıfını dengelemek için kullanılan bir yöntemdir. Bu teknik, azınlık sınıfındaki örneklerin yeni, sentetik versiyonlarını oluşturur, böylece model eğitiminde daha dengeli bir veri seti sağlanır.

---

#### 🚀 **Adımlar:**
1. **K-NN Kullanımı:** 
   - Azınlık sınıfındaki bir örnek seçilir ve k-nearest neighbors (k-en yakın komşu) algoritması ile komşuları belirlenir.

2. **Sentetik Örnekler Üretme:** 
   - Seçilen örnek ile komşuları arasında rastgele bir noktada yeni bir sentetik örnek oluşturulur.

3. **Denge Sağlama:** 
   - Bu işlem, azınlık sınıfının sayısı çoğaltılana kadar tekrarlanır, böylece veri seti daha dengeli hale gelir.

---

💡 **Sonuç:** SMOTE, sınıf dengesizliği problemini çözmeye yardımcı olarak model performansını artırır.
