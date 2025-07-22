# 🔍 Danny's Pokédex

Welcome to **Danny's Pokédex**, a responsive web app built with **React** and **Vite**. This application allows you to explore the first 151 Pokémon, view their stats, images, types, and move descriptions — all fetched live from the PokéAPI and cached for performance.

---

## 📁 Project Structure

```
.
├── public/
│   └── pokemon/             # Static images for Pokémon (001.png to 151.png)
├── src/
│   ├── components/
│   │   ├── Header.jsx       # Header with hamburger menu
│   │   ├── Modal.jsx        # Reusable modal component
│   │   ├── PokeCard.jsx     # Pokémon detail view
│   │   ├── SideNav.jsx      # Sidebar for search and selection
│   │   └── TypeCard.jsx     # Type tile component
│   ├── utils.js             # Utility functions (type colors, number formatting)
│   ├── App.jsx              # Main layout and state management
│   ├── main.jsx             # Entry point for rendering
│   ├── index.css            # Global CSS
│   └── fanta.css            # Additional styles
└── index.html               # HTML template
```

---

## ✨ Features

- 🔎 **Searchable Sidebar:** Quickly find Pokémon by name or number.
- 🧬 **Detailed View:** Shows stats, types, and image variations.
- 🌀 **Moves with Descriptions:** Click any move to open a modal with its description.
- ⚡ **Local Storage Caching:** Pokémon and move data are cached for faster access.
- 📱 **Responsive Design:** Mobile and desktop friendly layout.

---

## 🛠 Technologies Used

- **React** (with Hooks)
- **Vite** (blazing-fast dev server & build tool)
- **PokéAPI** ([pokeapi.co](https://pokeapi.co))
- **Font Awesome** (icon library)
- **localStorage** (browser-side caching)

---

## 🚀 Getting Started

### ✅ Prerequisites

- [Node.js](https://nodejs.org/) (v16+)
- npm or yarn

### 🧩 Installation

```bash
# Clone the repository
git clone https://github.com/your-username/dannys-pokedex.git
cd dannys-pokedex

# Install dependencies
npm install
# or
yarn install
```

### 🔧 Running Locally

```bash
npm run dev
# or
yarn dev
```

Visit [http://localhost:5173](http://localhost:5173) in your browser.

---

## 📦 Future Improvements

- Add support for more than 151 Pokémon.
- Display evolution chains and species data.
- Enhance mobile experience with animations.
- Add loading/error states for modal and sidebar.
- Refactor `showSideMenu` logic for clarity.

---

## 🙌 Acknowledgments

- Powered by the amazing [PokéAPI](https://pokeapi.co).
- Inspired by the original Pokédex UI from Pokémon games.

---

## 📄 License

MIT License — free to use, modify, and distribute.

---

> Made with ❤️ by Danny
