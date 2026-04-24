# App Bar

Launcher bar for Windows built with WPF (.NET 8). Lets you pin programs and folders, launch quickly, and control behavior via a simple settings panel. Includes tray icon, optional desktop context menu integration, and multilingual UI.

---

https://github.com/user-attachments/assets/d07395e0-9b80-4925-9fc7-f0d1fb01633f

<img width="318" height="146" alt="Image" src="https://github.com/user-attachments/assets/ea20e15d-522f-4c44-8953-907fafc6ec31" />
<img width="562" height="217" alt="Image" src="https://github.com/user-attachments/assets/4c32d9a5-761f-4924-8e09-2436a90ca664" />

---

## العربية

### فكرة البرنامج
- "App Bar" هو تطبيق WPF على ويندوز يُظهر شريطًا بسيطًا يحتوي على أيقونات البرامج والمجلدات لسهولة التشغيل والتنظيم.
- يوفّر إعدادات مرئية ووظيفية مثل عدد الصفوف وعدد العناصر في كل صف والشفافية واللغة، مع إمكانية التصغير إلى الشريط بجانب الساعة.

### المميزات
- إضافة البرامج يدويًا أو اكتشافها تلقائيًا من النظام.
- دعم إضافة المجلدات مع إمكانية تحديد أيقونة مخصصة للمجلد.
- سحب وإفلات الملفات/المجلدات إلى الشريط لإضافتها بسرعة.
- قائمة سياق لكل عنصر: تشغيل كمسؤول، فتح موقع الملف، حذف.
- الحفظ والاسترجاع التلقائي لقائمة البرامج في `%LOCALAPPDATA%`.
- إعدادات واجهة ولغة: العربية، الإنجليزية، الفرنسية، الروسية، الصينية.
- خيارات التشغيل: "ابدأ مع ويندوز"، "تصغير إلى الشريط"، "دائمًا في الأعلى"، و"الطي التلقائي".
- تكامل اختياري مع قائمة سطح المكتب (النقر بالزر الأيمن) عبر السجل.
- أيقونة في شريط النظام مع قائمة مختصرة لفتح التطبيق أو الخروج.
- **تحديثات الإصدار 1.4:**
    - جعل التمدد مركزياً (يمين ويسار) للحفاظ على موقع الشريط ثابتاً.
    - توسيط الأيقونة المصغرة عند الطي تماماً في منتصف النافذة.
    - جعل خلفية الأيقونة المصغرة شفافة تماماً لإظهار الأيقونة فقط عند الطي.
    - تحديث أيقونة البرنامج بتصميم جديد عالي الجودة.
- **تحديثات الإصدار 1.5:**
    - إصلاح مشكلة الخلفية السوداء التي كانت تظهر عند طي البرنامج.
    - تحسين عملية تصغير حجم النافذة لتناسب الأيقونة تماماً عند الطي.
    - معالجة مشاكل الشفافية لضمان تجربة عرض سلسة للأيقونة العائمة.

### متطلبات التشغيل
- نظام التشغيل: Windows 10 أو Windows 11.
- إطار العمل: .NET 8 Desktop Runtime (WPF).

### أين تُحفَظ البيانات
- الإعدادات: `%LOCALAPPDATA%\AppBar\settings.json`
- البرامج: `%LOCALAPPDATA%\AppBar\programs.json`

### ملاحظات
- قد تظهر قائمة سطح المكتب داخل "إظهار المزيد من الخيارات" على Windows 11.
- يمكن بدء التطبيق مصغّرًا باستخدام الوسيط: `--minimized`.

---

## English
### Idea
- App Bar is a WPF Windows application that shows a simple bar with program and folder icons for quick launching and organization.
- Provides visual and behavioral settings (rows, items per row, transparency, language) with optional tray minimization.

### Features
- Add programs manually or discover installed software automatically.
- Support adding folders with optional custom icons.
- Drag-and-drop files/folders onto the bar to add quickly.
- Per-item context menu: Run as Administrator, Open File Location, Delete.
- Persist programs and settings under `%LOCALAPPDATA%`.
- Multilingual UI: Arabic, English, French, Russian, Chinese.
- Behavior options: Start with Windows, Minimize to Tray, Always on Top, Auto-collapse.
- Optional desktop context menu integration via registry.
- Tray icon with quick menu to open or exit the app.
- **Version 1.4 Updates:**
    - Centered expansion (expands left and right) to keep the bar's position fixed.
    - Perfectly centered small icon during auto-collapse.
    - Made the collapsed icon background fully transparent to show only the icon.
    - Updated the application icon with a new high-quality design.
- **Version 1.5 Updates:**
    - Fixed the black background issue when the app was collapsed.
    - Optimized window resizing to fit the icon perfectly during collapse.
    - Improved transparency handling for a better floating icon experience.

### Requirements
- OS: Windows 10 or Windows 11.
- Runtime: .NET 8 Desktop Runtime (WPF).

### Data locations
- Settings: `%LOCALAPPDATA%\AppBar\settings.json`
- Programs: `%LOCALAPPDATA%\AppBar\programs.json`

### Notes
- On Windows 11, the desktop context menu entry may appear under "Show more options".
- Start minimized with the `--minimized` command-line switch.
