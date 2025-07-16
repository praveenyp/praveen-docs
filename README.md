# LiveDocs (Praveen-Docs)

[![Next.js](https://img.shields.io/badge/Next.js-13+-black?logo=nextdotjs)](https://nextjs.org/) [![TypeScript](https://img.shields.io/badge/TypeScript-blue?logo=typescript)](https://www.typescriptlang.org/) [![TailwindCSS](https://img.shields.io/badge/TailwindCSS-38B2AC?logo=tailwindcss&logoColor=white)](https://tailwindcss.com/) [![Liveblocks](https://img.shields.io/badge/Liveblocks-RealTime-blueviolet)](https://liveblocks.io/)

---

A modern, collaborative document editor inspired by Google Docs. Built with Next.js, Liveblocks, and Tailwind CSS, LiveDocs enables real-time editing, seamless collaboration, and robust document management—all with a beautiful, responsive UI.

---

## Table of Contents
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

---

## Features

- **Authentication:** Secure sign-in/out and session management (GitHub via NextAuth/Clerk)
- **Real-Time Collaboration:** Multiple users can edit documents simultaneously with instant updates
- **Document Management:**
  - Create, list, search, and sort documents
  - Delete owned documents
  - Share documents via email or link with view/edit permissions
- **Comments:** Inline and general comments with threaded discussions
- **Active Collaborators:** Real-time presence indicators for active users
- **Notifications:** Alerts for shares, comments, and collaborator activities
- **Responsive Design:** Optimized for all devices
- **Extensible & Reusable Architecture**

---

## Tech Stack

- **Framework:** Next.js 13+
- **Language:** TypeScript
- **Realtime:** Liveblocks
- **Authentication:** Clerk / NextAuth (GitHub)
- **Editor:** Lexical Editor
- **UI Components:** ShadCN
- **Styling:** Tailwind CSS

---

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/praveen-docs.git
   cd praveen-docs
   ```
2. **Install dependencies:**
   ```bash
   npm install
   # or
   yarn install
   ```
3. **Set up environment variables:**
   - Copy `.env.example` to `.env.local` and fill in required values (API keys, etc.)
4. **Run the development server:**
   ```bash
   npm run dev
   # or
   yarn dev
   ```
5. **Open in browser:**
   Visit [http://localhost:3000](http://localhost:3000)

---

## Usage
- Sign in with your GitHub account
- Create, edit, and share documents
- Collaborate in real-time with others
- Add and reply to comments
- Manage your documents from the dashboard

---

## Contributing

Contributions are welcome! Please open issues or submit pull requests for improvements and bug fixes.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a pull request

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details. 

