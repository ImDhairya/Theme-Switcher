# React + Vite
Project Description: 

This application leverages the power of React’s useContext hook to seamlessly switch between light and dark themes. Here’s a brief overview:

1️⃣ Theme Context: Created a context using createContext that holds the current theme mode and two functions to switch between these modes.

2️⃣ Theme Provider: Used the ThemeProvider to pass down the current theme mode and the theme switching functions as context values to the components.

3️⃣ Custom Hook: Developed a custom hook useTheme that uses useContext to access the current context value.

4️⃣ Theme Switching: Implemented a toggle button that switches the theme mode based on its checked status.


This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
