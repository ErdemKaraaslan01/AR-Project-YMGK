# Vuforia Kullanım Kılavuzu

## 1. Vuforia Engine Kurulumu
- Unity'de Vuforia kullanmak için Vuforia Engine'yi Unity Package Manager üzerinden ekleyin.
  1. Unity > Window > Package Manager > Add package from Git URL: 
     ```bash
     https://github.com/Vuforia/vuforia-unity-android.git
     ```
- Vuforia hesabı oluşturun ve lisans anahtarınızı alın.

## 2. Vuforia Yapılandırması
- Unity'de `ARCamera` nesnesine lisans anahtarınızı girin.
- `Database` oluşturup, kitap kapağının target image olarak eklendiğinden emin olun.
