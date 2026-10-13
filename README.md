# eem4011-proje
EEM4011 Proje: Epileptik Nöbet Tespiti ve Sinyal Analizi
Bu depo, tıbbi sinyaller üzerinden anormallik tespiti (z > 3 kuralı) ve makine öğrenmesi algoritmaları kullanılarak epileptik nöbet pencerelerinin sınıflandırılması projesini içermektedir.

Veri Seti
Veri seti boyutu nedeniyle bu depoya eklenmemiştir. Veri setine buradan ulaşabilirsiniz: [VERİ SETİ LİNKİNİ BURAYA YAZ]

Kodu Çalıştırma
Proje Google Colab üzerinde geliştirilmiştir. Herhangi bir kurulum yapmadan aşağıdaki bağlantı üzerinden kodu tarayıcınızda inceleyebilir ve çalıştırabilirsiniz:
👉 Proje Kodlarını Colab'da Açmak İçin Tıklayın

Ana Sonuç
Veri setindeki aşırı sınıf dengesizliği (Sınıf 1: Nöbet anlarının azınlıkta olması) nedeniyle değerlendirme metriği olarak Accuracy yerine F1-Skoru kullanılmış, modelin nadir ve kritik vakaları (Recall) kaçırmama performansı optimize edilmiştir.
