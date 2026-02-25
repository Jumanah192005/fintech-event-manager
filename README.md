# فنتك في حياتنا — نظام إدارة الفعالية
### Fintech in Our Lives — Event Management System

<div align="center">

![Version](https://img.shields.io/badge/version-2.0-gold)
![Firebase](https://img.shields.io/badge/Firebase-Realtime-orange)
![License](https://img.shields.io/badge/license-MIT-blue)

**نظام متكامل لإدارة ومتابعة فعالية "فنتك في حياتنا" — جامعة الإمام محمد بن سعود الإسلامية**

[🚀 تشغيل مباشر](https://YOUR_USERNAME.github.io/fintech-event-manager/) · [📋 المميزات](#المميزات) · [⚙️ التثبيت](#التثبيت)

</div>

---

## 📖 نبذة

نظام إدارة فعاليات متكامل مبني كتطبيق ويب واحد (Single HTML File) مع دعم Firebase للمزامنة اللحظية بين الأجهزة. مصمم خصيصاً لإدارة فعالية "فنتك في حياتنا" التي ينظمها نادي TechNation بالتعاون مع نادي المالية.

## ✨ المميزات

### 🔐 النظام
- تسجيل دخول آمن بـ Firebase Authentication (إيميل + باسورد)
- 3 أدوار: مدير، مشرف جامعي، عضو
- مزامنة لحظية بين جميع الأجهزة (Firestore Real-time)
- وضع أوفلاين مع حفظ محلي (localStorage)

### 📊 الإدارة
- لوحة تحكم تفاعلية مع إحصائيات مباشرة
- إدارة المهام (إضافة، تعديل، تتبع التقدم)
- نظام التقارير مع إرفاق ملفات وصور
- نظام الموافقات مع تذكير المشرف بالإيميل
- إدارة الشركات والرعاة
- نظام الإعلانات والتحذيرات

### 📅 التخطيط
- هيكل تقسيم العمل (WBS) تفاعلي
- مخطط جانت قابل للتعديل
- الجدول الزمني للمراحل
- التقرير التنظيمي التفاعلي

### 📧 الإشعارات
- إشعارات إيميل تلقائية عبر EmailJS
- تذكير المشرف بالموافقات المعلقة
- إشعار الأعضاء بالمهام والتحذيرات

## ⚙️ التثبيت

### الطريقة السريعة
1. حمّل ملف `index.html`
2. افتحه في المتصفح
3. سجّل حساب جديد وابدأ

### مع Firebase (مزامنة)
1. أنشئ مشروع على [Firebase Console](https://console.firebase.google.com/)
2. فعّل **Authentication** → Email/Password
3. فعّل **Firestore Database** → Test Mode
4. عدّل `firebaseConfig` في الملف بإعداداتك
5. انشر عبر GitHub Pages

### النشر على GitHub Pages
```bash
git clone https://github.com/YOUR_USERNAME/fintech-event-manager.git
cd fintech-event-manager
# الملف جاهز مباشرة — فقط ارفعه
git push
```
ثم فعّل GitHub Pages من Settings → Pages → Branch: main

## 🏗️ البنية التقنية

```
fintech-event-manager/
├── index.html          # التطبيق الكامل (ملف واحد)
├── README.md           # هذا الملف
├── LICENSE             # رخصة MIT
└── .gitignore          # ملفات مستثناة
```

**التقنيات:**
- HTML5 + CSS3 + Vanilla JavaScript
- Firebase Auth + Firestore (Real-time Database)
- EmailJS (إشعارات الإيميل)
- خط Tajawal (عربي)
- تصميم متجاوب (RTL)

## 👥 الفريق

| الدور | الاسم |
|-------|-------|
| مؤسسة الفكرة | جود الطريسي |
| مؤسسة الفكرة | العنود القحطاني |
| |

## 📄 الرخصة

MIT License — يمكنك استخدام وتعديل المشروع بحرية.

---

<div align="center">

**نادي TechNation × نادي المالية**

جامعة الإمام محمد بن سعود الإسلامية — 2026

</div>
