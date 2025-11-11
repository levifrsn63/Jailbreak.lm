# ChatGPT Clone

A modern, multi-provider AI chat interface that supports OpenAI, Anthropic, and DeepSeek APIs. This application provides a ChatGPT-like experience with a sleek, Apple-inspired UI and comprehensive features for AI-powered conversations.
The site is Live at: https://levifrsn63.github.io/Jailbreak.lm/
## 🌟 Features

### Multi-Provider Support
- **OpenAI** - GPT-4o, GPT-4o Mini, GPT-4 Turbo, GPT-3.5
- **Anthropic** - Claude 3.5 Sonnet, Claude 3 Opus, Claude 3 Haiku
- **DeepSeek** - DeepSeek Chat, DeepSeek Coder

### Advanced Functionality
- 💬 **Conversation Management** - Create, organize, and manage multiple chat sessions
- 🎨 **Modern UI** - Apple-inspired design with smooth animations
- 📱 **Fully Responsive** - Works seamlessly on desktop and mobile devices
- 🌓 **Dark Mode Support** - Built-in dark theme
- 💾 **Local Storage** - Conversations persist in your browser
- 🔒 **Secure API Keys** - Keys stored locally in browser storage

### Code Block Features
- 🎯 **Syntax Highlighting** - Support for 15+ programming languages
- 📋 **Copy to Clipboard** - One-click code copying
- 💾 **Download Code** - Save code blocks as files
- 🔍 **Smart Detection** - Automatically detects and formats code blocks

### Customization
- 🎛️ **Temperature Control** - Adjust response creativity (0-2)
- 📊 **Max Tokens** - Configure response length
- 🤖 **Custom System Prompts** - Personalize AI behavior for each provider
- 🔗 **Custom Endpoints** - Use alternative API endpoints

## 🚀 Getting Started

### Prerequisites
- API key from at least one provider:
  - [OpenAI API Key](https://platform.openai.com/api-keys)
  - [Anthropic API Key](https://console.anthropic.com/)
  - [DeepSeek API Key](https://platform.deepseek.com/)


## 📖 Usage Guide

### Creating Conversations
1. Click the **"+ New chat"** button in the sidebar
2. Select your AI provider from the model selector
3. Optionally choose a specific model from the dropdown
4. Start typing your message

### Managing Chats
- **Switch Chats**: Click on any conversation in the sidebar
- **Delete Chats**: Hover over a chat and click the trash icon
- **Auto-Save**: All messages are automatically saved to local storage
- **Chat History**: Organized by Today, Yesterday, Last 7 Days, and Older

### Code Blocks
When the AI generates code, you'll see:
- **Language label** at the top of each code block
- **Copy button** to copy code to clipboard
- **Download button** to save as a file
- **Syntax highlighting** for better readability

Supported languages include: JavaScript, Python, Java, C, C++, Go, Rust, TypeScript, Bash, JSON, SQL, C#, JSX/TSX, and more.

### Customizing AI Behavior

#### System Prompts (Jailbreaks)
System prompts help optimize each AI model's performance:
- **OpenAI**: General-purpose, creative responses
- **Anthropic**: Thoughtful, nuanced, and cautious responses
- **DeepSeek**: Code-focused, technical expertise

Access via Settings → Jailbreaks section

#### Model Parameters
- **Temperature**: Controls randomness (0 = focused, 2 = creative)
- **Max Tokens**: Limits response length

## 🎨 Platform-Specific Usage

### Desktop (Windows, Mac, Linux)
Simply open the website in your browser - no installation needed!

### Mobile Devices (iOS/Android)
1. Open the app in Safari (iOS) or Chrome (Android)
2. **iOS**: Tap Share → "Add to Home Screen"
3. **Android**: Tap Menu → "Add to Home Screen"
4. Launch from your home screen like a native app

### Tablets
Works seamlessly on iPads and Android tablets with the full desktop experience.

## 🔧 Technical Details

### Built With
- **Frontend**: Vanilla HTML, CSS, JavaScript
- **Syntax Highlighting**: Prism.js v1.29.0
- **Icons**: Font Awesome 6.4.2
- **Storage**: Browser LocalStorage API
- **Server**: Python HTTP Server (development)

### File Structure
```
├── index.html          # Main application file
├── style.css          # Styling and theming
├── README.md          # This file
├── server.py          # Development server
└── .replit            # Replit configuration
```

### API Integration
The app makes direct API calls to:
- `https://api.openai.com/v1/chat/completions`
- `https://api.anthropic.com/v1/messages`
- `https://api.deepseek.com/chat/completions`

All requests include your API key and conversation history for context-aware responses.

## 🔒 Security & Privacy

- ✅ **Client-Side Only**: All API keys stored in your browser's local storage
- ✅ **No Server Storage**: No data sent to any third-party servers (except AI providers)
- ✅ **Direct API Calls**: Communication directly with AI providers
- ⚠️ **Keep Keys Private**: Never share your API keys
- ⚠️ **Browser Storage**: Clearing browser data will delete your chats and settings

## 📱 Mobile Optimization

- Responsive design adapts to all screen sizes
- iOS-specific meta tags for web app capability
- Prevents zoom on input focus
- Safe area support for notched devices
- Touch-optimized buttons and controls

## 🎯 Tips for Best Results

1. **Be Specific**: Provide clear, detailed prompts
2. **Use Context**: Continue conversations for better understanding
3. **Try Different Models**: Each has unique strengths
4. **Adjust Temperature**: Lower for factual tasks, higher for creative work
5. **Custom System Prompts**: Tailor AI behavior to your needs

## 📄 License

This project is open source and available under the MIT License.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

## 💡 Acknowledgments

- Inspired by OpenAI's ChatGPT interface
- Built on Replit's powerful development platform
- Uses Prism.js for beautiful code highlighting

## 📧 Support

For issues or questions:
- Open an issue on this Repl
- Check the Replit Community Forums
- Review the AI provider documentation

---

**Enjoy your AI-powered conversations!** 🚀
