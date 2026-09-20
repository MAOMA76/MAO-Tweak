<div align="center">

# ⚡ Tweak

**أداة احترافية لتحسين ومراقبة ويندوز — بواجهة أنيقة ولغتين**

**A professional Windows optimizer & hardware monitor — elegant UI, bilingual (AR/EN)**

[![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%2F%2011-c9762e)](https://github.com)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)
[![Language](https://img.shields.io/badge/Language-C%23%20.NET%208-blue)](https://dotnet.microsoft.com)

</div>

---

## 📥 التحميل | Download

حمّل أحدث نسخة من صفحة [Releases](../../releases) — ملف `Tweak.zip`، فك الضغط وشغّل `Tweak.exe` **كمسؤول**.

> ⚠️ **ملاحظة SmartScreen:** البرنامج غير موقّع رقمياً حالياً، لذلك قد يظهر تحذير أزرق عند أول تشغيل. اضغط **More info → Run anyway** — هذا طبيعي لأي برنامج جديد غير موقّع.
>
> **SmartScreen note:** The app isn't code-signed yet, so Windows may show a blue warning on first run. Click **More info → Run anyway** — this is normal for new unsigned apps.

---

## ✨ المميزات | Features

### 📊 لوحة مراقبة حية | Live Dashboard
- **عداد دائري** لاستهلاك الرام يتحدث لحظياً
- المعالج: الاستهلاك، التردد، **الحرارة**
- الرام: الاستهلاك، **التردد الفعلي**، الحرارة (إن توفر الحساس)
- كرت الشاشة: الاستهلاك و**الحرارة**
- التخزين: المساحة المستخدمة + حرارة SSD
- عداد العمليات النشطة

> Circular RAM gauge, CPU/GPU/SSD **temperatures**, RAM speed, storage & process counters — all updated live.

### ⚡ تنظيف ذكي | Smart Cleaning
- تنظيف الرام والكاش (Standby) بطريقة RAMMap الرسمية
- قتل تطبيقات الخلفية الزائدة وتعطيلها نهائياً
- تنظيف الملفات المؤقتة + تفعيل Storage Sense
- خطة الأداء العالي

### 🛠️ إدارة خدمات تفاعلية | Interactive Services Manager
- 28 خدمة وميزة بشرح واضح — فعّل أو عطّل ما تريده أنت
- زر استعادة الوضع الافتراضي بأي وقت
- تعطيل Game DVR وCopilot وWidgets وOneDrive التلقائي

### 🗑️ Debloat
- حذف 20+ تطبيق مدمج زائد (لا يرجعون مع التحديثات)
- تعطيل مهام التتبع المجدولة (Telemetry)
- تعطيل إعلانات ويندوز والاقتراحات والتلميحات الترويجية

### 🌍 لغتان | Bilingual
- زر تبديل فوري بين **العربية والإنجليزية** — كل النصوص والشرح مترجم
- Instant **Arabic ⇄ English** toggle for the entire UI

---

## 🖥️ التوافق | Compatibility

| | |
|---|---|
| الأنظمة | Windows 10 (2004+) / Windows 11 — 64-bit |
| المتطلبات | لا شيء! ملف واحد مكتمل (self-contained) |
| الصلاحيات | مسؤول (يطلب تلقائياً عند التشغيل) |

---

## 🔨 البناء من المصدر | Build from Source

```bash
cd src
dotnet publish -c Release -o ./dist
# الناتج: dist/Tweak.exe — ملف واحد مكتمل
```

يتطلب [.NET 8 SDK](https://dotnet.microsoft.com/download) — Requires .NET 8 SDK.

---

## ⚖️ إخلاء مسؤولية | Disclaimer

استخدم البرنامج على مسؤوليتك الخاصة. كل التعديلات قابلة للاستعادة من داخل البرنامج نفسه (زر "استعادة الافتراضي")، لكن يُنصح بإنشاء نقطة استعادة نظام قبل الاستخدام الأول.

Use at your own risk. All changes are reversible from within the app ("Restore defaults"), but creating a system restore point before first use is recommended.

---

## 📚 التقنيات | Built With

- **C# / .NET 8** — WinForms
- **[LibreHardwareMonitor](https://github.com/LibreHardwareMonitor/LibreHardwareMonitor)** — قراءة حساسات الحرارة والترددات (MPL-2.0)

---

## 📄 الترخيص | License

MIT License — انظر ملف [LICENSE](LICENSE)

<div align="center">
صُنع بـ 🤎 بواسطة <b>MAO</b>
</div>
