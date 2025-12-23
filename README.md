# 🚧 İnşaat Güvenlik İhlal Tespit Sistemi (Construction Safety Detection)

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![YOLOv8](https://img.shields.io/badge/AI-YOLOv8-green)
![OpenCV](https://img.shields.io/badge/Computer_Vision-OpenCV-red)
![GUI](https://img.shields.io/badge/Interface-CustomTkinter-orange)

Bu proje, şantiyelerde iş güvenliğini (İSG) artırmak amacıyla geliştirilmiştir. **YOLOv8** yapay zeka modeli ve görüntü işleme teknikleri kullanılarak, işçilerin **baret, yelek ve maske** takıp takmadığını gerçek zamanlı olarak tespit eder.

## 📸 Proje Önizlemesi (Uygulama Arayüzü)

Proje hem **video** hem de **fotoğraf** üzerinden analiz yapabilir. Tespit sonuçları ve ihlal durumları anlık olarak modern arayüze yansıtılır.

<div align="center">
  <img src="https://github.com/user-attachments/assets/7953711f-2c09-4745-bd5f-9caf9ec405e1" width="800" alt="Arayüz Örneği 1">
  <br><br>
  <img src="https://github.com/user-attachments/assets/619931a1-7dc4-4bb7-9a67-87ab6644d564" width="800" alt="Arayüz Örneği 2">
</div>

<br>

## 📊 Model Performansı (Doğruluk Matrisi)

Eğitilen YOLOv8 modelinin test veri setindeki başarısını gösteren karmaşıklık matrisi (confusion matrix) aşağıdadır. Model, özellikle "Insan", "Baret" ve "Yelek" sınıflarında yüksek doğruluk oranlarına sahiptir.

<div align="center">
  <img src="https://github.com/user-attachments/assets/9f361fcb-d3b6-479c-9ef6-b51ed3ed681b" width="800" alt="Confusion Matrix">
</div>

## 🎯 Özellikler
* ✅ **Gelişmiş Nesne Tespiti:** Baret, Yelek, Maske, İnsan, İş Makinesi gibi çoklu sınıfları tanır.
* 🚨 **Akıllı İhlal Uyarısı:** Eğer personel KKD (Kişisel Koruyucu Donanım) kullanmıyorsa, sistem ekranda **"GÜVENLİK İHLALİ"** uyarısı verir ve paneli kırmızıya çevirir.
* 📹 **Çoklu Medya Desteği:** İster hazır video yükleyin, ister fotoğraf üzerinden analiz yapın.
* 💻 **Modern Arayüz:** CustomTkinter ile geliştirilmiş, kullanıcı dostu ve karanlık mod destekli GUI.
