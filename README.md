# Full Stack Reactive Native Instagram Clone
![screenshot](https://github.com/darrencai05/fullstack-instagram-clone/blob/master/src/assets/images/pictures.jpg) 
# Uses:       
- React Native (v0.62)
- Firebase
- Typescript
- React-native-navigation v5
- Redux / Redux-thunk

# Features:
- Features:
- User authentication (sign up, log in, log out)
- Post photos with captions
- Like and comment on posts
- Follow and unfollow other users
- Display posts from followed users in the feed
 

## Installation

## Prerequisites:
-Node.js installed on your system.
-A Firebase account to configure backend services.
-Expo CLI to run the React Native project.

1. Clone the repository:
```bash
git https://github.com/darrencai05/fullstack-instagram-clone.git
cd fullstack-instagram-clone
```
2. Install dependencies:
```bash
npm install
```

3. Set up Firebase:
- Go to Firebase Console and create a new project.
- Enable Firebase Authentication and configure sign-in methods.
- Set up Cloud Firestore to store posts, users, and comments.
- Copy your Firebase config (API Key, Auth Domain, etc.) and paste it into your project.
Open firebaseConfig.js and update it with your Firebase credentials:
```javascript
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_AUTH_DOMAIN",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_STORAGE_BUCKET",
  messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
  appId: "YOUR_APP_ID"
};
```
4. Run the app:
```bash
npm start
```


## License
This project is licensed under the MIT License.

