Arabic Language Pack (Community) v0.6 - Full Edition (Desktop Package)
=========================================================================

Unofficial Community Beta | إضافة مجتمعية غير رسمية (نسخة تجريبية Beta)
Translated with AI assistance and reviewed by sampling only.
أُعدّت الترجمات بمساعدة الذكاء الاصطناعي ومُورِجعت بالعينات فقط.

Contents / محتويات المجلد:
--------------------------
1. arabic-language-pack-0.6-full.zip
   - Main installable plugin ZIP (183 bundles, 25,877 keys)
   - Plugin ID: com.reda6dev.arabic.languagepack
   - Compatibility: Android Studio 2026.1.1 (build 261.*) only
   - الإضافة الرئيسية الجاهزة للتثبيت بالمعرّف الجديد (183 حزمة، 25,877 مفتاحاً).

2. messages/
   - All 183 Arabic-only *_ar.properties translation files (Key=Arabic only),
     ready to rebuild any edition using ArabicLangPack-Tool.
   - كل ملفات *_ar.properties العربية (مفتاح=ترجمة عربية فقط) لإعادة البناء.

3. extras/arabic-language-pack-0.6-full-legacy-id.zip
   - Fallback build with the previous plugin ID (com.intellij.ar.community),
     identical translations (183 bundles, 25,877 keys).
   - نسخة احتياطية بنفس الترجمات بالمعرّف القديم فقط عند الحاجة.

Installation / التثبيت والتفعيل:
--------------------------------
[IMPORTANT / هام]
If you previously installed an older version with ID "com.intellij.ar.community",
UNINSTALL IT FIRST and restart Android Studio before installing the new ID
("com.reda6dev.arabic.languagepack")!
إذا كنت قد ثبّتَّ نسخة سابقة بالمعرّف القديم (com.intellij.ar.community)، فاحذفها أولاً
وأعد تشغيل البرنامج قبل تثبيت النسخة الجديدة!

1. Open Android Studio 2026.1.1.
2. Go to Settings > Plugins > Gear icon > Install Plugin from Disk...
   افتح Settings > Plugins > أيقونة الترس > Install Plugin from Disk...
3. Select arabic-language-pack-0.6-full.zip and restart Android Studio.
4. Go to Settings > Appearance & Behavior > System Settings > Language and Region,
   select Arabic (ar), and restart again.
   من Language and Region اختر Arabic ثم أعد تشغيل Android Studio.

Emergency Manual Removal / الإزالة اليدوية عند الطوارئ:
--------------------------------------------------------
If the IDE UI fails to open properly:
1. Close Android Studio completely.
2. Delete the "arabic-language-pack-*" folder from your plugins directory:
   - Windows: %APPDATA%\Google\AndroidStudio2026.1.1\plugins\
   - macOS:   ~/Library/Application Support/Google/AndroidStudio2026.1.1/plugins/
   - Linux:   ~/.local/share/Google/AndroidStudio2026.1.1/plugins/
3. Start Android Studio again.

Disclaimer / إخلاء مسؤولية:
---------------------------
Independent community project (https://github.com/Reda6Dev), not affiliated with
Google LLC or JetBrains s.r.o. Android Studio, IntelliJ, and Gemini are trademarks
of their respective owners. Notice: original UI strings belong to their owners,
and legal licensing of derived translations has not been formally verified.
