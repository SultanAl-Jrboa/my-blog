---
title: 'مستويات إنترنت الأشياء'
description: ''
pubDate: 'Nov 03 2024'
heroImage: '/IoT-Levels-pic/IoT-Levels-H.png'
---

#### قراءة مقال "مكونات انترنت الاشياء" سيساعدك على فهم مستويات انترنت الاشياء
المستوى الاول - Level-1 : 
يحتوي نظام انترنت الاشياء في المستوى الاول على " عقدة او جهاز " واحد يقوم بالاستشعار او التشغيل, وتخزين البيانات., واجراء 
التحليل

![This is a placeholder image description](/IoT-Levels-pic/Level-1.jpg)

يعتبر نظام انترنت الاشياء من المستوى الاول مناسب جداً للنماذج الاولية ونماذج الحلول منخفضة التكلفة والبسيطة بدون تعقيد, بحيث لا تكون البيانات كبيرة ويمكن تحليلها ببساطة.

المستوى الثاني - Level-2 : 
يحتوي نظام انترنت الاشياء في المستوى الثاني على عقدة واحدة تقوم بالاستشعار و/او التشغيل والتحليل المحلي
في المستوى الثاني يتم تخزين البيانات في كلاود وغالباً يكون التطبيق يعتمد على الكلاود

![This is a placeholder image description](/IoT-Levels-pic/Level-2.jpg)

تعتبر انظمة انترنت الاشياء من المستوى الثاني مناسبة للحلول التي تكون فيها البيانات كبيرة نسبياً ومع ذلك فأن متطلب التحليل ليس اساسي وصعب انما يمكنك القيام به بنفسك 

المستوى الثالث - Level-3 : 
يحتوي المستوى الثالث على عقدة واحدة. البيانات تُخزن ويتم تحليلها في الكلاود والتطبيق بالكامل يكون مبني على الكلاود
غالباً يستعمل المستوى الثالث في الحلول التي تحتاج الى بيانات ضخمة نسبياً ومتطلبات تحليل عالية


![This is a placeholder image description](/IoT-Levels-pic/Level-3.jpg)

المستوى الرابع - Level-4 : 
يحتوي المستوى الرابع على عدة عقد تقوم باجراء التحليل محلياً ويتم تخزين البيانات في الكلاود وايضاً تطبيقها في السحابة

يحتوي المستوى الرابع على عقد مراقبة محلية مبنيه على الكلاود يمكنها الاشتراك في المعلومات التي يتم جمعها من مستشعرات انترنت الاشياء في السحابة

يُعتبر نظام انترنت الاشياء من المستوى الرابع مناسب للحلول التي تتطلب عقد متعددة وتكون البيانات كبيرة ومتطلبات التحليل مكثفه

![This is a placeholder image description](/IoT-Levels-pic/Level-4.jpg)

المستوى الخامس - Level-5 : 
المستوى الخامس يحتوي على عدة عقد وعقدة واحدة هي المتحكمة بينهم

العقد النهائية هي التي تقوم بالاستشعار او التشغيل

العقدة المتحكمة هي التي تجمع البيانات من العقد النهائية وترسلها الى الكلاود

المستوى الخامس مناسب للحلول التي تعتمد على حساسات الوايرليست "Wireless sensor" حيث تكون البيانات كبيرة ولها متطلبات تحليل مكثفة

![This is a placeholder image description](/IoT-Levels-pic/Level-5.jpg)

المستوى السادس - Level-6 : 
يحتوي نظام انترنت الاشياء من المستوى السادس على عدة مستقله تشتعر و/او تشغل وترسل البيانات الى الكلاود

يتم تخزين البيانات في الكلاود وايضاً البرنامج

يتم تحليل البيانات وتخزينها مباشرة على الكلاود

وحدة التحكم الاساسية على علم بجميع العقد وهي التي تتحكم بهم وترسل الاوامر

![This is a placeholder image description](/IoT-Levels-pic/Level-6.jpg)

هذا الشرح لتبسيط عملية فهم المخطط للمستوى السادس, ويمكنك فهم باقي المخططات عند فهم هذا المخطط:


### الجزء المحلي (Local)
1. **Device**: وهي الأجهزة الموجودة في البيئة المحلية، مثل المستشعرات أو المحركات. هذه الأجهزة تقوم بجمع البيانات أو تنفيذ عمليات محددة بناءً على أوامر معينة.
  
2. **Resource**: يمثل الموارد المرتبطة بالأجهزة، حيث يتم التواصل مع الأجهزة والوصول إلى بياناتها أو التحكم فيها. 

3. **Controller Service**: خدمة تحكم تتواصل مع الموارد وتدير الأجهزة المرتبطة بها. هذه الخدمة توفر الوسائل اللازمة للتعامل مع الأجهزة وتنفيذ عمليات التحكم.

4. **Centralized Controller**: وحدة تحكم مركزية تجمع البيانات من خدمات التحكم المختلفة. يتمثل دورها في التنسيق بين الأجهزة والموارد المختلفة وتوحيد البيانات لإرسالها إلى السحابة.

5. **Observer Node**: وحدة مراقبة تقوم بمراقبة الأنظمة وتقديم تقارير حول الأداء أو التحديثات الضرورية. 

### الجزء السحابي (Cloud)
1. **REST/WebSocket Services**: خدمات الاتصال مثل REST أو WebSocket تُستخدم لنقل البيانات بين الجزء المحلي والسحابة. هذه الطبقة تمثل البوابة بين الطرفين.

2. **Database**: قاعدة البيانات التي تخزن كل البيانات الواردة من الأنظمة المحلية. يتم استخدامها لحفظ البيانات لفترات طويلة والرجوع إليها عند الحاجة.

3. **Analytics Component (IoT Intelligence)**: مكون التحليلات الذي يقوم بمعالجة البيانات باستخدام تقنيات الذكاء الاصطناعي وتحليلها لإعطاء رؤى أو توقعات. هذا المكون ضروري لاستخلاص الفائدة من البيانات الضخمة المخزنة.

4. **App**: التطبيق الذي يتفاعل معه المستخدم، حيث يمكنه رؤية النتائج والتقارير والتحكم ببعض الإعدادات. التطبيق يمكن أن يكون على شكل واجهة مستخدم بسيطة أو تطبيق معقد يقدم حلول متقدمة.

5. **Observer Node**: كما في الجزء المحلي، هنا نجد وحدة مراقبة في السحابة، تتابع أداء النظام وتعمل كواجهة للإشعارات أو التقارير المتعلقة بالسحابة.

### عملية الاتصال والتكامل بين الجزئين
- يتم التواصل بين الجزئين عبر **خدمات REST/WebSocket**. حيث يقوم **Centralized Controller** في الجزء المحلي بإرسال البيانات إلى السحابة عبر هذه الخدمات.
- يتم حفظ البيانات في قاعدة البيانات السحابية، ومن ثم معالجتها باستخدام مكون التحليلات.
- بعد التحليل، تُرسل النتائج إلى **App** ليتم عرضها للمستخدم.