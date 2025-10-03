# ChemAI - Your Personal AI Chemistry Tutor

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/tanishvishal09-ctrl/CodeVibe-AI?style=social)](https://github.com/tanishvishal09-ctrl/CodeVibe-AI/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/tanishvishal09-ctrl/CodeVibe-AI?style=social)](https://github.com/tanishvishal09-ctrl/CodeVibe-AI/network/members)

![ChemAI Demo](https://www.chemai.in/opengraph-image.png)

> **Live Application:** **[https://www.chemai.in/](https://www.chemai.in/)**

An AI-powered web application designed to revolutionize chemistry education. ChemAI provides students with an intelligent, interactive, and accessible platform to solve complex chemistry problems, visualize molecules in 3D, and learn through a conversational AI tutor.

---

## 📋 Table of Contents

- [About The Project](#about-the-project)
- [Key Features](#-key-features)
- [Tech Stack](#-tech-stack)
- [Getting Started](#-getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Roadmap](#-roadmap)
- [Contact](#-contact)

## About The Project

Studying chemistry can be challenging due to its abstract concepts and complex problem-solving. ChemAI was built to bridge this gap by leveraging the power of Artificial Intelligence. It serves as a 24/7 personal tutor that helps students not just find answers, but understand the underlying principles behind them.

This project showcases a modern full-stack application with a sophisticated frontend, a robust backend, and seamless integration with advanced AI models.

## ✨ Key Features

-   **🤖 AI Problem Solver:** Get step-by-step solutions to a wide range of chemistry questions.
-   **🔬 Interactive 3D Molecule Viewer:** Input a molecule name (like "caffeine") and visualize its 3D structure. Interact with it by rotating and zooming.
-   **💬 Conversational AI Tutor:** Engage in a dialogue with an AI tutor to ask follow-up questions and deepen your understanding of various topics.
-   **📚 Comprehensive Coverage:** Handles problems from Organic, Inorganic, and Physical Chemistry.
-   **📱 Responsive Design:** Fully functional and intuitive UI for both desktop and mobile devices.

## 🛠️ Tech Stack

This project is built with a modern technology stack:

* **Frontend:**
    * [Next.js](https://nextjs.org/)
    * [React](https://reactjs.org/)
    * [Tailwind CSS](https://tailwindcss.com/)
    * [Framer Motion](https://www.framer.com/motion/)
* **Backend:**
    * [Node.js](https://nodejs.org/)
    * [Express.js](https://expressjs.com/) * **AI & APIs:**
    * [Google Gemini / OpenAI GPT API](https://openai.com/blog/openai-api) * [Vercel AI SDK](https://sdk.vercel.ai/docs)
* **Deployment:**
    * [Vercel](https://vercel.com/)

## 🚀 Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

Make sure you have Node.js and npm (or yarn) installed on your machine.
* `npm`
    ```sh
    npm install npm@latest -g
    ```

### Installation

1.  **Clone the repository**
    ```sh
    git clone [https://github.com/tanishvishal09-ctrl/CodeVibe-AI.git](https://github.com/tanishvishal09-ctrl/CodeVibe-AI.git)
    ```
2.  **Navigate to the project directory**
    ```sh
    cd CodeVibe-AI
    ```
3.  **Install NPM packages**
    ```sh
    npm install
    ```
4.  **Set up environment variables**
    Create a `.env.local` file in the root directory and add your API keys:
    ```env
    # Example
    NEXT_PUBLIC_API_ENDPOINT=http://localhost:3000/api
    GEMINI_API_KEY="YOUR_AI_API_KEY"
    ```
5.  **Run the development server**
    ```sh
    npm run dev
    ```
    Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Usage

Once the application is running, you can:
1.  Navigate to the "Solver" page to input chemistry problems.
2.  Use the "Molecule Viewer" to search for and interact with 3D molecular models.
3.  Open the "AI Tutor" chat to ask conceptual questions and get detailed explanations.

## 🗺️ Roadmap

-   [ ] User authentication and profile management to save query history.
-   [ ] Gamified quizzes and progress tracking.
-   [ ] Support for drawing chemical structures as input.
-   [ ] Expanding the database for the 3D molecule viewer.

See the [open issues](https://github.com/tanishvishal09-ctrl/CodeVibe-AI/issues) for a full list of proposed features (and known issues).

## 📧 Contact

Tanish Vishal - [@tanishvishal09-ctrl](https://github.com/tanishvishal09-ctrl)

Project Link: [https://github.com/tanishvishal09-ctrl/CodeVibe-AI](https://github.com/tanishvishal09-ctrl/CodeVibe-AI)
