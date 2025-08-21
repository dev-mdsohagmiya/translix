# 🌐 Translix  

Translix হলো এমন একটি Chrome Extension যা শুধু ইনস্টল করে রাখলেই,  
আপনি যেকোনো ইনপুট বক্সে সিলেক্ট করা টেক্সটকে যেকোনো ভাষায় রিপ্লেস করতে পারবেন  
খুব সহজে **Shortcut Key** প্রেস করে।  

👉 আবার **Long-Press** করলে অনুবাদ করা টেক্সট preview box এ দেখতে পারবেন।  
এভাবে Translix ব্যবহার করে আপনি সহজেই যেকোনো ভাষায় যেকারো সাথে কথা বলতে পারবেন।  

---

## 📑 Table of Contents

1. [🎥 Overview Video](#-overview-video)  
2. [🚀 Installation Guide](#-কিভাবে-এই-এক্সটেনশন-ইনস্টল-করবেন)  
3. [💡 Usage & Features](#-কিভাবে-ব্যবহার-করবেন)  
4. [⚙️ Settings & Customization](#️-settings)  
5. [⭐ Best Practices](#-best-way-to-use)  
6. [🛠️ Technology](#-প্রযুক্তি)  

---

## 🎥 Overview Video  

<div align="center">  
  <iframe width="800" height="450"  
    src="https://www.youtube.com/embed/9PSBWwj9DU8?si=CN_OmpFIwSwxEitN"  
    title="Translix Overview Video"  
    frameborder="0"  
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"  
    allowfullscreen  
    style="border-radius: 12px; box-shadow: 0px 4px 20px rgba(0,0,0,0.2);">  
  </iframe>  
</div>  

---

## 🚀 কিভাবে এই এক্সটেনশন ইনস্টল করবেন  

1. ⬇️ প্রথমে এক্সটেনশনের **ZIP ফাইল** ডাউনলোড করুন।  
2. 🌐 Chrome-এ যান → `chrome://extensions`  
3. ⚙️ উপরের ডানদিকে **Developer Mode** চালু করুন।  
4. 📂 **Load unpacked** এ ক্লিক করে ZIP ফাইল সিলেক্ট করুন।  
5. ✅ সফলভাবে ইনস্টল হলে Translix এক্সটেনশন লিস্টে দেখতে পাবেন।  

---

## 💡 কিভাবে ব্যবহার করবেন  

1. পেজ রিফ্রেশ দিন → যেকোনো টেক্সট সিলেক্ট করলে ২টা আইকন দেখাবে।  
   ![Step 1](https://i.postimg.cc/k5rgGp9j/step-1.jpg)  

2. ক্লিক করলে টেক্সট রিপ্লেস হবে।  
   উদাহরণ: **BN আইকনে ক্লিক করলে → বাংলায় রিপ্লেস হবে**।  
   ![Step 2](https://i.postimg.cc/rmMyCRDx/step-2.jpg)  

3. শুধু প্রিভিউ চাইলে → আইকনের উপর **Long Press** করুন।  
   ![Step 3](https://i.postimg.cc/4dPf84cM/step-3.jpg)  

4. এখান থেকে কপি করে যেকোনো জায়গায় ব্যবহার করতে পারবেন।  

---

## ⚙️ Settings  

1. Extension toolbar → **Settings Icon** এ ক্লিক করলে settings page আসবে।  
   ![Setting](https://i.postimg.cc/4dPf84cM/step-3.jpg)  

### 🔑 AI Provider  

- বিভিন্ন **LLM Provider** যোগ করতে পারবেন।  
- তাদের ওয়েবসাইট থেকে **Free API Key** নিয়ে এখানে ব্যবহার করা যাবে।  

👉 Example: Groq ফ্রি API key এর জন্য [groq.com](http://groq.com) এ যান → Account Create করুন → Settings থেকে Generate করুন।  

---

### 🌍 Language & Shortcut  

- Target Language পরিবর্তন করতে পারবেন (BN → Bangla, EN → English ইত্যাদি)।  
- Shortcut Key কাস্টমাইজ করতে পারবেন।  

**ডিফল্ট শর্টকাট:**  
- `Ctrl + M` → Bangla (BN)  
- `Ctrl + E` → English (EN)  

---

## ⭐ Best Way to Use  

1. ডিফল্ট Provider "Polination" → সবসময় সঠিক কাজ নাও করতে পারে।  
2. নিজের API Key (যেমন Groq) সেট করুন।  
3. Default Language ঠিক করুন।  
4. পেজ Refresh দিন এবং অনুবাদ শুরু করুন।  

---

## 🛠️ প্রযুক্তি  

- Chrome Extension → **CRX + React**  
- Backend API → **Express.js**  

---
