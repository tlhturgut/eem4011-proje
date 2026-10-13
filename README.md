# Epilepsi Nöbeti Tahmini için EEG Zaman Serisi Analizi

Bu proje, EEM4011 Biyomedikal Programlama dersi kapsamında geliştirilmiştir.

**Veri Seti:** 
Veri setinin boyutu nedeniyle dosyalar (.edf) bu depoya eklenmemiştir. Kod, çalıştırıldığında PhysioNet CHB-MIT Scalp EEG veritabanından ilgili kayıtları (`chb01_03`, `chb02_16` ve `chb03_01`) otomatik olarak indirmektedir.
Veri seti linki: https://physionet.org/content/chbmit/1.0.0/

**Çalıştırma Adımları:**
Kodlar Google Colab üzerinde yazılmıştır. Depodaki `.ipynb` dosyasını kendi Colab ortamınıza yükleyerek veya yerel bir Jupyter Notebook ortamında çalıştırabilirsiniz. Kod, gerekli olan `mne` kütüphanesini ilk hücrede otomatik olarak kurar.

**Ana Sonuç:**
Çizgi uzunluğu (line length) özniteliği ve z-skoru yöntemi kullanılarak hasta bazlı (leave-one-patient-out) ayrım ile ulaşılan ortalama genel baseline F1 skoru: **0.274**'tür (İyimser hastaya özel üst sınır: 0.519).
