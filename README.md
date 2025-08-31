# AIA to APK Builder (GitHub Actions)

এই রিপোজিটরি ব্যবহার করে আপনি ফ্রি-তেই **Kodular/MIT App Inventor `.aia` ফাইল → `.apk`** বানাতে পারবেন 🚀  
কোনো সফটওয়্যার ইনস্টল বা টাকা খরচের দরকার নেই। শুধু GitHub Actions ব্যবহার করতে হবে।

---

## কিভাবে ব্যবহার করবেন

### 1. `.aia` ফাইল আপলোড করুন
- এই রিপোতে যান → **Add file → Upload files**
- আপনার `.aia` ফাইল (Kodular/MIT App Inventor থেকে এক্সপোর্ট করা) **Root level** এ আপলোড করুন।
- Commit করুন।

### 2. Build চালান
- উপরে **Actions** ট্যাবে ক্লিক করুন।
- **Build AIA to APK** workflow সিলেক্ট করুন।
- ডানদিকে সবুজ **Run workflow** বাটনে ক্লিক করুন।
- ৫–১০ মিনিট অপেক্ষা করুন।

### 3. APK ডাউনলোড করুন
- Workflow শেষ হলে → **Artifacts** এ ক্লিক করুন।
- **Built-APK.zip** ডাউনলোড করুন।
- ZIP ফাইল Extract করলে ভেতরে `.apk` ফাইল পাবেন ✅

---

## নোট
- কিছু Kodular কম্পোনেন্ট (যেমন AdMob, Monetization) MIT App Inventor বিল্ডারে কাজ নাও করতে পারে।
- বড় অ্যাসেট (ইমেজ/অডিও) থাকলে বিল্ড ফেল করতে পারে।  
- যদি কোনো Error পান, অপ্রয়োজনীয় ফাইল ডিলিট করে আবার চেষ্টা করুন।

---

## কৃতজ্ঞতা
- [MIT App Inventor](https://appinventor.mit.edu) ওপেন-সোর্স টিম  
- GitHub Actions

---
