
# 🚀 مُنشئ قوالب تصدير غودوت (مؤمن بتشفير AES-256) 🔐

This GitHub Actions workflow automatically builds **Linux** and **Windows export templates** from the **latest stable version of Godot Engine**, with added security using an **AES-256 script** for protecting your game scripts.

## 🎯 Features

- ✅ Clones latest **Godot Engine** source
- 🔐 Integrates AES-256 encryption script for secure builds
- ⚙️ Builds export templates for:
  - 🐧 Linux
  - 🪟 Windows
- 💾 Uses SCons with LTO optimizations
- 📦 Uploads `.zip` export templates as artifacts
- ☁️ Caches build output to speed up rebuilds

---

## 📦 Build Artifacts

| Platform | Artifact |
|----------|----------|
| 🐧 Linux  | `export_templates_linux.zip` |
| 🪟 Windows| `export_templates_windows.zip` |

➡️ Download them from the **GitHub Actions run artifacts** once the workflow completes.

---

## 🧪 Run It Manually

Trigger this workflow using the **"Run workflow"** button under  
`Actions > Build Export Templates`.

---

## 📸 Follow Me & Stay Updated

- 🌐 GitHub:
- 📸 Instagram: 
- 📺 YouTube: 
- 🎮 itch.io: 

---

## 📽️ Watch the Tutorial

📹 عملت فيديو بيوضح الخطوات!

👉 الفيديو لازال غير جاهز رح ارفعه قريبا ان شاء الله 

---

## 🧠 Requirements

- Set a GitHub secret called: `SCRIPT_AES256_ENCRYPTION_KEY`  
  → Go to `Settings > Secrets and variables > Actions`

---

## 🤝 Contributions

Open to improvements! Fork it, extend it, or create a PR! 🚀

---

## 🛡️ License

MIT License — use freely, contribute kindly.

---

Made with ❤️ by @godotology
