# صحنه — Android WebView (v999999)

پروژه Android Studio با Java برای اجرای فایل HTML برنامه در WebView.

- Package: `ir.sahne.app`
- minSdk: 24
- targetSdk: 34
- Android Gradle Plugin: 8.2.2
- Gradle: 8.6
- JDK: 17

## ساخت APK در GitHub

تمام محتویات این پروژه را در ریشهٔ مخزن GitHub قرار دهید؛ فایل `settings.gradle` و پوشهٔ `app` باید مستقیماً در ریشه باشند. فایل workflow در `.github/workflows/build-apk.yml` قرار دارد و با push به شاخهٔ `main` یا اجرای دستی از بخش Actions فعال می‌شود.

پس از اجرای موفق، در صفحهٔ همان اجرای Actions بخش **Artifacts** فایل `sahne-release-apk` را دانلود کنید.

**توجه:** این workflow نسخهٔ Release بدون امضای اختصاصی ناشر تولید می‌کند. برای انتشار رسمی در فروشگاه، APK باید با کلید امضای خودتان امضا شود.
