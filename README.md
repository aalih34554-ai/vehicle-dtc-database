# Vehicle DTC Database

This repository provides a structured automotive diagnostic database for common DTC codes, manufacturer-specific codes, and model/year references for vehicles from 2014 to 2026.

## Contents

- `data/common_dtc.csv` — common OBD-II / general DTCs used across many makes and models
- `data/manufacturer_codes.csv` — manufacturer-level code references for Toyota, Nissan, Hyundai, BMW, Mercedes, Ford, and Volkswagen
- `data/vehicle_dtc_master.csv` — model-specific examples with year ranges and notes
- `docs/dtc-guide.md` — explanation of DTC categories, how to read them, and diagnostic workflow
- `docs/wiring-diagram-notes.md` — notes on wiring diagrams and OEM resources
- `README.md` — project overview and usage guide

## Scope

This database is intended as a practical reference for:

- OBD-II / generic DTCs
- Manufacturer-specific codes
- Common fault patterns by brand and model
- Typical root causes and guidance
- Year-based references for 2014-2026 vehicles

Important note:

- DTC codes vary by vehicle brand, model, engine, transmission, and year.
- Some codes are generic and shared across many cars, while others are manufacturer-specific or model-specific.
- Wiring diagrams and service schematics are usually available only via OEM service information, scan tools, or factory service documentation.

## Recommended use

1. Identify the vehicle brand and model.
2. Check if the DTC is generic or manufacturer-specific.
3. Validate the code with scan tool freeze-frame data.
4. Inspect the component or circuit related to the fault.
5. Use OEM repair information for exact wiring and pinout details.

## Project structure

```text
vehicle-dtc-database/
├── README.md
├── data/
│   ├── common_dtc.csv
│   ├── manufacturer_codes.csv
│   └── vehicle_dtc_master.csv
├── docs/
│   ├── dtc-guide.md
│   └── wiring-diagram-notes.md
└── LICENSE
```

## Example fields

The CSV files include these categories:

- brand
- model
- years
- code
- category
- meaning_ar
- meaning_en
- common_cause
- fix
- notes

## Languages

This project is available in:

- Arabic
- English

## Disclaimer

This repository is for educational and reference purposes only. Always confirm diagnosis with the vehicle’s official repair procedures and manufacturer service information before repairs.

## License

This project is released under an open project-style license unless otherwise stated.

## Contribution

Contributions are welcome. You can add:

- more model-specific DTCs
- more manufacturer code references
- newer VIN/platform-specific codes
- wiring diagram metadata
- OEM tool references

---

نظرة عامة:

هذا المستودع يوفر قاعدة بيانات منظمة لأكواد الأعطال (DTCs) الشائعة، وأكواد الشركات المصنعة، ومراجع الطراز والسنة للسيارات من 2014 إلى 2026.

## المحتويات

- `data/common_dtc.csv` — أكواد عالمية / OBD-II شائعة في كثير من السيارات
- `data/manufacturer_codes.csv` — أكواد خاصة بالشركات المصنعة
- `data/vehicle_dtc_master.csv` — أمثلة لأكواد حسب الطراز والسنة
- `docs/dtc-guide.md` — شرح لفئات الأكواد وكيفية قراءتها
- `docs/wiring-diagram-notes.md` — ملاحظات حول مخططات الدوائر ومصادر OEM
- `README.md` — دليل المشروع

## النطاق

هذا المشروع موجه للفحص التشخيصي في:

- أكواد OBD-II العامة
- أكواد الشركات المصنعة
- أعطال شائعة حسب الماركة والطراز
- أسباب شائعة للحالة الوظيفية
- مراجع السنين من 2014 إلى 2026

ملاحظة مهمة:

- تتغير الأكواد حسب الشركة والطراز والمحرك ونوع ناقل الحركة والسنة.
- بعض الأكواد عامة وتُستخدم في كثير من السيارات، والبعض الآخر خاص بالشركة المصنعة أو الطراز.
- مخططات الأسلاك ومعلومات الخدمة غالباً تتوفر عبر بيانات OEM أو برامج التشخيص الرسمية.

## الاستخدام الموصى به

1. تحديد الشركة والطراز.
2. التحقق من أن الكود عام أم خاص بالشركة المصنعة.
3. التأكد من البيانات في Freeze Frame أو بيانات المسح.
4. فحص المكوّن أو الدارة ذات العلاقة.
5. استخدام معلومات الخدمة الرسمية قبل الإصلاح النهائي.

## ملف المشروع

```text
vehicle-dtc-database/
├── README.md
├── data/
│   ├── common_dtc.csv
│   ├── manufacturer_codes.csv
│   └── vehicle_dtc_master.csv
├── docs/
│   ├── dtc-guide.md
│   └── wiring-diagram-notes.md
└── LICENSE
```

## التنبيه

هذا المستودع للأغراض التعليمية والمرجعية فقط. يُرجى التأكيد على التشخيص عبر إجراءات الصيانة الرسمية للمصنع قبل أي إصلاح.

## المساهمة

نرحب بالمساهمات في:

- أكواد أكثر تفصيلاً حسب الطراز
- أكواد إضافية حسب الشركة
- تزويد معلومات خاصة بالسنوات الجديدة
- مخططات وبيانات تبادل المكونات
- مراجع OEM والبرامج الرسمية

