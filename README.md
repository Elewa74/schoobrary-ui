# Schoobrary — Digital School Library UI

واجهة البحث والمكتبة التعليمية لمنصة **سكوبراري (Schoobrary)** — تصميم أمامي ثنائي اللغة (عربي RTL / إنجليزي LTR).
Bilingual front-end for the Schoobrary digital school library (search + library UI).

## الصفحات · Pages
| الملف | الوصف |
|------|-------|
| `index.html` | يحوّل تلقائياً إلى صفحة البحث · redirects to search |
| `search.html` | الصفحة الرئيسية — بحث: عام · بالموضوع · بالمنهج · المصادر الإثرائية |
| `library.html` | المكتبة التعليمية — عناصر تعليمية · خطط دروس · مصادر إثرائية |
| `curriculum.html` | نتائج البحث بالمنهج (تابات + فلاتر جانبية + كروت) |
| `topic-material.html` | نتائج البحث بالموضوع (فلاتر هرم الموضوع + كروت) |

## المميزات · Features
- بحث بأربعة أنواع مع نتائج داخل الصفحة (single-page) وأنيميشن collapse.
- ثنائية اللغة كاملة (عربي/إنجليزي) مع تبديل فوري RTL/LTR.
- فلاتر جانبية، كروت محتوى، خطط دروس، ومكتبات إثرائية (Ask Zad · دليل الكتاب العربي · مكتبة الصحافة والتلفزيون).
- هوية موحّدة: خط IBM Plex Sans Arabic + Tajawal، وألوان علامة سكوبراري.

## التشغيل · Run
افتح `index.html` مباشرةً في المتصفح، أو شغّل خادماً ثابتاً:

    npx serve .

---
© 2026 Almotahida Education Group
