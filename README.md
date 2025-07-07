<<<<<<< HEAD
#  AR Kitap Uygulaması

Bu proje, **Unity** ve **Vuforia** kullanılarak geliştirilmiş bir **Artırılmış Gerçeklik (AR)** kitap uygulamasıdır. Android cihazlarda çalışan bu uygulama, kitabın kapağını tanıyarak dijital ortamda aynısını görüntüler, sayfa geçişleri ve zoom gibi etkileşimli özellikler sunar.

##  Proje Hakkında

* **Proje Adı:** AR Kitap
* **Teknolojiler:** Unity 2021+, Vuforia Engine, C#
* **Hedef Kitle:** Eğitim teknolojileriyle ilgilenen geliştiriciler, öğrenciler, kitap yayıncıları

### Proje Amacı

Gerçek bir kitabın kapağının tanınması ile dijital kitap deneyimi sunmak. Kullanıcı fiziksel kitap ile etkileşime girerek sayfa geçişi ve yakınlaştırma yapabilir.

---

##  Kurulum Rehberi

Bu projenin sorunsuz çalışması için aşağıdaki yazılımların kurulu olması gereklidir:

### Gereken Yazılımlar

* Unity 2021.3.x veya üzeri
* Vuforia Engine SDK (Unity Package Manager ile eklenmeli)

### Adım Adım Kurulum

1. Bu repoyu klonlayın veya ZIP şeklinde indirin:


   git clone https://github.com/ErdemKaraaslan01/AR-Project-YMGK.git

2. Unity ile `My project.sln` veya `MainScene.unity` dosyasını açın
3. `Assets/Scenes/MainScene.unity` sahnesini açarak projeyi inceleyin
4. Vuforia ayarları için: `Window > Vuforia Engine > Configuration`
5. Gerekli lisans anahtarını ekleyin (kendi hesabınızla Vuforia'dan alabilirsiniz)

### Bağımlılıklar

* Vuforia Engine
* Unity Input System (Touch / Gesture kontrolleri)

---

##  Kullanım Talimatları

1. APK dosyasını `apk/` klasöründen Android cihaza kurun
2. Uygulamayı başlatın
3. Kameraya kitabın kapağını gösterin
4. Sayfa geçişi için parmağınızla sağa/sola kaydırın
5. Yakınlaştırmak için iki parmakla zoom yapın

---

##  AR Özellikler

* Kitap kapağı tanıma
* Sayfa geçişi (AutoFlip, LeanTouch)
* Zoom (Pinch gesture)
* Gerçek zamanlı kamera ile etkileşim

---


##  Dosya Yapısı

```
ARKitapProjesi/
├── README.md
├── INSTALLATION.md
├── USER_MANUAL.md
├── src/                # C# script dosyaları
├── docs/               # Diğer belgeler
├── screenshots/        # Ekran görüntüleri
├── apk/                # .apk dosyası (Android)
└── demo_video/         # Video linki
```

---


##  APK Dosyası

* APK dosyası `apk/ARKitap_v1.0.apk` olarak bulunur
* Android 10+ cihazlarda test edilmistir
* Çalışır durumdadır ve fiziksel kitap kapağıyla denenmelidir

=======
# AR-Project-YMGK
>>>>>>> a4f03398c8a25647b3026ef96adbc79db6b097d1
