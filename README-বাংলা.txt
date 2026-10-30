মন্ডল কম্পিউটার Android APK তৈরির প্রজেক্ট

এই ZIP-এ আপনার HTML ব্যবসা অ্যাপকে Android WebView অ্যাপ হিসেবে প্যাকেজ করার সোর্স কোড আছে।
এটি নিজে APK ফাইল নয়।

APK তৈরির সহজ পথ:
১) ZIP ফাইলটি GitHub-এ নতুন repository-তে আপলোড করুন।
২) Repository-এর Actions ট্যাবে যান।
৩) “Build Android APK” workflow নির্বাচন করে “Run workflow” চাপুন।
৪) কাজ শেষ হলে workflow run-এর নিচে Artifacts থেকে mondol-computer-apk ডাউনলোড করুন।
৫) ZIP extract করে app-debug.apk ইনস্টল করুন।

দ্রষ্টব্য:
- এই প্রজেক্টে JavaScript ও WebView চালু আছে।
- অ্যাপের ডেটা ফোনের অ্যাপ-স্টোরেজে থাকবে; অ্যাপ আনইনস্টল/ডেটা ক্লিয়ার করলে মুছে যেতে পারে।
- নিয়মিত অ্যাপের Settings/Backup থেকে JSON ব্যাকআপ রাখুন।
- এটি Debug APK; Play Store প্রকাশের জন্য আলাদা signed release build প্রয়োজন।
