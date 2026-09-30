# DTC Guide

## 1. DTC categories

- P = Powertrain (engine, transmission, emissions)
- C = Chassis (ABS, brakes, steering)
- B = Body (doors, lighting, cabin electronics)
- U = Network communication / CAN bus / module communication

## 2. How to read DTCs

A code such as `P0420` breaks down as:

- `P` = powertrain
- `04` = emissions system group
- `20` = specific component or fault

Examples:

- `P0100` = air flow system
- `P0300` = random misfire
- `P0420` = catalyst efficiency below threshold
- `C1201` = chassis / ABS issue
- `U0100` = lost communication with ECM

## 3. Typical fault patterns

Most common DTCs include:

- `P0171/P0172` — lean or rich air/fuel condition
- `P0300` — misfire/random misfire
- `P0420` — catalytic converter or oxygen sensor issue
- `P0562` — battery voltage low
- `P0335/P0340` — crankshaft/camshaft sensor faults
- `C1201` — ABS or wheel sensor issues
- `U0100` — CAN communication loss

## 4. Diagnostic workflow

1. Read current and pending codes.
2. Check freeze-frame data.
3. Confirm whether the issue is intermittent or constant.
4. Inspect the component and wiring related to the fault.
5. Perform system verification after repair.

## 5. OEM resources

For exact wiring diagrams, pinouts, and hidden codes, use official manufacturer data:

- Toyota Techstream
- Nissan Consult
- Hyundai GDS
- BMW ISTA / DIS
- Mercedes XENTRY
- Ford IDS / FDRS
- Volkswagen ODIS

## 6. Important warning

A code alone does not always identify the root cause. One symptom can lead to multiple possible faults. Always verify with live data, wiring, and system behavior.

---

## 1. أنواع أكواد الأعطال

- P = نظام الدفع (المحرك، ناقل الحركة، الانبعاثات)
- C = الهيكل (ABS، الفرامل، التوجيه)
- B = جسم السيارة (الأبواب، الإضاءة، الإلكترونيات الداخلية)
- U = الاتصال الشبكي / CAN bus / تبادل البيانات بين الوحدات

## 2. قراءة الأكواد

مثال: `P0420`

- `P` = نظام الدفع
- `04` = مجموعة الانبعاثات
- `20` = مكوّن أو عطل محدد

أمثلة:

- `P0100` = نظام تدفق الهواء
- `P0300` = احتراق متعدد غير منتظم
- `P0420` = كاتاليتيك غير فعال
- `C1201` = مشكلة ABS / فرامل
- `U0100` = فقدان اتصال مع ECU

## 3. الأنماط الشائعة

من أكثر الأكواد شيوعًا:

- `P0171/P0172` — خليط الهواء/الوقود رقيق/مغني
- `P0300` — احتراق متعدد غير منتظم
- `P0420` — كاتاليتيك أو حساس O2
- `P0562` — جهد بطارية منخفض
- `P0335/P0340` — حساسات العمود
- `C1201` — ABS أو حساس العجلات
- `U0100` — فشل اتصال CAN

## 4. سير العمل التشخيصي

1. قراءة الأكواد الحالية والمعلقة.
2. فحص بيانات Freeze Frame.
3. تأكد إن كان العطل مستمرًا أم متقطعًا.
4. فحص المكوّن والسلك الخاص بالخطأ.
5. التحقق من التشغيل بعد الإصلاح.

## 5. مصادر OEM

للحصول على مخططات الأسلاك بدقة، والمشابك، والأكواد المخفية، استخدم بيانات الشركة المصنعة الرسمية:

- Toyota Techstream
- Nissan Consult
- Hyundai GDS
- BMW ISTA / DIS
- Mercedes XENTRY
- Ford IDS / FDRS
- Volkswagen ODIS

## 6. تنبيه مهم

الكود وحده لا يحدد سبب المشكلة دائمًا. قد تعني نفس الأعراض عدة أسباب. تأكد من بيانات الوقت الحقيقي (live data) والأسلاك وسلوك النظام قبل الإصلاح.
