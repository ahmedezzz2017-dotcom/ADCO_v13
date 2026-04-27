ADCO Smart Daily Plan v13 - Android APK GitHub Build FIXED

الإصلاح:
- تم حذف مكتبة appcompat لأنها سببت خطأ Duplicate Kotlin Classes.
- التطبيق الآن يستخدم WebView مباشر بدون AndroidX.
- نفس نسخة v13 محفوظة داخل التطبيق.

طريقة الرفع:
1. ارفع محتويات هذا الفولدر على GitHub بدل الملفات القديمة أو حدث الملفات التالية:
   app/build.gradle
   app/src/main/java/com/adco/smartdailyplan/MainActivity.java
   gradle.properties
2. افتح Actions.
3. شغل Build ADCO v13 APK.
4. بعد النجاح، نزّل Artifact:
   ADCO-v13-Smart-Daily-Plan-APK
