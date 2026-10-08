# 📊 Smart Budget - Bilingual Budget Spreadsheet 

<div align="center">
  <img src="https://img.shields.io/badge/Budget-Finance-green" alt="Budget">
  <img src="https://img.shields.io/badge/Google%20Sheets-Data%20Analysis-blue" alt="Google Sheets">
  <h3>ميزانية ذكية ثنائية اللغة | Arabic & English Budget Tracker</h3>
</div>

---

## 🚀 Get Your Copy / احصلي على نسختك

لضمان حماية الملف الأصلي والسماح لكِ بتجربة المعادلات والبيانات بحرية، يرجى عمل نسخة من الملف:

### 🔗 [اضغطي هنا لعمل نسخة من الملف (Make a Copy)](https://docs.google.com/spreadsheets/d/1_VMCA1oeEKZ4k0-0z02jqvpKMV4mPPgu-3dMSQp74OM/copy)

*(ملاحظة: عند فتح الرابط، سيطلب منك Google Sheets عمل "Make a copy" لبدء الاستخدام).*

---

## ✨ Features / المميزات

| English | العربية |
|---------|---------|
| ✅ Bilingual Support (Arabic/English) | ✅ دعم اللغتين (عربي/إنجليزي) |
| ✅ Automatic Calculations & Formulas | ✅ حسابات ومعادلات تلقائية |
| ✅ Dynamic Monthly & Annual Views | ✅ عروض شهرية وسنوية ديناميكية |
| ✅ Interactive Charts & Dashboards | ✅ رسوم بيانية ولوحات معلومات تفاعلية |
| ✅ Data Standardization (No Duplicates) | ✅ توحيد البيانات (بدون تكرار في الفئات) |

---

## 🛠️ Skills & Tools Used / المهارات والأدوات المستخدمة
- Google Sheets (Advanced Formulas: SUMIFS, IFS, OR, EOMONTH, DATE, FILTER)
- Data Cleaning & Standardization (توحيد وتنظيف البيانات لضمان دقة التقارير)
- Data Visualization (تصور البيانات وربطها ديناميكياً باللوحات التفاعلية)
- Logical Data Flow (فصل خلايا الإدخال، والحساب، والمخرجات لتجنب الأخطاء الدائرية)

---

## 📸 Dashboard Preview / معاينة لوحة المعلومات
*(استبدلي الرابط أدناه برابط صورة حقيقية للداشبورد الخاص بكِ لجعل الملف أكثر جاذبية)*
![Dashboard Preview](https://via.placeholder.com/800x400.png?text=Smart+Budget+Dashboard+Screenshot)

---

## 🧠 Challenges & Solutions / التحديات والحلول
أثناء تطوير هذا المشروع، واجهت تحديات تحليلية قمت بحلها لتعزيز كفاءة الملف:
1. تكرار الفئات في الرسوم البيانية: 
   - *التحدي:* إدخال نفس الفئة بلغتين (مثال: "Food" و "طعام") كان يسبب ظهورها كشرائح منفصلة ومكررة.
   - *الحل:* إنشاء عمود "الفئة الموحدة" (Standard Category) باستخدام دالة IFS و OR لربط جميع المدخلات المتشابهة بمسمى واحد موحد قبل تغذية الرسم البياني.
2. أخطاء المرجع (#REF!) والاعتمادية الدائرية: 
   - *التحدي:* حدوث أخطاء عند حساب صافي الادخار بسبب الإشارة إلى الخلية نفسها أو نطاقات محذوفة.
   - *الحل:* مراجعة شاملة لهيكلية الملف وفصل خلايا الإدخال، والحساب، والمخرجات لضمان تدفق بيانات منطقي (Logical Data Flow).
3. تصفية البيانات حسب التاريخ ديناميكياً:
   - *الحل:* استخدام SUMIFS مقترنة بـ DATE و EOMONTH لضمان أن لوحة المعلومات تعرض فقط بيانات الشهر/السنة المحددة في القائمة المنسدلة.

---

## 🔮 Future Enhancements / تحسينات مستقبلية
- ربط الملف بقاعدة بيانات خارجية (مثل MySQL أو PostgreSQL) باستخدام Python.
- بناء نسخة متقدمة من لوحة المعلومات باستخدام Power BI أو Tableau.
- إضافة Google Apps Script لإرسال تقارير شهرية تلقائية عبر البريد الإلكتروني.

---
Developed by: Reenad | [LinkedIn](رابط-لينكد-إن-هنا) | [GitHub](رابط-جيت-هوب-هنا)
