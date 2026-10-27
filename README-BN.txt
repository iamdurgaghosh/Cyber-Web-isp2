CYBER WEB — মোবাইল থেকে চালানোর স্টার্টার

এই প্যাকেজে আছে:
- index.html: গ্রাহক অ্যাপ + অ্যাডমিন ডেমো
- manifest.webmanifest, sw.js, icon.svg: HTTPS-এ হোস্ট করলে PWA হিসেবে ইনস্টল করার প্রস্তুতি

এখন কী করবেন (শুধু Android ফোন দিয়ে):
1. ZIP ফাইলটি Downloads-এ রাখুন।
2. Files অ্যাপ থেকে ZIP Extract করুন।
3. index.html খুলে ডেমো পরীক্ষা করুন। এটি লোকাল ডেমো; তথ্য সাধারণত ফোনের ব্রাউজার রিফ্রেশ/বন্ধ করলে স্থায়ী থাকবে না।
4. হোম স্ক্রিনে ইনস্টল করার জন্য ফাইলটি অনলাইনে HTTPS-এ হোস্ট করতে হবে। এরপর Chrome-এ সাইট খুলে ⋮ > Add to Home screen / Install app চাপুন।

গুরুত্বপূর্ণ সীমাবদ্ধতা:
- এখানে কোনো বাস্তব লগইন, সার্ভার, ডাটাবেস, UPI পেমেন্ট, বা MikroTik সংযোগ নেই।
- UPI বাটন টাকা নেয় না; ডেমোতেই থাকবে।
- আসল গ্রাহকের তথ্য বা রাউটারের পাসওয়ার্ড এই ফাইলে/চ্যাটে লিখবেন না।
- লাইভ ব্যবহারের আগে নিরাপদ backend, database, login/role permissions, payment gateway webhook verification এবং RouterOS API-র জন্য নিরাপদ VPN/সার্ভার সেটআপ দরকার।
- MikroTik management API-কে সরাসরি public internet-এ খুলবেন না।

পরের ধাপ:
প্রথমে এই ডেমো ঠিক আছে কি না দেখুন। তারপর Android থেকেই HTTPS hosting ও backend/database সেটআপের ধাপ একে একে করা যাবে।
