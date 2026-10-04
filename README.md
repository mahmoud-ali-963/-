
# 🚀 مُنشئ قوالب تصدير غودوت (مؤمن بتشفير AES-256) 🔐

يقوم هذا الملف في جيت هب ببناء قوالب تصدير أنظمة أندرويد، ويندوز، ولينكس تلقائياً من أحدث إصدار مستقر لمحرك غودوت، مع ميزة الأمان الإضافية المتمثلة في استخدام سكريبت تشفير بحماية متقدمة لحماية ملفات اللعبة.

## 🎯 المميزات الرئيسية

- ✅ سحب واستنساخ أحدث مصدر رسمي لـ محرك Godot
- 🔐 دمج تشفير AES-256 لضمان بناء محرك وقوالب آمنة
- ⚙️ بناء قوالب التصدير لكل من:
  -  Android
  -  Windows
  -  Linux
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
## 📦 ملفات البناء الجاهزة (النتيجة النهائية يعني) (Artifacts)

| Platform | Artifact |
|----------|----------|
| 💻 Custom Editor  | `godot-custom-editor` |
| 🐧 Linux  | `linux-export-templates.zip` |
| 🤖 Android  | `android-export-templates.zip` |
| 🪟  Windows| `windows-export-templates.zip` |


➡️ يمكنك تحميلها مباشرة من قسم Artifacts في صفحة GitHub Actions فور اكتمال عملية البناء بنجاح.

او اذا كنت تريد الطريقة السهلة رابط تنزيل المحرر و قوالب التصدير الجاهزة هنا :
==سيتم ادراج الرابط هنا قريباً 
---

## 🧪  التشغيل اليدوي

يمكنك تشغيل هذا الـ Workflow يدوياً في أي وقت عبر الضغط على زر "Run workflow"

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
