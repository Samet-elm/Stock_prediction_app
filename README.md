## Proje Tanımı

SBFin, BIST100 endeksinde yer alan hisselerin son 5 yıllık günlük kapanış fiyatlarını temel alan bir zaman serisi tahmin projesidir. Projede, ham veriler öncelikle eksik değer analizi, sıralama, normalizasyon (Min-Max Scaling) ve ardışık zaman pencerelerine bölme işlemlerinden geçirilmiştir. Verilerin %70’i model eğitimi için, %30’u ise test ve tahmin süreci için ayrılmıştır. Zaman bağımlılığını öğrenebilen bir yapıya sahip olan LSTM (Long Short-Term Memory) sinir ağı modeli kullanılarak, gelecekteki fiyat hareketleri tahmin edilmiştir.

## Proje Amacı

Kullanıcıların şirketlere ait finansal verilere erişerek analiz yapabilmesi, karşılaştırmalar gerçekleştirebilmesi ve şeffaf bilgi akışı sağlanması hedeflenmektedir.

## Kullanılan Teknolojiler

- **Frontend**: HTML, CSS, JavaScript  
- **Backend**: Python (Flask / Django)  
- **Veritabanı**: MSSQL


## Düzenli bir paket yönetimi için Anaconda kullanabilirsiniz

## Gerekli paketler

```bash
  pip install numpy matplotlib pandas scikit-learn keras pillow```

##ncancoae
