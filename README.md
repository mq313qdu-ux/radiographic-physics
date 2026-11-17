# الفيزياء الشعاعية — QDU

إعداد مقتدى الكناني. تضم المنصة «مرشحات الفيزياء النظري» وفيها 42 سؤالًا، وقسم «اسئلة العملي» وفيه 84 سؤالًا في ثلاث محاضرات. تظهر الأسئلة والخيارات بالإنكليزية، وتظهر ترجمتها من زر الترجمة. لكل سؤال شرح علمي باللهجة العراقية يظهر بعد الإجابة الخاطئة، ومن زر «لماذا هذه الإجابة؟»، وفي مراجعة النتائج.

تُستخدم علامة الصح في الملفين لتحديد مفتاح كل سؤال، ويولّد القالب أرقام الأسئلة وحروف الخيارات تلقائيًا. ينتقل الترقيم في ملف العملي من 78 إلى 80، وتحتفظ معرّفات البيانات بالترقيم الأصلي للمراجعة.

## التشغيل والفحص

الموقع ثابت ويقرأ المحتوى من `data/`. لتشغيله محليًا، نفّذ `python -m http.server` من مجلد المستودع. لفحص البيانات شغّل `node tools/validate-data.js data`، ولاختبار المحرك شغّل `node tools/test-core.js`. اختبار الواجهة متاح من مجلد `tools` بالأمر `npm run test:ui`.

## مراجع الشروح

- [طبيعة الموجات الصوتية وطاقتها من OpenStax](https://openstax.org/books/university-physics-volume-1/pages/17-1-sound-waves)
- [شدة الصوت والموجات الواقفة من OpenStax](https://openstax.org/books/university-physics-volume-1/pages/17-4-normal-modes-of-a-standing-sound-wave)
- [قياس شدة الصوت من تغيّر الضغط من OpenStax](https://openstax.org/books/university-physics-volume-1/pages/17-3-sound-intensity)
- [دليل التجارب المختبرية لامتصاص الصوت في الهواء من PHYWE](https://ftp.uoh.edu.iq/admin/ebooks/12738-phywe-tess-phy-lep-en.pdf)
- [دليل التجربة المختبرية للموجات فوق الصوتية الواقفة من PHYWE](https://yunus.hacettepe.edu.tr/~tatar/dersler/fiz301/FIZ-301/Fiz301%20Kuantum_Lab/PHYWE%20EXP/LEP/LEP1513_00.pdf)
- [دراسة امتصاص الموجات فوق الصوتية في الهواء](https://www.ultragarsas.ktu.lt/index.php/USnd/article/view/8278)
- [موجات البلازما الأيونية الصوتية من جامعة برنستون](https://www.princeton.edu/~idodin/ast553/main.pdf)
- [فيزياء السونار من الوكالة الدولية للطاقة الذرية، الفصل 12](https://www-pub.iaea.org/MTCD/Publications/PDF/Pub1564webNew-74666420.pdf)
- [منهج AIUM لفيزياء المجسات واختيارها](https://doi.org/10.1002/jum.15088)
- [شرح AAPM للمحوّلات الكهروضغطية](https://www.brl.uiuc.edu/Publications/1993/OBrien-RadioGraphics-947-1993.pdf)
- [التصوير بالسونار من FDA](https://www.fda.gov/radiation-emitting-products/medical-imaging/ultrasound-imaging)
- [التحضير لفحوص السونار من RadiologyInfo](https://www.radiologyinfo.org/en/info/how-to-prepare-for-us-exam)
- [نشر الأخوين كوري عن التأثير الكهروضغطي عام 1880](https://www.persee.fr/doc/bulmi_0150-9640_1880_num_3_4_1564)
- [مبدأ SONAR من NOAA](https://oceanexplorer.noaa.gov/technology/sonar/)
- [الدراسة التجريبية للتأثير الكهروضغطي في العظم](https://doi.org/10.1143/JPSJ.12.1158)
- [قياس استجابة محوّل CMUT تجريبي](https://www.nature.com/articles/s41378-018-0022-5)
