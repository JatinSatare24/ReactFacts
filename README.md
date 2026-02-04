# ReactFacts ⚛️

**ReactFacts** is a static informational site built as a foundational project in the Scrimba "Learn React" course. This project focuses on the core principles of React, including component-based architecture, declarative programming, and modern styling techniques.

## 🚀 Key Features

* **Modular Component Architecture**: Deconstructs the UI into independent, reusable components like `Navbar` and `MainContent`.
* **Declarative UI**: Leverages JSX to describe the interface based on its current state, moving away from imperative DOM manipulation.
* **Modern CSS Integration**: Implements scoped styling and custom background logos to match professional Figma designs.
* **Local Development Workflow**: Configured with **Vite** for a high-performance development experience and HMR (Hot Module Replacement).

## 🛠️ Tech Stack

* **Library**: React 18+
* **Build Tool**: Vite
* **Frontend**: JSX, CSS3 (Custom Variables & Positioning)
* **Language**: JavaScript (ES6+)

## 📂 Project Structure

```text
├── src/
│   ├── components/
│   │   ├── Navbar.jsx    # Header with React logo and title
│   │   └── Main.jsx      # List of React fun facts
│   ├── App.jsx           # Main application container
│   ├── index.css         # Global styles and layout logic
│   └── main.jsx          # Entry point for the React DOM
├── public/               # Static assets (React logo)
└── index.html            # Main HTML skeleton
