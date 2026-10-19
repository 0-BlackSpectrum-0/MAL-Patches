# 🧩 Spectre patches

Custom patch bundle for **MyAnimeList** on Android, designed for **Morphe Patcher** and **Morphe Manager**.

## ❓ About

Custom enhancements for the official MyAnimeList Android app (`net.myanimelist.app`), targeting version **2.3.15**.

### How to use these patches in Morphe Manager

1. Open **Morphe Manager** on your Android device.
2. Go to **Sources** > **Add Source**.
3. Enter `0-BlackSpectrum-0/MAL-Patches` (or click [here to add](https://morphe.software/add-source?github=0-BlackSpectrum-0/MAL-Patches)).
4. Select **MyAnimeList** (v2.3.15) and apply the patches!

## 🩹 Patches list

<!-- PATCHES_START EXPANDED -->

| Patch | Description | Target Version |
| :--- | :--- | :--- |
| **AMOLED black theme** | Replaces the dark theme backgrounds with pure pitch black (`#000000`). | `2.3.15` |
| **Open links in app** | Opens `myanimelist.net` web links directly in the MyAnimeList app instead of an external browser. | `2.3.15` |

<!-- PATCHES_END -->

### 🛠️ Building locally

- Ensure Java 21 is installed.
- Run `./gradlew buildAndroid` (or `gradlew.bat buildAndroid` on Windows).
- The built `.mpp` patch bundle will be generated in `patches/build/libs/patches-*.mpp`.

## 📜 License

Spectre patches are licensed under the [GNU General Public License v3.0](LICENSE).
