---?image=images/newsMain.jpg&size=auto 70%
## @color[white](Android Dev News #1 07.2018)

---
### Constraint Layout 2.0 alpha1
- Zawiera Motion Layout |
- Pozwala ustawiac KeyFrames |
- Brak graficznego edytora w AStudio (narazie)|
- Debug paths |
- Pozwala definiowac Constraint Sety w scenach (a nie jak dotychczas tylko w layoutach) |
- Constraint Set moze zawierać nie tylko atrybuty umiejscowienia widoku |
+++?image=images/motionKeyFrame.gif
+++?image=images/motionTool.gif
+++?image=images/motionDrawer.gif&size=auto
+++?image=images/motionLottie.gif&size=auto
+++
### ImageFilterView
- Upraszcza operacje na obrazach podczas animacji |
- Umożliwia ustawienie alternatywnego źródła |
- Obecne ustawienia: crossfade, contrast, warmth, saturation |
- Kazdy z tych parametrów jest możliwy do animacji |
+++?image=images/motionCrossfade.gif
+++?image=images/saturationMotion.gif
+++
https://androidstudio.googleblog.com/2018/06/constraintlayout-200-alpha-1.html
https://developer.android.com/reference/android/support/constraint/classes
https://medium.com/google-developers/introduction-to-motionlayout-part-i-29208674b10d
---?image=images/toolsMain.jpg&size=auto
## Narzędzia
+++
### Emulator
- Wersja 28 canary umożliwia uruchomienie kilku instancji tego samego AVD |
- Dodanie supportu dla procesorów AMD® oraz Hyper-V® od Microsoftu® w 27.3.8 stable |
- Zarządanie snapshotami od 27.3.8 stable |
- Emulator w wersji 27.3.6 canary uzywający Hyper-V lub Windows® Hypervisor Platform® z procesorami AMD Ryzen czasami powodował bootloopa Windowsa |
+++
### AStudio
#### Wersja 3.2 wchodzi w faze bety (obecnie juz beta4)
 - App Bundles, |
 - Jetpack/AndroidX support/migration, |
 - Nowe profilery, |
 - Zmiany w lincie (+ linFix gradle task), |
 - D8 jako domyslny dexer, opcjonalnie R8 jako zamiennik za proguarda |
 - ADB connection assistant|
 - AAPT2 (Android asset packaging tool, incremental)|
+++
### Astudio
#### Wersja 3.3 udostępniona jako canary (obecnie canary 3)
- Rożnice miedzy runtime i compile classpathem będą od teraz errorami a nie warningami |
- Domyślne wczytywanie optymalizacji R8 dla kotlina, lambd i null checków |
- Wprowadza Gradle 4.9 |

---
### Inne
- JDK 12 nie będzie mogł targetować wersji 6 podczas kompilacji javac |
- Pickle - implementacja cucumber dla Androida generująca testy Compile Time |
- Jake Wharton wypuszcza chrome extension SDK search |
+++
https://github.com/fourlastor/pickle
https://github.com/JakeWharton/SDKSearch
