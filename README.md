# My-website
Gopal Samaj Utkarsh Sangh 
// Import the functions you need from the SDKs you need
import { initializeApp } from "firebase/app";
import { getAnalytics } from "firebase/analytics";
// TODO: Add SDKs for Firebase products that you want to use
// https://firebase.google.com/docs/web/setup#available-libraries

// Your web app's Firebase configuration
// For Firebase JS SDK v7.20.0 and later, measurementId is optional
const firebaseConfig = {
  apiKey: "AIzaSyBVxJSZ_Fpljc6i2xLIATruLyRcCoAV0D4",
  authDomain: "gopalsamaj-utkarsh-sangh.firebaseapp.com",
  projectId: "gopalsamaj-utkarsh-sangh",
  storageBucket: "gopalsamaj-utkarsh-sangh.firebasestorage.app",
  messagingSenderId: "474884202995",
  appId: "1:474884202995:web:7b8f1830b80e4d9993b286",
  measurementId: "G-HT8GL9Q556"
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);
const analytics = getAnalytics(app);
