# Learning Paths

The last chapters of this book are to help yoy apply what you've learned. So far, the book has taught you how to use Firebase in React to build sophisticated web applications. You've used all the fundamental features that power modern applications. Firebase offers you everything you need to implement authentication, authorization, and database interaction. However, there is plenty of room to explore the ecosystem, starting with this book's exercises and articles. 

## Firebase's Cloud Firestore

Firebase's Cloud Firestore is the latest version of Firebase's Realtime Database. We used the database because it comes with plenty of documentation, has a more established community, and offers plenty of online tutorials. However, Firebase's Cloud Firestore migh still take over at some point, because it has a more intuitive data model, more features, faster queries, and a better scaling experience for larger applications. Since it only affects the Firebase database, everything else like the Firebase authentication mechanisms stays the same. You only need to [migrate to Cloud Firestore](https://www.robinwieruch.de/react-firestore-tutorial) to give it a shot.

## Firebase's Admin API

We used Firebase's authentication and realtime database in this book. Conversely, Firebase's admin API gives advanced control over users by changing email addresses, sending verification emails, or deleting them. As developer and admin, you are responsible for crafting a full-fledged admin dashboard to manage user entities without boundaries.

## Firebase's Storage API

Users who have signed in to your application already come with an avatar, because they often use an image of themselves on Google, Facebook or Twitter. With Firebase's storage API, you can allow them to upload personalized imagery, like profile pictures.

## Firebase's Cloud Functions

Firebase's Cloud Functions are another advanced tool to outsource business logic from your application. For instance, cloud functions are often used to send recurring emails to users. When a user doesn't sign in for a while to your application, you could send this user a reminder email about the latest features they are missing out. Also you could use the cloud function to send emails about new content in your application. Exploring these email features with Firebase's Cloud Functions and [Sendgrid](https://sendgrid.com/) is a great learning experience in my opinion, because it let's you step away from only building frontend applications.

## Stripe and PayPal

You can also enable payments for your Firebase in React application to make it a full-fledged business application. [Stripe](https://w ww.robinwieruch.de/react-express-stripe-payment/) and [PayPal](https://www.robinwieruch.de/react-paypal-payment/) are two platforms that add [monetezation](https://en.wikipedia.org/wiki/Monetization), for actions like charging users a one-time or adding subscriptions. This is the next step in building a profitable online service.

## Keep Tinkering

The foremost recommendation I have is to continue tinkering with React with Firebase applications you build in this book. Try substituting technologies used under the hood to see what happens, while still keeping focus on your application's main features. Since React and Firebase have many user management built-in, you can concentrate on expanding their options. If you want to substitute Firebase with your own database and authentication, my other book The Road to GraphQL shows how too add these same features with your own backend application.

