# Zarnkina Mobile

![Downloads](https://img.shields.io/github/downloads/vasndalinfinity/ZarnkinaMobile/total)

> [!IMPORTANT]
> Bu proje Zalith Launcher 2'nin modifiye edilmiş bir versiyonudur. Orijinal proje:
> [ZalithLauncher/ZalithLauncher2](https://github.com/ZalithLauncher/ZalithLauncher2)

**Zarnkina Mobile**, Android cihazlar için tamamen Türkçe, mor temalı bir [Minecraft: Java Edition](https://www.minecraft.net/) başlatıcısıdır. Proje [PojavLauncher](https://github.com/PojavLauncherTeam/PojavLauncher) temel alınarak geliştirilmiştir ve **Jetpack Compose** ile **Material Design 3** kullanılarak modern bir arayüz sunar.

## 🎯 Özellikler

- 🇹🇷 **Tamamen Türkçe Arayüz** - Varsayılan dil Türkçe
- 💜 **Mor Koyu Tema** - Göz yormayan modern tema
- 🧩 **Tüm Mod Yükleyiciler** - Forge, Fabric, Quilt, NeoForge
- 🔑 **Microsoft + Çevrimdışı Giriş** - QR kod ile kolay giriş
- 🎨 **Skin + Pelerin Yönetimi** - 3D önizleme ile skin değiştirme
- 👁️ **Hesap Takibi** - İsim geçmişi, skin değişiklikleri
- 📦 **Modpaket Desteği** - CurseForge, Modrinth içe aktarma

## 📦 APK İndirme

En son APK sürümünü GitHub'dan indirebilirsiniz:

1. Bu repo'ya git
2. **Actions** sekmesine tıkla
3. **Build APK** workflow'unu çalıştır
4. **Artifacts** kısmından APK indir

## 🔧 Geliştirme

### Gereksinimler

- Android Studio Bumblebee veya üzeri
- Android SDK:
  - **Minimum API**: 26
  - **Target API**: 35
- JDK 17

### Kurulum

```bash
git clone https://github.com/vasndalinfinity/ZarnkinaMobile.git
# Android Studio ile projeyi aç
```

### Build

```bash
cd ZarnkinaMobile
./gradlew :ZalithLauncher:assembleDebug
```

## 📜 Lisans

Bu proje **[GPL-3.0 license](LICENSE)** altında lisanslanmıştır.

### Ek Şartlar (GPLv3 Madde 7'ye göre)

1. Bu programın değiştirilmiş versiyonunu dağıtırken, programın adını veya sürüm numarasını orijinalden farklı olacak şekilde değiştirmelisiniz.
   - Değiştirilmiş versiyonlarda orijinal program adı kullanılmamalıdır.
   - Tüm değiştirilmiş versiyonlar programın açılış veya ana ekranında "resmi olmayan değiştirilmiş versiyon" olarak işaretlenmelidir.

2. Programda görüntülenen telif hakları bildirimlerini kaldıramazsınız.

## 🤝 Katkıda Bulunanlar

Bu proje şu açık kaynak projelerden faydalanmaktadır:

- [Zalith Launcher 2](https://github.com/ZalithLauncher/ZalithLauncher2) - Ana temel
- [PojavLauncher](https://github.com/PojavLauncherTeam/PojavLauncher) - Minecraft Java için Android başlatıcısı
- [HMCL](https://github.com/Zarnkina/Zarnkina) - Windows sürümü temel alınmıştır

## 📞 İletişim

- **GitHub**: [ZarnkinaMobile](https://github.com/vasndalinfinity/ZarnkinaMobile)
- **Windows Sürümü**: [Zarnkina](https://github.com/Zarnkina/Zarnkina)

---

Zarnkina, Mojang veya Microsoft ile bağlantılı değildir. Minecraft, Mojang AB'nin ticari markasıdır.