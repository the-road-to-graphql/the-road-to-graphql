## Requirements

To get the most out of this book, you should be familiar with the basics of web development. That includes some knowledge of HTML, CSS and JavaScript. You will also need to be familiar with the term [API](https://www.robinwieruch.de/what-is-an-api-javascript/), because they are discussed frequently. I encourage you to join the official [Slack Group](https://slack-the-road-to-learn-react.wieruch.com/) for the book, help or get help from others.

### React

The book uses React as a  library to teach GraphQL for client-side applications in JavaScript. I consider it an ideal choice to demonstrate the usefulness of GraphQL in modern applications. Since React is just a view layer for your user interface, it is up to you to decide how to deal with data in your application. GraphQL is a great choice for dealing with your remote and local data in a client-side React application.

It is not necessary to be a React developer to learn about GraphQL. If you are developing with another framework like Angular, or a library like Vue, the lessons taught about GraphQL in this book still apply. GraphQL is framework and library agnostic because it is a query language.

Since this book uses React to teach GraphQL, I encourage you to read the **free** book: [The Road to learn React](https://www.robinwieruch.de/the-road-to-learn-react/) if you need more context. The Road to learn React transitions from JavaScript ES5 to JavaScript ES6, so you should possess all the knowledge to read this book. While the book is free, some developers still have no access to these resources since they must learn English to access it. The Road to learn React [supports education in the developing world](https://www.robinwieruch.de/giving-back-by-learning-react/), but it can be a challenge to self-publish without funding. While these books are offered free of charge, any patronage from readers who find it useful is greatly appreciated.

### Node and NPM

On the server-side, this book uses Node with Express as a library to teach GraphQL in JavaScript. You don't need to know about those technologies before using them for your first GraphQL-powered applications. The book will guide you through setting up a Node application with Express and how to weave GraphQL into the mix. Afterward, you'll be able to consume the GraphQL API provided by a server-side application into a client-side application.

You will also need to have [node and npm](https://nodejs.org/en/) installed, which are used to manage the libraries we'll use along the way. In this book, you will install external node packages via npm (node package manager). These node packages can be libraries or whole frameworks. You can verify which node and npm versions you have in the command line. If you don't see output in the terminal, you will need to install node and npm. These are the versions used for this publication:

{title="Command Line",lang="text"}
~~~~~~~~
node --version
*v8.9.4
npm --version
*v6.1.0
~~~~~~~~

If you read the Road to learn React, you should be familiar with the setup already, since it introduces the npm ecosystem as well.

### Editor and Terminal

For the development environment, use a running editor or IDE and terminal (command line tool), and [follow my setup guide](https://www.robinwieruch.de/developer-setup/). It is adjusted for MacOS users, but you can find a Windows setup guide for React, too. There are lots of articles about setting up a web development environment for your OS.

Optionally, you can also use git and GitHub while conducting the exercises in the book, to keep your projects and the progress in repositories on GitHub. There exists a [little guide](https://www.robinwieruch.de/git-essential-commands/) on how to use these tools. Once again, it is not mandatory for the book, and it can be overwhelming to learn everything from scratch. You can skip it if you are a newcomer to web development, or if you'd just like to focus on the essential parts taught in this book.

