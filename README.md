# Task Tracker

A simple, fast to-do app built with **React**. Add tasks, tick them off, filter by status, and your list is saved in the browser, so it's still there when you come back.

**Live demo:**file:///C:/Users/AHALYA%20SENAPATHI/Downloads/task%20tracker/task-tracker-react/task-tracker-react/index.html

## Features

- Add new tasks
- Mark tasks as done or not done
- Delete individual tasks
- Filter by **All**, **Active** or **Done**
- See how many tasks are left
- Clear all finished tasks in one click
- Tasks persist after refresh using `localStorage`
- Keyboard and screen reader friendly
- Responsive layout that works on phones and desktops

## Built with

- [React 18](https://react.dev/) (loaded from a CDN)
- [Babel Standalone](https://babeljs.io/docs/babel-standalone) to compile JSX in the browser
- HTML5 and CSS3 (Flexbox, CSS variables)
- GitHub Pages for hosting

## React concepts demonstrated

- Components and JSX
- State with `useState`
- Side effects with `useEffect`
- Event handling and controlled inputs
- Rendering lists with `map()` and `key`
- Conditional rendering
- Derived state and immutable updates

## Project structure

```
task-tracker/
├── index.html   # Page, React setup and the App component
├── style.css    # All styling
└── README.md    # Project description
```

## Getting started

No installation or build step is needed.

1. Clone or download this repository:
```bash
   git clone https://github.com/ahalya-senapathi/task-tracker.git
```
2. Open the folder and double-click `index.html` in your browser.

An internet connection is required, because React is loaded from a CDN.

## Deployment

The app is hosted with GitHub Pages:

1. Push the files to the `main` branch.
2. Go to **Settings → Pages**.
3. Set the source to **Deploy from a branch**, then choose `main` and `/ (root)`.

## Possible improvements

- Edit existing tasks
- Due dates and priorities
- Split the app into separate components
- Dark mode
- Sync across devices with a backend

## License

This project is open source and available under the [MIT License](LICENSE).
