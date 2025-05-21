# 🧍‍♂️ FakeTabPlayer

A lightweight and simple Spigot plugin for **Minecraft 1.19.3** that lets you display **fake players** in the server tablist using **NMS (Net Minecraft Server)**. Great for visual testing, UI demos, or just messing with your friends. 😄

> ⚠️ **Project Status: Not Actively Maintained**
>
> This project is no longer actively maintained. It remains public for learning, reference, or modification by others. Some parts of the code may be outdated or include minor bugs.

---

## 📌 Features

* ➕ Add fake player names to the server tablist
* 🗑️ Remove all fake players at once
* 🔁 Requires players to rejoin the server to reflect tablist changes
* 👻 Fake players are purely visual — they **do not exist** in the game world
* 🔒 Commands require **operator (OP)** permissions
---

## ⚙️ Commands

| Command                   | Description                                               |
| ------------------------- | --------------------------------------------------------- |
| `/fk_create <playerName>` | Adds a fake player with the specified name to the tablist |
| `/fk_remove`              | Removes all fake players from the tablist                 |

> 📌 **Note:** After using `/fk_remove`, players must **rejoin** the server to see the updated tablist.

---

## 🧱 Requirements

* Minecraft **1.19.3**
* **Spigot 1.19.3** server
* NMS access (requires BuildTools)

---

## 🧰 Installation
1. **Download Spigot BuiltTools: https://www.spigotmc.org/wiki/buildtools/** 

2. **Generate required server files with BuildTools in the folder where BuildTools jar is located:**

   ```bash
   java -jar BuildTools.jar --rev 1.19.3
   ```

3. **Open the project in your IDE:**

    * Use IntelliJ, Eclipse, or any Java IDE.
    * Link your Spigot 1.19.3 server jars built from BuildTools.

4. **Build the plugin JAR.**

5. **Deploy:**

    * Drop the compiled `.jar` into your server's `plugins/` folder.
    * Start your Spigot server.

---

## 📝 Notes

* This plugin uses **NMS**, so it is **version-locked** to 1.19.3.
* Fake players **only appear in the tablist** — they do not spawn in the game world.
* A **server rejoin** is required to reflect tablist removals for connected players.
* 🔒 Commands require **operator (OP)** permissions

---

## 📄 License

Released under the [MIT License](LICENSE).

---

## 👤 Author

**Jienniers**
GitHub: [@Jienniers](https://github.com/Jienniers)

Feel free to fork, learn from, or open issues on the project. Contributions are welcome for personal experimentation.
