# تعريب ريميك The Legend of Zelda: Ocarina of Time | Ocarina of Time Remake Arabic

<p align="center"><a href="https://iosamai.com/zelda-ocarina-of-time/"><img src="images/iosamai.png" alt="iosamai.com" height="64"></a></p>

![](images/01.jpg)

<div dir="rtl">

تعريب كامل لريميك The Legend of Zelda: Ocarina of Time (زيلدا: أوكارينا الزمن، أوكارينا أوف تايم) على نينتندو سويتش 2 (الإصدار 1.1.1، ويشمل ملف 2.0.0): الحوارات، القوائم والإعدادات، أسماء الأماكن والشخصيات، الأدوات والمعدات، شروح الحركات، والتلميحات والرسائل، وأيضًا شعار اللعبة وأسماء الزعماء. التعريب يحل محل الإنجليزية.

> **تعريب فقط، بدون أي ملفات من اللعبة.** لازم تكون عندك نسختك الخاصة من اللعبة. هذا المستودع ما فيه لعبة ولا مفاتيح ولا روابط تحميل لها.

## اللي تحتاجه

1. ملف اللعبة `nup.` بالإصدار **1.1.1**: إما ملف مدمج 1.1.1، أو ملف فيه اللعبة الأساسية مع التحديث (v131072، يسميه البعض 2.0.0). الاثنين مجربين ونفس الملفات.
2. لغة اللعبة: **English**.
3. محاكي [**Fritchii v5.8.4**](https://github.com/Frizti/Fritchii/releases/tag/fritchii-v5.8.4)، حمّل الملف `Fritchii-v5.8.4-Windows-x64.zip` (مو Source code ولا ملف debug-symbols)، فك ضغطه وشغّل `lichii.exe`.
   - أول تشغيل للعبة يجهّز المؤثرات مرة وحدة (حوالي 15 دقيقة)، بعدها اللعب سلس من البداية.

## التثبيت

**للكمبيوتر:** سكّر المحاكي (أو Hookshot أو NX2navi). حمّل [`ZeldaOoT-Arabic-3.0.0.zip`](https://github.com/OSAMAxALHARBI/ZeldaOcarinaOfTimeRemake-Arabic/releases/latest/download/ZeldaOoT-Arabic-3.0.0.zip) من [Releases](../../releases/latest) وفك ضغطه، وافتح `ZeldaOoTArabic.exe`. إذا ظهرت رسالة "Windows protected your PC"، اضغط More info ثم Run anyway.

الخطوة 1 في البرنامج تسألك **أين تلعب؟** اختر وحدة من خمس:

### 1) المحاكيات (ملف اللعبة، لكل المحاكيات)

1. اختر «المحاكيات» ثم «اختيار ملف اللعبة» وحدد ملف `nup.` حقك.
2. الخطوة 2 (اختيارية): «اختيار الخط». الخط الافتراضي هو المسيري.
3. الخطوة 3 (اختيارية): محاذاة النصوص. الافتراضي «بدون (كالسابق)»: كل سطر في وسط المربع. تقدر تختار «الحوار فقط» أو «الحوار والقوائم» أو «كل النصوص»، وكل خيار معه صور من اللعبة توضح الفرق.
4. الخطوة 4 (اختيارية): «مودات إضافية» (تحت).
5. الخطوة 5: «تثبيت التعريب». إذا كان عليه إصدار أقدم يصير الزر «تحديث التعريب».
6. شغّل اللعبة من المحاكي.

البرنامج يتأكد إن الملف هو الإصدار 1.1.1 قبل أي تعديل، ويرفضه بدون تغيير إذا ما كان كذا. بعدها يعدّل ملف `nup.` ويحفظ بيانات الإزالة في مكانين: ملف `arabic-undo.` جنب ملف اللعبة، ونسخة ثانية داخل ملف اللعبة نفسه.

**التحديث من إصدار أقدم إلى 3.0.0:** افتح البرنامج الجديد، اختر نفس الملف واضغط «تحديث التعريب». ما تحتاج تزيل الإصدار القديم أول، وحتى لو ضاع ملف `arabic-undo.` القديم، البرنامج يحاول يرجّع الملف الأصلي من ملف اللعبة نفسه ويتأكد منه، وإذا ما قدر ما يغيّر شيء.

**على ملفك تعريب آخر؟** البرنامج يكتشفه ويقول لك، ويعطيك زر «أزل التعريب الآخر وأرجع الملف أصليا». يتأكد من كل ملف قبل الحفظ، وإذا ما تطابق شيء مع الأصلي ما يغيّر شيء. بعدها تثبّت تعريبنا عادي.

### 2) Hookshot (عندك Hookshot مبني)

1. اختر «Hookshot» ثم «اختيار مجلد Hookshot».
2. **أي مجلد تختار؟** مجلد اللعبة اللي صنعه Hookshot Builder: فيه `hookshot.exe` ومجلد `romfs` (مو مجلد `bin` اللي بداخله، ومو مجلد Hookshot Builder نفسه). لو اخترت المجلد اللي فوقه أو `bin`، البرنامج يلقى المجلد الصح بنفسه.

   ![مجلد لعبة Hookshot](images/hookshot-folder.jpg)

   **1** اسم المجلد اللي تختاره · **2** فيه `hookshot.exe` · **3** وفيه مجلد `romfs`
3. اختر الخط، ثم «تثبيت التعريب»، وشغّل `hookshot.exe`.
4. التعريب ينزل في مجلد المودات حق Hookshot: `mods\Arabic (iOsamai)`، وملفات اللعبة تبقى كما هي. مع التعريب تظهر أزرار يد التحكم اللي تلعب فيها (PlayStation أو Xbox أو Steam Deck) من نظام Hookshot نفسه.
5. التعريب مجرب على Hookshot **v2.1.0**. إذا نسختك أقدم، البرنامج يقول لك وتقدر تحمّل الأحدث أو تتجاهل.
6. بعد أي تحديث لـ Hookshot يعيد بناء اللعبة، ثبّت التعريب مرة ثانية.

### 3) بناء Hookshot لي (ما عندك Hookshot)

1. اختر «بناء Hookshot لي» ثم «اختيار ملف اللعبة» وحدد ملف `nup.` حقك (الإصدار 1.1.1، أصلي بدون تعريب).
2. اختر الإصدار: **Hookshot v2.1.0 (المجرب)**، وهو الافتراضي وينصح به، أو «آخر إصدار (على مسؤوليتك)»: ما جُرّب مع التعريب وقد لا يعمل.
3. اضغط «بناء Hookshot والتثبيت» واختر المكان. يحتاج 45 جيجا فارغة أو أكثر (أكثر على أقراص exFAT) ونحو 40 دقيقة.
4. البرنامج ينزّل Hookshot من GitHub ويتأكد من كل ملف، ويبني اللعبة على جهازك، ثم يضيف التعريب وينقل أحدث حفظ عندك.
5. تلقى اللعبة في مجلد `Zelda OoT (Hookshot)` داخل المكان اللي اخترته: شغّل `hookshot.exe` منه. أول تشغيل أبطأ قليلا.

**إذا انحذفت ملفات v2.1.0 من GitHub:** حفظنا نسخة احتياطية مطابقة، [`Hookshot-v2.1.0-BuilderParts.zip`](https://drive.google.com/file/d/1ivPgod2dfPcUVpbr72JRijWfKHK6E7Sl/view?usp=sharing) (فيها كود Hookshot المصدري ورخصته GPL). البرنامج ينزلها بنفسه إذا ما لقى الملفات، أو تقدر تنزلها وتحطها كما هي (بدون فك) جنب البرنامج أو في مجلد التنزيلات، أو تختارها من البرنامج. يتأكد من كل ملف فيها قبل ما يستخدمه.

البناء يصير على جهازك، فبرنامج الحماية يفحص الملفات. إذا حذف ملف من أدوات البناء (مثل `clang.exe`)، البرنامج يوقف ويقول لك: رجّعه من الحجر وحاول مرة ثانية.

### 4) NX2navi (عندك NX2navi مبني)

1. اختر «NX2navi» ثم «اختيار مجلد NX2navi»: المجلد اللي فيه `ocarina.exe` ومجلد `romfs`.
2. اختر الخط، ثم «تثبيت التعريب»، وشغّل اللعبة.
3. التعريب ينزل في `mods\Arabic (iOsamai)` داخل مجلد اللعبة، وملفات اللعبة تبقى كما هي. البرنامج يقرأ ملفات اللعبة الأصلية من NX2navi نفسه، فما تحتاج ملف `nup.`.
4. التعريب مجرب على NX2navi **0.9.0**. على إصدار ثاني البرنامج يقول لك، ويخليك تثبت على مسؤوليتك.
5. أزرار PlayStation وXbox تختارها من إعدادات NX2navi نفسه (Controls).

### 5) بناء NX2navi لي (ما عندك NX2navi)

1. اختر «بناء NX2navi لي» ثم «اختيار ملف اللعبة» وحدد ملف `nup.` حقك (الإصدار 1.1.1، أصلي بدون تعريب).
2. اختر الإصدار: **NX2navi 0.9.0 (المجرب)**، الافتراضي، أو «آخر إصدار (على مسؤوليتك)».
3. اضغط «بناء NX2navi والتثبيت» واختر المكان: **قرص بنظام NTFS** فيه 40 جيجا فارغة (أقراص USB بنظام exFAT تخلي البناء بطيء جدا).
4. البرنامج ينزّل NX2navi من صفحته في GitHub ويتأكد من ملفاته، ويبني اللعبة على جهازك (30 إلى 40 دقيقة)، ثم يضيف التعريب وينقل أحدث حفظ عندك.
5. تلقى اللعبة في مجلد `Zelda OoT (NX2navi)`: شغّل `ocarina.exe` منه.

في Hookshot وNX2navi تبقى الأسطر في الوسط؛ خيارات المحاذاة للمحاكيات فقط.

## نقل الحفظ

- في Hookshot وNX2navi، الخطوة 3 «نقل الحفظ» تنقل حفظك من Fritchii أو Lichii أو Eden، أو من Port للثاني (NX2navi إلى Hookshot أو العكس). البرنامج يلقى الحفظ بنفسه، أو تختار المجلد.
- الحفظ القديم ما ينحذف: Hookshot يحفظ نسخة في `user\save-backups`، وNX2navi يحفظ نسخة منه بنفسه.
- ما لقى البرنامج حفظك؟ اضغط «أين أجد الحفظ؟»: الأسهل في المحاكي تضغط على اللعبة بالزر الأيمن ثم Open Save Data Location وتختار المجلد اللي ينفتح.
- **من ملف 1.1.1 إلى ملف 2.0.0:** الاثنين نفس اللعبة ونفس الحفظ. في المحاكي الحفظ محفوظ في المحاكي نفسه مو في ملف اللعبة، فتغيير الملف ما يضيّعه: ثبّت التعريب على الملف الجديد وكمّل.
- سكّر اللعبة والمحاكي قبل نقل الحفظ.

### ملفات المود (Mac وأي Port أو محاكي)

حمّل [`ZeldaOoT-Arabic-3.0.0-Mod-Files.zip`](https://github.com/OSAMAxALHARBI/ZeldaOcarinaOfTimeRemake-Arabic/releases/latest/download/ZeldaOoT-Arabic-3.0.0-Mod-Files.zip) من [Releases](../../releases/latest) وفك ضغطه. فيه مجلد `Arabic (iOsamai)` (فيه `romfs` و`exefs`) بالخط المسيري وكل سطر في الوسط. انسخه لمجلد المودات في اللي تلعب فيه:
- **محاكي على Mac** (Eglantine أو Lichii، لأجهزة Mac بمعالج Apple M1 وأحدث) **أو أي محاكي ثاني:** مجلد مودات اللعبة (رقمها `0400486024DEC000`)، بالطريقة اللي يشرحها المحاكي.
- **Port ثاني على الكمبيوتر:** مجلد `mods` جنب ملف اللعبة `exe`. (لـ Hookshot وNX2navi استخدم البرنامج: أسهل ومجرب.)

لعبتك لازم تكون الإصدار 1.1.1 وبالإنجليزي. هذي الطريقة **ما اختبرها صاحب التعريب** على كل الأجهزة والـ Ports. إذا جربتها، قل لي من صفحة التواصل في iosamai.com.

البرنامج بالعربي، وفيه زر English فوق إذا تبيه بالإنجليزي.

## مودات إضافية

الخطوة 4 «مودات إضافية» في البرنامج فيها مودات مجربة مع التعريب: لكل مود صور وشرح، وبعضها فيديو، وتشغله أو توقفه بزر واحد ثم «تطبيق». المودات تنزل في مجلد مودات المحاكي كما هي من أصحابها بدون أي تعديل، وتقدر تلغيها في أي وقت من نفس الصفحة.

| المود | وش يسوي | صاحبه | الرخصة |
|---|---|---|---|
| [Always-On Rupee Counter](https://gamebanana.com/mods/737829) | عداد الروبيات ظاهر دائما (الرصيد والحد، أو الرصيد فقط) | PixelSage | CC BY-NC-ND 4.0 |
| [HUD of Time](https://gamebanana.com/mods/738051) | ساعة عالم اللعبة على الشاشة (12 أو 24 ساعة) | PixelSage | CC BY-NC-ND 4.0 |
| [Auto Jump](https://gamebanana.com/mods/739034) | لينك يقفز وحده من الحواف مثل نسخة 1998 | HanSoloBlaster, afiaka87 | MIT |
| [Fast Travel](https://gamebanana.com/mods/737882) | قائمة تنقل سريع بالضغط على L3 و R3 (الأماكن اللي زرتها أو كل الأماكن) مع صورها | HanSoloBlaster | MIT |
| [Movement Speed Increase](https://gamebanana.com/mods/739234) | الركض أسرع بمرة ونصف | Zerossa | MIT |
| [Hero Mode](https://gamebanana.com/mods/738612) | ضرر مضاعف وبدون قلوب تسقط | p3k07 | CC BY-NC-ND 4.0 |
| [Button prompts](https://github.com/exgde/oot-switch2-button-prompts) | أزرار PlayStation أو Xbox أو Steam Deck، ويبقى شعار التعريب | exgde | ينزل من صفحة صاحبه |

- كلها للمحاكي فقط، ما عدا «وضع البطل» يشتغل في Hookshot وNX2navi بعد. باقي المودات تغيّر كود اللعبة، وهذا ما يشتغل في الـ Ports. (في Hookshot وNX2navi تظهر أزرار يدك من نفسها.)
- كلها مطفأة في البداية. إذا وجد البرنامج مودات مثبتة عندك في المحاكي من قبل، يقول لك ويعرضها مفعّلة، وتقدر تطفيها.
- كل المودات داخل البرنامج، ما عدا أزرار PlayStation وXbox وSteam Deck: تنزل من صفحة صاحبها وقت ما تختارها (نحو 67 ميجابايت).
- إذا كان المود مثبت عندك من قبل، البرنامج يكتب «مثبت عندك» وما يلمسه.
- «التنقل السريع» بكل الأماكن: احفظ نسخة من حفظك قبله.

## الترجمة في 3.0.0

راجعت كل أسطر اللعبة مرة ثالثة، وصححت 153 سطرًا: تذكير وتأنيث الشخصيات (نساء الجيرودو، البقرة «الآنسة موو»، «صديقة» مالون إيبونا)، ومعاني كانت مقلوبة في بعض الأسطر. وصارت الأسماء موحدة في كل اللعبة، مثل «الصخر المشوي» و«عينا الحقيقة» و«قناع غورون» و«شركة ZELDA NOTES».

## الترجمة في 2.0

راجعت كل أسطر اللعبة (16,228 سطرًا) مرة ثانية من أولها لآخرها، وصححت مئات الأسطر في المعنى والمصطلحات. الأسعار صارت «X روبية» لأي رقم. أسماء مثل «دين» و«شيك» و«شارب» صارت بلون مميز عشان تنقرأ أسماء، والحروف قبل الكلمات الملوّنة صارت متصلة. وأُعيدت صياغة الكلمات اللي تحتاج شدة، ووُصلت الضحكات مثل «هيهي».

## الخطوط

فيه 11 خطًا تختار منها، وتقدر تشوف كل خط على صورة من اللعبة قبل التثبيت: المسيري (الافتراضي)، فسطاط، ميرزا، كاتبة، روبيك، وزير متن، لاله زار، الإسكندرية، آلان، مرحي، بلاي بين.

تقدر تختار خطًا واحدًا للعبة كلها، أو خطًا مختلفًا لكل جزء: الحوار والنصوص، العناوين الصغيرة، القوائم والعناوين، الأسماء الكبيرة.

لتغيير الخط بعد التثبيت: افتح البرنامج، اختر نفس الملف، اختر الخط، ثم «تطبيق الخط فقط».

### أضف خطك

من شاشة الخطوط اضغط «+ أضف خطك» واختر ملف `ttf.` أو `otf.` فيه حروف عربية. تقدر تضيف حتى 7 خطوط وتوزعها على الأجزاء الأربعة، والبرنامج يتذكرها في المرة الجاية.

- الخطوط اللي في القائمة هي المجربة فقط. خطك قد تطلع بعض حروفه صغيرة أو ناقصة؛ إذا ما عجبك ارجع للخط الافتراضي.
- إذا كان الخط في `C:\Windows\Fonts`، انسخه لمجلد ثاني أول ثم اختره من هناك.
- استخدم خطك على نسختك فقط، ورخصته مسؤوليتك.

## الإزالة

افتح البرنامج، اختر نفس الطريقة ونفس الملف (أو المجلد)، وفي الخطوة 5 «التثبيت» اضغط «إزالة التعريب» ثم أكّد:
- ملف اللعبة: يرجع الملف الأصلي كما كان بالضبط.
- Hookshot وNX2navi: ينحذف مجلد `mods\Arabic (iOsamai)` (وفي Hookshot ترجع الملفات الإنجليزية لو كانت من 2.0).
- ملفات المود: احذف مجلد `Arabic (iOsamai)` من مجلد المودات.
- المودات الإضافية: من صفحة «مودات إضافية» أطفئ المود ثم «تطبيق».

## مشاكل معروفة

- المحاكي قد يعلق أحيانًا. احفظ لعبتك كثير. هذي مشكلة في المحاكي، مو في التعريب.
- في بعض الحوارات قد يظهر مربع الحوار فاضي أو فيه نقش غريب: مشكلة في المحاكي تصير حتى في اللعبة الإنجليزية بدون أي مود. سجل المحادثات (Y) يعرض الكلام صحيح.
- نادرًا تظهر شاشة تحميل شديدة الإضاءة أو بلون غريب: أعد تشغيل اللعبة. مشكلة معروفة في المحاكي.

## الحقوق

ترجمة وتعريب: **iOsamai**. ممنوع إعادة رفع الملفات في أي مكان آخر، شارك رابط هذي الصفحة بدلها.

</div>

| | |
|---|---|
| ![](images/02.jpg) | ![](images/03.jpg) |
| ![](images/04.jpg) | ![](images/05.jpg) |
| ![](images/06.jpg) | ![](images/07.jpg) |

---

## English

Complete Arabic translation of the Nintendo Switch 2 remake of The Legend of Zelda: Ocarina of Time (version 1.1.1, the 2.0.0 file included): dialogue,
menus and settings, place and character names, items and equipment, move tutorials, hints and messages, plus the game
logo and the boss title cards. The Arabic replaces English.

> **Arabic patch only, no game files.** You need your own copy of the game. This repository holds no game, no keys and
> no download links for it.

### What you need

1. The game's `.nup` file at version **1.1.1**: either a merged 1.1.1 file, or the base game with the update
   (v131072, some call it 2.0.0). Both are tested and hold the same files.
2. Game language: **English**.
3. The [**Fritchii v5.8.4**](https://github.com/Frizti/Fritchii/releases/tag/fritchii-v5.8.4) emulator: download `Fritchii-v5.8.4-Windows-x64.zip` (not Source code or the debug-symbols file), extract it and run `lichii.exe`.
   - The first start of the game prepares its shaders once (about 15 minutes); after that it plays smoothly.

### Install

**On PC:** close the emulator (or Hookshot or NX2navi). Download [`ZeldaOoT-Arabic-3.0.0.zip`](https://github.com/OSAMAxALHARBI/ZeldaOcarinaOfTimeRemake-Arabic/releases/latest/download/ZeldaOoT-Arabic-3.0.0.zip) from [Releases](../../releases/latest), extract it and open `ZeldaOoTArabic.exe`. If "Windows protected your PC" appears, click More info, then Run anyway.

Step 1 in the program asks **Where do you play?** Pick one of five:

#### 1) Emulators (the game file, every emulator)

1. Pick "Emulators", then "Choose game file" and select your `.nup`.
2. Step 2 (optional): "Choose font". The default is El Messiri.
3. Step 3 (optional): text alignment. The default "Off (as before)" centres every line. You can choose "Dialogue only", "Dialogue + menus" or "All text"; each option shows pictures from the game.
4. Step 4 (optional): "Extra mods" (below).
5. Step 5: "Install". If an older version is on the file, the button reads "Update the patch".
6. Start the game in the emulator.

The installer checks that the file is version 1.1.1 before changing anything, and refuses it without changes otherwise. It then patches your `.nup` and keeps the removal data in two places: an `.arabic-undo` file next to the game file, and a second copy inside the game file itself.

**Updating an older version to 3.0.0:** open the new installer, pick the same file and press "Update the patch". There is no need to remove the old version first. Even if the old `.arabic-undo` file is lost, the installer tries to rebuild the original from the game file itself and checks it; if it cannot, nothing is changed.

**Another patch on your file?** The installer finds it, tells you, and offers "Remove the other patch and restore the file". Every file is checked before saving; if anything does not match the original, nothing is changed. Then install our patch as usual.

#### 2) Hookshot (you already built Hookshot)

1. Pick "Hookshot", then "Choose Hookshot folder".
2. **Which folder?** The game folder the Hookshot Builder made: it has `hookshot.exe` and a `romfs` folder (not the `bin` folder inside it, and not the Hookshot Builder's own folder). If you pick the folder above it or `bin`, the installer finds the right one.

   ![Hookshot game folder](images/hookshot-folder.jpg)

   **1** the folder you choose · **2** it has `hookshot.exe` · **3** and a `romfs` folder
3. Pick a font, press "Install", then start `hookshot.exe`.
4. The patch goes into Hookshot's mods folder, `mods\Arabic (iOsamai)`, and the game files stay as they are. With the patch, Hookshot's own system shows the buttons of the pad you play with (PlayStation, Xbox or Steam Deck).
5. The patch is tested on Hookshot **v2.1.0**. If yours is older, the installer tells you; download the newer one or ignore it.
6. After a Hookshot update that rebuilds the game, install the patch again.

#### 3) Build Hookshot (no Hookshot yet)

1. Pick "Build Hookshot", then "Choose game file" and select your `.nup` (version 1.1.1, original, with no patch on it).
2. Pick the version: **Hookshot v2.1.0 (tested)**, the default and recommended, or "The latest (at your own risk)": not tested with the patch and may not work.
3. Press "Build and install" and choose where it goes. It needs 45 GB free or more (more on exFAT drives) and about 40 minutes.
4. The installer downloads Hookshot from GitHub, checks every file, builds the game on your PC, then adds the patch and copies your newest save.
5. The game is in a `Zelda OoT (Hookshot)` folder inside the place you chose: start `hookshot.exe` from it. The first start is a bit slower.

**If the v2.1.0 files are ever removed from GitHub:** an identical backup is kept, [`Hookshot-v2.1.0-BuilderParts.zip`](https://drive.google.com/file/d/1ivPgod2dfPcUVpbr72JRijWfKHK6E7Sl/view?usp=sharing) (with Hookshot's source code and its GPL licence). The installer downloads it by itself when the files are missing; you can also download it and put it, unextracted, next to the installer or in Downloads, or choose it in the installer. Every file inside is checked before use.

The build runs on your PC, so your antivirus checks the files. If it removes a build tool (such as `clang.exe`), the installer stops and tells you: restore it from quarantine and try again.

#### 4) NX2navi (you already built NX2navi)

1. Pick "NX2navi", then "Choose NX2navi folder": the folder with `ocarina.exe` and a `romfs` folder.
2. Pick a font, press "Install", then start the game.
3. The patch goes into `mods\Arabic (iOsamai)` inside the game folder, and the game files stay as they are. The installer reads the original game files from NX2navi itself, so no `.nup` is needed.
4. The patch is tested on NX2navi **0.9.0**. On another version the installer tells you and lets you install at your own risk.
5. Pick PlayStation or Xbox buttons in NX2navi's own settings (Controls).

#### 5) Build NX2navi (no NX2navi yet)

1. Pick "Build NX2navi", then "Choose game file" and select your `.nup` (version 1.1.1, original, with no patch on it).
2. Pick the version: **NX2navi 0.9.0 (tested)**, the default, or "The latest (at your own risk)".
3. Press "Build and install" and choose where it goes: **an NTFS drive** with 40 GB free (USB drives with exFAT make the build very slow).
4. The installer downloads NX2navi from its GitHub page, checks its files, builds the game on your PC (30 to 40 minutes), then adds the patch and copies your newest save.
5. The game is in a `Zelda OoT (NX2navi)` folder: start `ocarina.exe` from it.

In Hookshot and NX2navi lines stay centred; the alignment options are for emulators only.

### Move your save

- In Hookshot and NX2navi, step 3 "Move my save" copies your save from Fritchii, Lichii or Eden, or from one port to the other (NX2navi to Hookshot or back). The installer finds the save, or you choose the folder.
- The old save is not deleted: Hookshot keeps a copy in `user\save-backups`, and NX2navi keeps one by itself.
- Save not found? Press "Where is my save?": the easiest way is to right-click the game in the emulator, then Open Save Data Location, and choose the folder that opens.
- **From the 1.1.1 file to the 2.0.0 file:** both are the same game and the same save. In an emulator the save lives in the emulator, not in the game file, so changing the file keeps it: install the patch on the new file and carry on.
- Close the game and the emulator before moving a save.

#### Mod files (Mac and any port or emulator)

Download [`ZeldaOoT-Arabic-3.0.0-Mod-Files.zip`](https://github.com/OSAMAxALHARBI/ZeldaOcarinaOfTimeRemake-Arabic/releases/latest/download/ZeldaOoT-Arabic-3.0.0-Mod-Files.zip) from [Releases](../../releases/latest) and extract it. It holds an `Arabic (iOsamai)` folder (`romfs` and `exefs`) with the El Messiri font and every line centred. Copy it into the mods folder of what you play with:
- **An emulator on Mac** (Eglantine or Lichii, Apple Silicon M1 or newer) **or any other emulator:** the game's mod folder (title `0400486024DEC000`), the way that emulator adds mods.
- **Another PC port:** the `mods` folder next to the game's exe. (For Hookshot and NX2navi use the installer: easier and tested.)

Your game must be version 1.1.1, in English. This route is **not tested by the author** on every device and port. If you try it, tell me on the contact page at iosamai.com.

The program opens in Arabic; the English button at the top switches it to English.

### Extra mods

Step 4, "Extra mods", holds mods tested with the patch: each has pictures and a short text, some a video, and one switch; then press Apply. They go into the emulator's mod folder exactly as their authors made them, and you can turn them off any time on the same page.

| Mod | What it does | Author | Licence |
|---|---|---|---|
| [Always-On Rupee Counter](https://gamebanana.com/mods/737829) | the Rupee counter always on screen (current & max, or current only) | PixelSage | CC BY-NC-ND 4.0 |
| [HUD of Time](https://gamebanana.com/mods/738051) | the world clock on screen (12 or 24 hour) | PixelSage | CC BY-NC-ND 4.0 |
| [Auto Jump](https://gamebanana.com/mods/739034) | Link jumps off ledges by himself, like in 1998 | HanSoloBlaster, afiaka87 | MIT |
| [Fast Travel](https://gamebanana.com/mods/737882) | a warp menu on L3 + R3 (visited places or all places) with pictures | HanSoloBlaster | MIT |
| [Movement Speed Increase](https://gamebanana.com/mods/739234) | sprint 1.5x faster | Zerossa | MIT |
| [Hero Mode](https://gamebanana.com/mods/738612) | double damage, no dropped hearts | p3k07 | CC BY-NC-ND 4.0 |
| [Button prompts](https://github.com/exgde/oot-switch2-button-prompts) | PlayStation, Xbox or Steam Deck buttons, Arabic logo kept | exgde | downloaded from the author's page |

- All are for emulators only, except Hero Mode, which also works in Hookshot and NX2navi. The others change the game's code, which the ports do not take. (Hookshot and NX2navi show your pad's buttons by themselves.)
- All are off at first. If the installer finds mods already installed in your emulator, it tells you and shows them on; you can turn them off.
- Every mod is inside the program, except the PlayStation, Xbox and Steam Deck buttons: they download from their author's page when you pick them (about 67 MB).
- A mod you already installed yourself shows as "installed by you" and is left alone.
- Fast Travel with all places: back up your save first.

### The translation in 3.0.0

Every line of the game was reviewed a third time and 153 lines were corrected: characters' gender (the Gerudo women, the cow Li'l Miss Moo, Malon's friend Epona) and a few lines whose meaning was reversed. Names are now the same across the whole game, such as rock roast, the eyes of truth, the Goron Mask and ZELDA NOTES.

### The translation in 2.0

All 16,228 lines of the game were reviewed again from start to end, and hundreds of lines were corrected for meaning and terms. Prices now read «X روبية» for any number. Names such as Din, Sheik and Sharp are coloured so they read as names, and letters before coloured words now join. Words that needed a shadda were reworded, and laughs such as «هيهي» are joined.

### Fonts

11 fonts to choose from, each shown on a picture from the game before you install: El Messiri (default), Fustat, Mirza,
Katibeh, Rubik, Vazirmatn, Lalezar, Alexandria, Alan Sans, Marhey, Playpen Sans.

Use one font for the whole game, or a different font for each part: dialogue and text, small labels, menus and headings,
big titles.

To change the font after installing: open the program, pick the same file, choose the font, then "Apply font only".

#### Add your own font

On the font screen press "+ Add your font" and pick a `.ttf` or `.otf` file with Arabic letters. You can add up to 7
fonts and give them to any of the four parts; the program remembers them next time.

- Only the fonts in the list are tested. Some letters of your font may come out small or missing; if you do not like it,
  go back to the default font.
- If the font is in `C:\Windows\Fonts`, copy it to another folder first and pick it from there.
- Use your font on your own copy only; its licence is your responsibility.

### Uninstall

Open the program, pick the same route and the same file (or folder), and in step 5, "Install", press "Remove the patch" and confirm:
- Game file: the original file comes back exactly as it was.
- Hookshot and NX2navi: the `mods\Arabic (iOsamai)` folder is deleted (in Hookshot the English files also come back if they came from 2.0).
- Mod files: delete the `Arabic (iOsamai)` folder from the mods folder.
- Extra mods: on the Extra mods page, turn the mod off, then press Apply.

### Known issues

- The emulator can freeze now and then. Save often. This is an emulator issue, not the translation.
- On some lines the dialogue box can come up empty or with stray patterns: an emulator issue that happens in the English game with no mods too. The conversation log (Y) shows the text correctly.
- Rarely, a loading screen comes up overexposed or tinted: restart the game. A known emulator issue.

### Credits

Translation: **iOsamai**. Please do not re-upload these files anywhere else; share a link to this page instead.

Fonts, all under the SIL Open Font License 1.1 (files in `licenses/`): El Messiri, Fustat, Mirza, Katibeh, Rubik,
Vazirmatn, Lalezar, Alexandria, Alan Sans, Marhey, Playpen Sans Arabic; Kufam for the logo line (an image; the font
file itself is not included).

The installer uses HarfBuzz (Old MIT), HarfBuzzSharp (MIT), ZstdSharp (MIT), zstd (BSD) and Microsoft WebView2 (BSD); the
MIT notices of the bundled Auto Jump, Fast Travel and Movement Speed mods are there too. All notices are in
`licenses/`.

All my translations: https://iosamai.com
