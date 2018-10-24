## Requirements

To follow this book, you should be familiar with the basics of web development, i.e how to use HTML, CSS, and JavaScript. It also makes sense to understand how [APIs](https://www.robinwieruch.de/what-is-an-api-javascript/) work, as they will be covered thoroughly. Also, I encourage you to join the official [Slack Group](https://slack-the-road-to-learn-react.wieruch.com/) to be a part of a growing community where you can learn from and help others.

### React

The book uses React as library to teach about GraphQL for client-side applications in JavaScript. It is the perfect choice for demonstrating and learning GraphQL in modern applications. Because React is only a view layer for your UI, it is up to you to decide how to deal with the data in your application. GraphQL is a great choice for dealing with your remote (and local) data in a client-side React application.

After all, it's not necessary to be a React developer in order to learn about GraphQL in modern applications. If you are developing with another framework, such as Angular, or library, such as Vue, all these things about GraphQL taught in this book can still be applied in your applications. GraphQL is framework and library agnostic, because it is only a query language.

Still, since the book uses React for the sake of teaching GraphQL in a proper context, if you are not familiar with React or need to have a refresher on the topic, I encourage you to read the precedent book: [The Road to learn React](https://www.robinwieruch.de/the-road-to-learn-react/). It is for free and should enable everyone to learn React. However, you can decide to pay something to support the project.

Even though the Road to learn React is for free, people with lacking education have no access to these resources in the first place. They have to be educated in the English language to be enabled to access it. The Road to learn React attempts [to support education in the developing world](https://www.robinwieruch.de/giving-back-by-learning-react/) on an occasionally basis, but it is a tough undertaking since the book itself is pay what you want.

In addition, the Road to learn React teaches you to make the transition from JavaScript ES5 to JavaScript ES6. After having read the Road to learn React, you should possess all the knowledge to read this book. It builds up on the React book perfectly.

### Node

On the server-side, this book uses Node with Express as library to teach about GraphQL in JavaScript. You don't need to know much about those technologies before using them for your first GraphQL powered applications. The book will guide you through the process of setting up a Node application with Express and shows you how to weave GraphQL into the mix. Afterward, you should be able to consume the GraphQL API provided by your server-side application in your client-side application.

### Editor and Terminal

You will need a IDE or text editor and terminal (command line tool) to build the applications yourself while reading the book. I have provided [a setup guide](https://www.robinwieruch.de/developer-setup/) if you need additional help. Optionally, we recommend you keep your projects in GitHub while conducting the exercises in this book. There is a [short guide](https://www.robinwieruch.de/git-essential-commands/) on how to use these tools. Github has excellent version control, so you can see what changes were made if you make a mistake or just want a more direct way to follow along.

### Node and Npm

In addition, you will need an installation of [node and npm](https://nodejs.org/en/). Both are used to manage libraries you will need along the way. In this book, you will install external node packages via npm (node package manager). These node packages can be libraries or whole frameworks.

You can verify your versions of node and npm on the command line. If you don't get any output in the terminal, you need to install node and npm first. These are only my versions during the time writing this book:

{title="Command Line",lang="text"}
~~~~~~~~
node --version
*v10.11.0
npm --version
*v6.4.1
~~~~~~~~

If you read the Road to learn React, you should be familiar with the setup already. The book gives you a short introduction into the npm ecosystem on the command line, too. So if you are not familiar with this, once again you can pick up the Road to learn React book.
