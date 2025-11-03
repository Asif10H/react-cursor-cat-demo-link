# React Cursor Cat

# [Live Demo](https://react-cursor-catt.netlify.app/)

> A simple React component that adds the classic `oneko.js` cat to your website. The cat will chase your mouse cursor around the screen, bringing nostalgic fun to your React projects.

[![npm version](https://img.shields.io/npm/v/react-cursor-cat.svg)](https://www.npmjs.com/package/react-cursor-cat)
[![npm downloads](https://img.shields.io/npm/dm/react-cursor-cat.svg)](https://www.npmjs.com/package/react-cursor-cat)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

This component is a React-friendly wrapper for the original [oneko.js]() vanilla JavaScript code, using `useEffect` for proper mounting and cleanup. It's lightweight, dependency-free, and brings a fun, nostalgic touch to any React project.

---

## ✨ Features

- 🎯 **Easy to Use** — Just one line of code to get it running
- ⚛️ **React-Friendly** — Safely implemented using the `useEffect` hook
- 🧹 **Safe Cleanup** — Automatically removes the cat and event listeners on unmount
- 📦 **Zero Dependencies** — Runs entirely on its own
- 🎨 **Customizable** — Pass in any CSS filter to change the cat's color or appearance
- 🪶 **Lightweight** — Minimal bundle size impact

---

## 📦 Installation

Install the package using npm or yarn:

```bash
npm install react-cursor-cat
```

or

```bash
yarn add react-cursor-cat
```

---

## 🚀 Quick Start

Import the component into your React app and use it anywhere:

That's it! The cat will now follow your mouse cursor across the screen.

```jsx
import Oneko from "react-cursor-cat";

function App() {
  return (
    <div>
      {/* Default cat */}
      <Oneko />
    </div>
  );
}
```

---

## 🛠️ How It Works

The component uses React's `useEffect` hook to:

1. Create the cat sprite element on component mount
2. Add mouse movement event listeners
3. Update the cat's position and animation based on cursor movement
4. Clean up the sprite and event listeners on component unmount

This ensures proper integration with React's lifecycle and prevents memory leaks.

---

## 📖 Examples

### Basic Usage

```jsx
import Oneko from "react-cursor-cat";

function App() {
  return (
    <>
      <Oneko />
      <h1>
        A simple React component that adds the classic oneko.js cat to your
        website. The cat will chase your mouse cursor around the screen.
      </h1>
    </>
  );
}

export default App;
```

---

## 🌐 Browser Compatibility

Works in all modern browsers that support:

- React 16.8+ (Hooks)

---

## 🤝 Contributing

Contributions are welcome! If you find a bug or have a feature request, please open an issue on [GitHub](https://github.com/asif10h/react-cursor-cat).

---

## 📝 License

MIT © [Habibullah Md Asif]

---

## 🙏 Credits

- Original [oneko.js](https://github.com/adryd325/oneko.js) by [adryd](https://github.com/adryd325)
- Cat sprite from the classic Oneko desktop pet

---

## ⭐ Show Your Support

If you like this project, please consider giving it a ⭐️ on [GitHub](https://github.com/asif10h/react-cursor-cat)!

---
