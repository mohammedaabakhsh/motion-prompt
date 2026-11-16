<!-- هذا الملف ينشئه tools/build.mjs من meta.json. للتعديل عدّل meta.json وليس هذا الملف. -->

# حركات الموشن جرافيكس

24 اسم · #001–024 · الحزمة `motion` · اللغات: [English](README.md) / [Español](README.es.md) / [日本語](README.ja.md) / [简体中文](README.zh-Hans.md) / [繁體中文](README.zh-Hant.md)

لقيت الاسم؟ قله للذكاء الاصطناعي مثل ما هو. وإذا أضفت كم ثانية، وقد إيش القوة، وإيش اللي يتحرك، تطلع النتيجة أقرب للي في بالك.

![حركات الموشن جرافيكس — مثال](../../assets/preview-motion.gif)

## الدخول والنصوص

| # | الاسم | بالإنجليزي | وش هو | كيف تطلبه من الذكاء الاصطناعي |
|---|---|---|---|---|
| [#001](https://showheyohtaki.github.io/motion-prompt/#001) | **Pop-in** | Pop-in | يظهر بنطّة خفيفة | خلّ الشعار يدخل بـ Pop-in، تقريباً 0.4 ثانية، مع Overshoot خفيف. |
| [#002](https://showheyohtaki.github.io/motion-prompt/#002) | **Stagger (ظهور متتابع)** | Stagger | العناصر تظهر ورا بعض بفارق زمني بسيط | دخّل البطاقات الخمس بـ Stagger، بفارق 0.08 ثانية بين كل وحدة، من اليسار لليمين. |
| [#003](https://showheyohtaki.github.io/motion-prompt/#003) | **Burst (انفجار)** | Burst | خطوط ونقاط تنطلق للخارج لحظة ظهور العنصر | أضف Burst حول القلب لحظة ظهوره: 8 خطوط قصيرة تختفي خلال 0.3 ثانية. |
| [#004](https://showheyohtaki.github.io/motion-prompt/#004) | **Line draw (رسم الخط)** | Line draw | خط يمتد كأنه ينرسم قدامك | اعرض خط الرسم البياني بـ Line draw من اليسار، خلال 1.2 ثانية. |
| [#005](https://showheyohtaki.github.io/motion-prompt/#005) | **Mask reveal** | Mask reveal | النص يطلع من ورا حافة مخفية | دخّل العنوان بـ Mask reveal من تحت، 0.6 ثانية، وكل سطر يتأخر شوي عن اللي قبله. |
| [#006](https://showheyohtaki.github.io/motion-prompt/#006) | **تأثير الآلة الكاتبة (Typewriter)** | Typewriter | النص يظهر حرف حرف كأنه ينكتب | اعرض هذي الجملة بتأثير الآلة الكاتبة، 0.05 ثانية لكل حرف، مع مؤشر كتابة في النهاية. |
| [#007](https://showheyohtaki.github.io/motion-prompt/#007) | **العدّاد (Count-up)** | Count-up | رقم يزيد بسرعة لين يوصل قيمته النهائية | خلّ الرقم يعدّ من 0 إلى 1,280 خلال 1.5 ثانية، ويبطئ في النهاية. |
| [#008](https://showheyohtaki.github.io/motion-prompt/#008) | **Kinetic typography (الطباعة الحركية)** | Kinetic typography | الكلمات تتحرك وتكبر وتدور مع الكلام | حوّل هذا التعليق الصوتي إلى Kinetic typography: كبّر الكلمات المهمة وخلّها تنزل على الإيقاع. |

## لمسات الحركة

| # | الاسم | بالإنجليزي | وش هو | كيف تطلبه من الذكاء الاصطناعي |
|---|---|---|---|---|
| [#009](https://showheyohtaki.github.io/motion-prompt/#009) | **Easing** | Easing | الحركة تتسارع وتتباطأ بدل ما تمشي بسرعة وحدة | أضف Easing لهذي الحركة: ease-out، تبطئ وهي توقف. |
| [#010](https://showheyohtaki.github.io/motion-prompt/#010) | **Overshoot** | Overshoot | يتعدّى الهدف شوي وبعدين يرجع ويثبت | أعطِ إبرة المؤشر Overshoot: تتعدّى الهدف بحوالي 10% وترجع. |
| [#011](https://showheyohtaki.github.io/motion-prompt/#011) | **Squash & stretch (الانضغاط والتمدد)** | Squash & stretch | ينضغط ويتمدد عشان يبان مرن | أضف Squash & stretch لما تنزل الكورة على الأرض، وخلّ الانضغاط خفيف. |
| [#012](https://showheyohtaki.github.io/motion-prompt/#012) | **Morph (تحوّل الشكل)** | Shape morph | شكل يتحول لشكل ثاني بسلاسة | حوّل الدائرة إلى نجمة بـ Morph خلال 0.8 ثانية، واللون يتغير من الأزرق للأصفر أثناء التحول. |
| [#013](https://showheyohtaki.github.io/motion-prompt/#013) | **Liquid motion (حركة سائلة)** | Liquid motion | الأشكال تتحرك وتندمج كأنها سائل | خلّ دخول الشعار Liquid motion: قطرات تتجمع وتكوّن الشكل. |
| [#014](https://showheyohtaki.github.io/motion-prompt/#014) | **Motion trail (أثر الحركة)** | Motion trail | أثر يتلاشى يلحق العنصر المتحرك | أضف Motion trail للدائرة الطايرة: خمس نسخ وراها تتلاشى. |
| [#015](https://showheyohtaki.github.io/motion-prompt/#015) | **Particles (جزيئات)** | Particles | قطع صغيرة كثيرة تنطلق وتتناثر | لحظة النجاح، أطلق Particles من تحت لفوق: أربعة ألوان، وكلها تطيح خلال 1.5 ثانية. |
| [#016](https://showheyohtaki.github.io/motion-prompt/#016) | **Parallax (بارالاكس)** | Parallax | الطبقات القريبة والبعيدة تتحرك بسرعات مختلفة عشان يبان العمق | قسّم هذا المنظر لثلاث طبقات وحرّكها بـ Parallax، والقريبة أسرع. |

## الانتقالات واللقطات اللافتة

| # | الاسم | بالإنجليزي | وش هو | كيف تطلبه من الذكاء الاصطناعي |
|---|---|---|---|---|
| [#017](https://showheyohtaki.github.io/motion-prompt/#017) | **Mask transition** | Mask transition | المشهد الجاي يظهر داخل شكل يكبر | انتقل للمشهد الجاي بـ Mask transition: دائرة تكبر من المنتصف خلال 0.7 ثانية. |
| [#018](https://showheyohtaki.github.io/motion-prompt/#018) | **Shape transition** | Shape transition | أشكال تغطي الشاشة وتكشف المشهد الجاي | غيّر المشهد بـ Shape transition: أربعة أشرطة ملونة مائلة تمسح الشاشة من اليسار. |
| [#019](https://showheyohtaki.github.io/motion-prompt/#019) | **Liquid transition (انتقال سائل)** | Liquid transition | سائل ينساب ويستبدل المشهد | استخدم Liquid transition هنا: حبر أزرق يسيل من فوق ويعبّي الإطار. |
| [#020](https://showheyohtaki.github.io/motion-prompt/#020) | **Zoom through** | Zoom through | زوم داخل عنصر والعبور منه للمشهد الجاي | سوّ Zoom through من فتحة حرف "O" في الشعار للمشهد الجاي، 0.6 ثانية، مع تسارع. |
| [#021](https://showheyohtaki.github.io/motion-prompt/#021) | **Flip (قلب)** | Flip | ينقلب مثل البطاقة ويوريك الوجه الثاني | اقلب بطاقة الأسعار بـ Flip عشان تبان التفاصيل في ظهرها، خلال 0.5 ثانية. |
| [#022](https://showheyohtaki.github.io/motion-prompt/#022) | **Light sweep (لمعة ضوء)** | Light sweep | شريط ضوء يعبر على السطح | بعد ما يثبت الشعار، أضف Light sweep وحدة من فوق يسار لتحت يمين، خفيفة. |
| [#023](https://showheyohtaki.github.io/motion-prompt/#023) | **Glitch (تشويش)** | Glitch | الصورة تتكسر كأن فيها عطل | أضف Glitch سريع على العنوان: 0.3 ثانية، فصل ألوان خفيف، وبدون وميض. |
| [#024](https://showheyohtaki.github.io/motion-prompt/#024) | **Impact shake (اهتزاز الارتطام)** | Impact shake | الإطار كله يهتز لما ينزل شيء بقوة | أضف Impact shake لما ينزل العنوان الرئيسي، ويهدأ خلال 0.4 ثانية. |

كل رقم يفتح المثال المتحرك في المعرض. التوقيتات وقيم الـ Easing والكود المرجعي لكل اسم: `api/v1/en/e/<id>.txt` ([#001](../../api/v1/en/e/001.txt)).

[كل الحزم](../README.md)
