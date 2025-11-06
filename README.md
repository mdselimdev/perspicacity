# Perspicacity 🕌

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Live Demo](https://img.shields.io/badge/demo-online-20808d.svg)](https://perspicacity.is-cool.dev)
[![PWA Ready](https://img.shields.io/badge/PWA-Ready-success.svg)](https://perspicacity.is-cool.dev)
[![Support on Ko-fi](https://img.shields.io/badge/support-on%20kofi-ff5e5b.svg)](https://ko-fi.com/perspicacity)

> **Beyond Knowledge, Towards Wisdom**

Perspicacity is an AI-powered Islamic research assistant designed to provide reliable guidance by sourcing answers exclusively from trusted Islamic websites (**IslamQA.info** and **IslamWeb.net**). It features dual search modes, conversation memory, and a privacy-first architecture where your API keys never leave your browser.

🌐 **Live Demo**: [perspicacity.is-cool.dev](https://perspicacity.is-cool.dev)

## ✨ Key Features

- **🔍 Dual Modes**:
  - **Quick Search**: Immediate, sourced answers for everyday questions.
  - **Deep Research**: Comprehensive, multi-step analysis for complex topics.
- **📚 Trusted Sources**: Information is exclusively sourced from IslamQA.info and IslamWeb.net to ensure reliability.
- **🛡️ Privacy-First**: Serverless architecture means your API keys are stored locally in your browser and never transmitted to us.
- **🧠 Contextual Memory**: The assistant remembers your conversation for relevant follow-up questions.
- **📱 Progressive Web App (PWA)**: Installable on iOS, Android, and Desktop for a native app experience.

## 🚀 Quick Start

1. Visit [perspicacity.is-cool.dev](https://perspicacity.is-cool.dev).
2. Click the settings icon (⚙️) in the top right.
3. Enter your free API keys (instructions below) and click "Save Settings".
4. Start asking your questions!

## 🔑 Getting Free API Keys

Perspicacity requires two free API keys to function. These keys are stored only on your device.

### 1. Gemini API Key (for AI reasoning)
1. Visit [Google AI Studio](https://aistudio.google.com/app/apikey).
2. Sign in with your Google account.
3. Click **"Create API Key"**.
4. Copy the key and paste it into Perspicacity settings.

### 2. Google Cloud API Key (for searching trusted sites)
1. Go to [Google Cloud Console](https://console.cloud.google.com/apis/credentials).
2. Create a new project (or select an existing one).
3. Enable the **"Custom Search API"**.
4. Go to Credentials → **"Create Credentials"** → **"API Key"**.
5. Copy the key and paste it into Perspicacity settings.

## 📱 Installation (PWA)

Perspicacity is designed to be installed as a native app on your device.

| Platform | Instructions |
|----------|--------------|
| **iOS** | Open in Safari → Tap 'Share' icon → "Add to Home Screen" |
| **Android** | Open in Chrome → Tap menu (⋮) → "Add to Home Screen" / "Install App" |
| **Desktop** | Open in Chrome/Edge → Click the install icon in the address bar |

## 🛠️ Local Development

To run the project locally for development or contribution:

```bash
# Clone the repository
git clone https://github.com/mdselimdev/perspicacity.git

# Navigate to directory
cd perspicacity

# Start a simple local server (requires Python)
python3 -m http.server 8000
```

Open your browser to `http://localhost:8000`.

## 🤝 Contributing

Contributions are welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on how to report issues, suggest features, or submit pull requests.

## 💖 Support the Project

If Perspicacity has benefited your Islamic learning journey, please consider supporting its continued development.

- ☕ [**Support on Ko-fi**](https://ko-fi.com/perspicacity)
- ⭐ Star this repository on GitHub
- 🔄 Share it with your community

## 📄 License

This project is licensed under the MIT License - see [LICENSE](LICENSE) for details.

## 🙏 Acknowledgments

- **Sources**: Grateful acknowledgment to [IslamQA.info](https://islamqa.info) and [IslamWeb.net](https://www.islamweb.net) for their invaluable scholarly resources.
- **Technology**: Powered by Google Gemini and Google Custom Search.

---

**Made with ❤️ for the Muslim Ummah**
