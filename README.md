# Vitrified #
This was a very well-thought-out approach when I invented it. However, since then, I've adopted the micropackage apporach to software platforms; rather than one all-trades set of libraries, instead I now prefer several small special-purpose libraries. I publish these under the [RougeWare](https://github.com/RougeWare/) brand.

I'm keeping this repository public because I'm proud of what I did here, and vitrifying it with this note to let it be known that I no longer agree with it.


---

---

---

---

---

---

---

---

---

---

---

---


<img src="https://bluehuskystudios.github.io/Blue-Husky-Software-Platform/BHSP%20Logo.svg" width="256px" />

Blue Husky Software Platform 1.1
================================

The platform upon which Blue Husky software will be build henceforth.


Components
----------

The Software Platform has distinctly separate components, kept separate to encourage modular and functional architectures.

### Code Repositories ###

There are 27 repositories that make up the platform:

| Platform \ Module | Basics | UI | IO |
| ----------------- | ------ | -- | -- |
| Cross-Platform    | [Blue Base/Core](https://github.com/BlueHuskyStudios/Blue-Base/)💤 | [Husky UI/Core](https://github.com/BlueHuskyStudios/Husky-UI/)💤 | [Husky IO/Core](https://github.com/BlueHuskyStudios/Husky-IO/)💤
| JVM-only          | [Blue Base/JVM](https://github.com/BlueHuskyStudios/Blue-Base-JVM/)🆕 | [Husky UI/JVM](https://github.com/BlueHuskyStudios/Husky-UI-JVM/)🆕 | [Husky IO/JVM](https://github.com/BlueHuskyStudios/Husky-IO-JVM/) 🚫
| JS-only           | [Blue Base/JS](https://github.com/BlueHuskyStudios/Blue-Base-JS/) 🚫 | [Husky UI/JS](https://github.com/BlueHuskyStudios/Husky-UI-JS/) 🚫 | [Husky IO/JS](https://github.com/BlueHuskyStudios/Husky-JS/) 🚫
| Android-only          | [Blue Base/Android](https://github.com/BlueHuskyStudios/Blue-Base-Android/)🚫 | [Husky UI/Android](https://github.com/BlueHuskyStudios/Husky-UI-Android/)🚫 | [Husky IO/Android](https://github.com/BlueHuskyStudios/Husky-IO-Android/) 🚫
| Apple Shared      | [Blue Base/Foundation](https://github.com/BlueHuskyStudios/Blue-Base-Foundation/) 🚫 | [Husky UI/Foundation](https://github.com/BlueHuskyStudios/Husky-UI-Foundation/) 🚫 | [Husky IO/Foundation](https://github.com/BlueHuskyStudios/Husky-IO-Foundation/) 🚫
| macOS-only        | [Blue Base/macOS](https://github.com/BlueHuskyStudios/Blue-Base-macOS/) 🚫 | [Husky UI/macOS](https://github.com/BlueHuskyStudios/Husky-UI-macOS/) 🚫 | [Husky IO/macOS](https://github.com/BlueHuskyStudios/Husky-IO-macOS/) 🚫
| iOS-only          | [Blue Base/iOS](https://github.com/BlueHuskyStudios/Blue-Base-iOS/) 🚫 | [Husky UI/iOS](https://github.com/BlueHuskyStudios/Husky-UI-iOS/) 🚫 | [Husky IO/iOS](https://github.com/BlueHuskyStudios/Husky-IO-iOS/) 🚫
| Win32-only        | [Blue Base/Win32](https://github.com/BlueHuskyStudios/Blue-Base-Win32/) 🚫 | [Husky UI/Win32](https://github.com/BlueHuskyStudios/Husky-UI-Win32/) 🚫 | [Husky IO/Win32](https://github.com/BlueHuskyStudios/Husky-IO-Win32/) 🚫
| Linux-only        | [Blue Base/Linux](https://github.com/BlueHuskyStudios/Blue-Base-Linux/) 🚫 | [Husky UI/Linux](https://github.com/BlueHuskyStudios/Husky-UI-Linux/) 🚫<br/>[Husky UI/Gnome](https://github.com/BlueHuskyStudios/Husky-UI-Gnome/) 🚫 | [Husky IO/Linux](https://github.com/BlueHuskyStudios/Husky-IO-Linux/) 🚫

 * **Blue Base** is the base foundation upon which all future Blue Husky apps will be written.
 * **Husky IO** is the default I/O tools for Blue Husky software.
 * **Husky UI** is the default UI tools for Blue Husky software.

 > 💤 Not yet separated into subrepos<br/>
 > 🆕 Recently created<br/>
 > 🚫 Not yet created

### Abstract Structure ###

 * [Blue Husky Software Structure](https://github.com/BlueHuskyStudios/Blue-Husky-Software-Structure) - The structure of Blue Husky software going forward.
 * [Blue Husky Stages of Product Creation](https://github.com/BlueHuskyStudios/Blue-Husky-Stages-of-Product-Creation) - The stages through which a product goes throughout its lifetime.
