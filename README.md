# Test Raporu Oluşturucu

Bu proje, test verilerini analiz eden ve görsel raporlar oluşturan bir Python uygulamasıdır.

## Ne İşe Yarar?

- CSV formatındaki test verilerini PDF raporuna dönüştürür
- Test senaryolarını analiz eder ve görselleştirir
- Test durumlarını ve sonuçlarını raporlar
- Tekrarlanan testleri tespit eder

## Gereksinimler

- Python 3.x
- Gerekli Python paketleri:
  - pandas
  - matplotlib
  - seaborn
  - reportlab
- Arial Unicode MS yazı tipi

## Kurulum

1. Gerekli paketleri yükleyin:

```bash
pip install pandas matplotlib seaborn reportlab
```

2. Arial Unicode MS yazı tipini sisteminize yükleyin

## Nasıl Kullanılır?

1. Test verilerinizi CSV formatında hazırlayın
2. Jupyter notebook'u çalıştırın:

```bash
jupyter notebook converter.ipynb
```

3. Notebook'taki tüm hücreleri çalıştırın
4. Rapor otomatik olarak 'test_report.pdf' olarak kaydedilecektir

## Rapor İçeriği

Oluşturulan PDF raporunda şunlar bulunur:

- Proje tanıtımı
- Senaryo türü analizi
- Toplam test sayısı
- Modül/Bölüm dağılımı
- Tekrarlanan testler
- Öncelik dağılımı
- Cihaz/Tarayıcı bilgileri
- Test durumları
- Sonuç

## Önemli Notlar

- CSV dosyasının ilk 12 satırı atlanır
- Rapor Türkçe olarak oluşturulur
- Tüm grafikler PNG formatında kaydedilir
- CSV dosyanızın sütun başlıkları kodda belirtilen isimlerle eşleşmelidir




