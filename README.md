"""
Proje Başlığı: Türkiye Emlak Verileri ile Konut Fiyat Tahmini (Machine Learning Projesi)

Proje Amacı:
Gerçek emlak ilan verilerini kullanarak, kullanıcıdan alınan temel ev bilgileri (il, ilçe, m², oda sayısı, bina yaşı gibi) ile konut fiyatlarını tahmin edebilen uçtan uca bir makine öğrenmesi uygulaması geliştirmek.

Kapsanan Adımlar:
• Veri temizleme ve eksik/veri dışı değerlerin ayıklanması  
• price_per_m2 gibi türetilmiş değişkenlerin oluşturulması  
• Ortalama fiyat/m² üzerinden eksik değerlerin akıllı doldurulması  
• Logaritmik dönüşümle fiyat dağılımının normalize edilmesi  
• Pipeline ile standartlaştırma + Ridge regresyon modeli eğitimi  
• Kullanıcı girişiyle tahmin alma ve segmentasyon (düşük/orta/yüksek)  
• Doğruluk skoru (R² ≈ %99) ve görselleştirme ile model değerlendirmesi

🧩 Kullanılan Araçlar: Python, Pandas, Scikit-learn, Matplotlib
"""
