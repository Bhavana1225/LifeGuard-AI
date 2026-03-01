# LifeGuard AI - Health Risk Assessment

A modern, AI-powered health risk assessment tool built with React, Tailwind CSS, and Gemini AI.

## Features

- **Health Risk Analysis**: AI-driven assessment based on your symptoms and history.
- **Symptom Relief**: Quick suggestions for common ailments.
- **AI Chat Assistant**: Interactive health guidance.
- **Mock Mode**: Test the UI without API calls using `VITE_AI_MODE="mock"`.

## Local Setup

To run this project locally in VS Code:

### 1. Prerequisites

- [Node.js](https://nodejs.org/) (v18 or higher)
- [npm](https://www.npmjs.com/)

### 2. Installation

Clone the repository and install dependencies:

```bash
npm install
```



### 3. Running the App

#### Option A: Using VS Code (Recommended)
1. Open the project in VS Code.
2. Press **F5** or go to the **Run and Debug** tab and click **Launch App (Dev)**.
3. The app will be available at [http://localhost:3000](http://localhost:3000).

#### Option B: Using Terminal
Run the development server:

```bash
npm run dev
```

### 4. Building for Production

To create a production-ready build:

```bash
npm run build
```

The output will be in the `dist` folder.

## Technologies Used

- **Frontend**: React 19, Vite, Tailwind CSS 4
- **AI**: Google Gemini API (@google/genai)
- **Animation**: Motion (formerly Framer Motion)
- **Icons**: Lucide React
- **Charts**: Recharts
