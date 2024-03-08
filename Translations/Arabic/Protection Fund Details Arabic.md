# مقترح صندوق الحماية لمورفيوس

## مقدمة

يخصص الورقة البيضاء لمورفيوس 4٪ من جميع انبعاثات مور لغرض "صندوق الحماية" ويفوض مزودي الرموز بالعمل كأوراكل في حالة حاجة موارده.

أنواع الإجراءات:

- دفع مكافأة الثغرات لتجنب الهجمات.
- دفع التدقيقات قبل نشر عقود ذكية جديدة.
- توقف عقود ذكية في حالة هجوم جارٍ.
- الإشارة والآلية للدفع بعد الهجوم.
- خطة في حالة حدوث حدث خسارة كبير (سيناريو الشوكة الصعبة)

## الحالات المحددة مسبقًا التي تشغل دفعات صغيرة

قبل أن تذهب العقود الذكية مباشرة على شبكة Ethereum تم تحديد الشروط الذي تحتها سيدفع صندوق الحماية MOR أو stETH.

## أنواع المدفوعات:

1. الثغرات التي تم اكتشافها والتي تم الإبلاغ عنها بشكل مسؤول لمطوري Morpheus Capital، Code، Compute، Community أو صندوق الحماية الذكية.
2. دفع التدقيقات قبل نشر عقود ذكية جديدة على شبكة Morpheus.
3. خسائر المستخدمين من MOR أو stETH في حالة استغلال عقد ذكي Morpheus.
4. جعل مزودي الخدمة الذين لم يتلقوا انبعاثات MOR في حالة فشل عقد ذكي Morpheus بالكامل.

يجب أن تكون مبالغ المدفوعات من الصندوق الوقائي متناسبة مع الثغرة أو الخسارة أو خطأ الانبعاث.

## شروط التوقف للعقود الذكية

قبل أن يتمكنوا من معرفة مدى الأضرار، يجب أن تكون هناك شروط تؤدي إلى توقف العقود الذكية في حالة هجوم جارٍ.

## الإشارة والآلية للدفع

سيشارك مزودو الرموز في الإشارة عندما يجب تشغيل دفعة. أولاً، سيتم تفصيل الحادث ونشره في مستودع GitHub للعقد الذكي المتضرر. بما في ذلك قائمة العناوين المتضررة ومبالغ MOR و / أو stETH.

إذا قامت غالبية مزودي الرموز (كما يقاس بوزن رموز MOR التي يمتلكونها) الذين شاركوا في فترة الإشارة (لا تزيد عن 7 أيام) بالتحقق من تقرير الصحة كصحيح، فسيتم تشغيل دفعة.

بمجرد تشغيل الدفعة، سيقوم البرنامج بإرسال رسالة إلى المطورين للمصادقة على دفعة إلى العناوين المتضررة بالمبالغ المحددة.

## خطة في حالة حدوث حدث خسارة كبير

يتم تعريف حدث الخسارة الكبيرة على أنه حدث يتجاوز فيه خسائر MOR الموارد الإجمالية لصندوق الحماية. في هذه الحالة، بدلاً من إجراء دفعة من MOR، يجب على مزودي الرموز نشر عقود ذكية جديدة وتصحيح أرصدة MOR المتأثرة يدويًا. سيؤدي هذا بشكل فعال إلى تسبب الشوكة الصعبة في الرموز / أرصدة MOR وسيتعين على جميع مزودي الخدمات وحاملي الرموز ومزودي البنية التحتية الأخرى تحديث كودهم إلى العقود الذكية الجديدة.

في حالة فقدان stETH في حدث خسارة كبير، يجب على صندوق الحماية دفع بأقصى قدر ممكن بنسبة مئوية لمبلغ خسائر كل شخص.

## الختام

الثغرات والأخطاء في البرمجيات هي واقع وتميز التاريخ من انقسامات الشوكة الصعبة غير المقصودة ل