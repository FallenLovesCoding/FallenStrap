# FallenStrap

A lightweight, open-source alternative bootstrapper for Roblox built entirely in C#. It replaces the restrictive stock launcher to give you full control over client performance, aesthetics, and hidden engine configurations—completely external, safe, and with zero memory injection.

---

### Why use FallenStrap?
* **Persistent Mods:** Keep your custom fonts, textures, mouse cursors, and sounds (like the classic 'oof') intact. They won't get wiped when Roblox updates.
* **FastFlag Management:** Tweak hidden engine settings like custom FPS caps (`DFIntTaskSchedulerTargetFps`), forced lighting tech, and graphics optimizations via a simple UI.
* **Discord Integration:** Built-in Rich Presence shows your active game and server details securely without risking your account cookies.
* **Zero Bloat:** Written natively in C#. The bootstrapper closes completely the second the game starts, leaving no background processes running.

---

### How to Use It

#### 1. Initial Setup
* Run `FallenStrap.exe` to generate your local configuration files.
* Choose **Standard Integration** (replaces default Roblox shortcuts) or **Portable Mode** (runs strictly inside its own folder).

#### 2. Managing FastFlags (FFlags)
* Open the **FastFlag Editor** tab in the UI.
* Use the search bar to find or toggle performance presets (e.g., lower rendering details or disable telemetry).
* Click **Apply Changes** to write these directly into your profile.

#### 3. Installing Custom Mods
* Drop your custom assets into the `\ModFolder` directory inside the FallenStrap root.
* The launcher injects them into the client directory right before booting the game.

#### 4. Launching the Game
* Launch Roblox normally from your browser or desktop shortcut. 
* FallenStrap checks for official updates, patches your mods, boots the engine, and exits.

---

### Tech & Licensing
* **Language:** C#
* **Platform:** Windows 10 / 11
* **License:** [MIT License](LICENSE)

---

### Tags
`roblox-bootstrapper` · `csharp` · `bloxstrap-alternative` · `fastflags` · `fflag-editor` · `roblox-tweaks` · `discord-rpc` · `fps-unlocker` · `roblox-modding` · `windows-launcher`
