پروژه اندروید مدیریت هوشمند بندیل

این پروژه یک پوسته Android WebView است که فایل برنامه اصلی را به‌صورت محلی از داخل APK اجرا می‌کند.
برای اجرای برنامه اینترنت لازم نیست و داده‌های localStorage در حافظه برنامه ذخیره می‌شوند.

ساخت APK:
1) Android Studio را نصب کنید.
2) از File > Open پوشه BandilAndroidProject را انتخاب کنید.
3) صبر کنید Gradle Sync و دریافت Android SDK/Gradle تمام شود.
4) از منوی Build > Build Bundle(s) / APK(s) > Build APK(s) را انتخاب کنید.
5) فایل خروجی در app/build/outputs/apk/debug/app-debug.apk ساخته می‌شود.

برای انتشار عمومی، باید APK امضا‌شده (Generate Signed Bundle / APK) بسازید.
حداقل اندروید پشتیبانی‌شده: Android 6.0 (API 23).

نکته: این پوشه سورس پروژه اندروید است، نه فایل APK کامپایل‌شده.
