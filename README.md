# About this project:

It is a simple Crypto Currency dashboard where users can signup, view currency details and add currency to account watchlist. The app is built with React. Styled with Tailwind CSS. Firebase was used to store user account info, authentication and watchlist data. Coink Gecko API was used to pull in all the Crypto Currency Data and React Sparklines for the charts. I also added light and dark mode. Your latest choice is remembered for your next login. **see package.json for all the packages I used**

## Install and configure
From root application directory in the terminal run:

```yarn```


- Create a Firebase Account if you don't have one. https://firebase.google.com/.
- Create a project 
- Create a WebApp \
- Enable Authentication with Email and Password.
- Create a firestore database


- Create a .env file in the root directory of this application and add the following lines.
  
```
REACT_APP_API_KEY=<Firebase API Key>
REACT_APP_FIREBASE_AUTH_DOMAIN=<Firebase auth domain>
REACT_APP_FIREBASE_PROJECT_ID=<Firebase project id>
REACT_APP_FIREBASE_STORAGE_BUCKET=<Firebase storage bucket>
REACT_APP_FIREBASE_MESSAGING_SENDER_ID=<Firebase Messaging Sender>
REACT_APP_FIREBASE_APP_ID=<Firebase App id>
```
## Start up the Dev server
In the root directory of the application from the terminal run:

```
yarn dev
```

