![Translix Logo](https://i.postimg.cc/pLQNvWVL/fulllogopng.png)

# **Translix** - Seamless Text Translation Chrome Extension  

**Translix** is a powerful Chrome Extension that enables you to instantly translate selected text in any input box into your desired language with a simple **shortcut key** or **long-press** preview. Communicate effortlessly across languages with ease and precision!  

> **Effortless. Fast. Multilingual.**  
> Replace text or preview translations in just a few clicks.  

---

## 📑 **Table of Contents**  

1. [Overview Video](#overview-video)  
2. [Installation Guide](#installation-guide)  
3. [LLMs Providers Configuration](#llm-provider-configuration)  
   - [1. Groq Configuration](#groq-configuration)  
   - [2. Hugging Face Configuration](#hugging-face-configuration)  
   - [3. Gemini Configuration](#gemini-configuration)  
4. [How to Use](#how-to-use)  
   - [1. Replace Text](#replace-text)  
   - [2. Preview Translation](#preview-translation)  
5. [Settings & Customization](#settings--customization)  
   - [1. LLMs Providers Configuration](#llm-provider-configuration)  
   - [2. Language & Shortcut](#language--shortcut)  
6. [Technology Stack](#technology-stack)  
7. [Support & Feedback](#support--feedback)  

---

## Overview Video  

Get a quick glimpse of Translix in action! Watch the video below to see how it simplifies multilingual communication.  

[![Watch the Video](https://img.youtube.com/vi/9PSBWwj9DU8/maxresdefault.jpg)](https://www.youtube.com/watch?v=9PSBWwj9DU8)  

*Click the image to watch on YouTube*  

---

## Installation Guide  

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

## LLM Provider Configuration  

Translix requires a configured **LLM Provider** for accurate translations. Set up a **Free API Key** in the settings to enable translation functionality. Below are instructions for configuring popular providers:  

### Groq Configuration  

To use **Groq** for translations:  
1. Visit [console.groq.com](http://console.groq.com).  
2. Create an account or sign in. You can quickly sign up or log in with your Gmail.  
3. Click to create an API key from **API Keys**.  
   ![Step 1](https://i.postimg.cc/DwjWDy3t/6.jpg)  
4. Set your API key name, then click to submit. After that, you will see your API key — copy it.  
   ![Step 1](https://i.postimg.cc/wBn1qfv2/7.jpg)  
   ![Step 1](https://i.postimg.cc/QMFBrGXV/8.jpg)  
5. Open the Translix extension, go to Settings → API Configuration, select the provider Groq, enter your API key, click Save, and refresh the page to apply the changes.  
   ![Step 1](https://i.postimg.cc/KzLRRP32/9.jpg)  
   ![Step 1](https://i.postimg.cc/SRhj8ncz/10.jpg)  

> **Note**: Groq offers fast and accurate translations, ideal for multilingual communication.  

### Hugging Face Configuration  

To use **Hugging Face** for translations:  
1. Go to [huggingface.co](https://huggingface.co).  
2. Sign up or log in to your account.  
3. Navigate to **Settings > Access Tokens** and create a new API token.  
   ![Step 1](https://i.postimg.cc/vH8m5g45/11.jpg)  
4. Enter any token name you like. Setting the permission to Inference only will be enough.  
   ![Step 1](https://i.postimg.cc/5tz9f8rW/12.jpg)  
5. Scroll down, click the Create Token button to create the token, and copy the token.  
   ![Step 1](https://i.postimg.cc/htfP3kbj/13.jpg)  
   ![Step 1](https://i.postimg.cc/13nVNndJ/Untitled-design-5.jpg)  
6. Open the Translix extension, go to Settings → API Configuration, select the provider Hugging Face, enter your API key, click Save, and refresh the page to apply the changes.  
   ![Step 1](https://i.postimg.cc/xCSf8crJ/14.jpg)  
   ![Step 1](https://i.postimg.cc/4dbJ9sZ8/15.jpg)  

> **Note**: Hugging Face supports a wide range of open-source translation models.  

### Gemini Configuration  

To use **Google Gemini** for translations:  
1. Visit [aistudio.google.com](https://aistudio.google.com/).  
2. Go to API keys and click Create API key.  
   ![Step 1](https://i.postimg.cc/V6kpL8GQ/17.jpg)  
3. Select a project and click Create API Key in Existing Project. If you don’t see any project, go to [console.cloud.google.com](https://console.cloud.google.com/) and create a new one. Use the same Gmail account for generating the API key.  
   ![Step 1](https://i.postimg.cc/fLqFVrp3/18.jpg)  
   ![Step 1](https://i.postimg.cc/d1GfvTYt/Untitled-design-7.jpg)  
4. Copy the API key and paste it into the **AI Provider** section of Translix’s settings.  
   ![Step 1](https://i.postimg.cc/SRXPCGbg/19.jpg)  
5. Open the Translix extension, go to Settings → API Configuration, select the provider Gemini, enter your API key, click Save, and refresh the page to apply the changes.  
   ![Step 1](https://i.postimg.cc/J7gvmSjv/21.jpg)  
   ![Step 1](https://i.postimg.cc/SRwvrzyk/20.jpg)  

> **Note**: Ensure your Gemini API key has access to translation-capable models.  

---

## How to Use  

Translix makes translation intuitive and fast. Here’s how it works:  

1. **Select Text**: Highlight text in any input box after refreshing the page. Two icons will appear next to the selection.  
   ![Step 1](https://i.postimg.cc/k5rgGp9j/step-1.jpg)  

### Replace Text  

Click an icon to instantly replace the selected text with its translation.  
*Example*: Clicking the **BN** icon translates the text to Bangla.  
![Step 2](https://i.postimg.cc/rmMyCRDx/step-2.jpg)  

### Preview Translation  

Long-press an icon to view the translated text in a preview box. Copy the previewed translation and paste it anywhere you need.  
![Step 3](https://i.postimg.cc/4dPf84cM/step-3.jpg)  

> **Why It’s Awesome**: Translate directly in forms, chats, or text editors without leaving the page!  

---

## Settings & Customization  

Customize Translix to suit your needs via the **Settings** page, accessible by clicking the **Settings Icon** in the extension toolbar.  
![Settings](https://i.postimg.cc/4dPf84cM/step-3.jpg)  

### LLM Model Configuration  

Add your preferred **LLM Provider** for translations by configuring an API key. This enhances translation accuracy and speed.  

- Navigate to the **AI Provider** section in the settings.  
- Select a provider (e.g., Groq, Hugging Face, or Gemini) and input the API key.  
- For specific provider setup, refer to the [LLM Provider Configuration](#llm-provider-configuration) section.  

> **Note**: Configuring a custom LLM model ensures better translation quality over the default provider.  

### Language & Shortcut  

- Choose your **target language** (e.g., BN → Bangla, EN → English, etc.).  
- Customize **shortcut keys** for quick translations.  

**Default Shortcuts**:  
- `Ctrl + M` → Translate to Bangla (BN)  
- `Ctrl + E` → Translate to English (EN)  

> **Pro Tip**: Set shortcuts that don’t conflict with other browser or system commands.  

---

## Technology Stack  

Translix is built with modern, reliable technologies:  

- **Frontend**: Chrome Extension with **React** for a smooth and dynamic UI.  
- **Backend**: **Express.js** for fast and secure API communication.  
- **Translation APIs**: Powered by leading LLMs (Groq, Hugging Face, Gemini, etc.) for accurate translations.  

---

## Support & Feedback  

Have questions or suggestions? We’d love to hear from you!  

- **Email**: support@translix.com  
- **GitHub**: [Translix Issues](https://github.com/translix/extension)  
- **Community**: Join our [Discord Server](https://discord.gg/translix) for updates and tips.  

> **Your feedback helps us make Translix even better!**

---

**Translix** - Break language barriers with a single click. Start translating today!