# Graphql Fullstack MERN App

This is a solution to the [GraphQL Crash Course in 2024 - Build a Full Stack MERN App Project](https://www.youtube.com/watch?v=Vr-QHtbmd38&t=30s). I'm practicing and developing my coding competency by building projects after projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
  - [Author](#author)
  - [Acknowledgments](#acknowledgments)

## Overview

### The Challenge/User Stories

Build a GraphQL full-stack expense tracker app with Express, MongoDB, React, and Apollo.

### Screenshot

![](/screenshot-desktop.png)

### Links

- Solution URL: [https://github.com/traez/graphql-full-stack-mern-app](https://github.com/traez/graphql-full-stack-mern-app)
- Live Site URL: [https://graphql-full-stack-mern-app.onrender.com/](https://graphql-full-stack-mern-app.onrender.com/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox and CSS Grid
- Mobile-first workflow
- [React](https://reactjs.org/) - JS library
- [Next.js](https://nextjs.org/) - React framework
- Tailwind CSS
- Typescript**
- Nodejs (with/without Expressjs)
- MongoDB
- GraphQL  
- React Native**  

### What I learned

- **GraphQL Explorer**: Using Ctrl + Space provides autocompletion for faster development.  
- **Data Modeling**: While both the `typeDef` file and the `model` define data structure, they serve different purposes:
`typeDef` file: Defines the GraphQL schema (what data is exposed to the client).  
`model`: Defines the data structure for interacting with the MongoDB database.    
- **Passport.js Integration**: Passport.js is a popular Node.js middleware for authentication. It's graphql-passport dependency simplifies integrating Passport.js with GraphQL resolvers.  
- **Environment Variables**:  
`.env` files store environment variables in both Next.js and MERN stacks.   
Use `process.env` directly for server-side operations.  
Next.js offers `NEXT_PUBLIC_` in `next.config.js` to expose safe variables to the client-side while keeping sensitive information secure.  
- **ESLint Configuration**: Setting `"react/prop-types": "off"` in `.eslintrc.cjs` disables prop type linting (removes red squiggly lines).  
- **GraphQL Architecture**: Client-side queries (e.g., `user.query.js`) trigger server-side resolvers (e.g., `userResolver.js`) that manage user data and authentication logic (defined in `userTypeDef.js`).  
Communication happens through GraphQL queries and responses.  
- **VsCode Navigation**: In-code bookmarking and navigation use comments as markers for quick access using search functionality.  
- **GraphQL Cache Management**: Clearing the GraphQL cache upon logout is crucial for data security, privacy, and a seamless user experience in multi-user Next.js applications.  
Use appropriate GraphQL client methods to ensure users only see their own data.   

### Continued development

- More projects; increased competence!

### Useful resources

Stackoverflow  
YouTube  
Google  
ChatGPT

## Author

- Website - [Trae Zeeofor](https://github.com/traez)
- Twitter - [@trae_z](https://twitter.com/trae_z)

## Acknowledgments

-Jehovah that keeps breath in my lungs
