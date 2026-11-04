<div dir="rtl">

# استديو التعريب — Arabization Studio

**منصة متكاملة لتعريب الألعاب والبرامج وترجمة الملفات والترجمات المرئية**، بواجهة عربية كاملة من اليمين لليسار (والإنجليزية متوفرة).

[![أحدث إصدار](https://img.shields.io/github/v/release/baybarssy-source/Arabization_Studio_project?label=%D8%A3%D8%AD%D8%AF%D8%AB%20%D8%A5%D8%B5%D8%AF%D8%A7%D8%B1&color=2563eb)](https://github.com/baybarssy-source/Arabization_Studio_project/releases/latest)
[![التنزيلات](https://img.shields.io/github/downloads/baybarssy-source/Arabization_Studio_project/total?label=%D8%A7%D9%84%D8%AA%D9%86%D8%B2%D9%8A%D9%84%D8%A7%D8%AA&color=16a34a)](https://github.com/baybarssy-source/Arabization_Studio_project/releases)
![Windows 10/11](https://img.shields.io/badge/Windows-10%20%2F%2011%20(64--bit)-0078d4)

### ⬇️ [تحميل أحدث إصدار](https://github.com/baybarssy-source/Arabization_Studio_project/releases/latest)
حمّل ملف التثبيت `*_x64-setup.exe` من قسم **Assets** في صفحة الإصدار وشغّله.

![جدول الترجمة](images/01-editor.webp)

## ماذا يفعل البرنامج؟
افتح ملف نصوص اللعبة أو البرنامج أو الترجمة المرئية، ترجمه بالمحرك الذي تفضّله أو يدوياً، راجعه وافحص جودته، ثم احفظه **بنفس صيغته وترميزه** جاهزاً للاستخدام.

## المزايا الرئيسية
- **جدول ترجمة سريع** يفتح ملفات بملايين الأسطر: TXT وJSON وCSV/TSV وXLSX وPO وXLIFF وSRT/VTT/ASS، مع تراجع غير محدود وبحث واستبدال (تعبيرات نمطية وتطبيع عربي) وفلاتر ومشاريع `.asproj`.
- **ترجمة ذكية** بأكثر من 30 محركاً: Google وDeepL وMicrosoft وGemini وOpenAI وClaude وOpenRouter وGroq وOllama وغيرها — مع **مفاتيح API متعددة** وجدولة آمنة للحصص، وحماية الأكواد والوسوم (`{0}` و`<b>` و`%d`…) ومراجعة لغوية بالذكاء الاصطناعي.
- **ذاكرة ترجمة وقاعدة مصطلحات**: اقتراحات فورية بالمطابقة الضبابية، وتطبيق على كل المطابقات بخطوة تراجع واحدة.
- **عكس النصوص (ArabiFlip v4)** للألعاب التي لا تدعم العربية، مع معاينة «كما في اللعبة».
- **استوديو الترجمات المرئية**: التوقيتات، والإزاحة، وإصلاح التداخل، والتقسيم والدمج، وفحص سرعة القراءة وطول السطر.
- **نماذج محلية** تعمل دون إنترنت (NLLB وArgos وغيرها) وتشكيل النص العربي.
- **فحص الجودة، ضبط عربي، دردشة AI، ملفات متعددة، استيراد تحديث الأصل**، ودليل استخدام مدمج (F1).

## لقطات الشاشة
| | |
|---|---|
| ![الترجمة الذكية](images/02-smart-translate.webp) **الترجمة الذكية** | ![ذاكرة الترجمة](images/03-translation-memory.webp) **ذاكرة الترجمة** |
| ![المصطلحات](images/04-glossary.webp) **قاعدة المصطلحات** | ![عكس النصوص](images/05-arabiflip.webp) **عكس النصوص (ArabiFlip)** |
| ![الترجمات المرئية](images/06-subtitles.webp) **استوديو الترجمات المرئية** | ![النماذج المحلية](images/07-local-models.webp) **النماذج المحلية** |
| ![إعدادات الترجمة](images/08-engines.webp) **إعدادات الترجمة والمحركات** | ![الإعدادات](images/11-settings.webp) **الإعدادات** |
| ![معالج البداية](images/09-onboarding.webp) **معالج البداية** | ![دليل الاستخدام](images/10-help.webp) **دليل الاستخدام** |

![السمة الداكنة](images/12-editor-dark.webp)

## متطلبات التشغيل
- Windows 10 أو 11 (64-بت). يُثبَّت WebView2 تلقائياً إن لم يكن موجوداً.
- اتصال بالإنترنت للمحركات السحابية فقط؛ النماذج المحلية تعمل دون اتصال (محرّكها تنزيل اختياري من داخل البرنامج، نحو 1–2 غيغابايت).
- مفاتيح API للمحركات التي تحتاجها (Google Translate المجاني لا يحتاج مفتاحاً).

## تحذير SmartScreen عند أول تثبيت
ملف التثبيت غير موقّع بشهادة تجارية، لذلك قد يعرض Windows رسالة «Windows protected your PC». اضغط **مزيد من المعلومات** ثم **تشغيل على أي حال**. التحديثات نفسها موقّعة رقمياً ويتحقق البرنامج من توقيعها قبل تثبيتها.

## التحديثات
يتحقق البرنامج من وجود إصدار جديد عند التشغيل (يمكن إيقاف ذلك من الإعدادات)، فيظهر شريط «يتوفر إصدار جديد» مع **«ما الجديد»**، ويُنزَّل التحديث ويُثبَّت بضغطة واحدة بعد حفظ عملك. ويمكنك التحقق يدوياً من «مساعدة ← التحقق من التحديثات» أو نافذة «حول البرنامج». ملاحظات كل إصدار في [صفحة الإصدارات](https://github.com/baybarssy-source/Arabization_Studio_project/releases).

## التواصل
المصمم: abo3bdoo.sy@gmail.com · [x.com/Abo3bdooS](https://x.com/Abo3bdooS)

</div>

---

## English

**Arabization Studio** is an all-in-one Windows app for Arabizing games and software and translating files and subtitles, with a full right-to-left Arabic interface (English UI included).

**[⬇️ Download the latest release](https://github.com/baybarssy-source/Arabization_Studio_project/releases/latest)** — get the `*_x64-setup.exe` installer from **Assets**.

**Key features**
- Fast translation table for huge files (TXT, JSON, CSV/TSV, XLSX, PO, XLIFF, SRT/VTT/ASS), saved back with the same encoding and formatting; unlimited undo, regex find & replace, filters, projects.
- Smart translation with 30+ engines (Google, DeepL, Microsoft, Gemini, OpenAI, Claude, OpenRouter, Groq, Ollama…), multiple API keys with quota-safe scheduling, code/tag protection and AI review.
- Translation memory and glossary with fuzzy suggestions; ArabiFlip v4 text flipping for games without Arabic support; a subtitles studio; offline local models (NLLB, Argos) and diacritization; QA checks, AI chat, batch files and a built-in guide.

**Requirements:** Windows 10/11 64-bit (WebView2 is installed automatically if missing). Internet only for cloud engines.

**SmartScreen:** the installer isn't signed with a commercial certificate, so Windows may warn on first install — choose **More info → Run anyway**. Updates are signed and verified by the app.

**Updates:** the app checks for new versions at startup (can be turned off in Settings), shows the release notes ("What's new") and installs the update in one click. Release notes for every version are on the [Releases](https://github.com/baybarssy-source/Arabization_Studio_project/releases) page.
