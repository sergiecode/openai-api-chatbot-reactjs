# 🤖 OpenAI Chatbot - React.js

A modern, minimalist React.js chatbot application powered by OpenAI's GPT API. Built with TypeScript, Vite, and a beautiful glassmorphism design.

![OpenAI Chatbot](https://img.shields.io/badge/OpenAI-GPT--3.5--turbo-green)
![React](https://img.shields.io/badge/React-19-blue)
![TypeScript](https://img.shields.io/badge/TypeScript-5.8-blue)
![Vite](https://img.shields.io/badge/Vite-7.1-purple)

## 👨‍💻 Created by Sergie Code

**Software Engineer & Programming Teacher**

I teach programming through engaging YouTube tutorials and content across multiple platforms. This project demonstrates modern React development with AI integration.

### 🌟 Follow me on:

- 📽️ **YouTube**: [@SergieCode](https://www.youtube.com/@SergieCode) - Programming tutorials and tech content
- 📸 **Instagram**: [@sergiecode](https://www.instagram.com/sergiecode) - Behind the scenes and quick tips  
- 🧑🏼‍💻 **LinkedIn**: [sergiecode](https://www.linkedin.com/in/sergiecode/) - Professional updates and articles
- 😺 **GitHub**: [sergiecode](https://github.com/sergiecode) - Open source projects and code
- 👤 **Facebook**: [sergiecodeok](https://www.facebook.com/sergiecodeok) - Community and updates
- 🎞️ **TikTok**: [@sergiecode](https://www.tiktok.com/@sergiecode) - Quick coding tips and tricks
- 🕊️ **Twitter**: [@sergiecode](https://twitter.com/sergiecode) - Tech thoughts and updates
- 🧵 **Threads**: [@sergiecode](https://www.threads.net/@sergiecode) - Latest discussions

## ✨ Features

- 🎨 **Modern UI** - Clean glassmorphism design with smooth animations
- 🤖 **AI-Powered** - Integrated with OpenAI's GPT-3.5-turbo model
- 💬 **Real-time Chat** - Instant responses with typing indicators
- 📱 **Responsive** - Works perfectly on desktop and mobile devices
- 🔒 **Secure** - Environment variables for API key protection
- ⚡ **Fast** - Built with Vite for lightning-fast development
- 🎯 **TypeScript** - Full type safety and better development experience

## 🚀 Quick Start

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn
- OpenAI API key

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/sergiecode/openai-api-chatbot-reactjs.git
   cd openai-api-chatbot-reactjs
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   ```bash
   cp .env.template .env
   ```
   
   Edit `.env` and add your OpenAI API key:
   ```env
   VITE_OPENAI_API_KEY=your_openai_api_key_here
   ```

4. **Start the development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**
   Navigate to `http://localhost:5173`

## 🔑 Getting Your OpenAI API Key

1. Visit [OpenAI Platform](https://platform.openai.com/api-keys)
2. Sign in to your account (or create one)
3. Navigate to "API Keys" section
4. Click "Create new secret key"
5. Copy the key and paste it in your `.env` file

## 📁 Project Structure

```
src/
├── components/
│   ├── Chatbot.tsx          # Main chatbot component
│   └── Chatbot.css          # Chatbot styling
├── services/
│   └── openai.ts            # OpenAI API integration
├── App.tsx                  # Main application component
├── App.css                  # Global styles
└── main.tsx                 # Application entry point
```

## 🛠️ Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## 🎨 Customization

### Styling
The app uses a modern glassmorphism design. You can customize colors and effects in:
- `src/App.css` - Global styles and layout
- `src/components/Chatbot.css` - Chatbot-specific styling

### AI Configuration
Modify AI behavior in `src/services/openai.ts`:
- Change the model (e.g., gpt-4)
- Adjust max_tokens
- Modify temperature for creativity

## 🔒 Security Notes

- ⚠️ **Client-side API calls**: This demo makes API calls directly from the browser
- 🏢 **Production recommendation**: Implement a backend server to secure your API key
- 🔐 **Environment variables**: Never commit `.env` files to version control
- 📝 **Rate limiting**: Consider implementing rate limiting for production use

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests
- Improve documentation

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🎓 Learning Resources

This project is perfect for learning:
- React 19 with hooks
- TypeScript integration
- OpenAI API usage
- Modern CSS techniques
- Vite configuration
- Environment variable management

## 📞 Support

If you have questions or need help:
- 💬 Comment on my [YouTube videos](https://www.youtube.com/@SergieCode)
- 📧 Reach out on [LinkedIn](https://www.linkedin.com/in/sergiecode/)
- 🐦 Tweet me on [Twitter](https://twitter.com/sergiecode)

---

⭐ **If you found this project helpful, please give it a star on GitHub!**

**Made with ❤️ by [Sergie Code](https://github.com/sergiecode)**
