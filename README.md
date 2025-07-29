# Teknofest Yapay Zeka Yarışması Veri Seti

Bu depo, 2022 Teknofest Yapay Zeka Yarışması'nda birinci ve ikinci olan takımlarımızın kullandığı veri setini içerir. Toplamda 25.000 adede yakın kuş bakışı insan, taşıt, özel iniş alanı etiketleri içermektedir. Görseller stok video ve fotoğraflardan derlenmiştir.

## 📦 Veri Seti Linki

[![Download Dataset](https://img.shields.io/badge/Download-Dataset-blue)](https://drive.google.com/file/d/1NdMg_4DKWNWg6_lzqMm6tzfqBjaK8Hdu/view?usp=sharing)

## 🧪 Hugging Face Demo

[![Hugging Face Spaces](https://img.shields.io/badge/Demo-HuggingFace-orange)](https://huggingface.co/spaces/sezer-muhammed/Traffic-Object-Detection)

## 👥 Biz Kimiz

- Şevval Belkıs Dikkaya: [LinkedIn](https://www.linkedin.com/in/sbdikkaya/)
- Muhammed Sezer: [LinkedIn](https://www.linkedin.com/in/muhammed-sezer-160428208/)

> Daha fazla içerik için [YouTube kanalımız](https://bit.ly/SezerSevvalYoutube)'a abone olabilir, [web sitemizi](https://imsezer.com) ziyaret edebilirsiniz.

---

## 📊 Veri Seti Özeti

- **25.000+** kuş bakışı görsel
- **300.000+** etiket
- Sınıflar: **Taşıt (vehicle)** ve **Yaya (pedestrian)**
- Etiketler: **YOLO formatında**
- Yapı: `train/`, `test/` klasörleri ve `dataset.yaml` dosyası mevcut

---

## 📁 YOLO Formatı

Veri seti, YOLO tabanlı modeller (YOLOv5, YOLOv8, vb.) için doğrudan kullanılabilir. Her `.txt` etiketi aşağıdaki gibi düzenlenmiştir:

```txt
<class_id> <x_center> <y_center> <width> <height>
```

```
@misc{EflatunDataset,
  author       = {Şevval Belkıs Dikkaya, Muhammed İzzet Sezer},
  title        = {Eflatun Takımı Teknofest Ulaşımda Yapay Zeka Yarışması Veri Seti},
  year         = {2021},
  publisher    = {GitHub},
  journal      = {GitHub repository},
  howpublished = {\url{https://github.com/sezer-muhammed/Teknofest-Ulasimda-Yapay-Zeka-Veri-Seti}},
}
```
