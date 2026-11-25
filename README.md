# Arabic Language Pack for Android Studio — تعريب Android Studio

> **Unofficial community Beta** · Arabic (`ar`) user-interface translation for **Android Studio 2026.1.1 (build 261.\*)** · AI-assisted translation, reviewed by sampling only.
>
> **حزمة لغة عربية مجتمعية غير رسمية (تجريبية)** لواجهة Android Studio 2026.1.1، ترجمة بمساعدة الذكاء الاصطناعي وراجعتها بالعينات فقط.

<!-- Add screenshots here, for example:
![Menus in Arabic](screenshots/menus.png)
-->

## What you get

- **183 resource bundles / 25,877 translated keys** in a single installable plugin.
- Menus, dialogs, tooltips, **Settings** pages, Git / VCS, Run / Debug, Gradle, Logcat and device tools, and most of the **Gemini** agent panel.
- Partial localization by design: anything not translated falls back to English with no errors.
- Git operations and programming terms (`Commit`, `Push`, `Pull`, `Merge`, `Gradle`, `SDK`, `Refactor`, `Debug`...) are intentionally kept in English.

## Install

1. Download `arabic-language-pack-0.6-full.zip` from the **[Releases](../../releases)** page.
2. In Android Studio: `Settings > Plugins > ⚙ > Install Plugin from Disk...` → choose the zip → restart.
3. `Settings > Appearance & Behavior > System Settings > Language and Region` → select **Arabic** → restart.

If you installed an earlier build with the old plugin ID `com.intellij.ar.community`, **uninstall it first** and restart. If Arabic does not appear, try `arabic-language-pack-0.6-full-legacy-id.zip` from the same release.

## Remove

`Settings > Language and Region > English`, or uninstall the plugin from `Settings > Plugins`.
If the IDE fails to start: close Android Studio and delete the `arabic-language-pack-*` folder inside `%APPDATA%\Google\AndroidStudio2026.1.1\plugins\` (Windows).

## Known limitations

- Tested on **Windows with Android Studio 2026.1.1 (build 261.\*) only**.
- Some Android-specific items (for example most of the **Build** menu) are hard-coded in Google's code and **cannot** be translated by a language pack.
- Error messages, code inspections and programming-language-specific texts stay in English on purpose.
- Arabic text inside a left-to-right interface can show punctuation and shortcut-letter ordering quirks.
- Not published on JetBrains Marketplace (install from disk).

## Build your own / continue the work

The extraction, validation and build tools plus the full process guide live in the companion repository:
**[android-studio-arabic-langpack-tools](https://github.com/Reda6Dev/android-studio-arabic-langpack-tools)**.
The `messages/` folder here contains the Arabic `*_ar.properties` files (key = Arabic only) that the tools turn into the plugin zip.

## Report a wrong translation

Open an **[Issue](../../issues)** with: the English text, the current Arabic text, your suggested fix, and where it appears in the IDE.

## Disclaimer

Independent community project (https://github.com/Reda6Dev), not affiliated with or endorsed by Google LLC or JetBrains s.r.o. *Android Studio* and *Gemini* are trademarks of Google LLC; *IntelliJ* and *IntelliJ IDEA* are trademarks of JetBrains s.r.o. Original UI strings belong to their respective owners; the legal status of derived translations has not been formally reviewed.

---

# بالعربي

**تعريب Android Studio** — حزمة لغة عربية مجتمعية غير رسمية (Beta) لواجهة **Android Studio 2026.1.1 (بناء 261.\*)**.

- **183 حزمة نصوص و25,877 مفتاحاً مترجماً**: القوائم والحوارات والتلميحات وصفحات **Settings** وGit وRun وDebug وGradle وأدوات الأجهزة ومعظم لوحة **Gemini**.
- الترجمة جزئية بالتصميم: أي نص غير مترجم يظهر بالإنجليزية بدون أخطاء.
- عمليات Git والمصطلحات البرمجية (`Commit` و`Push` و`Gradle` و`SDK` ...) تبقى بالإنجليزية عمداً.

## التثبيت

1. نزّل `arabic-language-pack-0.6-full.zip` من صفحة **[Releases](../../releases)**.
2. من Android Studio: `Settings > Plugins > ⚙ > Install Plugin from Disk...` ← اختر الملف ← أعد التشغيل.
3. `Settings > Appearance & Behavior > System Settings > Language and Region` ← اختر **Arabic** ← أعد التشغيل.

إذا ثبّتَّ نسخة قديمة بالمعرّف `com.intellij.ar.community` فاحذفها أولاً. وإن لم تظهر العربية جرّب ملف `legacy-id` من نفس الصفحة.

## الإزالة

غيّر اللغة إلى English من `Language and Region`، أو احذف الإضافة من `Settings > Plugins`. وإن لم يفتح البرنامج: أغلقه واحذف مجلد `arabic-language-pack-*` من `%APPDATA%\Google\AndroidStudio2026.1.1\plugins\` (Windows).

## القيود

- جُرّبت على **Windows مع Android Studio 2026.1.1 فقط**.
- بعض عناصر أندرويد (مثل معظم قائمة **Build**) مكتوب نصها داخل كود Google ولا تغيّره حزمة لغة.
- رسائل الأخطاء ونصوص الفحوصات ونصوص لغات البرمجة تبقى بالإنجليزية عمداً.
- الواجهة تبقى من اليسار لليمين، فقد يظهر ترتيب علامات الترقيم وحرف الاختصار مقلوباً أحياناً.

## الإبلاغ عن ترجمة خاطئة

افتح **[Issue](../../issues)** واكتب النص الإنجليزي والترجمة الحالية والتصحيح المقترح ومكان ظهورها.

## للمساهمة أو إكمال العمل

الأدوات ودليل العملية الكامل في المستودع المرافق: **[android-studio-arabic-langpack-tools](https://github.com/Reda6Dev/android-studio-arabic-langpack-tools)**.

## إخلاء مسؤولية

مشروع مجتمعي مستقل لا يتبع Google ولا JetBrains. **Android Studio** و**Gemini** علامتان تجاريتان لشركة Google LLC، و**IntelliJ** علامة تجارية لشركة JetBrains s.r.o. نصوص الواجهة الأصلية ملك أصحابها، ولم تُراجَع الحالة القانونية للترجمات المشتقة.
