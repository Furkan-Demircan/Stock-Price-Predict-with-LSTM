# Hisse Analizi ve Tahmini

Bu proje, çeşitli hisse senetlerinin geçmiş kapanış fiyatlarını analiz ederek LSTM modelini kullanarak hisse fiyatlarini tahmin etmek amacıyla oluşturulmuş bir Jupyter Notebook çalışmasıdır. Python'da makine öğrenimi, veri analizi ve görselleştirme araçlarını kullanır.

[**Read this document in English**](./README_EN.md)

## Özellikler

- **Veri Çekme**: `yfinance` kütüphanesi kullanılarak belirli tarihler arasındaki hisse senedi kapanış fiyatlarını indirir.
- **Veri Görselleştirme**: Fiyat hareketlerini grafiksel olarak gösterir.
- **Makine Öğrenimi Modelleri**: LSTM gibi modellerle fiyat tahmini yapılabilir. Model, dört farklı hissenin kapanış fiyatlarıyla eğitilir.
- **Dropout ve Early Stopping**: Modelin doğruluğunu artırmak ve aşırı öğrenmeyi önlemek için Dropout katmanları ve Early Stopping teknikleri uygulanır.
- **Performans Ölçümü**: Çeşitli metrikler (ör. MAE, RMSE) ile modellerin performansı değerlendirilir.

## Gereksinimler

- Python 3.8 veya üzeri
- Gerekli Python paketleri: `yfinance`, `pandas`, `numpy`, `tensorflow`, `matplotlib`, `sklearn`

## Kurulum

1. Bu projeyi yerel makinenize klonlayın:
    ```bash
    git clone https://github.com/Furkan-Demircan/stock-analysis.git
    cd stock-analysis
    ```

2. Gerekli Python paketlerini yükleyin:
    ```bash
    pip install -r requirements.txt
    ```

3. Jupyter Notebook'u başlatın:
    ```bash
    jupyter notebook
    ```

## Kullanım

1. Jupyter Notebook'u başlattıktan sonra `Final.ipynb` dosyasını açın.
2. Belirli hisse senetleri ve tarih aralığı seçerek analizi çalıştırın.
3. Modelleri eğiterek fiyat tahminleri yapabilir ve sonuçları değerlendirebilirsiniz. Modelin doğruluğunu artırmak için Dropout ve Early Stopping ayarlarını özelleştirebilirsiniz.

## Katkıda Bulunma

Katkılar memnuniyetle karşılanır! Lütfen katkıda bulunmadan önce bir konu açarak değişikliklerinizi tartışın.

1. Fork'layın (Çatal oluşturun).
2. Kendi dalınızı oluşturun (`git checkout -b ozellik/yenilik`).
3. Değişikliklerinizi commit edin (`git commit -m 'Yeni özellik ekle'`).
4. Dalınıza push yapın (`git push origin ozellik/yenilik`).
5. Bir pull isteği (PR) açın.

## İletişim

Bu proje hakkında sorularınız veya önerileriniz için bizimle iletişime geçebilirsiniz:

- **E-posta**: goooglenudle@gmail.com
- **GitHub**: [Furkan-Demircan](https://github.com/Furkan-Demircan)

---

İyi analizler!
