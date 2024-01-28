# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

# Report

For this Assignment we got a task to identify a problem and create a Minimum Viable Product (MVP) using web technologies. We came along and chose to make a Wikipedia-style website that would help everyone thats looking for facts and answers. With this website we created, you simply search for what your looking for, and there yoi have it, just like Wikipedia.

The code for the website is a React application serving as a Wikipedia-style website. It employs the useState hook for state management and includes import statements for React's useState and an external CSS file for styling.

The primary component, App, manages three states: search for the search term, results for search results, and searchInfo for search-related information.

The core function, handleSearch, is triggered on form submission. It prevents default form behavior, checks for a non-empty search term, constructs the Wikipedia API endpoint, and fetches data. If successful, it updates the state with search results (setResults) and search information (setSearchInfo).

The JSX defines the user interface, featuring a title, search form, and section for displaying results. The form input is linked to the search state, and results are presented with titles, snippets, and "Read more" links.

Considerations for improvement include adding error handling for fetch operations and implementing loading indicators for a smoother user experience.

In summary, the code effectively uses React and useState to create a dynamic Wikipedia search interface, with handleSearch managing data fetching and state updates, and JSX defining the UI structure.
