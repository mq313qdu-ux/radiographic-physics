# الفيزياء الشعاعية — QDU

إعداد مقتدى الكناني. تضم المنصة اختبارًا واحدًا بعنوان «مرشحات الفيزياء النظري» وفيه الأسئلة الـ42 بترتيب الملف الأصلي. تظهر الأسئلة والخيارات بالإنكليزية، وتظهر ترجمتها من زر الترجمة. لكل سؤال شرح علمي باللهجة العراقية يظهر بعد الإجابة الخاطئة، ومن زر «لماذا هذه الإجابة؟»، وفي مراجعة النتائج.

تُستخدم علامة الصح في الملف لتحديد مفتاح كل سؤال، ويولّد القالب أرقام الأسئلة وحروف الخيارات تلقائيًا.

## التشغيل والفحص

الموقع ثابت ويقرأ المحتوى من `data/`. لتشغيله محليًا، نفّذ `python -m http.server` من مجلد المستودع. لفحص البيانات شغّل `node tools/validate-data.js data`، ولاختبار المحرك شغّل `node tools/test-core.js`. اختبار الواجهة متاح من مجلد `tools` بالأمر `npm run test:ui`.

## مراجع الشروح

- [طبيعة الموجات الصوتية وطاقتها من OpenStax](https://openstax.org/books/university-physics-volume-1/pages/17-1-sound-waves)
- [موجات البلازما الأيونية الصوتية من جامعة برنستون](https://www.princeton.edu/~idodin/ast553/main.pdf)
- [فيزياء السونار من الوكالة الدولية للطاقة الذرية، الفصل 12](https://www-pub.iaea.org/MTCD/Publications/PDF/Pub1564webNew-74666420.pdf)
- [منهج AIUM لفيزياء المجسات واختيارها](https://doi.org/10.1002/jum.15088)
- [شرح AAPM للمحوّلات الكهروضغطية](https://www.brl.uiuc.edu/Publications/1993/OBrien-RadioGraphics-947-1993.pdf)
- [التصوير بالسونار من FDA](https://www.fda.gov/radiation-emitting-products/medical-imaging/ultrasound-imaging)
- [مبدأ SONAR من NOAA](https://oceanexplorer.noaa.gov/technology/sonar/)
- [الدراسة التجريبية للتأثير الكهروضغطي في العظم](https://doi.org/10.1143/JPSJ.12.1158)
- [قياس استجابة محوّل CMUT تجريبي](https://www.nature.com/articles/s41378-018-0022-5)
