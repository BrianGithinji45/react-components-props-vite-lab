# Blog Site - React Components and Props Lab

Personal blog built with React.

## Component Tree
App
├── Header
├── About
└── ArticleList
    └── Article

## How to Run
npm install
npm run dev

## How to Test
npm test

## Components
- Header: receives `name` prop, renders `<header>` + `<h1>`
- About: receives `image`, `about` props, renders `<aside>` + `<img alt="blog logo">` + `<p>`
- ArticleList: receives `posts` prop, renders `<main>` and maps to Article with unique `key`
- Article: receives `title`, `date`, `preview` props, renders `<article>` + `<h3>` + `<small>` + `<p>`