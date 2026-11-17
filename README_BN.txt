ABIR FOOTBALL 3D — Android Studio প্রজেক্ট

এই প্যাকেজে তোমার দেওয়া 3D ফুটবল HTML প্রোটোটাইপটি Android WebView অ্যাপের মধ্যে রাখা হয়েছে।

APK বানানোর নিয়ম:
1. কম্পিউটারে Android Studio ইনস্টল করো।
2. Android Studio থেকে Open নির্বাচন করে এই ফোল্ডারটি খোলো।
3. Gradle sync শেষ হলে Build > Build Bundle(s) / APK(s) > Build APK(s) চাপো।
4. APK তৈরি হলে Android Studio-এর notification থেকে Locate চাপলে ফাইল পাবে।

গুরুত্বপূর্ণ:
- এটি প্রথম playable prototype-এর Android wrapper; সম্পূর্ণ eFootball-মানের গেম নয়।
- Three.js লাইব্রেরি CDN থেকে লোড হয়, তাই প্রথমবার চালু করতে ইন্টারনেট লাগবে।
- এই প্রজেক্ট নিজে থেকে APK তৈরি করে না; Android Studio দিয়ে build করতে হবে।
- Google Play-তে প্রকাশের আগে নিজস্ব backend, login, server-side player inventory,
  নিরাপদ payment, privacy policy, testing এবং Play Console setup লাগবে।
- গেমে টাকা দিয়ে প্লেয়ার কেনার ব্যবস্থা এখনো যুক্ত করা হয়নি। বাস্তব টাকা লেনদেন
  যোগ করার আগে Google Play Billing এবং সার্ভার-সাইড যাচাই লাগবে।
- Package name: com.abirfootball.game
