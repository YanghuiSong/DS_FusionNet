
## [DS_FusionNet: Dynamic Dual-Stream Fusion Network for Plant Disease Recognition](https://hsetdata.com/index.php/ojs/article/view/891/833)

![Plantdiseases](https://github.com/YanghuiSong/DS_FusionNet/blob/main/pdpw.png)

## 📖 Introduction

DS_FusionNet is a novel dynamic dual-stream fusion network designed for enhanced plant disease recognition under challenging conditions such as small-sample learning, leaf occlusion, illumination variations, and high inter-class similarity.

**Key Features:**
- Dual-backbone architecture (EfficientNet-B4 + ConvNeXt-Tiny)
- Deformable dynamic fusion modules
- Bidirectional knowledge distillation
- Excellent performance with limited labeled data

## 🏗️ Model Architecture


The network consists of:
1. **Dual Backbone**: EfficientNet-B4 (global features) + ConvNeXt-Tiny (local details)
2. **Deformable Dynamic Fusion**: Adaptive feature weighting with 3×3 deformable convolution
3. **Classification Head**: Fully connected layer with dual regularization

## 📊 Performance

| Dataset | Full Data Accuracy | 10% Data Accuracy |
|---------|-------------------|------------------|
| PlantDisease | 99.71% | 97.75% |
| PlantWild | 42.36% | 45.67% |
| CIFAR-10 | 96.55% | 85.68% |





📚 Datasets
Supported Datasets
PlantDisease: 61,486 training samples, 38 classes

PlantWild: 2,598 training samples, 15 classes

CIFAR-10: 50,000 training samples, 10 classes

### Installation
## 🚀 Quick Start
```bash
git clone https://github.com/Yanghuisong/DS_FusionNet.git
cd DS_FusionNet



