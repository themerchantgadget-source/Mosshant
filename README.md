# 🌐 Mosshant

A modern, web-based SSH/mosh client and connection manager. Access your remote servers from any browser, with support for terminal emulation, connection management, authentication, and session handling.

## ✨ Features

- **Web-Based Interface** – No installation needed, runs in any modern browser
- **Connection Management** – Save and organize your favorite SSH/mosh servers
- **Terminal Emulation** – Full terminal support with colors, formatting, and interactivity
- **Multi-Session Support** – Keep multiple SSH connections open simultaneously
- **Authentication** – Password and SSH key authentication methods
- **Android Support** – PWA for Android, installable directly to home screen
- **iOS Ready** – Future support when iOS dev program is available
- **Mosh Support** – Mobile shell for unstable network connections (v1.1+)

## 🚀 Quick Start

### Prerequisites
- Node.js 16+ and npm
- Modern web browser (Chrome, Firefox, Safari, Edge)

### Installation

```bash
# Clone the repository
git clone https://github.com/themerchantgadget-source/mosshant.git
cd mosshant

# Install dependencies
npm install

# Start development server
npm start
```

The app will be available at `http://localhost:3000`

## 📋 Project Structure

```
mosshant/
├── frontend/          # React web application
├── backend/           # Express.js server & SSH handling
├── docs/              # Documentation
└── README.md          # This file
```

## 🎯 v1.0 Roadmap

- [x] Project setup and structure
- [ ] Backend infrastructure (Express, WebSocket, SSH2)
- [ ] Connection management (save/load servers)
- [ ] Terminal emulation (xterm.js integration)
- [ ] SSH connection handling
- [ ] Authentication (password + SSH keys)
- [ ] Session management (tabs/multiple connections)
- [ ] Deployment configuration
- [ ] Android PWA setup
- [ ] Documentation

## 🔄 v1.1+ Planned Features

- File transfer (SCP/SFTP)
- SSH key generation
- Two-factor authentication
- Mosh mobile shell support
- Port forwarding
- Session recording
- Dark/Light themes
- iOS app (when Apple Dev Program available)

## 🛠️ Tech Stack

**Frontend:**
- React.js / Next.js
- xterm.js (terminal emulation)
- Tailwind CSS (styling)
- WebSocket client

**Backend:**
- Node.js + Express.js
- ssh2 library (SSH connections)
- WebSocket server
- SQLite/PostgreSQL (connection storage)

**Mobile:**
- React Native (future Android/iOS)
- PWA support

## 📖 Documentation

- [Development Setup](docs/DEVELOPMENT.md)
- [Architecture Overview](docs/ARCHITECTURE.md)
- [API Documentation](docs/API.md)
- [Contributing Guide](CONTRIBUTING.md)

## 🤝 Contributing

Contributions are welcome! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## 📝 License

MIT License - feel free to use this project for personal or commercial purposes.

## 🐛 Issues & Support

Found a bug or have a feature request? [Open an issue on GitHub](https://github.com/themerchantgadget-source/mosshant/issues)

---

**Made with ❤️ by themerchantgadget-source**