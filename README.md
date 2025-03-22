# Hisse Senedi Analizi ve Portföy Optimizasyonu

Bu proje, belirli hisse senetlerinin tarihsel verilerini kullanarak portföy optimizasyonu ve risk analizi yapmayı amaçlamaktadır. Proje, Python programlama dili ve çeşitli kütüphaneler kullanılarak geliştirilmiştir. Kullanılan yöntemler arasında Sharpe oranı, maksimum Sharpe oranlı portföy hesaplaması, Monte Carlo simülasyonu ve etkin sınır analizi bulunmaktadır.

## İçindekiler

- [Proje Açıklaması](#proje-açıklaması)
- [Kullanılan Kütüphaneler](#kullanılan-kütüphaneler)
- [Veri Kaynağı](#veri-kaynağı)
- [Kurulum](#kurulum)
- [Kullanım](#kullanım)
- [Sonuçlar](#sonuçlar)
- [Lisans](#lisans)

## Proje Açıklaması

Bu proje, yatırımcıların hisse senedi performansını daha iyi anlamalarına yardımcı olmak için tasarlanmıştır. Hisse senetlerinin günlük getirileri, volatilite, beklenen getiri ve Value at Risk (VaR) gibi önemli finansal metrikler hesaplanarak analiz edilmiştir. Ayrıca, yatırımcıların risk toleranslarına göre optimize edilmiş portföyler oluşturulmuştur.

## Kullanılan Kütüphaneler

- `yfinance`: Hisse senedi verilerini indirmek için kullanılır.
- `pandas`: Veri analizi ve manipülasyonu için kullanılır.
- `numpy`: Sayısal hesaplamalar için kullanılır.
- `scipy`: Optimizasyon işlemleri için kullanılır.
- `matplotlib`: Grafik ve görselleştirme için kullanılır.

## Veri Kaynağı

Veri, Yahoo Finance API'si kullanılarak indirilmiştir. Proje, aşağıdaki hisse senetlerini kapsamaktadır:

- Tesla (TSLA)
- Apple (AAPL)
- Microsoft (MSFT)
- Akbank (AKBNK.IS)
- Türk Hava Yolları (THYAO.IS)
- Pegasus (PGSUS.IS)
- Amazon (AMZN)
- Google (GOOGL)

## Kurulum

Proje kütüphanelerini yüklemek için aşağıdaki komutu terminalde çalıştırabilirsiniz:

```bash
pip install yfinance pandas numpy scipy matplotlib
