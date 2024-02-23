# Teknofest Yapay Zeka Yarışması Veri Seti

Bu depo, 2022 Teknofest Yapay Zeka Yarışması'nda birinci ve ikinci olan takımlarımızın kullandığı veri setini içerir. Toplamda 25.000 adede yakın kuş bakışı insan, taşıt, özel iniş alanı etiketleri içermektedir. Görseller stok video ve fotoğraflardan derlenmiştir.

## Veri Seti Linki
[Veri Seti](https://bit.ly/49BvN1w)

## Biz Kimiz
- Şevval Belkıs Dikkaya: [LinkedIn Profili](https://www.linkedin.com/in/sbdikkaya/)
- Muhammed Sezer: [LinkedIn Profili](https://www.linkedin.com/in/muhammed-sezer-160428208/)

### İletişim ve Daha Fazlası

Eğer yaptığımız işi sevdiyseniz ve bizi takipte kalmak isterseniz [YouTube kanalımıza](https://bit.ly/SezerSevvalYoutube) abone olmayı düşünebilirsiniz! Bizi daha iyi tanımak için [websitemizi](https://sezer-muhammed.github.io) ziyaret edebilirsiniz.

## Veri Seti Hakkında

Bu veri seti, ulaşım temalı 25.000'den fazla görüntü ve 300.000'den fazla etiket içerir. Her bir görüntü, çeşitli ulaşım araçları, yayalar, ve özel iniş alanlarını içerir.

## Veri Setini Kullanma

### YOLO Formatı

Bu veri seti, YOLO formatında etiketlenmiştir ve doğrudan YOLO tabanlı modellerde (YOLOv5 ve YOLOv8 gibi) kullanıma uygundur. YOLO formatı, görüntülerle aynı dizinde yer alan ve her bir görüntü için ayrı bir metin dosyası (.txt) içeren bir etiketleme sistemidir. Her metin dosyası, görüntüdeki nesneleri şu formatla temsil eder:

```
<class id> <x_center> <y_center> <width> <height>
```


Bu değerler, görüntünün genişliği ve yüksekliğine göre normalize edilir, böylece tüm değerler 0 ile 1 arasında olur. Bu format, nesne tanıma modellerini eğitirken hızlı ve etkili bir şekilde etiket verilerini kullanmanıza olanak tanır.

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

## Teşekkürler

Bu yarışma sürecinde bize büyük destek sağlayan Desird Ar&Ge ve Orema şirketlerine içtenlikle teşekkür ederiz.

## Lisans

Bu veri seti, [MIT Lisansı](LICENSE) altında yayınlanmıştır.

## İletişim

Herhangi bir sorunuz veya öneriniz olursa, lütfen [Issues](https://github.com/sezer-muhammed/Teknofest-Ulasimda-Yapay-Zeka-Veri-Seti/issues) bölümünü kullanarak bize bildirin.
