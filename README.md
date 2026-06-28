![Python](https://img.shields.io/badge/python-3.7+-blue)
![OpenCV](https://img.shields.io/badge/opencv-4.x-orange)
![License](https://img.shields.io/badge/license-MIT-teal)
![Status](https://img.shields.io/badge/status-active-brightgreen)

# 🖼️ Görüntü İşlemeye Giriş — OpenCV ile

Python ve OpenCV kullanarak görüntü işlemenin temellerini öğrenmek için hazırlanmış konu bazlı örnek serisi.
Görüntü yüklemeden video işlemeye, filtrelerden histogram analizine kadar 14 konu.

---

## 📋 İçerik

| # | Klasör | Konu | Etiket |
|---|--------|------|--------|
| 01 | [01_open_image](./01_open_image) | Görüntü okuma ve gösterme | `temel` |
| 02 | [02_video_play](./02_video_play) | Video dosyalarını okuma ve oynatma | `temel` |
| 03 | [03_video_camera](./03_video_camera) | Kamera erişimi ve video kaydı | `temel` |
| 04 | [04_resize_crop](./04_resize_crop) | Yeniden boyutlandırma ve kırpma | `temel` |
| 05 | [05_shape_text](./05_shape_text) | Görüntü üzerine şekil ve yazı ekleme | `çizim` |
| 06 | [06_joining_images](./06_joining_images) | Birden fazla görüntüyü birleştirme | `çizim` |
| 07 | [07_warp_perspective](./07_warp_perspective) | Perspektif düzeltme | `çizim` |
| 08 | [08_blending](./08_blending) | Görüntü karıştırma teknikleri | `çizim` |
| 09 | [09_image_thresholding](./09_image_thresholding) | Eşikleme yöntemleri | `filtre` |
| 10 | [10_blurring](./10_blurring) | Görüntü yumuşatma ve filtreleme | `filtre` |
| 11 | [11_morphological](./11_morphological) | Morfolojik işlemler | `filtre` |
| 12 | [12_gradients](./12_gradients) | Kenar tespiti ve gradyan hesaplamaları | `filtre` |
| 13 | [13_histogram](./13_histogram) | Histogram analizi | `analiz` |
| 14 | [14_opencv_goruntu_isleme_odevi](./14_opencv_goruntu_isleme_odevi) | Uygulama ödevi | `proje` |

---

## ⚙️ Kurulum

Kodları çalıştırmak için aşağıdaki kütüphanelerin kurulu olması gerekmektedir:

```bash
pip install opencv-python
pip install numpy
```

---

## 📁 Klasör Yapısı

Her konu kendi klasöründe şu yapıya sahiptir:

```
📁 XX_konu/
  ├── README.md     ← açıklama ve kullanım
  ├── main.py       ← ana kod
  └── images/       ← örnek görseller
```

---

> [!TIP]
> Konular sıralı tasarlanmıştır. `01_open_image` ile başlayıp sırayla ilerlemek önerilir.

---

## 🔗 Kaynaklar

- [OpenCV Resmi Dokümantasyon](https://docs.opencv.org/)
- [OpenCV Python Eğitimleri](https://docs.opencv.org/4.x/d6/d00/tutorial_py_root.html)
- [NumPy Dokümantasyon](https://numpy.org/doc/)
