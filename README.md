![Translix Logo](https://i.postimg.cc/pLQNvWVL/fulllogopng.png)

# **Translix** - Seamless Text Translation Chrome Extension  

**Translix** is a powerful Chrome Extension that enables you to instantly translate selected text in any input box into your desired language with a simple **shortcut key** or **long-press** preview. Communicate effortlessly across languages with ease and precision!  

> **Effortless. Fast. Multilingual.**  
> Replace text or preview translations in just a few clicks.  

---

## 📑 **Table of Contents**  

1. [🎥 Overview Video](#overview-video)  
2. [🚀 Installation Guide](#installation-guide)  
3. [🔑 LLM Provider Configuration](#llm-provider-configuration)  
   - [1. Groq Configuration](#1-grok-configuration)  
   - [2. Hugging Face Configuration](#2-hugging-face-configuration)  
   - [3. Gemini Configuration](#3-gemini-configuration)  
4. [💡 How to Use](#how-to-use)  
   - [1. Replace Text](#1-replace-text)  
   - [2. Preview Translation](#2-preview-translation)  
5. [⚙️ Settings & Customization](#settings--customization)  
   - [1. LLM Model Configuration](#1-llm-model-configuration)  
   - [2. Language & Shortcut](#2-language--shortcut)  
6. [⭐ Best Practices](#best-practices)  
7. [🛠️ Technology Stack](#technology-stack)  
8. [📞 Support & Feedback](#support--feedback)  

---

## 🎥 **Overview Video**  

Get a quick glimpse of Translix in action! Watch the video below to see how it simplifies multilingual communication.  

[![Watch the Video](https://img.youtube.com/vi/9PSBWwj9DU8/maxresdefault.jpg)](https://www.youtube.com/watch?v=9PSBWwj9DU8)  

*Click the image to watch on YouTube*  

---

## 🚀 **Installation Guide**  

Follow these simple steps to install Translix and start translating text instantly:  

1. ⬇️ **Download** the extension’s **ZIP file** [click here to download](./assets/versions/translix-1.0.0.zip).
2. 🌐 Open Chrome and navigate to `chrome://extensions`.  
3. ⚙️ Enable **Developer Mode** (top-right corner).  
   ![Step 1](https://i.postimg.cc/jjrcD5mG/3.jpg)  
4. 📂 Click **Load unpacked** and select the extracted ZIP folder.  
      ![Step 1](https://i.postimg.cc/yNXPcKzW/4.jpg)  
5. ✅ Once installed, Translix will appear in your Chrome extensions list.  
       ![Step 1](https://i.postimg.cc/JnrQQF1x/5.jpg)  

> **Pro Tip**: Pin Translix to your Chrome toolbar for quick access!  

---

## 🔑 **LLM Provider Configuration**  

Translix requires a configured **LLM Provider** for accurate translations. Set up a **Free API Key** in the settings to enable translation functionality. Below are instructions for configuring popular providers:  

### 1. Groq Configuration  

To use **Grok** for translations:  
1. Visit [groq.com](http://groq.com).  
2. Create an account or sign in.  
3. Navigate to **Settings** and generate a free API key.  
4. Copy the API key and paste it into the **AI Provider** section of Translix’s settings.  
5. Save and refresh the page to apply the changes.  

> **Note**: Groq offers fast and accurate translations, ideal for multilingual communication.  

### 2. Hugging Face Configuration  

To use **Hugging Face** for translations:  
1. Go to [huggingface.co](https://huggingface.co).  
2. Sign up or log in to your account.  
3. Navigate to **Settings > Access Tokens** and create a new API token.  
4. Copy the token and add it to the **AI Provider** section in Translix’s settings.  
5. Select a translation model (e.g., `Helsinki-NLP/opus-mt`) from the settings dropdown.  
6. Save and refresh the page.  

> **Note**: Hugging Face supports a wide range of open-source translation models.  

### 3. Gemini Configuration  

To use **Google Gemini** for translations:  
1. Visit [ai.google.dev](https://ai.google.dev).  
2. Sign in with your Google account.  
3. Navigate to the **API Keys** section and generate a new API key.  
4. Copy the API key and paste it into the **AI Provider** section of Translix’s settings.  
5. Save and refresh the page to enable Gemini-powered translations.  

> **Note**: Ensure your Gemini API key has access to translation-capable models.  

---

## 💡 **How to Use**  

Translix makes translation intuitive and fast. Here’s how it works:  

1. **Select Text**: Highlight text in any input box after refreshing the page. Two icons will appear next to the selection.  
   ![Step 1](https://i.postimg.cc/k5rgGp9j/step-1.jpg)  

### 1. Replace Text  

Click an icon to instantly replace the selected text with its translation.  
*Example*: Clicking the **BN** icon translates the text to Bangla.  
![Step 2](https://i.postimg.cc/rmMyCRDx/step-2.jpg)  

### 2. Preview Translation  

Long-press an icon to view the translated text in a preview box. Copy the previewed translation and paste it anywhere you need.  
![Step 3](https://i.postimg.cc/4dPf84cM/step-3.jpg)  

> **Why It’s Awesome**: Translate directly in forms, chats, or text editors without leaving the page!  

---

## ⚙️ **Settings & Customization**  

Customize Translix to suit your needs via the **Settings** page, accessible by clicking the **Settings Icon** in the extension toolbar.  
![Settings](https://i.postimg.cc/4dPf84cM/step-3.jpg)  

### 1. LLM Model Configuration  

Add your preferred **LLM Provider** for translations by configuring an API key. This enhances translation accuracy and speed.  

- Navigate to the **AI Provider** section in the settings.  
- Select a provider (e.g., Groq, Hugging Face, or Gemini) and input the API key.  
- For specific provider setup, refer to the [LLM Provider Configuration](#llm-provider-configuration) section.  

> **Note**: Configuring a custom LLM model ensures better translation quality over the default provider.  

### 2. Language & Shortcut  

- Choose your **target language** (e.g., BN → Bangla, EN → English, etc.).  
- Customize **shortcut keys** for quick translations.  

**Default Shortcuts**:  
- `Ctrl + M` → Translate to Bangla (BN)  
- `Ctrl + E` → Translate to English (EN)  

> **Pro Tip**: Set shortcuts that don’t conflict with other browser or system commands.  

---

## ⭐ **Best Practices**  

Maximize your Translix experience with these tips:  

1. **Switch from Default Provider**: The default provider, "Polination," may not always deliver optimal results. Use a custom API key (e.g., Groq, Hugging Face, or Gemini) for better accuracy.  
2. **Set Default Language**: Choose your primary language in settings for faster translations.  
3. **Refresh Pages**: Always refresh the page after changing settings to apply updates.  
4. **Test Shortcuts**: Ensure your custom shortcuts work smoothly across websites.  

> **Fun Fact**: Translix works seamlessly in chat apps, forms, and even social media platforms!  

---

## 🛠️ **Technology Stack**  

Translix is built with modern, reliable technologies:  

- **Frontend**: Chrome Extension with **React** for a smooth and dynamic UI.  
- **Backend**: **Express.js** for fast and secure API communication.  
- **Translation APIs**: Powered by leading LLMs (Grok, Hugging Face, Gemini, etc.) for accurate translations.  

---

## 📞 **Support & Feedback**  

Have questions or suggestions? We’d love to hear from you!  

- **Email**: support@translix.com  
- **GitHub**: [Translix Issues](https://github.com/translix/extension)  
- **Community**: Join our [Discord Server](https://discord.gg/translix) for updates and tips.  

> **Your feedback helps us make Translix even better!**

---

**Translix** - Break language barriers with a single click. Start translating today!  