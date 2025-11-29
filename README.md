Bu proje, ISIC 2018 Skin Lesion Dataset kullanılarak çeşitli görüntü işleme tekniklerinin uygulanmasını içeren bir Jupyter Notebook çalışmasıdır.
Notebook içinde hem RGB hem de grayscale görüntüler üzerinde:
- Veri yükleme ve inceleme
- Görüntü görselleştirme
- Histogram analizleri
- Kontrast germe
- Histogram eşitleme
- Gamma düzeltme
- Gürültü azaltma (Median – Gaussian)
- Döndürme ve ayna çevirme
- FFT ile frekans alanı filtresi
- Unsharp masking (keskinleştirme)
- Bicubic enterpolasyon ile büyütme
adım adım uygulanmaktadır.

Hata alınması durumunda yüklenmesi gereken paketler ==> %pip install opencv-python numpy pandas matplotlib seaborn
Eğer Jupyter yoksa ==> %pip install jupyter
