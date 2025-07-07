#  Kurulum Rehberi (INSTALLATION.md)

Bu doküman, **AR Kitap Uygulaması**'nı yerel ortamınızda çalıştırmak ve geliştirmek isteyenler için detaylı kurulum adımlarını içerir.

---

##  Sistem Gereksinimleri

### Donanım:

* Android 10 veya üzeri işletim sistemine sahip bir mobil cihaz
* Minimum 3 GB RAM

### Yazılım:

* Unity 2021.3 LTS veya üzeri
* Vuforia Engine SDK
* Android Build Support
* Android cihaz için USB debugging aktif olmalı

---

##  Unity Ortamı Kurulumu

1. Unity Hub üzerinden Unity 2021.3.x LTS versiyonu kurun
2. Unity kurulum ekranında şu özellikleri seçtiğinizden emin olun:

   * Android Build Support
   * OpenJDK
   * Android SDK & NDK Tools

---

##  Projeyi Yükleme ve Çalıştırma

1. Bu GitHub reposunu klonlayın veya ZIP şeklinde indirin:


   git clone https://github.com/ErdemKaraaslan01/AR-Project-YMGK.git


2. Unity Hub > Add > `AR-Project-YMGK` klasörünü seçin

3. Projeyi Unity'de açın

4. `Assets/Scenes/MainScene.unity` sahnesini açarak uygulamayı test edin

5. `Window > Vuforia Engine > Configuration` üzerinden kendi Vuforia lisans anahtarınızı girin

---

##  Vuforia Ayarları

1. Vuforia Engine'yi Unity Package Manager ile kurun:

   * Open Package Manager > Add package from Git URL:

     ```
     https://github.com/Vuforia/vuforia-unity-android.git
     ```

2. Vuforia Developer hesabı oluşturun: (https://developer.vuforia.com/)

3. License Manager üzerinden bir lisans oluşturun

4. Lisans anahtarını `ARCamera` nesnesine Configuration panelinden ekleyin

5. `Database` oluşturup, kitap kapağının target olarak eklendiğinden emin olun

---

##  APK Oluşturma

1. File > Build Settings > Android'i seçin
2. Switch Platform butonuna tıklayın
3. Scenes in Build listesine `MainScene`'i ekleyin
4. Player Settings > XR Settings > Vuforia Engine'i aktif edin
5. Build butonuna tıklayın, `ARKitap_v1.0.apk` adıyla kaydedin

---

##  Sık Karşılaşılan Sorunlar & Çözümler

| Sorun                       | Çözüm                                                                           |
| --------------------------- | ------------------------------------------------------------------------------- |
| Vuforia paketi eksik hatası | Unity Package Manager ile Vuforia URL'den yükleyin                              |
| Kamera açılmıyor            | Android izinlerini kontrol edin, Player Settings > Camera izinleri aktif olmalı |
| Target algılanmıyor         | Vuforia'da doğru target yüklenmiş mi kontrol edin                               |

---

> Kurulumla ilgili her tür sorun için `issues` sekmesinden geri bildirim bırakabilirsiniz.
