# صفحة روابط تطبيق خريج

صفحة هبوط ثابتة (Static Landing) تحتوي روابط التحميل للتطبيق والمتابعة على إنستغرام وتيليجرام.

## المميزات
- تصميم عربي RTL
- تدرجات وخلفية تفاعلية
- أزرار متاجر + سوشيال
- تأثيرات حركة بسيطة (Float / Sheen / Ripple)

## تشغيل محلي
افتح `index.html` مباشرة أو استخدم خادم بسيط:
```powershell
cd "E:\Programing\A wep app\graduate_profile"
python -m http.server 5500
```
ثم زر: http://localhost:5500/

## النشر على GitHub Pages
1. أنشئ مستودع GitHub (مثال: `graduate-profile`).
2. داخل مجلد المشروع شغّل:
```powershell
git init
git add .
git commit -m "Initial"
git branch -M main
git remote add origin https://github.com/USER/graduate-profile.git
git push -u origin main
```
استبدل USER باسم حسابك.
3. من Settings > Pages: اختر `Deploy from a branch` ثم الفرع `main` والمجلد `/root` (أو /). احفظ.
4. الرابط سيصبح: `https://USER.github.io/graduate-profile/`.
5. عدل في `index.html` الوسوم التي تحتوي `USER` و `REPO` (وسم og:image).
6. كل تحديث لاحق:
```powershell
git add .
git commit -m "Update"
git push
```

## نطاق مخصص (اختياري)
ضع اسم نطاقك في ملف `CNAME` (سطر واحد) ثم اربط سجلات DNS نحو GitHub Pages.

## تخصيص
- استبدل `images/logo.png` بشعارك.
- يمكن وضع صورة خلفية `images/bg.jpg` لتحل فوق التدرجات.
- لتغيير الألوان عدل متغيرات :root في `styles.css`.

## الرخصة
الاستخدام خاص بالمشروع (يمكنك التعديل بحرية داخل مؤسستك).
