# 🧠 AI Resume Analyzer

A modern, production-ready full-stack application built using the React Router framework, designed to analyze, parse, and optimize professional CVs using AI-driven insights.

---

## 🚀 Features

- 🤖 **AI-Powered Analysis:** Automatically parses resumes to extract skills, evaluate formatting, and provide tailored optimization feedback.
- ⚡ **High Performance:** Built with Server-Side Rendering (SSR) and seamless Hot Module Replacement (HMR) for an ultra-fast user experience.
- 🎨 **Modern Interface:** Fully responsive, interactive, and sleek UI crafted using TailwindCSS.
- 📦 **Asset Bundling:** Highly optimized asset delivery and production compilation pipelines.
- 🔒 **Type Safe:** Architected from the ground up using TypeScript for robust code reliability.

---

## 🛠️ Tech Stack

- **Frontend Core:** React, React Router v7 / Remix core, TypeScript
- **Styling:** TailwindCSS
- **DevOps & Infrastructure:** Docker (Containerized development and deployment)
- **Deployment Platform:** Vercel

---

## ⚙️ Getting Started

### 1. Installation
Clone the repository and install the required workspace dependencies:
```bash
npm install
```

### Development

Start the development server with HMR:

```bash
npm run dev
```

Your application will be available at `http://localhost:5173`.

## Building for Production

Create a production build:

```bash
npm run build
```

## Deployment

### Docker Deployment

To build and run using Docker:

```bash
# Build the Docker image
docker build -t ai-resume-analyzer .

# Run the containerized instance
docker run -p 3000:3000 ai-resume-analyzer
```

##Cloud Production Deployment
The production deployment pipeline is configured to automatically build and ship the static client assets and server logic straight to Vercel.

Make sure to deploy the output of `npm run build`

```
├── package.json
├── package-lock.json (or pnpm-lock.yaml, or bun.lockb)
├── build/
│   ├── client/    # Static assets
│   └── server/    # Server-side code
```

Built with ❤️ by Sthitiprajna Dash
