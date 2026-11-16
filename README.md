# Mikromobilite Kullanım Analizi — Power BI Dashboard

Saatlik paylaşımlı mikromobilite (bisiklet/scooter) kullanım verisini analiz eden interaktif bir Power BI raporu. Rapor; kullanımın saate, aya ve hava durumuna göre nasıl değiştiğini, abonelikli ve aboneliksiz kullanıcıların davranış farklarını tek sayfada özetler.

## Dosya

| Dosya | Açıklama |
|---|---|
| `micromobility_ana_dosya.pbix` | Power BI Desktop rapor dosyası (veri modeli + rapor) |

> GitHub `.pbix` dosyalarını tarayıcıda önizleyemez. Raporu incelemek için dosyayı indirip **Power BI Desktop** ile açın.

## Rapor İçeriği — "Kullanım Özeti" sayfası

**KPI kartları**
- Toplam kullanım
- Abonelikli ve aboneliksiz kullanım
- Ortalama saatlik kullanım
- Pik saat ve pik saatteki kullanım
- Korelasyon göstergesi

**Grafikler**
- Saate göre toplam kullanım
- Saate göre abonelikli / aboneliksiz kullanım karşılaştırması
- Aylık toplam kullanım ve abonelikli kullanım trendi
- Hava durumuna göre ortalama kullanım

**Filtreler**
- Yıl
- Ay
- Hava durumu

## Kullanılan Araçlar ve Teknikler

- **Power BI Desktop**
- **DAX** — KPI ölçüleri, abonelik tipine göre kullanım, hava durumuna göre ortalama kullanım, korelasyon hesaplaması
- **Deneb (Vega-Lite)** — özelleştirilmiş grafikler
- **HTML Content** görseli — tasarımı özelleştirilmiş KPI kartları
- **Chiclet Slicer** — buton tipi filtreler
- Türkçe ay ve hava durumu etiketleriyle yerelleştirilmiş veri modeli

## Analiz Soruları

- Gün içinde talebin en yoğun olduğu saatler hangileri?
- Abonelikli ve aboneliksiz kullanıcıların kullanım saatleri nasıl farklılaşıyor?
- Kullanım aylara ve mevsimlere göre nasıl değişiyor?
- Hava durumu kullanımı ne ölçüde etkiliyor?

## Hazırlayan

**Gizem Sökmen** — Endüstri Mühendisi | Veri & İş Analitiği
