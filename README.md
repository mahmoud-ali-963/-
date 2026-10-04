
# 🚀 مُنشئ قوالب تصدير غودوت (مؤمن بتشفير AES-256) 🔐

This GitHub Actions workflow automatically builds **Android** and **Windows export templates** from the **latest stable version of Godot Engine**, with added security using an **AES-256 script** for protecting your game scripts.

## 🎯 المميزات الرئيسية

- ✅ سحب واستنساخ أحدث مصدر رسمي لـ محرك Godot
- 🔐 دمج تشفير AES-256 لضمان بناء محرك وقوالب آمنة
- ⚙️ بناء قوالب التصدير لكل من:
  -  Android
  -  Windows
- 📦 رفع قوالب التصدير بصيغة ملفات ضغط .zip جاهزة للتحميل
- ☁️ تفعيل التخزين المؤقت (Caching) لتسريع عمليات البناء القادمة

---
## الخطوات المختصرة :
اسم الريبو الجديدة :
My-Encrypted-Godot

اسم المفتاح السري في غت هب
SCRIPT_AES256_ENCRYPTION_KEY

برومت توليد مفتاح عشوائي:
"اكتب لي مفتاح تشفير عشوائي وقوي بصيغة AES-256 مكون من 64 حرفاً سداسياً عشرياً (Hex) صالحاً للاستخدام كمفتاح سري في GitHub Secrets، وبدون أي نصوص إضافية."


مسار و اسم الملف: 
.github/workflows/Encrypted-Godot-Build.yml

---
## 📦 ملفات البناء الجاهزة (Artifacts)

| Platform | Artifact |
|----------|----------|
| 💻 Custom Editor  | `godot-custom-editor` |
| 🐧 Linux  | `linux-export-templates.zip` |
| 🤖 Android  | `android-export-templates.zip` |
| 🪟  Windows| `windows-export-templates.zip` |


➡️ يمكنك تحميلها مباشرة من قسم Artifacts في صفحة GitHub Actions فور اكتمال عملية البناء بنجاح.

---

## 🧪  التشغيل اليدوي

يمكنك تشغيل هذا الـ Workflow يدوياً في أي وقت عبر الضغط على زر "Run workflow" من تبويب:
`Actions > Build Export Templates`.

---

## 📸 تابعني على منصات التواصل 


- 📸 Instagram: https://www.instagram.com/godotology/
- 📺 YouTube: https://www.youtube.com/@godotology
- 🎮 itch.io: https://mahmoud-ali-963.itch.io/

---

## 📹 عملت فيديو بيوضح الخطوات!

👉 الفيديو لازال غير جاهز رح ارفعه قريبا ان شاء الله 

---

## 🧠 المتطلبات

- Set a GitHub secret called: `SCRIPT_AES256_ENCRYPTION_KEY`  
  → Go to `Settings > Secrets and variables > Actions`

---

## 🤝 المساهمة والتطوير

المشروع مفتوح دائماً للتحسينات! قم بعمل Fork، طوّر المشروع، أو افتح طلب سحب (PR) لإضافاتك الجديدة 🚀.

---

## 🛡️ الترخيص

MIT License — use freely, contribute kindly.

---

Made with ❤️ by @godotology
