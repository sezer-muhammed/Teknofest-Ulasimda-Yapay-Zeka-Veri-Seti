# Teknofest Artificial Intelligence Competition Dataset

![Preview](https://bmeqhxsikltbwjf8.public.blob.vercel-storage.com/image.webp)

## 🔗 Links

- 🧪 [Live Demo (Hugging Face)](https://huggingface.co/spaces/sezer-muhammed/Traffic-Object-Detection)
- 📦 [Download Dataset (Google Drive)](https://drive.google.com/file/d/1NdMg_4DKWNWg6_lzqMm6tzfqBjaK8Hdu/view?usp=sharing)
- 📺 [YouTube Channel](https://bit.ly/SezerSevvalYoutube)

---

## 📘 Description

This repository contains the dataset used by the first and second place teams in the 2022 Teknofest Artificial Intelligence Competition. It includes nearly **25,000** top-down annotated images of people, vehicles, and helipads. Images were sourced from stock video and photography.

---

## 📊 Dataset Summary

- **25,000+** aerial view images
- **300,000+** annotations
- Classes: **Vehicle**, **Pedestrian**
- Format: **YOLO-style annotations**
- Structure includes `train/`, `test/` folders and a `dataset.yaml` config file

---

## 📁 YOLO Format

The dataset is directly compatible with YOLO-based models (e.g., YOLOv5, YOLOv8). Each `.txt` annotation file follows the format below:

```
<class_id> <x_center> <y_center> <width> <height>
```

---

## 📚 Citation

```
@misc{EflatunDataset,
  author       = {Şevval Belkıs Dikkaya, Muhammed İzzet Sezer},
  title        = {Eflatun Team Teknofest AI in Transportation Competition Dataset},
  year         = {2021},
  publisher    = {GitHub},
  journal      = {GitHub repository},
  howpublished = {\url{https://github.com/sezer-muhammed/Teknofest-Ulasimda-Yapay-Zeka-Veri-Seti}},
}
```
