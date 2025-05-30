# Learn & Master GitHub Actions

This is a simple React application to help you learn the basics of Git, GitHub, and GitHub Actions. The project demonstrates a basic React setup using [Vite](https://vitejs.dev/) and includes automated tests with [Vitest](https://vitest.dev/) and [Testing Library](https://testing-library.com/).

## Features

- React 18 with functional components and hooks
- Modular component structure
- CSS modules for styling
- Automated testing with Vitest and Testing Library
- Linting with ESLint

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v16 or higher recommended)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
   ```

2. Install dependencies:

   ```sh
   npm install
   # or
   yarn install
   ```

### Running the App

Start the development server:

```sh
npm run dev
# or
yarn dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser to view the app.

### Running Tests

To run all tests:

```sh
npm test
# or
yarn test
```

### Linting

To lint and auto-fix code:

```sh
npm run lint
# or
yarn lint
```

## Project Structure

```
index.html
package.json
vite.config.js
public/
src/
  App.jsx
  index.css
  main.jsx
  assets/
    images/
      logo.png
  components/
    HelpArea.css
    HelpArea.jsx
    HelpBox.css
    HelpBox.jsx
    MainContent.jsx
    MainContent.test.jsx
  test/
    setup.js
```

## License

This project is licensed under the MIT License.