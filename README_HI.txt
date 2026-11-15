मेरा खर्च - Android APK प्रोजेक्ट

यह प्रोजेक्ट आपके दिए हुए pwa.html को Android WebView ऐप के रूप में चलाता है। खर्च और बजट का डेटा फोन के WebView local storage में सेव होता है। कुछ डिज़ाइन लाइब्रेरी (Tailwind, Google Fonts, Font Awesome) इंटरनेट से लोड होती हैं।

APK बनाने के लिए:
1. कंप्यूटर पर Android Studio इंस्टॉल करें।
2. Android Studio में इस पूरे MeraKharch फ़ोल्डर को Open करें।
3. Gradle Sync पूरा होने दें।
4. मेनू में Build > Build Bundle(s) / APK(s) > Build APK(s) चुनें।
5. APK app/build/outputs/apk/debug/app-debug.apk में मिलेगा।

नोट: यह Android Studio source project है, पहले से compiled APK नहीं। इस वातावरण में Android SDK/Gradle build उपलब्ध नहीं है, इसलिए यहां सीधे APK compile नहीं किया गया। रिलीज़/पब्लिक वितरण से पहले ऐप को टेस्ट और sign करें।
