# React Design Pattern (React + Vite)

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh


# Layout Components (Main branch)
This repository helps us follow better design patterns for client-side code, making it easier to maintain.

- The first part shows how to split a page into multiple sections without repeating the logic in each component.

- The second part shows how to implement a dynamic iterator.
Let's call this component <b>'RegularList'</b>. It is responsible for iterating over a collection. We can reuse it multiple times to avoid using <i>.map()</i> repeatedly.

- The last part demonstrates how to implement dynamic modals in the project.

# Container Components (Container branch)
- To dynamically parse the return value of an API.

# Controlled and Uncontrolled Components (ControlledUncontrolled branch)
- An effective approach to implementing both controlled and uncontrolled components.
