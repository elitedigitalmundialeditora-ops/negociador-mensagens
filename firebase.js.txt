// Configuração do Firebase
const firebaseConfig = {
  apiKey: "AIzaSyAWJSWcnn1ePdM8mZPb-ti6__tm8fiwnGI",
  authDomain: "negociador-mensagens.firebaseapp.com",
  projectId: "negociador-mensagens",
  storageBucket: "negociador-mensagens.firebasestorage.app",
  messagingSenderId: "96021013704",
  appId: "1:96021013704:web:61db6c0af1a63de55071fd"
};

// Inicializa Firebase
firebase.initializeApp(firebaseConfig);
const auth = firebase.auth();
const db = firebase.firestore();
