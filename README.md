
Bu proje, **Gelecek Hayalim – W-CODE 2.0** programı kapsamında geliştirilmiştir.  
Amaç; Türkiye’deki orman yangınlarının nedenlerini, yıllara ve bölgelere göre dağılımını, bu yangınların orman kaybına etkisini analiz ederek **veriye dayalı çevresel farkındalık** yaratmaktır.

## Proje Hedefleri

- Yangınların çıkış nedenlerini yıllara ve bölgelere göre analiz etmek  
- Yangına bağlı orman kayıplarını, toplam orman kayıplarıyla karşılaştırmak  
- Görselleştirme araçlarıyla veriyi anlaşılır ve yorumlanabilir hale getirmek  
- Veri bilimi teknikleriyle çevresel veri üzerinden anlamlı sonuçlara ulaşmak  

## Ekip

- **Sinem Akyaman** – Veri temizleme, analiz, görselleştirme  
- **Sıla Topal** – Yangın nedenleri ve bölgesel analiz  
- **Aylin Günay** – Makine öğrenmesi ile yangın tahminleme  

##  Kullanılan Veri Setleri

| Kaynak | Açıklama |
|--------|---------|
| Orman Genel Müdürlüğü | Yıllara göre orman yangını sayısı, yanan alan, çıkış nedenleri |
| Global Forest Watch | 2001–2024 ağaç örtüsü kaybı ve yangın ilişkisi |
| Subnational Tree Cover Loss | Bölgesel düzeyde orman kayıpları |
| Bölge Müdürlüklerine Göre Dağılım | Yangın nedenlerinin bölgesel dağılımı (2013–2024) |

## Yapılan Analizler

- Yıllara göre ihmal, kasıt ve doğal nedenli yangınların hektar bazında değişimi
- Bölge müdürlüklerine göre toplam etki alanı
- Yangın nedenlerinin yıllar içindeki artış/azalış trendleri
- Toplam orman kaybı ve yangına bağlı kaybın karşılaştırması
- Yıllara göre nedenlerin stacked bar (yığılmış çubuk) gösterimi
- Makine öğrenmesi ile 2030 yılına kadar olası yangın tahminleri

## Kullanılan Teknolojiler

- `Python`
- `Pandas`, `NumPy` – Veri işleme
- `Matplotlib`, `Seaborn` – Görselleştirme
- `Scikit-learn` – Regresyon tahmini (ML)

## Proje Dosya Yapısı

 OrmanYanginiAnalizi/
├─ data/                # CSV & Excel veri kaynakları
├─ notebooks/           # Jupyter/Colab analiz dosyaları
├─ README.md

 ## Öğrenilenler
_Farklı kaynaklardan gelen veri setlerini birleştirme
_Veri temizleme (eksik veriler, encoding sorunları, format dönüşümleri)
_Zaman serisi ve kategorik analizler
_Gerçek bir sorun üzerine veri bilimi uygulaması
_Grup içi rol dağılımı ve proje yönetimi

## Teşekkürler
Bu proje, Ford Otosan, Mikado Impact, Vehbi Koç Vakfı ve Kodluyoruz’un desteklediği Gelecek Hayalim – W-CODE 2.0 programı kapsamında gerçekleştirilmiştir.
STEM alanındaki kadınları teknolojiyle buluşturma misyonuyla yola çıkan bu yolculukta bize eşlik eden herkese teşekkür ederiz.

## Projeyi Çalıştırmak İçin
1.data/ klasöründeki dosyaları indir
2.Notebooks klasöründeki .ipynb dosyasını aç
3.Gerekli kütüphaneleri yükle


## İletişim
📧 sinemakyaman@gmail.com
📌 [LinkedIn](www.linkedin.com/in/sinemakyaman)
📌 [GitHub](https://github.com/Sinemakyaman)