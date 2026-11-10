# Global Dating — Android starter project

এটি Global Dating-এর প্রথম Android UI prototype। এতে Discover card, Like/Skip action, Likes, Chats এবং Profile navigation আছে। ভিডিওর প্রাপ্ত স্ক্রিনে থাকা অনিরাপদ/প্রাপ্তবয়স্ক কনটেন্ট অনুকরণ করা হয়নি; এর বদলে নিরাপদ dating-app UI রাখা হয়েছে।

## APK বানানোর নিয়ম
1. কম্পিউটারে Android Studio ইনস্টল করুন।
2. এই ZIP extract করে Android Studio থেকে `GlobalDating` ফোল্ডার Open করুন।
3. Gradle sync শেষ হলে **Build > Build Bundle(s) / APK(s) > Build APK(s)** চাপুন।
4. APK পাবেন `app/build/outputs/apk/debug/app-debug.apk`-এ।

## গুরুত্বপূর্ণ
এটি UI starter, production dating service নয়। Login, database, photo upload, real-time chat, matching backend, moderation, privacy policy এবং secure authentication এখনও যুক্ত করতে হবে। এই পরিবেশে Android SDK/Gradle build setup নেই, তাই এখানে সরাসরি installযোগ্য APK তৈরি করা হয়নি।
