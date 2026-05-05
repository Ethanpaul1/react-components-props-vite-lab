# React Components and Props Blog Lab

This project is a static personal blog built with React and Vite. It practices
creating components, writing JSX, and passing data through props.

## Component Tree

```txt
App
|-- Header
|-- About
`-- ArticleList
    `-- Article
```

## Component Responsibilities

- `App` imports `src/data/blog.js` and passes blog data into child components.
- `Header` receives the blog `name` prop and renders it in an `h1`.
- `About` receives `image` and `about` props and renders the blog logo and intro.
- `ArticleList` receives the `posts` array and renders one `Article` per post.
- `Article` receives `title`, `date`, and `preview` props and renders a post preview.

## Run the Project

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Run the tests:

```bash
npm test -- --run
```

Build the production version:

```bash
npm run build
```

## Screenshot

![Blog site screenshot](./images/demo.png)

## Submission Checks

The project passes:

- `npm run lint`
- `npm test -- --run`
- `npm run build`
