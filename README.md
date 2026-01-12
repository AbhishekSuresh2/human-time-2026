# ⏱️ human-time-2026

**Human-friendly time formatting for modern JavaScript.**  
Turn boring timestamps into natural, readable phrases like **“just now”**, **“this morning”**, **“3d ago”**, or **“in 5m”** — instantly.

Built for **2026 projects**, minimal, fast, and dependency-free.

---

## 🚀 Why human-time-2026?

Most time libraries are heavy or overkill.  
**human-time-2026** focuses on what humans actually say.

✔ Ultra-lightweight  
✔ Zero dependencies  
✔ Past & future support  
✔ Smart context detection  
✔ Works everywhere (Node, Bun, Deno, Browser)

---

## 📦 Installation

```bash
npm install human-time-2026
````

---

## 🧠 Usage

```js
import humanTime from "human-time-2026";

humanTime(new Date()); 
// → "just now"

humanTime("2026-01-10T10:30:00");
// → "this morning"

humanTime(Date.now() - 60000);
// → "1m ago"

humanTime(Date.now() + 3600000);
// → "in 1h"
```

---

## 🪄 Output Examples

| Input Time       | Output         |
| ---------------- | -------------- |
| 2 seconds ago    | `just now`     |
| 45 seconds ago   | `45s ago`      |
| 5 minutes ago    | `5m ago`       |
| Same day morning | `this morning` |
| Yesterday        | `yesterday`    |
| 3 days ago       | `3 days ago`   |
| 2 weeks ago      | `2w ago`       |
| Last year        | `2025`         |

---

## ⚙️ How It Works

* Automatically detects **past or future**
* Uses **natural language**, not robotic strings
* Smart day-based context:

  * morning / afternoon / evening
  * yesterday / tomorrow
* Falls back to **month/day** or **year** when needed

No configs. No setup. Just import & use.

---

## 🛠️ Use Cases

* Chat apps
* Social media feeds
* Logs & dashboards
* Notifications
* WhatsApp / Telegram bots
* Any UI that shows time to humans

---

## ⭐ Support the Project

If this package saved you time or made your UI better:

👉 **Give it a ⭐ on GitHub**
Stars help this project reach more developers ❤️

---

## 🔄 Updates & Contributions

Want to improve `human-time-2026`?

* 🐞 Found a bug? → **Create an Issue**
* ✨ Have an idea? → **Open an Issue**
* 🔧 Want to fix something? → **Fork & Pull Request**
* 📈 New feature? → **PRs are welcome**

Please contribute only through the **official repository**.

---

## 📜 License

MIT License © 2026
**Abhishek Suresh**
[https://github.com/AbhishekSuresh2](https://github.com/AbhishekSuresh2)

> ⚠️ Please do not copy, modify, or republish this package as your own without explicit permission.

---

## 🌍 Vision for 2026

Make time **feel human**, not mechanical.
Let machines adapt to people — not the other way around.

**human-time-2026** ⏳✨
