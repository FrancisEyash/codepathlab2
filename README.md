# Lab 2 project

In this lab, you will create a game called Samosa Selector that is based on an incremental game called Cookie Clicker. The goal of the game is to produce as many cookies by clicking on the Big Cookie as you can. However, in this version, instead of clicking a cookie, the user will be selecting a delicious samosa.

Gameplay
The game starts out with the user having zero samosas. When the user clicks the Big Samosa, it initially produces one samosa per click. Then,

When the user has 10 samosas, they can buy a Double Stuffed upgrade, which produces double the amount of samosas per click.
When the user has 100 samosas, they can buy the Party Pack upgrade, which produces 5x the amount of samosas per click.
When the user has 1000 samosas, they can buy the Full Feast upgrade, which produces 10x the amount of samosas per click.
The game continues on forever and the user can continue to gain gigantic amounts of samosas. Yum!

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
