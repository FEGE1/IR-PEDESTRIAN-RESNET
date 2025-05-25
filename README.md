
# 📌 Proje Adı: Görüntü İşleme ile Görsel Analiz

## 🔍 Proje Hakkında

Bu proje, görüntü işleme teknikleri kullanarak görseller üzerinde çeşitli analiz ve dönüşümler gerçekleştirmektedir. 
Notebook dosyası içerisinde adım adım ön işleme (preprocessing), görselleştirme ve sonuç analizi adımları yer almaktadır.

## 🧰 Kullanılan Teknolojiler ve Kütüphaneler

- Python 3.x
- OpenCV (`cv2`)
- NumPy
- Matplotlib

## 📂 Proje Yapısı

```
📁 IR-PEDESTRIAN-RESNET/
│
├── Data/
│ └── LSIFIR/
│ ├── Classification/
│ │ ├── Train/
│ │ └── Test/
│ └── Detection/
│ ├── Train/
│ └── Test/
│
├── output/ # Model çıktı dosyalarının kaydedileceği klasör
├── best_resnet4.pth # Eğitimli model dosyası
├── best_resnet_mac.pth # Mac uyumlu model dosyası (MPS destekli)
├── main.ipynb # Eğitim + test işlemlerini içeren notebook
├── test.ipynb # Test amaçlı ayrı notebook
├── ResNet.ipynb # Model mimarisi tanımı (isteğe bağlı)
└── README.md 
```

## ⚙️ Kurulum

1. Bu repoyu klonlayın:
```bash
git clone https://github.com/kullaniciadi/proje-adi.git
cd proje-adi
```

2. Gerekli kütüphaneleri yükleyin:
```bash
pip install -r requirements.txt
```

> Alternatif olarak:
```bash
pip install opencv-python numpy matplotlib
```

4. Notebook dosyasında düzenleme ve çalıştırma:
```
Final adlı, kodun son bölümde yer alan input_dir değişkenine, modeli çalıştırmak istediğiniz görsellerin bulunduğu klasörün yolunu girin."
```

## 🧪 Örnek Çıktılar

### Girdi Görseli:
![Input](images/input_example.png)

### İşlenmiş Görsel:
![Output](images/output_example.png)

