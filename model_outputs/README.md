# Model Outputs

Bu klasör eğitilmiş modellerin çıktılarını ve sonuçlarını içermektedir.

## Klasör Yapısı

```
model_outputs/
├── checkpoints/     # Model checkpoint'leri
├── predictions/     # Tahmin sonuçları
├── metrics/         # Performans metrikleri
├── visualizations/ # Görselleştirmeler
└── logs/           # Eğitim logları
```

## İçerik

- **checkpoints/**: PyTorch model dosyaları (.pth)
- **predictions/**: Segmentasyon tahminleri
- **metrics/**: Dice skoru, IoU, hassasiyet/duyarlılık metrikleri
- **visualizations/**: Topolojik özellik görselleştirmeleri
- **logs/**: TensorBoard ve diğer eğitim logları