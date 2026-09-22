# AI Phone Line

שרת קו טלפוני מבוסס Yemot + Gemini Audio.

המערכת מקבלת הקלטת שמע גולמית מ-Yemot, שולחת את האודיו ישירות ל-Gemini, מקבלת תשובה, ומחזירה אותה להקראה דרך Yemot.

כולל:
- Gemini Audio עם fallback בין מודלים ומפתחות
- שמירת שיחות ב-Supabase כאשר מוגדר
- Dashboard בסיסי
- חיפוש אינטרנט מפורש דרך Gemini
- הגדרת IVR אוטומטית ב-Yemot כאשר YEMOT_API_KEY ו-PUBLIC_BASE_URL מוגדרים
- בחירת קולות Yemot
- סינון תוכן מובנה
