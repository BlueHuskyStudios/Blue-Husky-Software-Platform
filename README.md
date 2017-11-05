Blue Husky Software Platform 1.1
================================

The platform upon which Blue Husky software will be build henceforth.


Components
----------

The Software Platform has distinctly separate components, kept separate to encourage modular and functional architectures.

### Code Repositories ###

There are 12 repositories that make up the platform:

| Platform \ Module | Basics | UI | IO | 
| ----------------- | ------ | -- | -- | 
| Cross-Platform    | [Blue Base/Core](https://github.com/BlueHuskyStudios/Blue-Base/)💤 | [Husky UI/Core](https://github.com/BlueHuskyStudios/Husky-UI/)💤 | [Husky IO/Core](https://github.com/BlueHuskyStudios/Husky-IO/)💤
| JVM-only          | [Blue Base/JVM](https://github.com/BlueHuskyStudios/Blue-Base-JVM/)🆕 | [Husky UI/JVM](https://github.com/BlueHuskyStudios/Husky-UI-JVM/)🆕 | [Husky IO/JVM](https://github.com/BlueHuskyStudios/Husky-IO-JVM/) 🚫
| JS-only           | [Blue Base/JS](https://github.com/BlueHuskyStudios/Blue-Base-JS/) 🚫 | [Husky UI/JS](https://github.com/BlueHuskyStudios/Husky-UI-JS/) 🚫 | [Husky IO/JS](https://github.com/BlueHuskyStudios/Husky-JS/) 🚫
| Native-only       | [Blue Base/Native](https://github.com/BlueHuskyStudios/Blue-Base-Native/) 🚫 | [Husky UI/Native](https://github.com/BlueHuskyStudios/Husky-UI-Native/) 🚫 | [Husky IO/Native](https://github.com/BlueHuskyStudios/Husky-IO-Native/) 🚫

 * **Blue Base** is the base foundation upon which all future Blue Husky apps will be written.
 * **Husky IO** is the default I/O tools for Blue Husky software.
 * **Husky UI** is the default UI tools for Blue Husky software.
 
 > 💤 Not yet separated into subrepos<br/>
 > 🆕 Recently created<br/>
 > 🚫 Not yet created

### Abstract Structure ###

 * [Blue Husky Software Structure](https://github.com/BlueHuskyStudios/Blue-Husky-Software-Structure) - The structure of Blue Husky software going forward.
 * [Blue Husky Stages of Product Creation](https://github.com/BlueHuskyStudios/Blue-Husky-Stages-of-Product-Creation) - The stages through which a product goes throughout its lifetime.
