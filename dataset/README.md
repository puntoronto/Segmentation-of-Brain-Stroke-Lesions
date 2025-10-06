# Dataset

Bu klasör beyin inmesi CT görüntüleri ve segmentasyon maskeleri için kullanılmaktadır.

## Veri Kaynağı

Veriler [Türkiye Cumhuriyeti Sağlık Bakanlığı](https://acikveri.saglik.gov.tr/Home/DataSetDetail/1) tarafından sağlanmış olup, [Kaggle platformunda](https://www.kaggle.com/datasets/ozguraslank/brain-stroke-ct-dataset) Özgür Arslan tarafından derlenmiştir.

## Klasör Yapısı

```
dataset/
├── images/          # CT görüntüleri
├── masks/           # Segmentasyon maskeleri
└── processed/       # Ön işlenmiş veriler
```

## Kullanım

Dataset indirildikten sonra uygun klasörlere yerleştirilmelidir. Veri yükleme ve ön işleme için ilgili notebook'lara bakınız.