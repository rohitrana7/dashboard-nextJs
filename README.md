# dashboard-nextJs-official-tut
- A project features of NextJs and ReactJS demonstrating a dashboard
- Tutorial from https://nextjs.org/learn/react-foundations/getting-started-with-react

### What is Next.js?
- Next.js is a React framework that gives you building blocks to create web applications.
- By framework, we mean Next.js handles the tooling and configuration needed for React, and provides additional structure, features, and optimizations for your application.
- ![image](https://github.com/user-attachments/assets/a2a31ba3-8c52-4182-b6f3-779161ebb7ec)
- You can use React to build your UI, then incrementally adopt Next.js features to solve common application requirements such as routing, data fetching, and caching - all while improving the developer and end-user experience.
- The browser then reads the HTML and constructs the Document Object Model (DOM).

### What is the DOM?
- The DOM is an object representation of the HTML elements. It acts as a bridge between your code and the user interface, and has a tree-like structure with parent and child relationships.

- Updating the DOM with plain JavaScript is very powerful but verbose. You've written all this code to add an ```<h1>``` element with some text:
- With this approach, developers spend a lot of time writing instructions to tell the computer how it should do things. But wouldn't it be nice to describe what you want to show and let the computer figure out how to update the DOM?

### Imperative vs. declarative programming
- In other words, imperative programming is like giving a chef step-by-step instructions on how to make a pizza. Declarative programming is like ordering a pizza without being concerned about the steps it takes to make the pizza. 🍕
- <b> React is a popular declarative library that you can use build user interfaces. </b>

### JSX
- JSX is a syntax extension for JavaScript that allows you to describe your UI in a familiar HTML-like syntax. 
- The nice thing about JSX is that apart from following three JSX rules, you don't need to learn any new symbols or syntax outside of HTML and JavaScript.
- But browsers don't understand JSX out of the box, so you'll need a JavaScript compiler, such as a Babel, to transform your JSX code into regular JavaScript.
- <b>3 rules of JSX</b> https://react.dev/learn/writing-markup-with-jsx#the-rules-of-jsx
    1. Return a single root element 
        - If you don’t want to add an extra <div> to your markup, you can write <> and </> instead. 
        - This empty tag is called a Fragment. Fragments let you group things without leaving any trace in the browser HTML tree.
    2. Close all the tags 
    3. camelCase all most of the things! 
- https://transform.tools/html-to-jsx Converter