# 🏫 نظام حجز المختبرات

[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

## 📋 نظرة عامة

نظام حجز م交互ي للمختبرات في مدرسة **الحوراء** بسلطنة عمان. يعرض جدول الحجز الحالي على شاشة عرض (TV) مع ميزات متقدمة.

## ⭐ المميزات

### 📊 عرض البيانات
- جدول حجز تفاعلي
- تمييز الفترة الحالية (ذهبي) والتالية (سماوي)
- فرق بين المحجوز والمتاح
- إحصائيات الحجز (المحجوز، المتاح، النسبة المئوية)

### ⏱️ ميزات إضافية
- عداد تنازلي لبداية الدوام (6:30 صباحاً)
- رمز QR للوصول من الجوال
- شريط أخبار الأمان
- دعم اليومين (الجمعة والسبت)

### 🕐 الجدولة
- دعم 10 فترات دراسية
- جدول الصباح والمساء
- تحديث تلقائي كل 5 دقائق

### 🔌 التكامل
- ربط مع Google Sheets
- تحديث تلقائي عبر CSV Feed
- دعم منطقة Oman الزمنية (Asia/Muscat)

## 🖥️ الواجهة

```
┌─────────────────────────────────────────┐
│        مدرسة الحوراء - حجز المختبر       │
├─────────────────────────────────────────┤
│  الفترة الحالية: الفصل 3 (golden)      │
│  الفترة التالية: الفصل 4 (sky blue)     │
├─────────────────────────────────────────┤
│  │ الفصل │ المحجوز │ الحالة │         │
│  │   1    │  ✓✓✓   │ محجوز  │         │
│  │   2    │  ✓     │ متاح   │         │
│  │   3    │  ✓✓✓✓  │ محجوز  │         │
│  ...                                    │
└─────────────────────────────────────────┘
```

## 🚀 التشغيل

```bash
# استنساخ المستودع
git clone https://github.com/ahmed4050/LAB_BOOKING2.git

# فتح index.html في المتصفح
# أو استخدام محرك خادم محلي
```

## ⚙️ الإعدادات

1. أنشئ Google Sheet يحتوي على بيانات الحجز
2. انشر الـ Sheet كـ CSV Feed
3. حدث رابط الـ CSV في الكود

## 📁 هيكل الملفات

```
LAB_BOOKING2/
├── index.html          # الصفحة الرئيسية
├── style.css           # الأنماط
├── script.js           # المنطق البرمجي
└── README.md           # هذه الملفات
```

## 📱 متوافق مع

- 🖥️ أجهزة الكمبيوتر
- 📱 الهواتف الذكية
- 📺 شاشات العرض (TV)

## 👨‍💻 المؤلف

**Ahmed Al-Qassabi** - [GitHub](https://github.com/ahmed4050)

## 📄 الرخصة

هذا المشروع مرخص بموجب رخصة MIT.
