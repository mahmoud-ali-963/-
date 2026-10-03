
# 🚀 مُنشئ قوالب تصدير غودوت (مؤمن بتشفير AES-256) 🔐

This GitHub Actions workflow automatically builds **Linux** and **Windows export templates** from the **latest stable version of Godot Engine**, with added security using an **AES-256 script** for protecting your game scripts.

## 🎯 المميزات الرئيسية

- ✅ سحب واستنساخ أحدث مصدر رسمي لـ محرك Godot
- 🔐 دمج تشفير AES-256 لضمان بناء محرك وقوالب آمنة
- ⚙️ بناء قوالب التصدير لكل من:
  -  Android
  -  Windows
- 📦 رفع قوالب التصدير بصيغة ملفات ضغط .zip جاهزة للتحميل
- ☁️ تفعيل التخزين المؤقت (Caching) لتسريع عمليات البناء القادمة

---

## 📦 ملفات البناء الجاهزة (Artifacts)

| Platform | Artifact |
|----------|----------|
| Android  | `android-export-templates.zip` |
| 🪟 Windows| `windows-export-templates.zip` |

➡️ يمكنك تحميلها مباشرة من قسم Artifacts في صفحة GitHub Actions فور اكتمال عملية البناء بنجاح.

---

## 🧪  التشغيل اليدوي

يمكنك تشغيل هذا الـ Workflow يدوياً في أي وقت عبر الضغط على زر "Run workflow" من تبويب:
`Actions > Build Export Templates`.

---

## 📸 تابعني على منصات التواصل 

- 🌐 GitHub:
- 📸 Instagram: 
- 📺 YouTube: 
- 🎮 itch.io: 

---

## 📽️ Watch the Tutorial

📹 عملت فيديو بيوضح الخطوات!

👉 الفيديو لازال غير جاهز رح ارفعه قريبا ان شاء الله 

---

## 🧠 المتطلبات

- Set a GitHub secret called: `SCRIPT_AES256_ENCRYPTION_KEY`  
  → Go to `Settings > Secrets and variables > Actions`

---

## 🤝 المساهمة والتطوير

المستودع مفتوح دائماً للتحسينات! قم بعمل Fork، طوّر المشروع، أو افتح طلب سحب (PR) لإضافاتك الجديدة 🚀.

---

## 🛡️ الترخيص

MIT License — use freely, contribute kindly.

---

Made with ❤️ by @godotology
