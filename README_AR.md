# ELIT FITNESS CLUB — Android

هذا مشروع Android كامل لتغليف نسخة ELIT FITNESS CLUB الحالية كتطبيق Android يعمل محليًا بدون إنترنت.

## المتطلبات
- Android Studio حديث.
- Android SDK Platform 35.
- JDK 17 أو أحدث.

## فتح المشروع
1. فك ضغط المشروع.
2. افتح مجلد `ELIT_FITNESS_CLUB_Android` في Android Studio.
3. وافق على تثبيت/تنزيل Android SDK 35 وAndroid Gradle Plugin إذا طلب Android Studio ذلك.
4. من القائمة: **Build → Build APK(s)**.
5. ستجد ملف APK عادةً في:
   `app/build/outputs/apk/debug/app-debug.apk`

## ملاحظات
- التطبيق يستخدم HTML المحلي الموجود في `app/src/main/assets/index.html`.
- البيانات المخزنة في التطبيق تعتمد على Local Storage، ولا تحتاج اتصالًا بالإنترنت.
- اسم التطبيق: ELIT FITNESS CLUB.
- Package ID: `com.elitfitnessclub.app`.
- الإصدار الأول: 1.0 (versionCode 1).
