# PasteApp 📋

A modern, responsive web application for creating, storing, and managing text snippets/pastes. Built with React and powered by Vite for optimal performance.

## 🌐 Live Demo

**[Try PasteApp Live](https://paste-app-xi.vercel.app/)**

## ✨ Features

- **Create Pastes**: Write and save text snippets with custom titles
- **Edit Pastes**: Modify existing pastes easily
- **View Pastes**: Browse all your saved pastes in a clean interface
- **Copy to Clipboard**: One-click copying of paste content
- **Local Storage**: All pastes are stored locally in your browser
- **Responsive Design**: Works perfectly on desktop and mobile devices
- **Toast Notifications**: User-friendly feedback for all actions

## 🛠️ Tech Stack

- **Frontend**: React 18.3.1
- **Build Tool**: Vite 5.4.9
- **State Management**: Redux Toolkit
- **Routing**: React Router DOM
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **Notifications**: React Hot Toast
- **Code Quality**: ESLint

## 🚀 Getting Started

### Quick Start

🔗 **[Access the live application](https://paste-app-xi.vercel.app/)** - No installation required!

### Local Development

#### Prerequisites

#### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn

#### Installation

1. Clone the repository:
```bash
git clone https://github.com/yashsinghal14/PasteApp.git
cd paste-app
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173`

## 📝 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## 📁 Project Structure

```
src/
├── components/
│   ├── Home.jsx          # Main page for creating/editing pastes
│   ├── Navbar.jsx        # Navigation component
│   ├── Paste.jsx         # All pastes listing page
│   └── ViewPaste.jsx     # Individual paste view page
├── redux/
│   ├── store.js          # Redux store configuration
│   └── pasteSlice.js     # Paste state management
├── utils/
│   └── formatDate.js     # Date formatting utilities
├── data/
│   └── Navbar.js         # Navigation data
└── assets/
    └── react.svg         # Static assets
```

## 🎯 Usage

1. **Create a Paste**: Go to the home page, enter a title and content, then click "Create My Paste"
2. **View All Pastes**: Navigate to the "Pastes" section to see all your saved pastes
3. **Edit a Paste**: Click on any paste to view it, then use the edit functionality
4. **Copy Content**: Use the copy button to quickly copy paste content to clipboard
5. **Delete Pastes**: Remove unwanted pastes from your collection

## 🔧 Configuration

The project uses several configuration files:

- `vite.config.js` - Vite configuration
- `tailwind.config.js` - Tailwind CSS configuration
- `postcss.config.js` - PostCSS configuration
- `eslint.config.js` - ESLint configuration

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Yash Singhal**
- GitHub: [@yashsinghal14](https://github.com/yashsinghal14)

## 🙏 Acknowledgments

- React team for the amazing framework
- Vite team for the blazing fast build tool
- All the open-source contributors who made this project possible
