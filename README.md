# Web Search Plugin for Hukusis

A powerful web search plugin designed specifically for Hukusis, enabling seamless internet search capabilities through Google Custom Search Engine integration.

## 🚀 Features

- 🔍 Google Custom Search Engine integration
- 🌐 Web content extraction and processing
- 🔄 Real-time search results
- 🛡️ CORS-enabled API endpoints
- 📦 Lightweight and efficient implementation

## 📋 Prerequisites

- Node.js (Latest LTS version recommended)
- Bun runtime environment
- Google Custom Search Engine API key

## 🛠️ Installation

1. Clone the repository:
```bash
cd web-plugin-hukusis
```

2. Install dependencies:
```bash
bun install
```

3. Configure your environment:
   - Set up your Google Custom Search Engine API key
   - Configure any necessary environment variables

## 🚀 Usage

### Development Mode
```bash
bun run dev
```

### Production Mode
```bash
bun run start
```

## 📡 API Endpoints

### Base URL: `/api`

- `GET /` - Welcome endpoint with API information
- `POST /gateway` - Plugin gateway endpoint
- `POST /search` - Web search endpoint

## 🛠️ Technical Stack

- **Runtime**: Bun
- **Framework**: Hono
- **Dependencies**:
  - @lobehub/chat-plugin-sdk
  - @lobehub/chat-plugins-gateway
  - @mozilla/readability
  - jsdom

## 📝 License

This project is licensed under the terms specified in the LICENSE file.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📞 Support

For support, please open an issue in the GitHub repository.

---

Made with ❤️ for Hukusis
