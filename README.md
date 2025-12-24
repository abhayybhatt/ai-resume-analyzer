# Resum8: AI Resume Analyzer

An AI-powered resume analyzer that provides ATS (Applicant Tracking System) scores and personalized feedback for job applications. Upload your resume, provide job details, and get instant AI-powered insights to improve your chances of landing your dream job.

<div align="center">

**🌐 [Live Demo](https://ai-resume-analyzer-one-mocha.vercel.app/)** | [GitHub Repository](https://github.com/abhayybhatt/ai-resume-analyzer)

  <img alt="Static Badge" src="https://img.shields.io/badge/React-4c84f3?style=for-the-badge&logo=react&logoColor=white">
  <img src="https://img.shields.io/badge/-Tailwind-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />
  <img src="https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logoColor=white&logo=typescript&color=3178C6" alt="TypeScript" />
  <img alt="Static Badge" src="https://img.shields.io/badge/Puter.js-181758?style=for-the-badge&logoColor=white">

</div>

## ✨ Features

- 🔐 **Browser-based Authentication**: Seamless authentication using Puter.js—no backend setup required
- 📄 **Resume Upload & Storage**: Upload and securely store multiple resumes in one place
- 🤖 **AI-Powered Analysis**: Get instant ATS scores and personalized feedback tailored to specific job listings
- 📊 **Detailed Feedback**: Receive comprehensive analysis including strengths, weaknesses, and improvement suggestions
- 🎨 **Modern UI/UX**: Clean, responsive design built with Tailwind CSS
- 📱 **Cross-Device Compatible**: Fully responsive design that works seamlessly across all devices
- ⚡ **Fast & Efficient**: Built with React Router v7 and Vite for optimal performance

## 🛠️ Tech Stack

- **[React](https://react.dev/)** - UI library for building user interfaces
- **[React Router v7](https://reactrouter.com/)** - Routing library with SSR support
- **[Puter.js](https://jsm.dev/resumind-puterjs)** - Client-side SDK for auth, storage, and AI capabilities
- **[Tailwind CSS](https://tailwindcss.com/)** - Utility-first CSS framework
- **[TypeScript](https://www.typescriptlang.org/)** - Typed superset of JavaScript
- **[Vite](https://vite.dev/)** - Fast build tool and dev server
- **[Zustand](https://github.com/pmndrs/zustand)** - Lightweight state management
- **[PDF.js](https://mozilla.github.io/pdf.js/)** - PDF rendering and processing

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/) (v20 or higher)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

1. Clone the repository:

```bash
git clone https://github.com/abhayybhatt/ai-resume-analyzer.git
cd ai-resume-analyzer
```
2. Install dependencies:

```bash
npm install
```
3. Start the development server:

```bash
npm run dev
```
4. Open http://localhost:5173 in your browser

## 📦 Building for Production

Create a production build:

```bash
npm run build
```
The build output will be in the `build/` directory:
- `build/client/` - Static assets
- `build/server/` - Server-side code (if SSR is enabled)

## 🚢 Deployment

### Deploy to Vercel

This project is configured for easy deployment on Vercel:

1. Push your code to GitHub
2. Import your repository in [Vercel](https://vercel.com)
3. Vercel will auto-detect the settings
4. Click "Deploy"

The project is configured with:
- Build Command: `npm run build`
- Output Directory: `build/client`
- Framework: React Router

### Manual Deployment

For other platforms, ensure you deploy the `build/` directory along with `package.json` and `package-lock.json`.

## 📁 Project Structure
```bash
ai-resume-analyzer/
├── app/
│ ├── components/ # Reusable React components
│ ├── lib/ # Utility functions and libraries
│ ├── routes/ # Route components
│ └── root.tsx # Root layout component
├── api/ # Serverless functions (for SSR)
├── public/ # Static assets
├── constants/ # App constants
├── types/ # TypeScript type definitions
└── vercel.json # Vercel configuration
```
## 🎯 Usage

1. **Sign In**: Authenticate using Puter.js (no backend required)
2. **Upload Resume**: Upload your resume PDF
3. **Enter Job Details**: Provide company name, job title, and job description
4. **Get Analysis**: Receive instant ATS score and AI-powered feedback
5. **Review Results**: View detailed analysis and improvement suggestions

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/abhayybhatt/ai-resume-analyzer/issues).

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Built with [React Router](https://reactrouter.com/)
- Powered by [Puter.js](https://puter.com/) for backend services
- Styled with [Tailwind CSS](https://tailwindcss.com/)
