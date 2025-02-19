# 🚀 Full-Stack Code Compiler

A blazing-fast online code compiler supporting multiple languages, built with Next.js, Express, and WebSockets. Execute code in real-time with a smooth developer experience.

## 🌟 Features

- 🖥️ **Multi-Language Support** – Compile and run multiple programming languages.
- ⚡ **Instant Execution** – Optimized for low-latency code execution.
- 🌐 **Web-Based** – No installation required, just open and start coding.
- 🔐 **Secure Execution** – Sandboxed environment to ensure safe code execution.
- 📜 **Syntax Highlighting** – Integrated with Monaco Editor for a smooth coding experience.
- 📡 **WebSockets Powered** – Live feedback and instant execution results.
- 🤓 **Supports Vim Mode** - Supports vim mode, so nerds can use it.


## 🌍 Live Demo

Check out the live version here: [Live Compiler](https://your-live-compiler-url.com)

> ⚠️ **Note:** The hosted version may not be blazingly fast due to VPS limitations (I'm running this on a budget 😅). Expect occasional delays in execution times.


## 🛠️ Tech Stack

- **Frontend:** Next.js, React, Code Mirror Editor
- **Backend:** Express.js, WebSockets
- **Database:** Prisma (if applicable)
- **Execution Engine:** Dockerized runtime

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:
- Node.js & npm
- Docker (if using testing execution)

### Installation

```bash
git clone https://github.com/wiper-r/code-compiler.git
cd code-compiler
pnpm install
```

### Running the Project

Start docker services:
```bash
docker compose -f docker-compose.dev.yml up
```

Start the project:
```bash
pnpm dev
```

Visit `http://localhost:3000` to start coding!

## 🤝 Contributing

Contributions are welcome! If you’d like to improve this project, feel free to:
- Open an issue for feature requests or bugs
- Submit a pull request with your improvements
- Star the repo to show support ⭐

## 📜 License

MIT License. Feel free to use, modify, and share!

---

Happy coding! 💻🔥
