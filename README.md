# المحفظة الصيدلانية العملية: 40 مشروعًا لبناء مسار مهني ودعم السيرة الذاتية

> دليل لبناء مشاريع صيدلانية قابلة للنشر باستخدام البيانات المفتوحة ووكلاء الذكاء الاصطناعي

دليل لحديثي التخرج في الصيدلة، وللصيادلة الذين يريدون إثبات كفاءتهم عند التقدم لوظيفة أو داخل جهة عملهم، ولتقوية مهارات العمل باستخدام وكلاء الذكاء الاصطناعي.

لا يفترض الدليل معرفة مسبقة بالبرمجة. كل ما يحتاجه المتدرب والراغب في التجربة هو فهم مشكلة مهنية أو مهمة في مجال معين، وقيادة وكيل ذكاء اصطناعي للمساعدة في تبني الحل وأداء المهمة، والقدرة على شرح النتائج.

الجزء الأول من الدليل بالعربية ويشرح الفكرة والمصطلحات وطريقة العمل. الجزء الثاني يحوي «العقد العام» وأربعين برومبت مشروع بالإنجليزية، تُعطى مباشرة إلى أداة الذكاء الاصطناعي. في كل مشروع: شرح عربي مبسط قبل نص «البرومبت» الإنجليزي.

تاريخ التحقق من المصادر: 3 سبتمبر 2026. كل مصدر بيانات مذكور في هذا الدليل جُرّب فعليًا في ذلك التاريخ: فُتح الرابط، ونُزّل الملف أو استُدعيت الواجهة، وفُحصت الحقول. لا يوجد مشروع مبني على افتراض أن البيانات «موجودة على الأرجح».

**ملاحظة:** كل «البرومبتات» في هذا الدليل أمثلة وسيناريوهات افتراضية، وليست وصفات نهائية. عدّلها وحسّنها بحسب النتائج التي تحصل عليها، وبحسب حاجتك وتخصصك.

---

# الجزء الأول: الفكرة بلغة بسيطة

## 1. لماذا المشروع، لدعم السيرة المهنية؟

بنية الأعمال تتغير سريعًا مع دخول الذكاء الاصطناعي، ويتغير معها ما يُقنع الجهات الراغبة بالتوظيف.

وُضع هذا الدليل لمساعدة الراغبين في تدعيم السيرة المهنية ببعض المشاريع، وليكون نقطة بداية لمن يريد تحسين قدرته على التعامل مع وكلاء الذكاء الاصطناعي لإنجاز المهام.

## 2. ما الذي يتم بناؤه بشكل محدد؟

كل مشروع في هذا الدليل هو بناء أداة تعمل على بيانات عامة رسمية (قوائم الأدوية المسجلة، بلاغات الأعراض الجانبية، سجلات التجارب السريرية)، تجيب عن سؤال مهني واحد محدد، وتعرض الإجابة بوضوح.

مثال: بدل عبارة عامة في سيرتك عن «التعامل مع نقص الأدوية»، تشير إلى أداة تثبت ذلك: تجمع قوائم النقص المنشورة رسميًا في أمريكا وأوروبا والسعودية، وتُظهر أي المواد الفعالة تتكرر في أكثر من قائمة، وتحدّث نفسها أسبوعيًا.

## 3. المصطلحات

كل مصطلح أدناه مكتوب بالإنجليزية في سطر مستقل، ثم شرحه بالعربية.

**GitHub**<br>
موقع يُحفظ فيه الكود والملفات مع تاريخ كامل لكل تغيير. المستودع (`repository`) هو مجلد المشروع على هذا الموقع. يستطيع مدير التوظيف فتحه وقراءة كل شيء، ولذلك يُعد الدليل الأساسي على عملك.

**Vercel**<br>
خدمة تنشر واجهة المشروع على الإنترنت برابط عام يستطيع أي شخص فتحه وتجربته دون تثبيت شيء. تُستخدم للمشاريع التي لها واجهة تفاعلية.

**GitHub Pages**<br>
خدمة داخل GitHub لنشر صفحات وتقارير ثابتة. تناسب المشاريع الإحصائية التي يكون ناتجها تقريرًا لا تطبيقًا تفاعليًا.

**AI coding agent**<br>
أداة ذكاء اصطناعي تكتب الكود وتشغّله وتختبره وتصلح أخطاءه داخل مجلد المشروع، مثل Claude Code وCodex وGemini CLI. أنت تعطيها التعليمات وتراجع النتيجة، وهي تنفذ.

**Prompt**<br>
نص التعليمات الذي تعطيه للوكيل. في هذا الدليل، البرومبت الكامل لأي مشروع هو «العقد العام» مضافًا إليه «برومبت المشروع». تنسخ النصين معًا وتعطيهما للوكيل.

**Data source**<br>
الجهة الرسمية التي تأتي منها البيانات، مثل هيئة الغذاء والدواء أو منظمة الصحة العالمية. كل مشروع هنا يعتمد على مصدر جرى اختباره فعليًا.

**API**<br>
واجهة إلكترونية تتيح للبرنامج الحصول على البيانات مباشرة بدل تنزيل ملف يدويًا. بعض الجهات توفر واجهة API، وبعضها يوفر ملفات قابلة للتنزيل فقط.

**Snapshot**<br>
نسخة من البيانات مؤرخة بتاريخ أخذها. تتغير البيانات الحكومية، لذلك يوضح المشروع الجيد دائمًا تاريخ النسخة التي بُنيت عليها نتائجه.

**Checksum**<br>
بصمة رقمية للملف تساعد على إثبات ما إذا كان قد تغير. يسجلها المشروع لتحديد نسخة الملف التي استُخدمت في التحليل.

**Source doctor**<br>
أمر داخل المشروع يفحص آليًا ما إذا كان رابط المصدر يعمل، والملف بالشكل المتوقع، والأعمدة المطلوبة موجودة. إذا تغير شيء، يتوقف المشروع برسالة واضحة بدل إنتاج أرقام خاطئة بصمت.

**Fixture**<br>
عينة صغيرة وثابتة من البيانات، مثل 50 صفًا، تُحفظ داخل المشروع لتشغيل الاختبارات دون إنترنت ودون رفع الملف الحكومي الكامل.

**Synthetic data**<br>
بيانات مصطنعة تشبه البيانات الحقيقية في بنيتها، لكنها لا تخص أشخاصًا حقيقيين. تُستخدم عندما يحتاج المشروع إلى مرضى أو مطالبات أو مخزون، ويجب وسمها بوضوح بأنها مصطنعة.

**Tests**<br>
فحوصات آلية تتأكد من صحة الحسابات ومن توقف المشروع بوضوح عند تغير البيانات. وجودها من أهم أدلة جدية المشروع.

**Review queue**<br>
قائمة بالحالات التي لم تستطع الأداة حسمها آليًا، فتركتها لمراجعة الإنسان. الأداة الصادقة لا تدّعي أنها حسمت كل الحالات.

**Gold set**<br>
عينة صغيرة يراجعها إنسان بعناية وتُستخدم لقياس دقة الأداة. بدل قول «الأداة دقيقة»، يمكن إظهار عدد الحالات الصحيحة من إجمالي الحالات المراجعة يدويًا.

**README**<br>
أول ملف يقرؤه زائر المستودع. يشرح المشروع ومصدر البيانات والمنهج والقيود وطريقة التشغيل.

## 4. تقسيم العمل بينك وبين الوكيل

| أنت (الصيدلي) | الوكيل (الذكاء الاصطناعي) |
|---|---|
| تحدد السؤال المهني ووحدة التحليل | يقترح البنية ويكتب الكود |
| تقرر معنى الحقول وحدود ما يجوز ادعاؤه | يفحص البيانات ويكتب الاختبارات |
| تراجع عينة النتائج يدويًا وتسجل الأخطاء | يبني الواجهة وقوائم المراجعة |
| تختار المقاييس المقبولة مهنيًا | ينفذ الحسابات ويقارنها بالاختبارات |
| تتحمل مسؤولية ما تكتبه في سيرتك | يوثق الأوامر والنتائج ويقترح صياغات |

### مصادر فشل الاستخدام السطحي لوكيل الذكاء الاصطناعي

حين يبدأ بالواجهة قبل فتح المصدر، أو يخترع عمودًا لأن وجوده يبدو منطقيًا، أو يحسب مؤشر بلاغات ويسميه «احتمال حدوث العرض»، أو يجمع سعرين لعبوتين مختلفتين في عدد الأقراص مثلًا ويسمي الفرق توفيرًا، أو يملأ الفراغات بصفر كي يبدو الشكل البياني أجمل.

«العقد العام» في الجزء الثاني يمنع هذه الأخطاء صراحة.

## 5. كيف تستخدم هذا الدليل خطوة بخطوة؟

1. اختر مشروعًا من الجدول في القسم 6. إن كنت لا تكتب كودًا، ابدأ بمشروع موسوم ✓ ومن الفئة الزمنية
S.
2. اقرأ الشرح العربي للمشروع وتأكد أنك تفهم السؤال الذي يجيب عنه، وما الذي لا يدّعيه.
3. افتح رابط المصدر بنفسك مرة واحدة وتأكد أنه يعمل اليوم. إن لم يعمل، لا تبدأ.
4. أنشئ مجلدًا فارغًا على جهازك، وشغّل الوكيل داخله.
5. انسخ «العقد العام» كاملًا، ثم انسخ تحته برومبت المشروع، وأعطهما للوكيل كرسالة واحدة. إن كنت غير مبرمج، أضف في أول سطر:
Project owner is not a programmer.
6. أول ما يجب أن يسلّمه الوكيل: تقرير فحص المصدر
(source audit)
وعينة بيانات صغيرة واختبار واحد. لا تسمح له ببناء الواجهة قبل ذلك.
7. راجع النتائج على مراحل: هل الأرقام منطقية؟ افتح خمس حالات يدويًا وقارنها بالمصدر.
8. اطلب من الوكيل أن يمتحنك بعشرة أسئلة عن المشروع، وأجب بنفسك. إن لم تستطع، فالمشروع ليس جاهزًا للعرض بعد.
9. انشر المستودع على
GitHub
وإن كان له واجهة فانشرها على
Vercel.
10. اكتب في سيرتك سطرًا واحدًا عن المشروع بأرقام حقيقية من التشغيل (انظر القسم 9).

## 6. جدول المشاريع الأربعين

**النطاق:** سعودي / خليجي / عالمي.
**المدة** بدوام جزئي (10–15 ساعة أسبوعيًا):
S
= 2–3 أسابيع،
M
= 3–5 أسابيع،
L
= 5–8 أسابيع.
**غير مبرمج:** ✓ يمكن لصيدلي لا يكتب كودًا أن يقود المشروع ويمتلكه؛ ◐ ممكن مع مراجع تقني؛ ✗ يحتاج قدرة برمجية أو إحصائية ذاتية.

| # | المشروع | النطاق | المجال | المدة | غير مبرمج |
|---:|---|---|---|---|---|
| 1 | مستكشف جودة سجل الأدوية السعودي | سعودي | تنظيمي / بيانات | M | ✓ |
| 2 | مستكشف تطبيق دليل ضمان للأدوية | سعودي | تأمين / ترميز / معلوماتية | L | ◐ |
| 3 | مطابقة سجلات الأدوية السعودية الموحدة | سعودي | تكامل / إمداد | L | ◐ |
| 4 | مراقب تغيرات كتالوج الشراء الموحد | سعودي | سلسلة إمداد | M | ✓ |
| 5 | رادار المنافسات العامة للشراء الموحد | سعودي | مشتريات | L | ✗ |
| 6 | محاكي أثر النقص والتعاميم | سعودي | سلامة / إمداد | L | ◐ |
| 7 | مختبر مطابقة مطالبات التأمين الإلكترونية | سعودي | تأمين / معلوماتية | L | ✗ |
| 8 | بطاقة جودة بيانات الحد الأدنى للتأمين | سعودي | تأمين / جودة بيانات | M | ◐ |
| 9 | مختبر جاهزية ملف اقتصاديات الدواء للهيئة | سعودي | وصول سوق / اقتصاد صحي / تنظيمي | L | ◐ |
| 10 | خريطة التجارب السريرية في الخليج والإقليم | إقليمي | أبحاث سريرية | M | ✓ |
| 11 | مؤشرات المضادات الحيوية الإقليمية | إقليمي | صحة عامة | M | ◐ |
| 12 | مستكشف موافقات الأدوية الأمريكية | عالمي | تنظيمي | M | ✓ |
| 13 | مختبر المنافسة والحصرية للأدوية الجنيسة | عالمي | جنيس / ملكية فكرية | L | ◐ |
| 14 | خريطة البدائل الحيوية | عالمي | بيولوجيات | M | ✓ |
| 15 | مقارن نسخ نشرات الأدوية | عالمي | معلومات دوائية | L | ✗ |
| 16 | مختبر فرز إشارات السلامة الدوائية | عالمي | يقظة دوائية | L | ✗ |
| 17 | مراقب التغيرات التنظيمية والنقص الأوروبي | أوروبي | تنظيمي / نقص | M | ◐ |
| 18 | محلل موضوعات خطابات التحذير الصناعية | عالمي | جودة / تصنيع | L | ◐ |
| 19 | تدقيق توقيت نشر نتائج التجارب | عالمي | أبحاث / نزاهة | M | ◐ |
| 20 | مختبر أهلية التجارب على بيانات مصطنعة | عالمي | أبحاث | L | ✗ |
| 21 | رابط التجارب بالمنشورات | عالمي | أدلة | L | ✗ |
| 22 | خط جداول السلامة السريرية المعيارية | عالمي | أبحاث سريرية / برمجة | L | ✗ |
| 23 | مواءمة الأدوية على بيانات مصطنعة | عالمي | صيدلة سريرية | M | ◐ |
| 24 | مختبر جودة ربط المصطلحات الطبية | عالمي | ترميز | L | ✗ |
| 25 | مختبر تحويل البيانات إلى نموذج بحثي موحد | عالمي | معلوماتية | L | ✗ |
| 26 | تباين الوصف في برنامج الدواء الأمريكي | أمريكي | تأمين / استخدام دواء | M | ◐ |
| 27 | مقارن تغطية خطط التأمين الأمريكية | أمريكي | تأمين | L | ✗ |
| 28 | مراقب تكلفة اقتناء الأدوية الجنيسة | أمريكي | تسعير | M | ✓ |
| 29 | نموذج فعالية التكلفة الشفاف | عالمي | اقتصاد صحي | L | ✗ |
| 30 | صندوق سيناريوهات الأثر الميزاني السعودي | سعودي | اقتصاد صحي | L | ◐ |
| 31 | قائمة جاهزية ملفات التغييرات | سعودي | تنظيمي | M | ✓ |
| 32 | خريطة ترشيد المضادات الحيوية للسجل السعودي | سعودي / عالمي | ترشيد مضادات | M | ✓ |
| 33 | مراقب تقاطع نقص الأدوية عبر الحدود | سعودي / عالمي | إمداد / نقص | M | ✓ |
| 34 | مستكشف أسباب خطابات الرفض التنظيمي | عالمي | تنظيمي | L | ◐ |
| 35 | مختبر أنماط سحب الأدوية | عالمي | جودة / تصنيع | M | ✓ |
| 36 | مستكشف تغطية إرشادات الصيدلة الجينية | سعودي / عالمي | صيدلة جينية | M | ◐ |
| 37 | خدمة حل هوية الدواء | عالمي | بنية بيانات | M | ✗ |
| 38 | خريطة الأجهزة الطبية المدعومة بالذكاء الاصطناعي | عالمي | أجهزة طبية | S | ✓ |
| 39 | التأهيل المسبق الدولي مقابل السجل السعودي | سعودي / عالمي | صحة عالمية | S | ✓ |
| 40 | مستكشف بنية السوق الدوائي السعودي | سعودي | وصول سوق | M | ◐ |

## 7. كيف تختار؟

لبناء أفضل محفظة يُنصح بثلاثة مشاريع: مشروع أساسي عميق في المسار الذي تستهدفه، ومشروع مجاور يثبت اتساع الفهم، ومشروع ثالث داعم.

| المسار المستهدف | الحزمة المقترحة |
|---|---|
| حديث تخرج يريد أول مشروع دون برمجة | 38 أو 39، ثم 33 أو 32 |
| شؤون تنظيمية محلية | 31 + 40 + 1 |
| شؤون تنظيمية عالمية | 12 + 34 + 15 |
| وصول السوق والتسعير | 3 + 9 + 40 |
| تأمين صحي ومطالبات | 2 + 7 + 8 |
| يقظة دوائية وسلامة | 16 + 6 + 21 |
| سلاسل الإمداد والمشتريات | 4 + 33 + 40 |
| صيدلة سريرية ومستشفيات | 32 + 23 + 36 |
| جودة وتصنيع | 35 + 18 + 34 |
| اقتصاد صحي وتقييم التقنيات | 29 + 30 + 28 |
| أبحاث سريرية وبيانات واقعية | 19 + 22 + 25 |
| أجهزة طبية وصحة رقمية | 38 + 7 + 37 |
| صحة عالمية ومنظمات دولية | 39 + 11 + 10 |

قاعدة الاختيار: قيّم نفسك من 1 إلى 5 في معرفة المجال والإحصاء والبرمجة والوقت والقدرة على الشرح، ثم اختر مشروعًا أعلى بدرجة واحدة فقط. لا تبدأ بمشروع فئة
L
مباشرة قبل الاطلاع على المقام الإحصائي فيه.

## 8. القواعد التي لا يجوز كسرها

هذه القواعد موجودة داخل «العقد العام» بالإنجليزية، وهذا معناها بالعربية:

1. **لا بيانات مرضى حقيقية ولا بيانات منشأة حقيقية.** أي مريض أو مطالبة أو مخزون يجب أن يكون مصطنعًا وموسومًا.
2. **الأداة تحليلية تعليمية، ليست أداة تشخيص أو وصف أو اعتماد تنظيمي.** التحذير يظهر بجوار الرقم لا في أسفل الصفحة.
3. **المطابقة بين اسمين ليست تكافؤًا علاجيًا.** الإشارة في قاعدة بلاغات ليست سببية ولا معدل حدوث. سعر القائمة ليس تكلفة صافية. التسجيل ليس توافرًا.
4. **لا شعارات جهات رسمية ولا اسم يوحي بالاعتماد.** تُذكر الجهة كمصدر بيانات فقط، مع عبارة «مشروع مستقل غير تابع لأي جهة».
5. **الأفراد في البيانات العامة لا يُصنّفون.** أسماء المبلغين والموقّعين وجهات الاتصال تُحذف أو تُعرض تجميعيًا.
6. **الذكاء الاصطناعي لا يدخل في حساب أي رقم معروض.** يجوز للتلخيص بجانب النص الأصلي فقط.
7. **الطلب الآلي إلى المواقع الحكومية مرة واحدة.** بعض المواقع الرسمية تقبل الطلب الأول ثم ترفض المتكرر. الحل: طلب واحد، وحفظ الملف بالبصمة، ومسار تنزيل يدوي موثق. لا محاولة لتجاوز ذلك.
8. **الفراغ يبقى فراغًا.** لا تحويل «غير متاح» إلى صفر.
9. **كل رقم في السيرة الذاتية من التشغيل الفعلي.** لا «حسّنت الكفاءة 40%» بلا قياس.
10. **إذا فشل المصدر يتوقف العمل.** لا استبدال خفي بمصدر غير رسمي، ولا بيانات مخترعة.

## 9. كيفية الاستشهاد به في السيرة الذاتية والعرض في مقابلة؟

صيغة السطر في السيرة: فعل + ما بُني + المصدر والحجم + الطريقة + نتيجة مقاسة. مثال بالإنجليزية لأن أغلب السير الذاتية في القطاع تُكتب بها:

Built a bilingual cross-border shortage overlap monitor over 1,635 FDA and 84 EMA shortage records plus the Saudi anticipated-shortage list, with source-audit checks, schema tests, and a weekly change feed.

ملاحظة: لا تكتب هذا السطر قبل أن تظهر الأرقام الفعلية من تشغيل مشروعك الذي قمت باختياره.

## 10. قائمة الإنهاء قبل النشر

- [ ] المصدر الرسمي يعمل، وتاريخ النسخة وتاريخ آخر فحص ظاهران في الواجهة.
- [ ] شروط استخدام المصدر موثقة، وترخيص الكود منفصل عن شروط البيانات.
- [ ] سؤال المشروع ووحدة التحليل والمقام مكتوبة بوضوح.
- [ ] لا بيانات حقيقية حساسة، ولا مفاتيح سرية في المستودع.
- [ ] كل قيمة مصطنعة موسومة.
- [ ] كل حالة غامضة في قائمة المراجعة لا في النتائج النهائية.
- [ ] لا ادعاء سببية أو فعالية أو تكافؤ.
- [ ] لا شعار جهة، وعبارة «مشروع مستقل» موجودة.
- [ ] لا ترتيب أو درجة على مستوى الأفراد.
- [ ] الاختبارات شُغّلت فعلًا ونتائجها مسجلة بتاريخها.
- [ ] شخص جديد يستطيع تشغيل المشروع من ملف
README
وحده.
- [ ] رابط تجربة عام أو فيديو قصير يعمل.
- [ ] قيد واحد على الأقل مكتوب بصدق.
- [ ] تستطيع شرح المشروع وتعديل جزء منه دون إعادة توليده.

## 11. من الفكرة إلى GitHub في خطوات بسيطة

بعد اختيار أحد المشاريع من هذا الدليل وتنفيذه، يمكنك نشره على GitHub بسهولة حتى يصبح جزءًا من محفظتك المهنية.

### 1. أنشئ حساب GitHub

اذهب إلى GitHub وأنشئ حسابًا مجانيًا. بعد ذلك سيكون لديك رابط شخصي مشابه لـ:

```text
github.com/your-name
```

وهذا هو المكان الذي تحفظ فيه مشاريعك.

### 2. اربط GitHub بأداة البرمجة التي تستخدمها

إذا كنت تستخدم وكيل برمجة مثل:

- Codex
- Claude Code
- Gemini
- أو أي Coding Agent يدعم GitHub

سجّل الدخول إلى GitHub من داخل الأداة، ثم وافق على منحها الصلاحيات المطلوبة للوصول إلى مشاريعك. في معظم الحالات ستظهر لك نافذة مثل:

```text
Connect GitHub
↓
Sign in to GitHub
↓
Authorize
```

بعدها يستطيع الوكيل مساعدتك في إنشاء المستودع ورفع المشروع وتحديثه.

### 3. اطلب من الوكيل تجهيز المشروع

بعد الانتهاء من المشروع، يمكنك ببساطة أن تقول للوكيل:

```text
جهّز هذا المشروع للنشر على GitHub.
أنشئ README واضحًا،
وتأكد من عدم رفع كلمات المرور أو API Keys،
ثم أنشئ Repository للمشروع وارفع الملفات إليه.
```

أو:

```text
Publish this project to my GitHub account
and prepare it as a professional portfolio project.
```

### 4. راجع المشروع قبل النشر

قبل الموافقة على الرفع، تأكد خصوصًا من عدم وجود:

```text
API Keys
Passwords
.env files
Private data
Patient data
```

ثم اسمح للوكيل بإكمال عملية النشر.

### 5. احصل على رابط مشروعك

بعد النشر سيصبح لديك رابط مثل:

```text
github.com/your-name/project-name
```

يمكنك بعدها مشاركته في:

- LinkedIn
- السيرة الذاتية
- ملف GitHub الشخصي

وبذلك تصبح العملية:

```text
اختر فكرة من الدليل
        ↓
نفذها مع Coding Agent
        ↓
اربط الوكيل بـ GitHub
        ↓
اطلب منه نشر المشروع
        ↓
راجع الملفات
        ↓
GitHub Portfolio
```

**ملاحظة:** تختلف طريقة ربط GitHub قليلًا من أداة إلى أخرى، لكن المبدأ واحد: تسجيل الدخول إلى GitHub، منح الأداة الصلاحية المناسبة، ثم السماح لها بإنشاء أو تحديث مستودع المشروع.

## 12. نشر المشروع على Vercel بسهولة

إذا كان مشروعك يحتوي على واجهة ويب أو تطبيق يمكن تشغيله عبر المتصفح، يمكنك نشره على Vercel للحصول على رابط مباشر يفتحه أي شخص.

### 1. أنشئ حساب Vercel

أنشئ حسابًا في Vercel، ويفضّل تسجيل الدخول باستخدام حساب GitHub نفسه. بعدها اربط Vercel بحساب GitHub وامنحه صلاحية الوصول إلى المستودعات التي تريد نشرها. الفكرة ببساطة:

```text
GitHub
   ↓
Vercel
   ↓
رابط مباشر للتطبيق
```

### 2. ارفع المشروع إلى GitHub

بعد أن يصبح المشروع موجودًا في مستودع GitHub، يمكنك استيراده مباشرة إلى Vercel. الخطوات عادة:

```text
Add New Project
↓
Import Git Repository
↓
اختر المشروع
↓
Deploy
```

وفي كثير من المشاريع يستطيع Vercel اكتشاف إعدادات التشغيل تلقائيًا.

### 3. استخدم وكيل البرمجة للمساعدة

إذا كنت تستخدم Codex أو Claude Code أو وكيلًا برمجيًا مشابهًا، يمكنك أن تطلب منه:

```text
Prepare this project for deployment on Vercel.
Check the build configuration,
fix any deployment issues,
make sure secrets are handled correctly,
and deploy the application.
```

أو ببساطة:

```text
Deploy this project to Vercel
and give me the public URL.
```

إذا كانت الأداة مرتبطة بحساب Vercel أو تملك صلاحية النشر، فيمكنها تنفيذ معظم الخطوات نيابة عنك.

### 4. أضف المتغيرات السرية داخل Vercel

إذا كان المشروع يستخدم:

- API Keys
- Database URLs
- Supabase Keys
- OpenAI Keys

فلا تضعها داخل الكود، بل أضفها داخل إعدادات المشروع في Vercel ضمن:

```text
Environment Variables
```

### 5. احصل على رابط المشروع

بعد نجاح النشر سيمنحك Vercel رابطًا مثل:

```text
https://your-project.vercel.app
```

يمكنك وضع هذا الرابط بجانب رابط GitHub في محفظتك:

```text
GitHub Repository
      +
Live Demo
```

فتصبح رحلة المشروع:

```text
اختر فكرة
   ↓
نفذ المشروع مع الوكيل
   ↓
ارفعه إلى GitHub
   ↓
اربط GitHub بـ Vercel
   ↓
Deploy
   ↓
رابط مباشر للتطبيق
```

وبذلك يصبح لديك GitHub لعرض الكود والمشروع، وVercel لعرض التطبيق بشكل حي يمكن تجربته مباشرة.

---

# الجزء الثاني: العقد العام وبرومبتات المشاريع (بالإنجليزية)

## كيف تُركّب البرومبت الكامل؟

البرومبت الذي تعطيه للوكيل قطعتان تُلصقان في رسالة واحدة:

1. **العقد العام:** النص الطويل الذي يلي هذه الفقرة مباشرة. هو نفسه في كل المشاريع، وينسخ كاملًا دون حذف.
2. **برومبت المشروع:** الصندوق الإنجليزي الخاص بالمشروع الذي اخترته من القائمة.

الترتيب: العقد أولًا، ثم البرومبت تحته، ثم أرسل الرسالة.

مثال: اخترت المشروع 38؟ الرسالة = نص العقد العام، يليه نص صندوق
PROJECT 38.

ولا تحذف من البرومبت قسمَي
METHOD AND LIMITS
و
ACCEPTANCE TESTS.

## The Master Contract (copy this first, in full)

```text
You are a coding agent and data researcher responsible for building an auditable, publishable professional portfolio project. Implement the project specification that follows this contract inside a standalone repository. If the contract and the specification conflict, the contract wins. If the project owner asks for a "stronger claim" than the data supports, the contract wins and the disagreement is documented in docs/decisions.md.

1) PROOF GATE BEFORE ANY CODE
- Open every official source named in the specification and test it with ONE small request or ONE real download.
- Record in docs/source-audit.md: final URL, publishing body, UTC timestamp, HTTP status, Content-Type, size, SHA-256 of files, sheet/table names, actual field names, access terms, the data date as stated by the source, and "last successful verification" date.
- Create a command such as `make source-doctor` (or `npm run source:doctor`) that re-runs these non-destructive checks and prints a report. It must pass offline using a stored fixture, and it must fail clearly online if the schema changed.
- If a source is unreachable or its schema differs, STOP with a precise message. Never invent columns or data, and never silently substitute an unofficial source.
- Government firewalls: some official sites (including sfda.gov.sa) accept the first request and then reject repeated automated requests or drop connections. Therefore: one request per file per run, mandatory caching keyed by checksum, at most two retries with increasing delay, an honest User-Agent naming the project, and a documented MANUAL DOWNLOAD path (the user places the file in data/raw/ and source-doctor records its checksum, date, and origin). Never attempt to bypass a firewall.
- Periodic re-verification: run source-doctor on day one, before every release, and monthly via GitHub Actions. On failure, open an issue automatically and do NOT refresh demo data. Show "Last successful source verification: <date>" in the UI.

2) DOMAIN UNDERSTANDING BEFORE DESIGN
- Read the methodological references in the specification and summarize in docs/methodology.md: the project question, unit of analysis, denominator, variables, assumptions, sources of bias, and what the project cannot prove, with direct links.
- Keep regulatory/observational data separate from clinical inference.
- Never describe a code mapping as a deterministic translation, a spontaneous report as causality, a list price as net cost, a trial registration as proof of efficacy, a registration as availability, or absence from a public database as compliance or non-existence.
- Every displayed metric has a "How was this computed?" card stating numerator, denominator, exclusions, and data version.

3) SMALL, COMPLETABLE ARCHITECTURE
- Choose the simplest architecture that meets the goal within the duration class in the catalog (S: 2–3 weeks, M: 3–5, L: 5–8). Default: reproducible pipeline + DuckDB/Parquet + TypeScript/Next.js UI on Vercel. For statistical or R/Quarto projects, GitHub + GitHub Pages is the primary path.
- Separate data/raw/ (not committed if large or restricted), data/staging/, data/curated/, public/demo/. Commit a small fixture, its checksum, and the fetch script.
- Pin versions (lockfiles), provide .env.example with no secrets, and do not require an API key if the source works without one.
- Build source adapters, typed models, schema contracts, and a lineage record from raw field to displayed field.
- Money as decimal (never float); dates with explicit time zones; identifiers as strings that preserve leading zeros.

4) PRIVACY AND SAFETY
- Never use real patient, claims, or facility inventory data. Any patient, claim, stock, or uptake value must be synthetic and labeled as such in data, UI, and docs with a fixed tag and color.
- People in public data: official datasets sometimes contain individuals (reporters, letter signatories, prescribers, contact persons). Never build rankings, scores, or classifications at the individual level; never display contact details; aggregate or drop these fields in curated data. Companies and institutions appear as in the source, without a composite "reputation" score.
- The project is analytical/educational, not a diagnostic, prescribing, regulatory-approval, or live adjudication tool. Place the domain-specific warning on the relevant screen next to the number or table, not only in a footer. The warning is covered by an E2E test.
- Branding and affiliation: do not use logos, distinctive colors, or names of any authority (SFDA, CHI, NUPCO, NPHIES, FDA, EMA, WHO, or others) in a way that implies ownership or endorsement. Name the authority only as a data source. State in README and UI: "Independent project, not affiliated with or endorsed by any official body; data from public sources as of the snapshot date."
- LLMs inside the product: no LLM in any computation or classification that produces a displayed number or judgment. Allowed only for summarizing text shown next to the original with citations, or as an optional, switchable path beside a deterministic one. Record model name, version, and prompt in docs/methodology.md; keep a documented human review sample; never send text containing personal names or contact details to an external model.

5) MINIMUM SECURITY
- No secrets in the repository or git history; automated check in CI.
- Any published endpoint serves static curated data only; no open proxy to the government source; no source call per user request. Rate limit and cache any public project API.
- Dependency audit (npm audit / pip-audit) before release; pin GitHub Actions to specific versions.
- No server-side file upload in the published version; user-provided files are processed client-side only.

6) REQUIRED USER EXPERIENCE
- A landing page that explains the question, source, data date, and last verification in under 30 seconds.
- Filters, search, sortable table, detail page, data-quality/completeness panel, and a "How was this computed?" section for each metric.
- Show missing, not-applicable, and suppressed values as they are; never convert them to zero.
- Provide CSV download of the filtered result and a stable URL for the state if safe.
- For Saudi or Gulf projects: Arabic/English UI with correct RTL, keyboard accessibility, and good mobile performance. Regulatory terms appear in English as in the source with an Arabic explanation; never machine-translate the term itself.

7) TESTS AND ASSURANCE
- Unit tests for transformations, metrics, and edge cases.
- Schema/data-contract tests for fields, types, uniqueness, allowed values, and dates.
- Small golden fixtures for reproducibility.
- Integration test for ingest→curate→query and an E2E test for the main user path and for the presence of the domain warning.
- Negative-claim tests: the UI must not show causality or incidence from a reporting database; must not accept an ambiguous mapping without a review state; must not mix synthetic with observed; must not show individual-level rankings; must not show any authority logo.
- Run lint/typecheck/build/tests and link checks. Record actual results (command, counts, date) in docs/verification.md. Never write "passed" without running.

8) REPOSITORY OUTPUTS
- Clear Arabic README with an English summary, a short demo image/video, an architecture diagram, how to run, data source, data dictionary, methodology, limitations, tests, and roadmap.
- LICENSE for code and NOTICE for data sources, following the fixture matrix:
  • Source with an explicit open license (CC0/CC-BY/Apache): a quoted fixture with attribution is allowed.
  • Public source with no stated license (many regional government files): commit fetch script + checksum + a fixture of at most 50 rows or 1%, whichever is smaller, and say so in NOTICE.
  • Source whose terms forbid redistribution or that contains individuals: no quoted fixture; synthetic fixture with the same schema.
- At least one ADR explaining an important decision, plus CHANGELOG, CONTRIBUTING, and issue templates.
- GitHub Actions for periodic verification and build; a source failure must never silently refresh demo data.
- If Vercel fits, deploy a demo UI with small curated data. Never run heavy ETL inside a serverless request; run it in CI or locally beforehand.

9) PROOF OF PROFESSIONAL OWNERSHIP
- Create docs/portfolio-evidence.md: the problem, the owner's decisions, three data errors discovered, a test that failed and was fixed, an unresolved limitation, and before/after screenshots.
- Propose three CV bullets in the form: verb + what was built + source/size + method + measurable result, with no unmeasured commercial or clinical impact.
- Create docs/interview-demo.md for a 5-minute walkthrough: problem, evidence, demo, technical decision, limitation, next step.
- Create docs/quiz.md with ten questions a hiring manager would ask the owner (why this denominator? what if a column changes? why reject the alternative?) WITHOUT answers; the owner answers them personally.

10) WAY OF WORKING
- Start with a short plan and risk matrix, then build a vertical slice that works from source to one screen before expanding.
- Do not ask about small decisions resolvable from the specification and the source. Stop only if the primary source is unavailable, the scope shifts to real data or a production connection, or a legal or terms-of-use conflict appears.
- If the first line of the specification says "Project owner is not a programmer": explain every architectural decision in two sentences in docs/decisions.md, name tests after the domain behavior they protect, and avoid unnecessary libraries. Never lower verification or claim standards because of this.
- Finish with an honest summary: what is complete, what was tested with commands and results, what is incomplete, and links/paths to outputs.

Now apply this contract to the project specification that follows.
```

---

## Project Prompts

كل برومبت يبدأ بشرح عربي مبسط (الفكرة، ولمن يناسب، وما الذي لا يدّعيه)، ثم نص البرومبت بالإنجليزية داخل صندوق. انسخ محتوى الصندوق بعد العقد العام.

---

### 1 — Saudi Drug Registry Quality Explorer

**الفكرة ببساطة:** قائمة الأدوية البشرية المسجلة في السعودية ملف عام كبير. هذا المشروع يفحص جودة هذا الملف نفسه: أي الحقول ناقصة، أين التكرارات، وكيف تغيرت القائمة بين نسختين. مناسب لمن يستهدف الشؤون التنظيمية أو تحليل البيانات.

```text
PROJECT 1 — Saudi Drug Registry Quality Explorer
Duration class: M. Publish: GitHub + Vercel.

GOAL
Build a bilingual (Arabic/English) explorer of the data quality of the Saudi Human Drug List: completeness of registration, classification, form, route, and price fields; duplicates and contradictions; and what changed between two snapshots.

VERIFIED SOURCES
- CHI "Daman Drug Formulary" page publishing direct Excel files, including the Human Drug List built on SFDA data: https://www.chi.gov.sa/Rules/Pages/DamanDrugFormulary.aspx (tested: Excel downloaded; ICD-10, ATC, scientific name, form, route, strength, registration and price fields inspected).
- SFDA Open Data page as a secondary reference: https://www.sfda.gov.sa/en/open-data (firewall behavior: one request per run; manual download path required).
Do not invent an SFDA API.

METHOD AND LIMITS
- Unit of analysis: one product/registration record.
- Explainable quality rules: missingness, registration-number uniqueness, date validity, strength/unit consistency, form/route normalization, formal ATC validity, scientific/brand name duplication. A difference is not an error until fields and context are checked.
- Ship the quality rules as a reusable package (quality-rules/) that runs on any pharmaceutical export with name/strength/unit/manufacturer columns, plus a deliberately messy synthetic fixture (mixed units, fuzzy duplicates, incomplete rows) with one test per rule.
- Never call the list a "live SFDA database".

DELIVERABLES
Python + DuckDB pipeline; overview page; field dictionary; record explorer; quality dashboard; diff between two snapshots; downloadable exceptions report. Keep file checksum and release date. Do not commit the full file if terms are unclear; commit a 50-row fixture with its share of the total.

ACCEPTANCE TESTS
Detects schema drift; never turns null into zero; shows row counts before/after each transform; ten cases proven by hand; the UI never labels the list as live SFDA data; three CV bullets with real numbers from the run.
```

---

### 2 — CHI Formulary Implementation Navigator

**الفكرة ببساطة:** دليل ضمان للأدوية مرجع رسمي يربط دواعي الاستعمال وأكواد ICD-10-AM بالأسماء العلمية والتصنيف والشكل الصيدلاني وضوابط الوصف والملاحق. يحوّل المشروع هذه العلاقات إلى مستكشف ثنائي اللغة يساعد الصيدلي وشركة التأمين وفريق الأنظمة على فهم الدليل والبحث فيه وتتبع التغييرات بين إصداراته. يفحص المشروع سلامة استيراد الملف إلى التطبيق.

```text
PROJECT 2 — CHI Formulary Implementation Navigator
Duration class: L. Publish: GitHub + Vercel.

GOAL
Build a bilingual, read-only implementation navigator for the officially published CHI Drug Formulary.

The application must preserve and explain the published relationships between:
- Indication
- ICD-10-AM code
- Scientific name
- ATC code
- Pharmaceutical form
- Route
- Strength
- Substitutability
- Prescribing edits
- Referenced appendices

It must support search, filtering, source-row traceability, and descriptive comparison between dated formulary releases.

VERIFIED SOURCE
Official CHI Drug Formulary page:
https://www.chi.gov.sa/Rules/Pages/DamanDrugFormulary.aspx

Use the downloaded CHI Formulary workbook and record:
- Download date
- Published release date
- File name
- File size
- SHA-256 checksum
- Sheet names
- Column names
- Row counts

SOURCE TREATMENT
- Treat every source row as an officially published record for that release.
- Preserve source values without silently correcting, normalizing, or replacing them.
- Limit validation to technical ingestion integrity: file readability, expected schema, row-count reconciliation, data types, exact duplicate preservation, referenced-link reachability, and confirmation that every source row is represented.
- A value the application cannot parse must be labelled "not parsed by this tool", never "invalid".
- A blank field must be displayed as "not provided in this release", not classified as an error.
- Release differences must be described as added, removed, or changed records; they must not be labelled corrections, defects, or regressions.
- Any external terminology descriptions or mappings must be kept in a separate overlay with their source, version, and licensing status.
- Do not assess the clinical, regulatory, or coding correctness of CHI decisions.
- Do not infer coverage, claim approval, medical necessity, or therapeutic suitability.
- State clearly that the navigator is not connected to live NPHIES adjudication.

DELIVERABLES
- Source manifest and checksum report
- Arabic/English searchable formulary explorer
- Filters for indication, ICD-10-AM, scientific name, ATC, form, and route
- Relationship view from indication to published medication records
- Prescribing-edit glossary based only on official CHI documentation
- Appendix and protocol navigator
- Raw-source evidence drawer for every displayed record
- Descriptive comparison between two dated releases
- Exportable implementation test cases for developers and analysts
- Data dictionary distinguishing source fields from derived display fields

ACCEPTANCE TESTS
- Reconcile imported sheet and row counts with the downloaded workbook.
- Demonstrate that every displayed value links back to its original sheet and row.
- Manually verify at least 20 searches against the official workbook.
- Preserve exact source values in the evidence view.
- Test blank fields, repeated rows, unparsed edits, and unreachable appendix links without calling them source errors.
- Show the source release date and checksum on every exported report.
- Do not use "suspicious", "incorrect", "invalid mapping", "coding error", or "anomaly" to characterize official records.
- No coverage recommendation, claim decision, therapeutic recommendation, or live-adjudication claim anywhere in the application.
```

---

### 3 — Saudi Medicine Master Crosswalk

**الفكرة ببساطة:** الجهات السعودية تسمي الدواء نفسه بصيغ مختلفة: قائمة التسجيل قد تحوي صيغة معينة، وكتالوج الشراء الموحد يحوي صيغة أخرى. هذا المشروع يقترح مطابقات بين السجلين بدرجة ثقة، ويترك القرار النهائي للإنسان. مناسب لوصول السوق والإمداد والتكامل.

```text
PROJECT 3 — Saudi Medicine Master Crosswalk
Duration class: L. Publish: GitHub + Vercel.

GOAL
Build a workbench that proposes matches between the SFDA/CHI Human Drug List and the NUPCO pharmaceutical catalogue at the level of ingredient, strength, form, route, and pack, with confidence scores and full human review.

VERIFIED SOURCES
- CHI Human Drug List: https://www.chi.gov.sa/Rules/Pages/DamanDrugFormulary.aspx
- NUPCO Unified Catalogue (pharmaceuticals Excel): https://www.nupco.com/suppliers/unified-catalogue/ (tested July 2026: 4,697 rows, 20 columns including NUPCO Generic Code, Active Ingredient, Concentration, UOM, ATC).

METHOD AND LIMITS
- Canonical model separating ingredient, salt, strength numerator/denominator, dose form, route, pack.
- Exact → normalized rules → fuzzy only as a candidate. Every score has reasons. States: matched, candidate, ambiguous, unmatched, invalid.
- Never claim that a match proves therapeutic or contractual equivalence.

DELIVERABLES
Profiler for both sources; normalization library; side-by-side comparison UI; reviewer decision screen; dated overrides log; metrics on a small hand-made gold set; a crosswalk file containing only accepted decisions.

ACCEPTANCE TESTS
Every match shows original fields; no fuzzy match auto-accepted; tests for multi-ingredient products, units, and packs; precision/recall on a published gold set; source rights documented; raw files not committed without permission.
```

---

### 4 — NUPCO Catalogue Change Monitor

**الفكرة ببساطة:** كتالوج الشراء الموحد يتغير مع كل إصدار: أصناف تُضاف وتُحذف، ورموز تتبدل. هذا المشروع يراقب هذه التغيرات ويعرضها بوضوح على خط زمني. مناسب لسلاسل الإمداد.

```text
PROJECT 4 — NUPCO Catalogue Change Monitor
Duration class: M. Publish: GitHub + Vercel.

GOAL
Build a release monitor for the NUPCO pharmaceutical catalogue that detects added, removed, and changed items, including changes of code, ATC, description, or concentration.

VERIFIED SOURCE
https://www.nupco.com/suppliers/unified-catalogue/ (tested July 2026: 4,697 records, 20 columns, including a code-change indicator).

METHOD AND LIMITS
- Define the composite identity before comparing; treat a code change as a lineage event, not an automatic delete/add.
- Separate formatting changes from meaning changes.
- Store versions as checksums and metadata, not raw copies in Git if large.

DELIVERABLES
Fetch command; schema contract; snapshot manifest; semantic diff; per-code timeline; dashboard by division/ATC; local RSS/JSON change feed; weekly GitHub Action that halts for review on schema drift.

ACCEPTANCE TESTS
Deterministic replay between two fixtures; tests for code change with stable attributes; no claims about stock or price; data time shown; no notification if fetch failed or file is empty.
```

---

### 5 — NUPCO Public Tender Intelligence Radar

**الفكرة ببساطة:** الشراء الموحد ينشر قائمة المنافسات وخطتها ونتائجها علنًا. هذا المشروع يجمع البيانات الوصفية العامة فقط (الرقم، العنوان، الحالة، التواريخ) ويعرضها كتقويم وخط زمني. مناسب للمشتريات.

```text
PROJECT 5 — NUPCO Public Tender Intelligence Radar
Duration class: L. Publish: GitHub + Vercel.

GOAL
Build a radar for public pharmaceutical tenders that tracks new, updated, cancelled, preliminary and final results, and the tender plan, turning them into a searchable timeline and general item analytics.

VERIFIED SOURCES
NUPCO tenders list https://www.nupco.com/tenders/tenders-list/ and tenders plan https://www.nupco.com/tenders/tenders-plan/ plus public tender pages and published item-list links. Never use paid tender documents or a supplier account.

METHOD AND LIMITS
- Collect only public metadata: number, title, status, publish/close/open dates, category, public links. Store HTML snapshot hashes and provenance.
- If a public item file exists, parse it with a separate adapter.
- No prediction of winners, prices, or eligibility.

DELIVERABLES
Polite scraper with caching and rate limits; adapter per page type; calendar; state machine for the tender lifecycle; saved searches; change feed; lead-time and metadata-completeness report; Arabic RTL UI.

ACCEPTANCE TESTS
Respects robots/terms; backoff; DOM-change detection; no login/paywall bypass; each event linked to its snapshot; tests for an available, a cancelled, and a result page; warning that the platform is not a substitute for the official portal or documents.
```

---

### 6 — Saudi Shortage & Recall Impact Simulator

**الفكرة ببساطة:** حين تُنشر قائمة نقص أو تعميم سحب، ماذا يحدث لمخزون افتراضي ومرضى افتراضيين؟ هذا المشروع يحاكي الأثر التشغيلي على بيانات مصطنعة بالكامل. مناسب للسلامة والإمداد في المستشفيات.

```text
PROJECT 6 — Saudi Shortage & Recall Impact Simulator
Duration class: L. Publish: GitHub + Vercel.

GOAL
Build a simulation tool estimating the potential operational impact of Saudi shortage lists and circulars on a fully synthetic patient cohort and inventory. Not a real-shortage prediction tool.

VERIFIED SOURCES
SFDA Anticipated Shortage https://www.sfda.gov.sa/en/anticipatedShortage (public web table; dated snapshot only), SFDA drug circulars https://www.sfda.gov.sa/en/drugs-circulars, the public Human Drug List, and Synthea https://github.com/synthetichealth/synthea for synthetic patients/prescriptions.

METHOD AND LIMITS
- Normalize names/strength/form, then propose matches with review.
- Scenarios on synthetic stock: days of coverage, affected prescriptions, hypothetical substitution lead time, cases with no known alternative.
- Never suggest a therapeutic alternative; never use RSD or facility data.

DELIVERABLES
List snapshotter; match queue; scenario builder; impact dashboard by drug/form/time; sensitivity sliders; a ledger that visibly separates observed source facts from synthetic assumptions.

ACCEPTANCE TESTS
No use of "forecast" without definition; no national stock displayed; every derived number shows its formula; tests prevent mixing observed/synthetic; scenarios reproducible from a seed and config file.
```

---

### 7 — NPHIES FHIR Claims Conformance Lab

**الفكرة ببساطة:** منصة التأمين الإلكترونية السعودية تنشر دليل تطبيق عامًا يحدد شكل المطالبة الإلكترونية. هذا المشروع يبني مختبرًا محليًا يفحص أمثلة مصطنعة من المطالبات ضد هذا الدليل ويشرح الأخطاء بلغة يفهمها الصيدلي. مناسب للتأمين والمعلوماتية الصحية.

```text
PROJECT 7 — NPHIES FHIR Claims Conformance Lab
Duration class: L. Publish: GitHub + Vercel.

GOAL
Build a local lab that validates synthetic claim/insurance transaction fixtures against the public NPHIES Implementation Guide and FHIR profiles/capabilities, explaining errors in language both pharmacists and developers understand.

VERIFIED SOURCES
NPHIES IG https://portal.nphies.sa/ig/, artifacts https://portal.nphies.sa/ig/artifacts.html, Provider CapabilityStatement JSON https://portal.nphies.sa/ig/CapabilityStatement-Provider.json (tested: HTTP 200, JSON). FHIR R4 Claim https://hl7.org/fhir/R4/claim.html as general reference, NPHIES files take priority.

METHOD AND LIMITS
- Separate structural validation, profile/cardinality, terminology/binding, and business hints.
- No adjudication, no claim of NPHIES certification. Synthetic passing and failing fixtures for eligibility/preauthorization/claim as far as the public release covers.

DELIVERABLES
Validator CLI + web viewer of the Bundle/Resource tree; errors linked to JSONPath/FHIRPath; profile comparison; Arabic/English glossary; documented synthetic example pack with source and version.

ACCEPTANCE TESTS
IG version pinned; source doctor for the CapabilityStatement; cardinality/reference/code-binding tests; PHI blocked; report separates error/warning/info; explicit statement that success is technical and educational, not claim acceptance or platform accreditation.
```

---

### 8 — Synthetic CHI Minimum-Data-Set Quality Scorecard

**الفكرة ببساطة:** مجلس الضمان الصحي يحدد الحد الأدنى من البيانات التي يجب أن ترافق كل مطالبة أو زيارة. هذا المشروع يحول هذه المتطلبات إلى قواعد فحص تعمل على بيانات مصطنعة ويعرض أثر الأخطاء على قابلية التحليل. مناسب لجودة البيانات في التأمين.

```text
PROJECT 8 — Synthetic CHI MDS Data Quality Scorecard
Duration class: M. Publish: GitHub + Vercel.

GOAL
Turn minimum-data-set requirements into an executable schema and quality tests over synthetic claims/visits, then show how errors affect analyzability.

VERIFIED SOURCES
MDS requirements from CHI laws and regulations https://www.chi.gov.sa/en/knowledge-center/Pages/laws-regulations.aspx, public NPHIES documents, and Synthea/CPCDS or a local generator for synthetic data.

METHOD AND LIMITS
- Extract fields, definitions, required/optional, allowed values into a human-reviewed data dictionary.
- Dimensions: completeness, validity, uniqueness, consistency, timeliness, referential integrity.
- Do not claim the schema is a complete operational version if the PDF/IG is insufficient.

DELIVERABLES
JSON Schema or Pydantic models; synthetic generator with controlled errors; validation engine; scorecard with drill-down; experimental data-quality SLA; before/after repair report preserving the original.

ACCEPTANCE TESTS
At least 20 documented rules, each linked to a source clause; no PHI; missing ≠ zero; failure data reproducible; sensitivity of the score to weights shown instead of one absolute quality number.
```

---

### 9 — SFDA Pharmacoeconomic Submission Readiness Lab

**الفكرة ببساطة:** يحوّل المشروع دليل الهيئة العامة للغذاء والدواء لتقييم دراسات اقتصاديات الدواء إلى مختبر رقمي لفحص جاهزية ملف اقتصادي تجريبي. يحدد المتطلبات المناسبة حسب نوع المنتج والدراسة، ويكشف العناصر المكتملة والناقصة وما يحتاج إلى تبرير أو مراجعة بشرية. مناسب لمسارات **Market Access وHEOR والشؤون التنظيمية**.

```text
PROJECT 9 — SFDA Pharmacoeconomic Submission Readiness Lab
Duration class: L. Publish: GitHub + Vercel.

GOAL
Build a bilingual, evidence-traceable readiness laboratory that converts the SFDA Economic Evaluation Studies Guidelines into structured validation rules.

The application must assess a synthetic or demonstration pharmacoeconomic dossier and classify each requirement as:
- Complete
- Missing
- Not applicable
- Needs justification
- Human review required

This is an educational completeness and readiness tool. It must never predict, guarantee, or represent SFDA acceptance.

VERIFIED SOURCES
- Official SFDA guideline page: https://www.sfda.gov.sa/en/guide/19004
- Official PDF: https://www.sfda.gov.sa/sites/default/files/2025-10/EconomicEvaluationStudies_1.pdf
- CHEERS 2022: https://www.equator-network.org/reporting-guidelines/cheers/

The SFDA PDF was directly tested on 3 September 2026:
- HTTP status: 200
- Content-Type: application/pdf
- File size: 592,465 bytes
- Pages: 19
- Version: 1.1
- SHA-256: 86163CA5F4F24830B8D833C10F7F05D59431939C08CB10E57B2C8C831C5210DA

The guideline contains:
- General submission requirements
- Economic study requirements by product type
- Full economic evaluation requirements
- Budget impact analysis requirements
- Potential exemption criteria
- General Requirements Form A
- Pharmacoeconomics Submission Form B
- Budget Impact Analysis Submission Form C
- The stated location of the summary within eCTD section 1.8.2

SCOPE
Support the following product categories:
- New chemical product
- Biological product
- Generic chemical product
- Biosimilar

Support the following study types:
- Budget Impact Analysis — BIA
- Cost-Minimization Analysis — CMA
- Cost-Effectiveness Analysis — CEA
- Cost-Utility Analysis — CUA

The tool must distinguish between:
1. General requirements
2. Full economic evaluation requirements
3. Partial economic evaluation and BIA requirements
4. Submission Forms A, B, and C
5. CHEERS reporting items
6. Potential exemption conditions

METHOD
Manually review the official guideline and encode each requirement in a version-controlled YAML or JSON rule registry.

Each rule should contain at least:
- rule_id
- guideline_version
- source_page
- source_section
- product_type
- study_type
- requirement_category
- required_or_conditional
- evidence_expected
- validation_method
- failure_message_ar
- failure_message_en
- review_note
- last_verified_date

Do not merge SFDA requirements with CHEERS requirements. Display them as separate layers:
- SFDA submission readiness
- CHEERS reporting completeness

Do not automatically determine exemption eligibility. The guideline contains interactions between the study-requirement table and the exemption criteria that may require regulatory interpretation. Such cases must be classified as:

“Potential exemption — regulatory review required.”

Do not hard-code the stated cost-effectiveness threshold, discount rate, time horizon, or other numerical guidance as timeless policy. Every numerical rule must remain linked to the guideline version, source page, and verification date.

DELIVERABLES
1. A versioned SFDA requirements registry.
2. A bilingual product-and-study selection wizard.
3. A synthetic dossier manifest uploader.
4. A readiness dashboard.
5. A rule-level traceability viewer.
6. A Forms A/B/C completeness viewer.
7. A separate CHEERS 2022 completeness assessment.
8. A gap report generator.
9. A downloadable CSV/JSON audit trail.
10. A synthetic example dossier containing no confidential company information.
11. A source-doctor command that verifies the guideline URL, file type, size, checksum, version, and required sections.
12. A methodology page explaining what the tool can and cannot conclude.

The dashboard must show:
- Overall completeness by requirement category
- Missing mandatory evidence
- Conditional requirements awaiting a decision
- Items requiring justification
- Items requiring regulatory review
- SFDA requirements and CHEERS items separately
- The exact source page for every result

SYNTHETIC DOSSIER
Create demonstration fixtures for:
- One new chemical product with a CEA/CUA and BIA
- One biological product with incomplete sensitivity analysis
- One generic product with a CMA/BIA scenario
- One biosimilar claiming a potential exemption that requires human review

The fixtures may include synthetic epidemiological estimates, market-share projections, marketing plans, target populations, comparators, perspectives, time horizons, costs, outcomes, discounting, DSA, PSA, scenario analyses, generalizability assessments, conflicts of interest, funding, and international HTA recommendations.

Every synthetic value must be visibly labeled as synthetic in the data, interface, and exported report.

METHOD AND SAFETY LIMITS
- Do not upload or process confidential company dossiers.
- Do not provide regulatory, legal, pricing, or reimbursement advice.
- Do not predict the probability of SFDA approval.
- Do not label a dossier “SFDA compliant.”
- Use “readiness” or “completeness against the encoded guideline version.”
- Do not infer that a completed checklist proves methodological quality.
- Do not treat CHEERS as an SFDA requirement unless the SFDA guideline explicitly references it.
- Do not convert “not applicable” into “missing.”
- Do not resolve ambiguous exemption cases automatically.
- Do not silently update rules when the official guideline changes.

ACCEPTANCE TESTS
- Decision tests for every supported product and study type.
- One complete synthetic fixture and at least three incomplete fixtures.
- Tests distinguishing missing, conditional, not applicable, and needs justification.
- Every encoded rule has a guideline version, page, section, and verification date.
- Manual visual verification of Forms A, B, and C against the official PDF.
- A version and checksum test for the source PDF.
- A schema-drift test for the rule registry.
- A test proving that CHEERS and SFDA scores cannot be merged.
- A test proving that potential exemptions always require human review.
- No confidential documents, real company prices, or personal data in the repository.
- Mobile, RTL, accessibility, build, unit, integration, and E2E tests must pass.
- The interface must display this warning prominently:

“Educational readiness and completeness tool. It is not regulatory advice, an official SFDA submission system, or a guarantee of acceptance.”

PORTFOLIO EVIDENCE
Document:
- How the official PDF was verified
- How each requirement was converted into a rule
- One ambiguous regulatory condition that was intentionally not automated
- One discrepancy detected between a synthetic dossier and the guideline
- One failed test and how it was corrected
- The limitations of checklist-based assessment
- The difference between submission completeness and methodological validity

CV OUTPUT
Generate CV bullets only from measured implementation results, for example:

“Built a bilingual SFDA pharmacoeconomic submission-readiness laboratory encoding X versioned requirements across Forms A/B/C, with page-level traceability, synthetic dossier testing, and separate CHEERS reporting assessment.”

Replace X only after counting the implemented and tested rules.
```

---

### 10 — GCC/EMRO Clinical-Trial Footprint Map

**الفكرة ببساطة:** سجل التجارب السريرية الأمريكي يوفر واجهة عامة تُظهر كل التجارب المسجلة ومواقعها. هذا المشروع يرسم خريطة للتجارب في دول الخليج وشرق المتوسط: عددها وحالتها ومرحلتها ورعاتها، مع صفحة خاصة بالسعودية. مناسب للأبحاث السريرية.

```text
PROJECT 10 — GCC/EMRO Clinical-Trial Footprint Map
Duration class: M. Publish: GitHub + Vercel.

GOAL
Map registered trials in Gulf and Eastern Mediterranean countries: number of studies, status, phase, specialty, results availability, sites, and trend over time, with a mandatory Saudi drill-down.

VERIFIED SOURCE
ClinicalTrials.gov API v2 https://clinicaltrials.gov/data-about-studies/learn-about-api (tested: /api/v2/version and a studies query returned HTTP 200), with a fixed documented country list. Optional contextual indicators from WHO EMRO https://rho.emro.who.int/drs without mixing denominators.

METHOD AND LIMITS
- Define study vs site; never count a study several times in regional comparisons. Separate interventional/observational, recruitment status, phase, sponsor class, results posted. Show missing locations and multi-country studies.
- Saudi drill-down page: cities/institutions as stated in the location field (normalized with review), sponsors by the official sponsor class only, phases, status, results. No ranking of principal investigators; aggregate or drop their names.

DELIVERABLES
Paginated fetcher storing dataTimestamp; curated study/site tables; map and table; trends; sponsor/condition filters; citation-ready download; Saudi drill-down.

ACCEPTANCE TESTS
Reconciliation between study and site counts; time-zone/date tests; no "best country" ranking without denominator and definition; no interpretation of counts as research quality; a link for every NCT.
```

---

### 11 — EMRO AWaRe Antimicrobial Benchmark

**الفكرة ببساطة:** منظمة الصحة العالمية تنشر مؤشرات استهلاك المضادات الحيوية حسب تصنيفها الثلاثي للدول. هذا المشروع يعرض هذه المؤشرات لدول الإقليم مع إبراز الفجوات بدل ملئها. مناسب للصحة العامة وترشيد المضادات.

```text
PROJECT 11 — EMRO AWaRe Antimicrobial Benchmark
Duration class: M. Publish: GitHub + Vercel.

GOAL
Build a regional dashboard exploring antimicrobial consumption indicators by WHO AWaRe category and data coverage across years, highlighting gaps rather than filling them.

VERIFIED SOURCES
WHO GHO OData API https://ghoapi.azureedge.net/api/ (tested: indicator GLASSAMC_AWARE returned), WHO GLASS https://www.who.int/initiatives/glass, and the AWaRe classification page https://www.who.int/teams/surveillance-prevention-control-AMR/control-and-response-strategies/AWaRe.

METHOD AND LIMITS
- Inspect each indicator's definition, unit, source, and years. Never mix consumption with resistance or prescribing appropriateness. Show coverage/missingness; never create a value for a missing country. If a population denominator is used, fix its source and year.

DELIVERABLES
Metadata-first ingestion; map, time trend, and Access/Watch/Reserve composition; completeness matrix; download; "how to read this indicator" in Arabic and English.

ACCEPTANCE TESTS
Unit/denominator checks; proportions sum where expected; flag for non-comparable years; no causal claims; WHO definitions paraphrased briefly, not copied at length; a test that a missing country stays missing.
```

---

### 12 — Drugs@FDA Approval Timeline Explorer

**الفكرة ببساطة:** إدارة الغذاء والدواء الأمريكية تنشر بيانات كل الطلبات والمنتجات والموافقات. هذا المشروع يبني مستكشفًا لتاريخ الموافقات يوضح العلاقة بين الطلب والمنتج والمادة الفعالة. مناسب للشؤون التنظيمية العالمية.

```text
PROJECT 12 — Drugs@FDA Approval Timeline Explorer
Duration class: M. Publish: GitHub + Vercel.

GOAL
Build an explorer of approval history, products, and applications in Drugs@FDA, showing the relations between application, product, active ingredient, and submission where available.

VERIFIED SOURCES
Drugs@FDA data files https://www.fda.gov/drugs/drug-approvals-and-databases/drugsfda-data-files or openFDA Drugs@FDA https://open.fda.gov/apis/drug/drugsfda/ (tested: API call and download metadata succeeded; 29,312 records listed in download.json).

METHOD AND LIMITS
- Never equate approval date with launch date, nor application number with one product. Document NDA/ANDA/BLA type if available; fix relations before counting. Show labels/actions as links, not recommendations.

DELIVERABLES
Relational DuckDB model; search by ingredient/sponsor/application; approval timeline; product table; annual trends; source lineage; snapshot diff.

ACCEPTANCE TESTS
Relation-key and duplication tests; sample compared with FDA pages; date precision tests; no exclusivity claims except from their source; source update date shown.
```

---

### 13 — Orange Book Competition & Exclusivity Lab

**الفكرة ببساطة:** «الكتاب البرتقالي» الأمريكي يسجل المنتجات المرجعية والتكافؤ العلاجي والبراءات وفترات الحصرية. هذا المشروع يشرح البنية التنافسية لكل مادة وأحداث دخول الجنيس المحتملة كإشارات تنظيمية. مناسب لمسار الجنيس والملكية الفكرية.

```text
PROJECT 13 — Orange Book Competition & Exclusivity Lab
Duration class: L. Publish: GitHub + Vercel.

GOAL
Build a lab explaining the competitive structure of approved products: reference listed drug, therapeutic equivalence, applications, patents/exclusivities, and possible generic-entry events.

VERIFIED SOURCE
FDA Orange Book data files https://www.fda.gov/drugs/drug-approvals-and-databases/orange-book-data-files with official definitions (openFDA lists 48,664 orangebook records). Use Drugs@FDA to verify approval relations; no commercial sources.

METHOD AND LIMITS
- Distinguish RLD, RS, TE code, patent, and exclusivity. Never infer patent validity, freedom to operate, or commercial availability. A patent expiry date is not a confirmed entry date. Define "market candidate" as a regulatory signal only.

DELIVERABLES
Multi-file ETL; ingredient/application explorer; patent/exclusivity timeline; competition counts with switchable definitions; documented case studies for three ingredients.

ACCEPTANCE TESTS
Referential-integrity tests; no double-counting of products/strengths; TE codes explained from FDA text; unit tests for date overlaps; legal/regulatory disclaimer; output never described as patent advice.
```

---

### 14 — Purple Book Biosimilar Landscape

**الفكرة ببساطة:** «الكتاب الأرجواني» يسجل المنتجات البيولوجية والبدائل الحيوية وحالة قابلية التبادل. هذا المشروع يعرض العلاقات بين المنتج المرجعي وبدائله وتواريخها. مناسب لمسار البيولوجيات.

```text
PROJECT 14 — Purple Book Biosimilar Landscape
Duration class: M. Publish: GitHub + Vercel.

GOAL
Build an explorer of reference biological products, biosimilars, interchangeability status, approvals, and dates.

VERIFIED SOURCE
Official monthly Purple Book downloads https://purplebooksearch.fda.gov/index.cfm?event=downloads with FDA explanatory pages for biosimilar and interchangeable products.

METHOD AND LIMITS
- Never use "generic" for biosimilar; never assume interchangeability from biosimilar status. Separate product, reference product, licensure, and exclusivity fields as provided; show the release date.

DELIVERABLES
Download/version manifest; relationship graph; timeline; sponsor/ingredient filters; evidence cards; monthly diff; Arabic glossary of terms.

ACCEPTANCE TESTS
Graph without unexplained cycles; manual check of 10 relations; version-change test; licensure never interpreted as preferred clinical use; links to original FDA records.
```

---

### 15 — DailyMed Label Version Diff Engine

**الفكرة ببساطة:** نشرات الأدوية الأمريكية تُحدّث باستمرار، والفرق بين نسختين قد يحمل تحذيرًا جديدًا. هذا المشروع يقارن نسختين من نشرة منتج واحد ويُظهر ما تغير في الأقسام المهمة مع الرجوع إلى النص الأصلي. مناسب للمعلومات الدوائية.

```text
PROJECT 15 — DailyMed Label Version Diff Engine
Duration class: L. Publish: GitHub + Vercel.

GOAL
Build an engine comparing two SPL versions of one product and detecting changes in key sections such as BOXED WARNING, WARNINGS AND PRECAUTIONS, ADVERSE REACTIONS, and INDICATIONS.

VERIFIED SOURCE
DailyMed RESTful web services https://dailymed.nlm.nih.gov/dailymed/app-support-web-services.cfm and SPL history (tested: list endpoint returned JSON).

METHOD AND LIMITS
- Resolve SETID/SPL version identity; convert XML to sections preserving headings and identifiers. Semantic-aware text diff after removing whitespace-only changes. Classify changes deterministically first; if an LLM summarizes, show both texts and supporting passages and never let it invent clinical meaning.

DELIVERABLES
Search; version timeline; side-by-side diff; section filters; change summary with XML citations; Markdown export; local watchlist.

ACCEPTANCE TESTS
Golden tests for paragraph change / section move / formatting only; no mixing of same-name products; every summary traceable to text; no therapeutic recommendation; statement that DailyMed is the latest submitted labeling but does not replace the authority's source in a given context.
```

---

### 16 — FAERS Signal Triage Laboratory

**الفكرة ببساطة:** قاعدة بلاغات الأعراض الجانبية الأمريكية مفتوحة للجميع. هذا المشروع يعيد إنتاج طريقة فرز الإشارات: استخراج أزواج الدواء والعرض، إزالة التكرار، وحساب مؤشرات التناسب مع فواصل الثقة، ووضع النتائج في قائمة مراجعة. مناسب لليقظة الدوائية.

```text
PROJECT 16 — FAERS Signal Triage Laboratory
Duration class: L. Publish: GitHub + GitHub Pages (Quarto).

GOAL
Build an educational lab reproducing drug–event pair extraction, case-version deduplication, and ROR/PRR with confidence intervals and minimum-count rules, placing results in a review queue.

VERIFIED SOURCES
openFDA Drug Event API https://open.fda.gov/apis/drug/event/ for experimentation (20.7 million records listed in download.json) and FAERS quarterly data files https://www.fda.gov/drugs/drug-approvals-and-databases/fda-adverse-event-reporting-system-faers-latest-quarterly-data-files for larger analysis.

METHOD AND LIMITS
- Use CASEID/PRIMARYID/CASEVERSION and FDA's latest-version retention rule. Normalize drug names carefully; use MedDRA PT as provided. ROR/PRR are disproportionality signals, not incidence, risk, or causality. Show stimulated reporting, missingness, confounding, duplicate uncertainty, and absence of a denominator.
- Optional documented extensions: (a) an external aggregate cross-check using the single cumulative global count from VigiAccess https://www.vigiaccess.org/ stated explicitly as aggregate-only with no time or country breakdown and stored as a dated manual snapshot if automated fetching is not permitted; (b) stratified analysis for pediatric/pregnancy subgroups versus the general population with a fixed warning that reporting in these groups is incomplete and biased and that a difference between groups is not a difference in risk. No "alerts"; review lists only.

DELIVERABLES
Reproducible notebook/Quarto; ETL; 2×2 table explainer; volcano/table view; filters; case drill-down stripped of sensitive narrative; data-quality panel; method card per metric.

ACCEPTANCE TESTS
Tests with known 2×2 tables; dedupe audit; minimum-cell suppression; comparison with a manual result; no ranking titled "most dangerous drugs"; warning visible next to every signal; reporter names never in curated data.
```

---

### 17 — EMA Regulatory & Shortage Change Monitor

**الفكرة ببساطة:** وكالة الأدوية الأوروبية تنشر بيانات موقعها كاملة بصيغة منظمة تُحدّث مرتين يوميًا: الأدوية، الإجراءات، الوثائق، والنقص. هذا المشروع يراقب التغيرات ويبني سجل أحداث قابلًا للتدقيق. مناسب للشؤون التنظيمية الأوروبية والنقص.

```text
PROJECT 17 — EMA Regulatory & Shortage Change Monitor
Duration class: M. Publish: GitHub + Vercel.

GOAL
Build a daily monitor of changes in EMA medicine pages, post-authorisation procedures, documents, and supply shortages, with an auditable event log.

VERIFIED SOURCES
EMA JSON website data downloads https://www.ema.europa.eu/en/about-us/about-website/download-website-data-json-data-format (documented twice-daily updates). Tested file: shortages JSON https://www.ema.europa.eu/en/documents/report/shortages-output-json-report_en.json (HTTP 200, 84 records with INN, status, forms, dates). Take the other file URLs (medicines, post-authorisation, documents, referrals) from the same official page.

METHOD AND LIMITS
- Store manifest and hash; extract stable identifiers such as EMA product number/URL. Distinguish new/updated/resolved, and source change from parser change. Never claim that every European regulatory action or shortage is represented beyond the website files.

DELIVERABLES
Scheduled ingest; schema monitor; event-sourcing table; filters; watchlist; RSS/Atom feed; evidence diff; timeline UI.

ACCEPTANCE TESTS
Idempotent re-run; change events not duplicated; a resolved shortage stays in history; one file failing never erases old data; screen shows both EMA timestamp and capture timestamp.
```

---

### 18 — FDA Quality & CAPA Theme Analyzer

**الفكرة ببساطة:** خطابات التحذير الأمريكية للمصانع وثائق عامة تشرح ملاحظات الجودة والتصنيع. هذا المشروع يصنف موضوعاتها (سلامة البيانات، التحقق، التلوث، الثبات) بقواعد قابلة للتدقيق ومع عينة يراجعها إنسان. مناسب لوظائف الجودة والتصنيع.

```text
PROJECT 18 — FDA Quality & CAPA Theme Analyzer
Duration class: L. Publish: GitHub + Vercel.

GOAL
Build an auditable classifier of quality and manufacturing themes in FDA warning letters and public inspection classification data, to learn from observation patterns, not to rate a specific company.

VERIFIED SOURCES
FDA Warning Letters https://www.fda.gov/inspections-compliance-enforcement-and-criminal-investigations/compliance-actions-and-activities/warning-letters (public table/Excel), Inspection Classifications https://www.fda.gov/inspections-compliance-enforcement-and-criminal-investigations/inspection-basics/inspection-classifications, and official NAI/VAI/OAI definitions. Note: fda.gov may return 401 to requests without browser-like headers; use an honest User-Agent and one request per page.

METHOD AND LIMITS
- Human taxonomy (data integrity, validation, contamination control, stability, complaints, investigations, supplier quality). Multi-label rules baseline, optional classifier. Double-coded gold sample; precision/recall or F1 and agreement. Never turn absence of letters into compliance; never build a company reputation score; drop signatory names from curated data.

DELIVERABLES
Document fetcher; short citation-level excerpts; taxonomy browser; trends with denominators; confusion matrix; review queue; model card.

ACCEPTANCE TESTS
Every label linked to an excerpt and URL; no long quotations; holdout set; baseline vs LLM comparison if an LLM is used; hallucinated citations blocked; selection bias stated; databases not presented as covering all inspections.
```

---

### 19 — ClinicalTrials Results-Timeliness Audit

**الفكرة ببساطة:** كثير من التجارب المسجلة لا تنشر نتائجها في الوقت المتوقع. هذا المشروع يقيس وصفيًا زمن نشر النتائج حسب الراعي والمرحلة والحالة والدولة، بقواعد معلنة لما هو «مرشح للتأخر». مناسب لنزاهة البحث.

```text
PROJECT 19 — ClinicalTrials Results-Timeliness Audit
Duration class: M. Publish: GitHub + Vercel.

GOAL
Build a descriptive audit of results-posting time in ClinicalTrials.gov by sponsor/phase/condition/country, with explicit rules for what is eligible and what is an overdue candidate.

VERIFIED SOURCE
ClinicalTrials.gov API v2 https://clinicaltrials.gov/data-about-studies/learn-about-api with protocol/results/status fields and official registry definitions. No automated legal conclusion about FDAAA; call results "rule-based candidates" unless every exception is applied.

METHOD AND LIMITS
- Pre-register the cohort rule in config; define primary completion date, results first posted, study type/status. Descriptive time-to-event with censoring where appropriate. Separate missing date from no results.

DELIVERABLES
Cohort builder; flow diagram; timeliness distributions; sponsor/condition explorer; study details; downloadable audit trail; Quarto methodology appendix.

ACCEPTANCE TESTS
Cohort counts at each exclusion; date tests; no duplicate NCT; sensitivity to the time-window definition; no accusation of non-compliance; links to records.
```

---

### 20 — Synthetic Trial Eligibility Feasibility Lab

**الفكرة ببساطة:** معايير أهلية التجارب مكتوبة نصًا، وتحويلها إلى قواعد قابلة للتنفيذ مهارة مطلوبة في الأبحاث السريرية. هذا المشروع يختار تجربة واحدة ويحول خمسة إلى عشرة معايير إلى قواعد تعمل على مرضى مصطنعين، ويقيس نسبة التأهل. مناسب للأبحاث السريرية.

```text
PROJECT 20 — Synthetic Trial Eligibility Feasibility Lab
Duration class: L. Publish: GitHub + Vercel.

GOAL
Pick one registered drug trial (or a small set), convert selected eligibility criteria into executable rules over a Synthea cohort, then measure synthetic evaluability and eligibility rates.

VERIFIED SOURCES
ClinicalTrials.gov API v2, Synthea https://github.com/synthetichealth/synthea (Apache-2.0; FHIR/CSV outputs), FHIR R4. Never use real patients.

METHOD AND LIMITS
- Do not attempt NLP over every criterion. Choose 5–10 representable rules (age, sex, diagnosis, medication, lab, period). For each criterion: met/not met/unknown, with a documented manual mapping to FHIR paths/codes. Unknown is not excluded.

DELIVERABLES
Trial importer; small criteria DSL; synthetic cohort generator; patient-level explanation; attrition waterfall; missingness dashboard; scenario editor.

ACCEPTANCE TESTS
Manual validation of 30 synthetic patients; tested temporal rules; trace from criterion text to code; no claim about real recruitment or generalizability; statement that Synthea does not automatically reflect real disease prevalence.
```

---

### 21 — Trial–Publication Evidence Linker

**الفكرة ببساطة:** كل تجربة لها رقم تسجيل، وكل منشور له معرف، لكن الربط بينهما غالبًا ناقص. هذا المشروع يربط التجارب بالمنشورات عبر ثلاث قواعد بيانات علمية عامة، ويميز الروابط المؤكدة من المرشحة من المفقودة. مناسب لمسار الأدلة والمراجعات المنهجية.

```text
PROJECT 21 — Trial–Publication Evidence Linker
Duration class: L. Publish: GitHub + Vercel.

GOAL
Link NCT IDs to publications and results within one drug topic, revealing trials with documented, candidate, or missing links.

VERIFIED SOURCES
ClinicalTrials.gov, Europe PMC API https://europepmc.org/developers, OpenAlex API https://docs.openalex.org/ (tested: public search requests succeeded without keys).

METHOD AND LIMITS
- Match exact NCT in identifiers/full-text metadata first; then DOI/PMID and registry links; title/author/year fuzzy only as candidate. Absence of a link is not definitive non-publication; not every publication is the trial's primary result.

DELIVERABLES
Provenance graph study→publication; confidence/reason; review queue; evidence timeline; orphan reports; DOI/PMID deduplication; RIS/CSV export.

ACCEPTANCE TESTS
Gold set of 50 relations; precision/recall by threshold; no fuzzy auto-accept; source coverage shown; no scientific conclusions summarized from an abstract as final fact; original links for every node.
```

---

### 22 — Synthetic SDTM Safety TLF Pipeline

**الفكرة ببساطة:** شركات الأدوية تُخرج جداول السلامة من بيانات التجارب بصيغة معيارية. هذا المشروع يبني خطًا برمجيًا يعالج بيانات اختبار مفتوحة بهذه الصيغة وينتج جداول الأعراض الجانبية والتعرض والخصائص بشكل قابل لإعادة الإنتاج. مناسب لمسار البرمجة السريرية.

```text
PROJECT 22 — Synthetic SDTM Safety TLF Pipeline
Duration class: L. Publish: GitHub + GitHub Pages (Quarto).

GOAL
Build a clinical-research pipeline processing open SDTM test data into reproducible safety tables, listings, and figures (adverse events, exposure, demographics).

VERIFIED SOURCE
pharmaverse test data and packages https://github.com/pharmaverse (e.g., pharmaversesdtm) with available CDISC/package documentation. Use openly licensed versions only.

METHOD AND LIMITS
- Define population flags, treatment-emergent window, SOC/PT, severity/relatedness in an analysis plan before code. Data are synthetic/test; never attribute them to a real drug. Never claim "CDISC compliant" without a validator or a defined scope.

DELIVERABLES
R project with renv; Quarto report; data checks; small derived analysis datasets; AE overview table; SOC/PT table; subject listing; exposure plot; traceability from TLF to source variable.

ACCEPTANCE TESTS
Results stable from a clean environment; clear denominators; subjects counted once where required; missing category visible; unit tests for the TEAE window; validation snapshot stating what was not verified.
```

---

### 23 — Synthea Medication Reconciliation Sandbox

**الفكرة ببساطة:** مواءمة الأدوية عند انتقال المريض بين مستويات الرعاية مهمة صيدلانية أساسية. هذا المشروع يبني قائمة الأدوية النشطة من سجلات مصطنعة ويكشف التعارضات المحتملة (تكرار مادة، جرعة ناقصة، أمر قديم). مناسب للصيدلة السريرية.

```text
PROJECT 23 — Synthea Medication Reconciliation Sandbox
Duration class: M. Publish: GitHub + Vercel.

GOAL
Build an educational sandbox that composes an active medication list from FHIR MedicationRequest/MedicationStatement/Dispense (where present in a Synthea release) and detects potential discrepancies at a synthetic care transition.

VERIFIED SOURCE
Synthea https://github.com/synthetichealth/synthea and FHIR R4. Inspect the outputs of a pinned release; never assume every resource exists.

METHOD AND LIMITS
- Define "active medication" with explicit time logic; separate ordered/dispensed/reported. Discrepancy rules limited to duplicate ingredient, overlapping strength records, missing route/dose, stale order. No clinical drug–drug interaction without a licensed, verified rule base.

DELIVERABLES
FHIR bundle importer; timeline; reconciliation workspace; per-line provenance; synthetic transition scenario; unresolved-discrepancy queue; educational export summary.

ACCEPTANCE TESTS
Fixtures for every status/time boundary; no record merged without a reason; source-resource view; synthetic tag on every screen; never the phrase "the patient's real medication list".
```

---

### 24 — Terminology Mapping QA Lab

**الفكرة ببساطة:** الانتقال بين أنظمة الترميز الطبية (تشخيصات، مصطلحات سريرية، أسماء أدوية، تصنيف علاجي) ليس استبدال نص؛ فالكود الواحد قد يقابل صفرًا أو عدة أكواد. هذا المشروع يبني مختبرًا يوضح ذلك ويقيّم جودة خرائط صغيرة عامة. مناسب لمسار الترميز والمعلوماتية.

```text
PROJECT 24 — Terminology Mapping QA Lab
Duration class: L. Publish: GitHub + Vercel.

GOAL
Build a lab showing why moving between SNOMED CT, ICD-10-CM/AM, RxNorm, and ATC is not text substitution, and evaluate the quality of a small public or legitimately derived mapping set.

VERIFIED SOURCES
SNOMED CT Mapping Guide https://docs.snomed.org/snomed-ct-practical-guides/snomed-ct-mapping-guide, NLM SNOMED CT to ICD-10-CM https://www.nlm.nih.gov/research/umls/mapping_projects/snomedct_to_icd10cm.html, RxNav API https://lhncbc.nlm.nih.gov/RxNav/APIs/RxNormAPIs.html (tested), WHO ATC references. Never redistribute restricted UMLS/SNOMED packages.

METHOD AND LIMITS
- Model supports source concept, target, map rule, advice, context, cardinality, version, confidence, provenance. Represent zero-to-one/many, unmapped, broader/narrower, ingredient vs clinical drug. Use a small licensed sample or synthetic codes.

DELIVERABLES
Mapping inspector; rule trace; side-by-side concept details; ambiguity queue; version diff; unit tests; interactive teaching of five pitfalls.

ACCEPTANCE TESTS
No "final translation" button; every mapping has version/license/provenance; tests for one-to-many and no-map; live RxNorm lookup works; explanation that ICD, being a classification, does not always preserve SNOMED meaning.
```

---

### 25 — Synthea-to-OMOP ETL Quality Lab

**الفكرة ببساطة:** الأبحاث على البيانات الواقعية تعتمد على نموذج بيانات موحد عالمي. هذا المشروع يحول سجلات مرضى مصطنعين إلى هذا النموذج ويقيس ما فُقد وما لم يُربط أثناء التحويل. مناسب لمسار المعلوماتية والبيانات الواقعية.

```text
PROJECT 25 — Synthea-to-OMOP ETL Quality Lab
Duration class: L. Publish: GitHub + GitHub Pages.

GOAL
Implement a small local ETL from Synthea to the OMOP CDM, then build a before/after quality report explaining information loss, mapping rates, and vocabulary constraints.

VERIFIED SOURCES
OHDSI ETL-Synthea https://github.com/OHDSI/ETL-Synthea, OHDSI Tutorial ETL https://github.com/OHDSI/Tutorial-ETL/tree/master/etl/etl-synthea, and Synthea. DuckDB and small seeds allowed; never make restricted vocabulary downloads a prerequisite for the demo.

METHOD AND LIMITS
- Choose 20–100 synthetic patients; pin Synthea/CDM versions. Measure row counts, person/visit/drug/condition referential integrity, unmapped source values, date plausibility, representation loss. Never call the output real RWD.

DELIVERABLES
One-command local ETL; source-to-target mapping doc; DuckDB schema; Achilles-like mini dashboard; reconciliation tables; DQ report.

ACCEPTANCE TESTS
Counts before/after; orphans = 0 where required; idempotent re-run; known-unmapped list; demo runs without proprietary vocabularies; explanation of CDM conformance vs fitness for use.
```

---

### 26 — CMS Part D Prescribing Variation Explorer

**الفكرة ببساطة:** برنامج الدواء الحكومي الأمريكي ينشر بيانات الوصف والتكلفة حسب الجغرافيا والتخصص. هذا المشروع يستكشف التباين في وصف أدوية مختارة مع ضبط المقامات والقيم المحجوبة. مناسب لتحليل استخدام الدواء والتأمين.

```text
PROJECT 26 — CMS Part D Prescribing Variation Explorer
Duration class: M. Publish: GitHub + Vercel.

GOAL
Build an explorer of geographic or specialty variation in prescribing/cost for selected drugs in Medicare Part D, with correct denominators, suppression handling, and interpretation limits.

VERIFIED SOURCE
CMS Part D Prescribers by Provider and Drug https://data.cms.gov/provider-summary-by-type-of-service/medicare-part-d-prescribers/medicare-part-d-prescribers-by-provider-and-drug or Geography and Drug, latest year. Free; API/CSV and dictionary. Note: the research environment's requests were blocked by a CDN layer; implement an early connectivity test and an official CSV fallback.

METHOD AND LIMITS
- Choose one grain: provider-drug or geography-drug. Never compare raw counts without a suitable rate; never describe variation as overuse. Understand suppression flags; total drug cost aggregates multiple payment sources. Never expose NPI as an accusatory classification; no individual-prescriber rankings.

DELIVERABLES
Resilient downloader; sample fixture; data-dictionary viewer; cost/fill/day-supply metrics; small-multiple charts; outlier candidates at aggregate level; methods panel.

ACCEPTANCE TESTS
Works from the official CSV if the API fails; suppression never becomes zero; no individual-level rankings; aggregation tests; year and population coverage stated on every chart.
```

---

### 27 — QHP Formulary & Benefit Coverage Comparator

**الفكرة ببساطة:** سوق التأمين الأمريكي ينشر ملفات عامة لخطط التأمين ومزاياها وروابط قوائم أدويتها. هذا المشروع يقارن عددًا محدودًا من الخطط ويُظهر اختلاف بنية البيانات وجودتها. مناسب لمسار التأمين والتغطية.

```text
PROJECT 27 — QHP Formulary & Benefit Coverage Comparator
Duration class: L. Publish: GitHub + Vercel.

GOAL
Build a tool comparing Marketplace plan attributes, benefits/cost sharing, and machine-readable formulary links for a limited set of states and plans, showing differences in data structure and quality.

VERIFIED SOURCES
CMS Exchange Public Use Files 2026 https://www.cms.gov/marketplace/resources/data/public-use-files: Benefits and Cost Sharing, Plan, Service Area, Crosswalk, Machine-readable URL PUF and their dictionaries.

METHOD AND LIMITS
- Start with two states and 20 plans. Join PlanID/VariantID/IssuerID per the dictionary. Treat formulary URLs as external sources that may fail; log status/schema. Never claim individual eligibility or actual out-of-pocket cost; never generalize to uncovered state-based exchanges.

DELIVERABLES
PUF loader; relational model; plan compare; coverage-link health monitor; benefit/cost-sharing explorer; data completeness score; snapshot date.

ACCEPTANCE TESTS
Referential tests; no mixing plan/variant; URL failure never deletes the plan; user agreement/disclaimer shown; no "best plan" recommendation; explainers for every deductible/copay/coinsurance field used.
```

---

### 28 — NADAC Generic Acquisition-Cost Monitor

**الفكرة ببساطة:** الحكومة الأمريكية تنشر أسبوعيًا متوسط تكلفة اقتناء الأدوية للصيدليات. هذا المشروع يراقب تغير هذه التكلفة للأدوية الجنيسة والتجارية عبر الزمن. مناسب لمسار التسعير.

```text
PROJECT 28 — NADAC Generic Acquisition-Cost Monitor
Duration class: M. Publish: GitHub + Vercel.

GOAL
Build a weekly monitor of NADAC per-unit changes for generics and brands, with an optional conservative link to the Orange Book at NDC/ingredient level after verification.

VERIFIED SOURCES
NADAC 2026 https://data.medicaid.gov/dataset/fbb83258-11c7-47f5-8b18-5f8e79f7e704 and NADAC methodology https://www.medicaid.gov/medicaid/nadac (tested: CSV download of 2 Sept 2026 succeeded; 12 columns confirmed including NDC, NADAC per unit, effective date, pricing unit, classification). Use the Orange Book only for separate regulatory enrichment.

METHOD AND LIMITS
- Respect Effective Date, As of Date, Pricing Unit, and classification. Normalize NDC preserving leading zeros. Compute absolute and percent change with winsorization for display only. NADAC is an acquisition-cost benchmark, not retail price, reimbursement, or net price.

DELIVERABLES
Weekly snapshot manifest; NDC timeline; price-change explorer; generic/brand comparison; reason-code glossary; anomaly review; download.

ACCEPTANCE TESTS
Decimal, not float, for currency; unit tests for overlapping dates and NDC; no comparison across different units; source hash; no savings claims; effect of the generic moving-average method shown per CMS documentation.
```

---

### 29 — Transparent Markov Cost-Effectiveness Model

**الفكرة ببساطة:** تحليل فعالية التكلفة يقارن دواءين في تكلفتهما ونتائجهما الصحية عبر الزمن. هذا المشروع يبني نموذجًا تعليميًا شفافًا لحالة مرضية واحدة مع تحليل عدم اليقين وتقرير يتبع معيار الإبلاغ الدولي. مناسب للاقتصاد الصحي.

```text
PROJECT 29 — Transparent Markov Cost-Effectiveness Model
Duration class: L. Publish: GitHub + GitHub Pages.

GOAL
Build a transparent educational Markov model comparing two drug strategies in one condition, using inputs from open literature or a declared illustrative set, with deterministic and probabilistic sensitivity analysis.

VERIFIED REFERENCES
NICE Economic Evaluation https://www.nice.org.uk/process/pmg36/chapter/economic-evaluation-2, CHEERS 2022 https://www.equator-network.org/reporting-guidelines/cheers/, and relevant decision references. Cite every value or tag it synthetic/illustrative.

METHOD AND LIMITS
- Define perspective, population, comparator, states, cycle length, horizon, half-cycle correction, costs, utilities, mortality, discounting, ICER, and NMB. Validate the transition matrix; apply justified deterministic and probabilistic distributions. Never state the model is suitable for a Saudi decision unless local inputs are sufficient.

DELIVERABLES
R or Python package; config inputs; cohort trace; state occupancy; costs/QALYs; ICER plane; CEAC; tornado; scenario analysis; CHEERS-aligned technical report; web/static demo.

ACCEPTANCE TESTS
Probabilities sum to 1; manual results for two cycles; zero-discount/horizon edge tests; seeds; parameter table with source and year; internal validation; statement of structural uncertainty and what was not externally validated.
```

---

### 30 — Saudi Budget-Impact Scenario Sandbox

**الفكرة ببساطة:** الأثر على الميزانية هو تكلفة إدخال دواء جديد على جهة ما خلال سنوات. هذا المشروع يبني صندوق سيناريوهات لسياق سعودي بمدخلات موسومة (حقيقية من القوائم العامة أو مصطنعة). مناسب للاقتصاد الصحي والتأمين.

```text
PROJECT 30 — Saudi Budget-Impact Scenario Sandbox
Duration class: L. Publish: GitHub + Vercel.

GOAL
Build a sandbox for the budget impact of a hypothetical drug/intervention in a Saudi context, focusing on eligible population, uptake, mix substitution, and annual cost, not cost-effectiveness.

VERIFIED SOURCES
List prices and products from CHI DDF/Human Drug List https://www.chi.gov.sa/Rules/Pages/DamanDrugFormulary.aspx; public contextual data from CHI/WHO/General Authority for Statistics when needed; ISPOR Budget Impact guidance https://www.ispor.org/publications/journals/value-in-health/abstract/Volume-17--Issue-1/budget-impact-analysis-principles-of-good-practice-report-of-the-ispor-2012-budget-impact-analysis-good-practice-ii-task-force. Make population, use, and discounts synthetic unless a suitable public source exists.

METHOD AND LIMITS
- Define payer perspective, eligible population, current/new mix, uptake, discontinuation, drug/admin/monitoring/adverse-event costs, and a 1–5 year period. Separate list price from net price; show scenario ranges. Never use QALY/ICER as if it were BIA; never call the output a CHI budget forecast.

DELIVERABLES
Input registry with provenance flags; current-vs-new calculator; annual and cumulative impact; optional PMPM with declared denominator; one-way/scenario sensitivity; waterfall; assumption audit.

ACCEPTANCE TESTS
Every input tagged observed or synthetic; hand recomputation of a simple case; negative/zero population tests; no hidden value; prices and dates visible; fixed statement: "Educational scenario model, not an official payer budget estimate."
```

---

### 31 — SFDA Variation Readiness Checklist

**الفكرة ببساطة:** أي تغيير على دواء مسجل (مصنع جديد، مواصفة جديدة، تغليف جديد) يحتاج ملفًا بوثائق محددة يذكرها دليل الهيئة حرفيًا. هذا المشروع يحول الدليل إلى قائمة تحقق تفاعلية: تختار نوع التغيير فتظهر الوثائق المطلوبة بمرجع الصفحة، وتحصل على قائمة نواقص. مناسب للشؤون التنظيمية المحلية، ومن أنسب المشاريع لغير المبرمج.

```text
PROJECT 31 — SFDA Variation Readiness Checklist
Duration class: M. Publish: GitHub + Vercel.

GOAL
Build a document-readiness checker for post-marketing variation submissions: the user selects a variation type per the Saudi variation guideline; the tool shows the conditions to be fulfilled and the documentation to be supplied, quoted from the guideline with page/clause citations, and produces a gap list. No timeline predictions, no approval probabilities.

VERIFIED SOURCE
SFDA "Guidelines for Variation Requirements" version 6.3 (March 2025): https://www.sfda.gov.sa/sites/default/files/2025-03/Variation.pdf — downloaded on 2026-09-03: PDF, 82 pages, 1,450,674 bytes, SHA-256 starting d5a65e00; contains "Conditions to be fulfilled" and "Documentation to be supplied" per variation and definitions of Type IA/IAIN/IB/II. FIREWALL NOTE: the first request succeeded; the second automated request was rejected. Download once, store with checksum, document the manual download path.

METHOD AND LIMITS
- Extract the structure (category → variation → conditions → documents) into hand-reviewed YAML with a citation (page/clause) for every item. Items not extracted with confidence are tagged needs-review and never shown as requirements.
- Do not interpret clauses; do not add requirements from general experience or other agencies' guidelines.
- Never predict review time or query likelihood; no public dataset exists for it, and any number would be guesswork with statistical make-up.

DELIVERABLES
PDF extractor with a coverage report (variations extracted vs the guideline's index); reviewed YAML tagged with guideline version; bilingual UI: pick variation → interactive checklist → exportable gap report; a "What this tool does not do" page; diff between two guideline versions when an older one is available.

ACCEPTANCE TESTS
100% of displayed items carry a citation; a sample of 30 variations compared by hand with the PDF, agreement rate documented; a test blocks any needs-review item from display; a text test blocks the words "predict", "probability", "review time" in the UI; guideline version and date shown on every screen; statement that the tool replaces neither the guideline nor correspondence with the authority.
```

---

### 32 — Saudi Registry × WHO AWaRe Stewardship Map

**الفكرة ببساطة:** منظمة الصحة العالمية تصنف المضادات الحيوية إلى ثلاث مجموعات (متاح، مراقَب، احتياطي) ومجموعة رابعة «غير موصى بها» للتوليفات الثابتة. هذا المشروع يربط المضادات المسجلة في السعودية بهذا التصنيف ويُظهر توزيعها، وأي مضادات الاحتياطي لا منتج مسجل لها، وأي التوليفات غير الموصى بها موجودة في السجل. مناسب لترشيد المضادات والصيدلة السريرية.

```text
PROJECT 32 — Saudi Registry × WHO AWaRe Stewardship Map
Duration class: M. Publish: GitHub + Vercel.

GOAL
Build a stewardship map linking antibiotics registered in the Saudi Human Drug List to the WHO AWaRe classification (Access/Watch/Reserve/Not recommended), showing the distribution of registered products by category, Reserve antibiotics with no registered product, and Not-recommended fixed-dose combinations present in the registry.

VERIFIED SOURCES
- Saudi Human Drug List via CHI/SFDA: https://www.chi.gov.sa/Rules/Pages/DamanDrugFormulary.aspx
- WHO AWaRe portal list page: https://aware.essentialmeds.org/list — tested 2026-09-03: server-rendered HTML (549,179 bytes) containing 376 antibiotics each tagged with its group (145 Watch, 94 Access, 30 Reserve, 107 Not recommended). No official CSV export and no public API (three API paths returned 404).
- Official publication for pinning: WHO AWaRe classification 2025 https://www.who.int/publications/i/item/B09489 (PDF).
LIMIT: the parser depends on HTML structure and may break; a schema test, a dated fixture, and the PDF as manual reference are mandatory.

METHOD AND LIMITS
- Normalize active ingredients (including "A + B" combinations) into a single key; exact → normalized → fuzzy candidate with a review queue.
- Count at ingredient/combination level when comparing with the classification; show product counts as a second layer.
- Never compute consumption, DDD, or a "60% Access target" from a registration list; registration is not use.
- Never call a product "inappropriate"; "Not recommended" is WHO's classification of combinations, shown as is with a link to its definition.

DELIVERABLES
AWaRe fetcher with snapshot manifest and PDF reference; registry adapter; match workbench with a 50-ingredient gold set; dashboard by category, route, and form; a Reserve-not-registered list and a Not-recommended-registered list (both titled "for review", never "violations"); Arabic glossary of AWaRe concepts.

ACCEPTANCE TESTS
A test fails when the antibiotic count or HTML structure changes beyond a declared threshold; precision/recall on the gold set; the words "consumption" and "60% target" absent from the UI; ingredient-level vs product-level distinction tested; warning next to every list that registration ≠ availability ≠ use and that clinical decisions are out of scope.
```

---

### 33 — Cross-Border Shortage Overlap Monitor

**الفكرة ببساطة:** أمريكا وأوروبا والسعودية تنشر قوائم نقص الأدوية علنًا، كلٌّ بصيغته. هذا المشروع يجمع القوائم الثلاث ويُظهر أي المواد الفعالة تظهر في أكثر من قائمة، وأي المواد في نقص أجنبي لها منتجات مسجلة محليًا. مناسب لسلاسل الإمداد وصيدلة المستشفيات، ومناسب لغير المبرمج.

```text
PROJECT 33 — Cross-Border Shortage Overlap Monitor
Duration class: M. Publish: GitHub + Vercel.

GOAL
Build a monitor of the overlap between officially published drug-shortage lists from three jurisdictions (United States, Europe, Saudi Arabia) at ingredient/form level, showing what is in shortage here and there, and what is in foreign shortage for an ingredient with locally registered products, as a descriptive fact only.

VERIFIED SOURCES
- openFDA Drug Shortages https://api.fda.gov/drug/shortages.json — tested 2026-09-03: 1,635 records; fields generic_name, availability (Available 752 / Unavailable 299 / Limited Availability 124), update_type, package_ndc, openfda.substance_name/rxcui.
- EMA shortages JSON https://www.ema.europa.eu/en/documents/report/shortages-output-json-report_en.json — tested: 84 records; fields international_non_proprietary_name_inn_or_common_name, supply_shortage_status, pharmaceutical_forms_affected, first_published_date, last_updated_date, shortage_url.
- SFDA Anticipated Shortage https://www.sfda.gov.sa/en/anticipatedShortage — public web table; no confirmed bulk download; dated manual snapshot.
- Saudi Human Drug List (CHI) for registered products.

METHOD AND LIMITS
- Entity = (normalized INN, form, route). Use RxNorm where an rxcui exists and a reviewed synonym list otherwise.
- Keep each jurisdiction's status vocabulary as is; never force-unify (FDA "Unavailable" ≠ EMA "Shortage ongoing").
- Store every list as a dated snapshot; build an event log (appeared / changed / resolved).
- No "early warning", no "expected exposure", no risk score. FDA includes resolved "Available" records; do not count them as active shortage. A manufacturer name in FDA data does not identify the manufacturing site of a Saudi product; never infer a "shared supplier".

DELIVERABLES
Three adapters with schema contracts; normalization library; overlap explorer (Venn counts + table); per-ingredient timeline; weekly change feed via GitHub Actions that halts if any source fails; a status-vocabulary page per jurisdiction; CSV download.

ACCEPTANCE TESTS
Tests for an ingredient in FDA only, in two lists, in all three, and an FDA record with Available status; no fuzzy auto-match; non-unification of statuses tested; the words "predict", "alert", "risk" absent from the UI; each source's timestamp shown separately; the SFDA list labeled "manual/web snapshot" with its date.
```

---

### 34 — FDA Complete Response Letter Theme Explorer

**الفكرة ببساطة:** حين ترفض إدارة الغذاء والدواء الأمريكية طلب تسجيل، ترسل «خطاب رد كامل» يشرح الأسباب. الإدارة نشرت مئات هذه الخطابات بنصها الكامل. هذا المشروع يصنف أسباب الرفض (تصنيع، سريري، سلامة، تسمية، تفتيش، إحصاء) بقواعد قابلة للتدقيق مع اقتباس المقطع. مناسب للشؤون التنظيمية وفهم لماذا تُرفض الملفات.

```text
PROJECT 34 — FDA Complete Response Letter Theme Explorer
Duration class: L. Publish: GitHub + Vercel.

GOAL
Build an explorer of FDA's published Complete Response Letters that classifies reasons for non-approval into themes (CMC/manufacturing, clinical/efficacy, safety, labeling, inspection, statistics/study design, other) with auditable rules and a quoted supporting passage, and shows distribution by year, center, and application type.

VERIFIED SOURCE
openFDA transparency/crl https://api.fda.gov/transparency/crl.json — tested 2026-09-03: 458 letters (445 Complete Response, 4 Tentative Approval, others rare); years 2002–2026 concentrated in 2016–2026; fields letter_date, letter_year, letter_type, approval_status (Approved 309 / Unapproved 149, meaning the application's later status), application_number, company_name, approver_center, text (full text, 4–18 thousand characters). VERIFIED LIMIT: the text is OCR output with header noise; text quality must be measured before classification.

METHOD AND LIMITS
- Human taxonomy documented with examples; explainable lexical baseline rules; optional classifier compared with the baseline on a double-coded gold sample (≥60 letters) with precision/recall/F1 and agreement. Every label links to a passage ≤300 characters and a URL.
- The collection is selective (only what FDA published) and does not represent all refusals; never build a score for a company, center, or officer; signatory and company-representative names are dropped from curated data and shown only in aggregate. approval_status is the application's later status, not the letter's outcome.

DELIVERABLES
Fetcher with pagination and snapshot; text-quality scorer; taxonomy browser; classification engine with rule trace; gold set and confusion matrix; trends with denominators (letters available per year); letter page with tagged passages; model card.

ACCEPTANCE TESTS
Every label has a passage and link; no quote longer than 300 characters; separate holdout set; no individual names in curated data (regex test); selection bias stated on the landing page; baseline vs LLM comparison if an LLM is used, disabled by default.
```

---

### 35 — Drug Recall & Enforcement Pattern Lab

**الفكرة ببساطة:** كل سحب دواء من السوق الأمريكي يُسجل علنًا مع سببه وتصنيف خطورته. هذا المشروع يصنف أسباب السحب (تلوث، انحراف مواصفات، تغليف، ثبات) ويعرض توزيعها حسب الخطورة والسنة والشكل الصيدلاني. مناسب لوظائف الجودة والتصنيع، ومناسب لغير المبرمج.

```text
PROJECT 35 — Drug Recall & Enforcement Pattern Lab
Duration class: M. Publish: GitHub + Vercel.

GOAL
Build a lab of US drug recall and enforcement patterns: classify recall reasons into quality themes (contamination, specification deviation, labeling/packaging, stability, CGMP, other) and show distribution by classification (Class I/II/III), year, dosage form, and distribution pattern, quoting the original reason.

VERIFIED SOURCE
openFDA Drug Enforcement https://api.fda.gov/drug/enforcement.json — tested 2026-09-03: 17,899 records; fields classification, status, product_description, reason_for_recall, recall_initiation_date, voluntary_mandated, distribution_pattern, product_quantity, recalling_firm, openfda.* (often empty). openFDA license is public (CC0 per the license link in every response).

METHOD AND LIMITS
- Unit of analysis: recall event × product, with event_id grouping multiple products of one event; never count an event once per product when showing events.
- Documented reason taxonomy, lexical rules first, gold sample of 100 double-coded records.
- No "worst companies" ranking; the firm appears as in the source with no composite score; do not require openfda fields; product_quantity is free text and not summable; no inference about the Saudi market.

DELIVERABLES
Paginated fetcher (API limit 26,000 records; use the full download from download.json when needed); event/product model; reason taxonomy engine with trace; dashboard by class/year/form; event page; gold-set metrics; glossary of FDA Class I/II/III definitions.

ACCEPTANCE TESTS
Event non-duplication test; every classification has a supporting passage; precision/recall documented; no company-level score (test); meta last_updated shown; statement that the data are US-only and do not represent other authorities' recalls.
```

---

### 36 — Pharmacogenomics Guidance Coverage Explorer

**الفكرة ببساطة:** الصيدلة الجينية تدرس كيف تؤثر جينات المريض في استجابته للدواء، وهناك جهة دولية تنشر إرشادات لأزواج «جين–دواء» بمستوى دليل لكل زوج. هذا المشروع يُظهر أي المواد الفعالة المسجلة في السعودية لها إرشادات منشورة وبأي مستوى. مناسب للصيدلة السريرية والطب الدقيق.

```text
PROJECT 36 — Pharmacogenomics Guidance Coverage Explorer
Duration class: M. Publish: GitHub + Vercel.

GOAL
Build an explorer showing which active ingredients registered in the Saudi Human Drug List have published pharmacogenomic guidance (gene–drug pair with an evidence level), the most frequent genes, and common combinations without guidance. A knowledge-coverage tool, not a testing or dosing recommendation tool.

VERIFIED SOURCES
- CPIC API https://api.cpicpgx.org/v1/ — tested 2026-09-03: /guideline (fields name, genes, url, clinpgxid, version) and /pair (fields genesymbol, drugid as "RxNorm:<rxcui>", cpiclevel A/B/C/D, clinpgxlevel, pgxtesting, citations, removed). CPIC content is CC-BY per its site; document in NOTICE.
- RxNav https://lhncbc.nlm.nih.gov/RxNav/APIs/RxNormAPIs.html to resolve RxCUI to names and ingredients.
- Saudi Human Drug List (CHI).

METHOD AND LIMITS
- Map RxCUI → ingredient via RxNav, then match to locally registered ingredients with the rules of Project 3 (exact/normalized/fuzzy-candidate). Show the evidence level as CPIC defines it with a link to the definition; show removed pairs (removed=true) as history, not current.
- No testing recommendation, no dosing, no "should"; guidance coverage is not a judgment of the drug's importance; existence of guidance does not mean a test is available locally. No patient data or population allele frequencies unless from a cited published source.

DELIVERABLES
CPIC ingester with version pinning; RxNorm resolver with cache; match workbench with a 50-item gold set; coverage dashboard by gene, level, and therapeutic class (ATC from the registry if present); drug page linking to the original guideline; Arabic glossary of evidence levels.

ACCEPTANCE TESTS
Every displayed pair has an original guideline.url; removed pairs isolated; a test blocks the words "recommended", "dose", "test the patient" in the UI; ingredient-level vs product-level distinction tested; warning next to every table: "Coverage of published guidance; not a clinical recommendation and not evidence of local test availability."
```

---

### 37 — Drug Identity Resolution Service

**الفكرة ببساطة:** الدواء الواحد قد يُكتب بعدة طرق: اسم تجاري، اسم علمي، ملح مختلف، خطأ إملائي، اسم عربي منقول. هذا المشروع يبني خدمة صغيرة تحوّل أي اسم إلى هوية معيارية بدرجة ثقة وبدائل، ولا تقبل تطابقًا صامتًا عند الشك. مناسب لمسار البيانات والتكامل، وقد يحتاج قدرة برمجية.

```text
PROJECT 37 — Drug Identity Resolution Service
Duration class: M. Publish: GitHub.

GOAL
Build a small service resolving a drug name (brand or generic, variant spelling, Arabic or English) to a canonical identity: active ingredient/salt, RxCUI, UNII, with a confidence score and alternatives, transparent scoring, and a "no silent match at low confidence" rule.

VERIFIED SOURCES
- RxNav RxNorm API https://lhncbc.nlm.nih.gov/RxNav/APIs/RxNormAPIs.html (tested: amoxicillin → RxCUI 723).
- openFDA Drug NDC https://api.fda.gov/drug/ndc.json — tested: 137,637 products; fields generic_name, brand_name, active_ingredients[], openfda.unii.
- openFDA UNII dataset listed in https://api.fda.gov/download.json under other/unii (176,049 records).
- ChEMBL API https://www.ebi.ac.uk/chembl/api/data/ — tested with molecule.json?pref_name__iexact=AMOXICILLIN and atc_class.json?level5=J01CA04. ChEMBL is CC-BY-SA; document the share-alike effect on fixtures.

METHOD AND LIMITS
- Layers: exact (after character/space/salt normalization) → reviewed synonym dictionary (including hand-documented common Arabic transliterations) → fuzzy (rapidfuzz) as candidate with a threshold tuned on a tuning set separate from the test set. Always return identity, score, score reason, and alternatives.
- Name resolution ≠ therapeutic equivalence ≠ strength/form match. Non-US brand names may be absent from references and must return "unresolved", not a guess. No LLM in the resolution path.

DELIVERABLES
Python/TypeScript library + CLI + local REST endpoint (no open published proxy); reference cache with manifest; public benchmark of ≥150 hard names (salts, misspellings, transliterated Arabic names, combinations) with documented results; classified error report.

ACCEPTANCE TESTS
Precision/recall on the benchmark with separate tuning and test sets; "no silent match" test (every result below threshold returns candidate); tests for salts, combinations, leading zeros; rate limiting on external references and offline operation via cache; scoring documented with an explicit formula.
```

---

### 38 — AI-Enabled Medical Device Landscape

**الفكرة ببساطة:** إدارة الغذاء والدواء الأمريكية تنشر قائمة رسمية بكل الأجهزة الطبية المدعومة بالذكاء الاصطناعي التي صرحت بها. هذا المشروع يبني مستكشفًا لهذه القائمة: التوزيع حسب التخصص الطبي ومسار التصريح والسنة، مع ربط كل جهاز بسجله الرسمي وبأي سحب مرتبط به. مناسب لمسار الأجهزة الطبية والصحة الرقمية، وهو من أسهل المشاريع لغير المبرمج.

```text
PROJECT 38 — AI-Enabled Medical Device Landscape
Duration class: S. Publish: GitHub + Vercel.

GOAL
Build an explorer of AI-enabled medical devices authorized in the United States: distribution by medical panel, product code, authorization pathway (510(k)/De Novo/PMA), and year, linking each device to its openFDA device record and to any recall tied to its number.

VERIFIED SOURCES
- FDA AI-Enabled Medical Devices list page https://www.fda.gov/medical-devices/software-medical-device-samd/artificial-intelligence-enabled-medical-devices with official CSV https://www.fda.gov/media/178541/download?attachment — downloaded 2026-09-03: 1,525 data rows; columns Date of Final Decision, Submission Number, Device, Company, Panel (Lead), Primary Product Code; page last updated June 2026. Excel and XML versions also offered.
- openFDA device/510k https://api.fda.gov/device/510k.json (175,879 records), device/recall https://api.fda.gov/device/recall.json (59,049), device/classification (7,088).
NOTE: the FDA page returned 401 to an automated request without browser-like headers, then 200; use an honest User-Agent and one request.

METHOD AND LIMITS
- Join key: Submission Number (K/DEN/P) and product code. Classify the pathway from the number prefix with a documented rule. Link to recalls only via explicit k_numbers/product_code matches; show a recall as a recorded fact, not a judgment.
- FDA's list is not exhaustive of every device with an AI component; US authorization ≠ Saudi registration; no clinical performance assessment; no company ranking.

DELIVERABLES
CSV ingester with snapshot and diff between list releases; joiner to 510k/classification/recall with match status; dashboard by panel/year/pathway; device page with original FDA links; Arabic glossary of authorization pathways and SaMD terms; join coverage report (share of devices whose record was found).

ACCEPTANCE TESTS
Referential tests for the join; no recall linked without an explicit key; list release date shown; diff test between two snapshots; devices without an openFDA record remain "unmatched"; statement that the tool is regulatory-descriptive, not a quality assessment.
```

---

### 39 — WHO Prequalification × Saudi Registry Coverage

**الفكرة ببساطة:** منظمة الصحة العالمية «تؤهل مسبقًا» منتجات دوائية محددة (لعلاج الإيدز والسل والملاريا وغيرها) لتشتريها المنظمات الدولية بثقة. هذا المشروع يقارن هذه المنتجات بالمواد المسجلة في السعودية: ما المؤهل مسبقًا وله منتج محلي، وما ليس له. مناسب لمسار الصحة العالمية والمشتريات، وسهل لغير المبرمج.

```text
PROJECT 39 — WHO Prequalification × Saudi Registry Coverage
Duration class: S. Publish: GitHub + Vercel.

GOAL
Compare WHO-prequalified finished pharmaceutical products (HIV, TB, malaria, reproductive health, and others) with ingredients/forms registered in the Saudi Human Drug List: which prequalified ingredients have locally registered products, which do not, and how prequalified applicants distribute by therapeutic area and basis of listing.

VERIFIED SOURCES
- WHO Prequalified FPPs https://extranet.who.int/prequal/medicines/prequalified/finished-pharmaceutical-products with official CSV export tested 2026-09-03 via /export?page&_format=csv: 130,242 bytes; 649 data rows; columns WHO Reference Number, "INN, Dosage Form and Strength", Product Type, Therapeutic Area, Applicant, Dosage Form, Basis of Listing, Basis of alternative listing, Date of Prequalification.
- Saudi Human Drug List (CHI).
LIMIT: INN, form, and strength are merged into one text column and need a parser with a review queue.

METHOD AND LIMITS
- Parser for the merged column (INN, form, strength, combinations) with tests on 40 hand cases; match by ingredient and form (not strength in phase one) using the rules of Project 3. Distinguish "Basis of Listing" (direct WHO assessment vs alternative listing via stringent authorities such as USFDA/PEPFAR) because they differ.
- Prequalification is not Saudi registration and does not mean the same product is registered; matching is at ingredient level, not product/company; never infer an "access gap" without a definition; no prices.

DELIVERABLES
PQ fetcher with snapshot manifest and schema contract; parser with a parse-success report; match workbench with gold set; coverage dashboard by therapeutic area and basis of listing; list of prequalified ingredients with no locally registered product (titled "for review"); glossary of prequalification terms.

ACCEPTANCE TESTS
Parse-success rate documented with a failure list; no fuzzy auto-accept; the two bases of listing distinguished (test); schema test fails when columns change; fixed warning: "Descriptive registration comparison at ingredient level; not an assessment of quality or availability."
```

---

### 40 — Saudi Market Structure Explorer

**الفكرة ببساطة:** من ملف الأدوية المسجلة العام يمكن فهم بنية السوق: لكل مادة فعالة كم شركة وكم تركيزًا وكم شكلًا وعبوة، وأي الفئات العلاجية يسيطر عليها مصنّع واحد. هذا المشروع يبني خريطة تفاعلية لذلك مع مؤشر تركّز يُسمى بصدق «بديل هيكلي بعدد المنتجات». مناسب لوصول السوق والتخطيط والإمداد.

```text
PROJECT 40 — Saudi Market Structure Explorer
Duration class: M. Publish: GitHub + Vercel.

GOAL
Build an explorer of the structure of the registered Saudi pharmaceutical market from the public list: an SKU map per active ingredient (companies, strengths, forms, packs), a proxy concentration index (Herfindahl on product counts) per ATC class, single-source categories (ingredient/form with one manufacturer), and a "second agent" indicator if that field exists in the release used.

VERIFIED SOURCE
Saudi Human Drug List via CHI/SFDA https://www.chi.gov.sa/Rules/Pages/DamanDrugFormulary.aspx (registration, scientific name, strength, form, route, manufacturer, agent, price, and ATC fields as inspected). No sales sources; no stock sources.

METHOD AND LIMITS
- Canonical product model (Project 3) to decompose ingredient/salt/strength/form/pack. The concentration index is computed on registered product counts per manufacturer within ATC-4 and labeled on every screen "structural proxy on product counts, not market share"; do not use antitrust thresholds (1500/2500), which apply to value shares.
- Single source = (ingredient, form, route) with one manufacturer after manufacturer-name normalization with a review queue (subsidiaries and multiple names of one company are merged only by a documented decision).
- The second-agent indicator is enabled only if the field is proven present; if absent, show "not available in this release", not zero.
- Registration ≠ actual marketing ≠ availability; no "national supply risk" inference; no brand names in evaluative headlines; prices shown only as published list prices.

DELIVERABLES
Registry profiler; manufacturer normalization with dated overrides; interactive SKU matrix per INN (form × strength × manufacturer); concentration dashboard by ATC with drill-down to raw rows; single-source list titled "for review"; diff between two releases; Arabic/English UI.

ACCEPTANCE TESTS
Index recomputed by hand for three classes; a text test blocks "market share" and "monopoly" in the UI; test that the agent indicator is disabled when the field is absent; gold set for manufacturer normalization; file release and date shown on every screen; statement that the analysis is structural, on a public registration list, not market analysis.
```

---

## Before sending any project prompt to the agent

- Did you copy the Master Contract first, in full?
- Is the agent working in an empty folder or a standalone repository?
- Does the primary source still work today? Open it yourself once.
- Does the source contain names of individuals? If so, is the aggregation/removal plan written?
- Can you explain the question, the method, and the limits without the agent?
- Can the result be shown in five minutes?
- Will there be an honest quantitative result to put in a CV after the run?

If the answer to any of the first four is "no", do not start building yet.

---

هذا الدليل مرخص برخصة
CC BY 4.0
(يجوز النقل والتعديل مع الإسناد). مصادر البيانات المشار إليها تبقى تحت شروط جهاتها. مشروع مستقل غير تابع لأي جهة رسمية وغير معتمد منها.

