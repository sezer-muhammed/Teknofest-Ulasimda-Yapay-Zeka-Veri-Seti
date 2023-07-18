# Teknofest Yapay Zeka Yarışması Veri Seti

Bu depo, 2022 Teknofest Yapay Zeka Yarışması'nda birinci ve ikinci olan takımlarımızın kullandığı veri setini içerir. Toplamda 25.000 adede yakın kuş bakışı insan, taşıt, özel iniş alanı etiketleri içermektedir. Görseller stok video ve fotoğraflardan derlenmiştir.

## Veri Seti Linki
[Veri Seti](https://bit.ly/EflatunDataSet)

## Biz Kimiz

Veri seti, Teknofest 2022 Ulaşımda Yapay Zeka Yarışması'nda birinci ve ikinci olan takımlar tarafından oluşturulmuştur. 

1. takımın lideri: Şevval Belkıs Dikkaya, 
2. takımın lideri: Muhammed İzzet Sezer
## Veri Seti Hakkında

Bu veri seti, ulaşım temalı 25.000'den fazla görüntü ve 400.000'den fazla etiket içerir. Her bir görüntü, çeşitli ulaşım araçları, yayalar, ve özel iniş alanlarını içerir.

## Veri Setini Kullanma

### PASCAL VOC Formatı

Bu veri setinde etikerler PASCAL VOC formatındadır. Bu format, her görüntü için bir XML dosyası içerir. 

Bu XML dosyası, görüntüdeki nesnelerin etiketlerini, konumlarını ve boyutlarını içerir:

- `filename`: Görüntünün dosya adı.
- `size`: Görüntünün boyutu (genişlik, yükseklik, derinlik).
- `object`: Görüntüdeki her bir nesne için bir `object` öğesi bulunur. Her `object` öğesi aşağıdaki bilgileri içerir:
  - `name`: Nesnenin sınıf adı.
  - `bndbox`: Nesnenin sınırlayıcı kutusunun (bounding box) koordinatları (xmin, ymin, xmax, ymax).

### YOLO ile Kullanım

YOLO, PASCAL VOC formatındaki verileri kullanabilir, ancak verilerin YOLO'nun beklediği belirli bir formata dönüştürülmesi gerekmektedir. 

Bu işlemler genellikle bir dönüştürme scripti ile yapılır:

1. Her bir görüntü için bir metin dosyası oluşturun. Metin dosyasının adı, görüntünün dosya adına karşılık gelmelidir.
2. Her bir metin dosyasında, görüntüdeki her bir nesne için bir satır olmalıdır. Her satır, aşağıdaki formatı izlemelidir:
```
<class id> <x_center> <y_center> <width> <height>
```

3. Bu değerler, görüntünün genişliği ve yüksekliğine göre normalize edilmelidir, yani tüm değerler 0 ile 1 arasında olmalıdır.
4. Dönüştürme tamamlandığında, veri seti YOLO'nun beklediği formatta hazır olacaktır.

İşinize yarayabilecek bir kaynak: [Gist](https://gist.github.com/Amir22010/a99f18ca19112bc7db0872a36a03a1ec)

## Referans Verme

Eğer bu veri setini kendi çalışmanızda kullanırsanız, lütfen aşağıdaki gibi referans verin:

```
@misc{EflatunDataset,
author = {Şevval Belkıs Dikkaya, Muhammed İzzet Sezer},
title = {Eflatun Takımı Teknofest Ulaşımda Yapay Zeka Yarışması Veri Seti},
year = {2021},
publisher = {GitHub},
journal = {GitHub repository},
howpublished = {\url{https://github.com/sezer-muhammed/Teknofest-Ulasimda-Yapay-Zeka-Veri-Seti}},
}
```

```
Şevval Belkıs Dikkaya, & Muhammed İzzet Sezer. (2021). Eflatun Takımı Teknofest Ulaşımda Yapay Zeka Yarışması Veri Seti (Version 1.0) [Data set]. GitHub. [https://github.com/sezer-muhammed/Teknofest-Ulasimda-Yapay-Zeka-Veri-Seti](https://github.com/sezer-muhammed/Teknofest-Ulasimda-Yapay-Zeka-Veri-Seti)
```

Umarız ki, bu veri seti üzerinde çalışmak sizi heyecanlandırır ve kendi projelerinizde kullanmaktan zevk alırsınız!


## Teşekkürler

Bu yarışma sürecinde bize büyük destek sağlayan Desird Ar&Ge ve Orema şirketlerine içtenlikle teşekkür ederiz.

## Lisans

Bu veri seti, [MIT Lisansı](LICENSE) altında yayınlanmıştır.

## İletişim

Herhangi bir sorunuz veya öneriniz olursa, lütfen [Issues](https://github.com/sezer-muhammed/Teknofest-Ulasimda-Yapay-Zeka-Veri-Seti/issues) bölümünü kullanarak bize bildirin.

## Öneriler

- Veri setini kullanırken dikkatli bir şekilde etiketleri inceleyin, bazı etiketler hatalı olabilir.
- Veri setini kullanmadan önce, verileri kendi projeniz için uygun formata dönüştürün.
- Bu veri seti üzerinde herhangi bir düzenleme veya iyileştirme yaparsanız, lütfen düzenlemelerinizi paylaşmayı düşünün.
## Veri Seti İstatistikleri

![Combined Images](./images/combined_image.jpg)

![Labels](./images/labels.jpg)

![Labels Correlogram](./images/labels_correlogram.jpg)

![Veri Seti](./images/bit.ly_3POeBPz.png)
