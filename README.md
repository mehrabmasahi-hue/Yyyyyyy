# صحنه — Android WebView

پروژه Android Studio با Java برای نمایش فایل HTML اصلی برنامه در WebView.

- Package: `ir.sahne.app`
- minSdk: 24
- targetSdk: 34
- Android Gradle Plugin: 8.2.2
- Gradle: 8.6 (در GitHub Actions)
- JDK: 17

فایل HTML برنامه در `app/src/main/assets/index.html` قرار دارد.

## ساخت APK از GitHub

محتوای این پوشه را به ریشهٔ مخزن GitHub با شاخهٔ `main` اضافه کنید. از تب Actions، گردش‌کار **Build Sahne Android APK** را اجرا کنید. پس از موفقیت، فایل `sahne-release-apk` را از بخش Artifacts دریافت کنید.

توجه: APK ساخته‌شده توسط این workflow، Release ولی بدون امضای اختصاصی ناشر است. برای انتشار رسمی، باید کلید امضای خودتان را به‌صورت امن تنظیم کنید.
