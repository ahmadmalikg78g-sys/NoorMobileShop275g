Noor Mobile Shop Android project

یہ Android Studio project آپ کی HTML ایپ کو Android WebView میں کھولتا ہے۔

APK بنانے کے لیے:
1. کمپیوٹر پر Android Studio انسٹال کریں۔
2. File > Open سے NoorMobileAndroid فولڈر کھولیں۔
3. Gradle sync مکمل ہونے دیں اور Android SDK Platform 35 انسٹال کریں اگر پوچھا جائے۔
4. Build > Build Bundle(s) / APK(s) > Build APK(s) سے ٹیسٹ APK بنائیں۔
5. Play Store کے لیے Build > Generate Signed Bundle / APK منتخب کریں، Android App Bundle منتخب کریں، اور نئی upload key بنائیں۔
6. Signed .aab فائل کو Play Console میں اپ لوڈ کریں۔

اہم:
- یہ project/source ہے، پہلے سے compiled یا signed APK/AAB نہیں۔
- Play Store سے پہلے privacy policy، Data safety، app icon/screenshots اور target SDK requirements چیک کریں۔
- موجودہ HTML ریکارڈ اسی app کی WebView local storage میں محفوظ ہوتے ہیں؛ app uninstall یا app data clear کرنے سے ریکارڈ ضائع ہو سکتے ہیں۔ باقاعدہ Export backup کریں۔
