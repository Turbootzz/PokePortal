---
# 🎮 PokéPortal - Your Ultimate Pokémon Game Hub

Welcome to **PokéPortal**, the central hub for a collection of fun and challenging Pokémon mini-games. Built with a modern, performant tech stack, this portal serves as a fast and beautiful gateway to different game experiences.

This project is a standalone landing page, designed to be easily extendable as new games are developed.

<!-- Screenshot URLS coming soon.. -->
---

## ✨ Features

- **Blazing Fast Performance**: Built with [Astro](https://astro.build) for a super-fast, static-first experience with zero client-side JavaScript by default.
- **Centralized Game Access**: A single, elegant page to launch all available Pokémon games.
- **Visually Appealing UI**: Styled with [Tailwind CSS](https://tailwindcss.com/) for a clean, modern, and responsive design with a retro gaming feel.
- **Extensible by Design**: Easily add new "game cards" for future projects like "Who's That Pokémon?" or "Guess The Shiny".
- **Future-Ready**: Prepared for a centralized authentication system that can be shared across all games.

---

## 🕹️ Featured Games

| Game Title              | Status         | Description                                                       |
| ----------------------- | -------------- | ----------------------------------------------------------------- |
| **Guess The Cry**       | ✅ **Active**  | Listen to the cry and guess the Pokémon. A true test for any fan! |
| **Who's That Pokémon?** | ⏳ Coming Soon | A classic silhouette challenge. Can you identify them all?        |
| **Guess The Shiny**     | ⏳ Coming Soon | Spot the difference! Pick the correct shiny from a lineup.        |

---

## 🛠️ Tech Stack

This project leverages a modern, performance-focused frontend stack:

| Category           | Technology                                        |
| ------------------ | ------------------------------------------------- |
| Core Framework     | [**Astro**](https://astro.build)                  |
| UI Components      | Astro Components (`.astro`)                       |
| Styling            | [**Tailwind CSS**](https://tailwindcss.com/)      |
| Code & Types       | [**TypeScript**](https://www.typescriptlang.org/) |
| Development Server | [**Vite**](https://vitejs.dev/)                   |

---

## ⚙️ Getting Started

To get the PokePortal running on your local machine, follow these steps.

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or higher recommended)
- `npm` or `yarn`

### Installation & Setup

1.  **Clone the repository** (if you haven't already):

    ```bash
    git clone https://github.com/Turbootzz/PokePortal.git
    cd poke-portal
    ```

2.  **Install dependencies**:

    ```bash
    npm install
    ```

3.  **Run the development server**:

    ```bash
    npm run dev
    ```

4.  **Open your browser**:
    Navigate to `http://localhost:4321` to see the PokePortal live!

### Available Scripts

- `npm run dev`: Starts the local development server with Hot Module Replacement (HMR).
- `npm run build`: Creates a production-ready, optimized build of the site in the `dist/` folder.
- `npm run preview`: Starts a local server to preview your production build.
- `npm run format`: Formats all code using [Prettier](https://prettier.io/) for consistent styling.

---

## 📁 Project Structure

```
/
├── public/                 # Static assets (images, favicons, etc.)
│   └── gen-backgrounds/
├── src/
│   ├── components/         # Reusable Astro/UI Framework components
│   │   └── GameCard.astro
│   ├── layouts/            # Base page layouts
│   │   └── Layout.astro
│   ├── pages/              # Astro pages, which become routes
│   │   └── index.astro
│   └── styles/             # Global CSS and Tailwind configuration
│       └── global.css
├── astro.config.mjs        # Astro configuration file
├── tailwind.config.mjs     # Tailwind CSS configuration file
└── package.json            # Project dependencies and scripts
```

---

## 🛑 Disclaimer

This is a fan-made project created for educational and entertainment purposes only. It is not affiliated with, sponsored, or endorsed by Nintendo, Game Freak, or The Pokémon Company. All Pokémon-related trademarks, names, sounds, and images are the property of their respective owners.

---

## 🙌 Credits

Made by **Thijs Herman** ([@Turbootzz](https://github.com/Turbootzz))
