# PixelPals

**PixelPals** is a real-time multiplayer drawing and guessing game where players create and guess custom word lists. The game includes features like hints, leaderboards, and multilingual support, providing a fun and engaging experience for players on both desktop and mobile devices.

---

## Project Overview

### Features
- **Custom Word Lists**: Players can create, view, edit, and delete custom word lists for gameplay.
- **Real-Time Drawing and Guessing**: Live interaction via a drawing canvas and guessing area.
- **Hints and Progressive Reveal**: Players can request hints to reveal letters of the word.
- **Leaderboard**: Tracks and displays top scores in real time.
- **Multilingual Support**: Translates word lists to a user’s preferred language using Google Translate API.
- **Mobile-Responsive Design**: Optimized for desktop and mobile devices.

---

## Getting Started

### Prerequisites
Ensure you have the following installed on your machine:
- **Node.js**: Download and install the latest LTS version from [nodejs.org](https://nodejs.org).
- **npm**: Comes with Node.js installation.
- **Git**: Install Git from [git-scm.com](https://git-scm.com/).

---

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/fiyinfoluwaafol/pixel-pals.git
   ```
2. **Navigate to the frontend directory**:
   ```bash
   cd pixel-pals/frontend
   ```
3. **Install dependencies**:
    ```
    npm install
    ```
4. **Start the development server**:
    ```
    npm start
    ```
The application will be available at `http://localhost:3000` in your browser.
---

## Project Structure

```plaintext
ScribbleScape/
├── frontend/      # React app files
│   ├── src/       # React components and logic
│   ├── public/    # Static assets
│   └── package.json # Frontend dependencies
├── backend/       # Backend logic
├── docs/          # Documentation files
└── README.md      # Project overview
```