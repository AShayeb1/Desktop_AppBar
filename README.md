# App Bar

Launcher bar for Windows built with WPF (.NET 8). Lets you pin programs and folders, launch quickly, and control behavior via a simple settings panel. Includes tray icon, optional desktop context menu integration, and multilingual UI.

---

<img width="318" height="146" alt="Image" src="https://github.com/user-attachments/assets/ea20e15d-522f-4c44-8953-907fafc6ec31" />
<img width="501" height="211" alt="Image" src="https://github.com/user-attachments/assets/a8e2757a-512d-4800-8d96-ff1112c0ba6a" />
<img width="332" height="269" alt="Image" src="https://github.com/user-attachments/assets/1bd8ee4c-31cc-4cf9-afa0-caed339e0f89" />
<img width="743" height="761" alt="Image" src="https://github.com/user-attachments/assets/bd1ef335-2879-4047-8ea5-191f963e2fa1" />
<img width="628" height="510" alt="Image" src="https://github.com/user-attachments/assets/014fbe07-ffc2-4140-82c3-d2d750f17569" />
<img width="209" height="163" alt="Image" src="https://github.com/user-attachments/assets/646da28e-3dd9-4f22-83ea-5d06ec4ed434" />
![Image](https://github.com/user-attachments/assets/c49c9c54-8d68-4b66-b964-c8de575123fc)

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

### Requirements
- OS: Windows 10 or Windows 11.
- Runtime: .NET 8 Desktop Runtime (WPF).

### Data locations
- Settings: `%LOCALAPPDATA%\AppBar\settings.json`
- Programs: `%LOCALAPPDATA%\AppBar\programs.json`

### Notes
- On Windows 11, the desktop context menu entry may appear under "Show more options".
- Start minimized with the `--minimized` command-line switch.
