# Email Reply Generator Chrome Extension

This is the official Chrome Extension for the **Email Reply Generator** project. It brings AI-powered reply suggestions directly into Gmail, using the Google Gemini API via a Spring Boot backend.

## 🔧 What It Does

The extension adds an **"AI REPLY"** button inside your Gmail interface when you open an email thread. Clicking it automatically fetches a smart reply using the backend, saving you time and effort.

---

## 🛠 How to Install the Extension

Follow these steps to load and use the extension in your Chrome browser:

### 1. Download or Clone the Repo

```bash
git clone https://github.com/yourusername/email-writer-extension.git
```

Or download the ZIP file and extract it.

### 2. Open Chrome Extension Settings

* Open Google Chrome.
* Navigate to `chrome://extensions` in your address bar.

### 3. Enable Developer Mode

* On the top-right corner, enable **Developer mode** by toggling the switch.

### 4. Load Unpacked Extension

* Click the **"Load unpacked"** button.
* Select the folder where the extension files (`manifest.json`, `content.js`, etc.) are located (from step 1).

<img width="499" height="280" alt="Screenshot 2025-07-13 104908" src="https://github.com/user-attachments/assets/893626cf-ecbd-418c-9d59-3b9f140e5cd7" />


### 5. You're All Set!

* Open Gmail in a new tab.
* Open any email conversation.
* You'll see an **"AI REPLY"** button below the reply box.
* Click it to generate a response automatically.

---

## ⚙️ How It Works (Under the Hood)

* The extension captures the most recent email content.
* Sends it to your local or deployed Spring Boot backend.
* The backend forwards it to the Gemini API and returns a reply.
* The extension then inserts the AI-generated reply into the Gmail reply box.

---

> ✨ Created to streamline your email workflow with the power of AI. Just click and reply!
