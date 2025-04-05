## Proje Tanımı

SBFin, BIST100 endeksinde yer alan hisselerin son 5 yıllık günlük kapanış fiyatlarını temel alan bir zaman serisi tahmin projesidir. Projede, ham veriler öncelikle eksik değer analizi, sıralama, normalizasyon (Min-Max Scaling) ve ardışık zaman pencerelerine bölme işlemlerinden geçirilmiştir. Verilerin %70’i model eğitimi için, %30’u ise test ve tahmin süreci için ayrılmıştır. Zaman bağımlılığını öğrenebilen bir yapıya sahip olan LSTM (Long Short-Term Memory) sinir ağı modeli kullanılarak, gelecekteki fiyat hareketleri tahmin edilmiştir.

## Proje Amacı

Kullanıcıların şirketlere ait finansal verilere erişerek analiz yapabilmesi, karşılaştırmalar gerçekleştirebilmesi ve şeffaf bilgi akışı sağlanması hedeflenmektedir.

## Kullanılan Teknolojiler

- **Frontend**: HTML, CSS, JavaScript  
- **Backend**: Python (Flask / Django)  
- **Veritabanı**: MSSQL

## Gerekli paketler
  
`numpy, matplotlib, pandas, scikit-learn, keras, pillow`

-Düzenli bir bağımlılık yönetimi için anaconda kullanabilirsiniz
-Eğer Anaconda'yı henüz yüklemediyseniz, [Anaconda'yı buradan indirin](https://www.anaconda.com/products/individual) ve işletim sisteminize uygun talimatları takip edin.

*Anaconda kurulduktan sonra, **Anaconda Prompt**'u (veya terminalinizi) açın ve aşağıdaki komutu çalıştırarak yeni bir sanal ortam oluşturun (env_name yerine istediğiniz ortam adını yazın ve python=3.8 yerine tercih ettiğiniz Python sürümünü belirtin):
  ```bash
  conda create --name env_name python=3.*
  ```
*Sanal ortamı başlatıp sonlandırmak için komutlar
  ```bash
  conda activate env_name
  conda deactivate env_name
  ```
*Paketleri indirin
 ```bash
  pip install numpy matplotlib pandas scikit-learn keras pillow
  ```
