# Canlı Kamera Yayın TCP üzerinden - Python -> C#
Bu proje, bir Python sunucu uygulaması ile canlı kamera görüntüsünü TCP üzerinden bir C# istemci uygulamasına aktaran bir sistemdir. Python sunucusu, kameradan gelen görüntüyü alır, yeniden boyutlandırır ve JPEG formatında şifreleyerek ağ üzerinden gönderir. C# istemcisi ise bu görüntüleri alır ve ekranda gösterir.

## Özellikler
- *Python sunucu*: OpenCV kullanarak canlı kamera görüntüsü alır.
- *C# istemci*: TCP üzerinden alınan görüntüleri gerçek zamanlı olarak ekranda gösterir.
- Görüntüler JPEG formatında şifrelenip ağ üzerinden gönderilir.
- Performans için görüntüler 240x240 piksel boyutuna küçültülür.

## Gereksinimler

### Python
- Python 3.x
- OpenCV (Kurmak için: pip install opencv-python)

### C# 
- .NET 6 veya daha yeni bir sürüm


![Test](https://github.com/Hamzaerend/CanliGoruntuAktarimi/blob/main/%C3%96rnek%20Ekran%20G%C3%B6r%C3%BCnt%C3%BCs%C3%BC.png)
