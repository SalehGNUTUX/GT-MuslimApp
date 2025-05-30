
# GT-MuslimApp - Dhikr & Prayer | برنامج المسلم - الذكر والصلاة
# 🕌 برنامج المسلم - GT-MuslimApp

**الإصدار:** 0.1  
**الرخصة:** رخصة غنو العمومية الإصدار الثاني (GNU GPL v2)  
**الواجهة:** العربية والإنجليزية  
**المنصة:** لينكس (AppImage)  
**الحالة:** مبدئية - قيد التطوير

---

## 📌 نظرة عامة

**GT-MuslimApp** هو برنامج بسيط يعمل من خلال الطرفية لمساعدة المسلم في أداء الأذكار اليومية تلاوة و الإستماع للقرأن الكريم وبعض المهام المتعلقة بالصلاة. يهدف إلى تقديم تجربة خفيفة وسريعة عبر واجهة تفاعلية باللغة العربية (مع دعم لاحق للإنجليزية).

---

## ✅ الميزات الحالية

- يعمل من الطرفية (Terminal) بشكل مباشر.
- دعم الواجهة بالعربية والإنجليزية.
- التبديل بين اللغات أثناء التشغيل.
- تنظيم البيانات بشكل يسهّل إضافة الأذكار لاحقًا.
- توزيع البرنامج كـ AppImage لتسهيل الاستخدام.

---

## 🚧 الميزات القادمة

- عرض الأذكار اليومية (الصباح، المساء، بعد الصلاة، ...إلخ).
- البحث في القرآن الكريم (الميزة قيد الإصلاح).
- دعم التنبيهات ومواقيت الصلاة.

---

## 📦 الإعتماديات

البرنامج لا يحتاج إلى تثبيت، ولكن يجب توفر بيئة مناسبة لتشغيله، وتتضمن الأدوات التالية:

- **bash**: لتشغيل السكربت.
- **طرفية رسومية** (مثل `gnome-terminal`, `xterm`, `xfce4-terminal`, `konsole`) لتشغيل البرنامج داخل نافذة طرفية مستقلة.
- دعم **UTF-8** في الطرفية لعرض النصوص العربية بشكل سليم.
- **jq**: لتحليل ملفات JSON المستخدمة في البرنامج.
- **curl**: لجلب البيانات من الإنترنت (مثل المحتوى الصوتي أو الأذكار من السيرفرات).
- **mpv** (اختياري): لتشغيل التلاوة الصوتية داخل البرنامج.
- لا يتطلب صلاحيات الجذر (root).

> ملاحظة: يمكن تثبيت هذه الأدوات في أغلب توزيعات لينكس بواسطة مدير الحزم الخاص بتوزيعتك، مثل `apt` في أوبونتو:

```bash
sudo apt install jq curl mpv
```

## 🧰 طريقة التشغيل

بعد تحميل الملف:

```bash
chmod +x GT-MuslimApp-0.1-x86_64.AppImage
```
```bash
./GT-MuslimApp-0.1-x86_64.AppImage
```

**Version | الإصدار:** 0.1  
**License | الرخصة:** GNU General Public License v2.0 (GPLv2)  
**Language | اللغة:** 🇸🇦 العربية، 🇬🇧 English

---

## 🌙 English - Overview

**GT-MuslimApp** is a simple terminal-based Islamic utility that helps Muslims perform daily dhikr (remembrance of Allah) and prayer-related tasks. This is version `0.1`, with a minimal working set of features.

### ✅ Current Features

- Launches in terminal with future-proof support for Arabic and English.
- Multi-language support with dynamic switching.
- Designed to be lightweight and terminal-based.
- GPLv2 licensed and open-source.
- Easy to distribute as an AppImage on Linux.

### 🚧 Upcoming Features

- Displaying categorized daily **Dhikr** and Islamic remembrances.
- **Search in the Holy Qur’an** (feature under repair).
- Notifications and timed reminders.

---

## 📦 Dependencies

The program is portable and does not require installation, but the following tools must be available in your environment:

* **bash**: to run the main script.
* A **graphical terminal emulator** (e.g. `gnome-terminal`, `xterm`, `konsole`, `xfce4-terminal`).
* **UTF-8 support** in terminal to properly display Arabic text.
* **jq**: for parsing JSON files used by the program.
* **curl**: to fetch data from the internet (e.g. audio files or Dhikr content).
* **mpv** (optional): to play audio recitations within the app.
* **No root privileges** required.

> Note: You can install these dependencies easily using your Linux distribution package manager, for example on Ubuntu:

```bash
sudo apt install jq curl mpv
```

## 🛠 Usage

After downloading the AppImage:

```bash
chmod +x GT-MuslimApp-0.1-x86_64.AppImage
```
```bash
./GT-MuslimApp-0.1-x86_64.AppImage
```
Make sure your terminal supports UTF-8 to properly display Arabic text.

No root privileges are needed.

---

## 📜 License

This project is licensed under the GNU General Public License v2 (GPLv2)

## 🤝 Contributions

We welcome any suggestions or future contributions to improve the content or add new features. May Allah reward you.
