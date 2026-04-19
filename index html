<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>S.R.K Studio | Premium Wedding Photography & Cinematography</title>

  <meta name="description" content="S.R.K Studio - Premium wedding photography, cinematic videography, drone coverage and wedding planning assistance in Saharsa, Bihar." />

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    :root {
      --burgundy: #4b0016;
      --deep-burgundy: #170006;
      --gold: #d7aa32;
      --light-gold: #ffe28a;
      --silver: #d8d8d8;
      --white: #ffffff;
      --soft-red: #ff8c8c;
      --yellow: #ffd15c;
      --glass: rgba(255, 255, 255, 0.08);
      --border: rgba(215, 170, 50, 0.35);
      --text: #f8eeee;
      --muted: #cdbfc4;
      --shadow: 0 35px 90px rgba(0, 0, 0, 0.55);
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      font-family: "Segoe UI", Arial, sans-serif;
      background:
        radial-gradient(circle at 20% 10%, rgba(215, 170, 50, 0.18), transparent 32%),
        radial-gradient(circle at 90% 20%, rgba(255, 140, 140, 0.12), transparent 35%),
        linear-gradient(180deg, #120005, #23000c 40%, #0a0003);
      color: var(--white);
      overflow-x: hidden;
    }

    body::before {
      content: "";
      position: fixed;
      inset: 0;
      pointer-events: none;
      background-image:
        linear-gradient(rgba(255,255,255,0.035) 1px, transparent 1px),
        linear-gradient(90deg, rgba(255,255,255,0.035) 1px, transparent 1px);
      background-size: 46px 46px;
      mask-image: linear-gradient(to bottom, black, transparent);
      z-index: -1;
    }

    a {
      text-decoration: none;
      color: inherit;
    }

    img {
      max-width: 100%;
      display: block;
    }

    .container {
      width: min(1180px, calc(100% - 36px));
      margin: auto;
    }

    .welcome-screen {
      position: fixed;
      inset: 0;
      z-index: 9999;
      display: grid;
      place-items: center;
      background:
        radial-gradient(circle, rgba(215,170,50,0.22), transparent 30%),
        linear-gradient(135deg, #080002, #3a0011, #090003);
      animation: welcomeOut 3s ease forwards;
    }

    .welcome-inner {
      text-align: center;
      perspective: 1200px;
    }

    .welcome-logo {
      width: 115px;
      height: 115px;
      margin: 0 auto 26px;
      border-radius: 50%;
      display: grid;
      place-items: center;
      font-weight: 900;
      font-size: 2rem;
      color: #150005;
      background: conic-gradient(from 180deg, var(--gold), var(--silver), var(--light-gold), var(--burgundy), var(--gold));
      border: 3px solid rgba(255,255,255,0.5);
      box-shadow: 0 0 70px rgba(215,170,50,0.55);
      animation: logoSpin 2.4s ease;
    }

    .welcome-screen h1 {
      font-family: Georgia, serif;
      color: var(--light-gold);
      font-size: clamp(2.6rem, 9vw, 7.5rem);
      letter-spacing: clamp(8px, 2vw, 24px);
      text-transform: uppercase;
      transform-origin: center;
      animation: title3d 2.4s ease;
    }

    .welcome-screen p {
      margin-top: 20px;
      color: var(--silver);
      letter-spacing: 8px;
      font-size: 0.9rem;
      text-transform: uppercase;
      animation: fadeUp 1.6s ease 0.4s both;
    }

    @keyframes welcomeOut {
      0%, 78% {
        opacity: 1;
        visibility: visible;
      }
      100% {
        opacity: 0;
        visibility: hidden;
      }
    }

    @keyframes logoSpin {
      from {
        transform: rotateY(90deg) scale(0.6);
        opacity: 0;
      }
      to {
        transform: rotateY(0) scale(1);
        opacity: 1;
      }
    }

    @keyframes title3d {
      from {
        opacity: 0;
        transform: rotateX(72deg) translateY(60px) scale(0.75);
      }
      to {
        opacity: 1;
        transform: rotateX(0) translateY(0) scale(1);
      }
    }

    @keyframes fadeUp {
      from {
        opacity: 0;
        transform: translateY(22px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    header {
      position: sticky;
      top: 0;
      z-index: 1000;
      background: rgba(15, 0, 5, 0.78);
      backdrop-filter: blur(22px);
      border-bottom: 1px solid var(--border);
    }

    .navbar {
      min-height: 92px;
      display: grid;
      grid-template-columns: 1fr auto 1fr;
      align-items: center;
      gap: 20px;
    }

    .nav-left,
    .nav-right {
      display: flex;
      align-items: center;
      gap: 10px;
      flex-wrap: wrap;
    }

    .nav-right {
      justify-content: flex-end;
    }

    .brand-area {
      text-align: center;
    }

    .brand-logo {
      width: 58px;
      height: 58px;
      margin: 0 auto 6px;
      border-radius: 50%;
      display: grid;
      place-items: center;
      background: linear-gradient(135deg, var(--gold), var(--silver), var(--yellow));
      color: #180006;
      font-weight: 900;
      border: 2px solid rgba(255,255,255,0.65);
      box-shadow: 0 0 35px rgba(215,170,50,0.35);
    }

    .brand-name {
      font-family: Georgia, serif;
      color: var(--gold);
      font-size: 1.45rem;
      letter-spacing: 5px;
      text-transform: uppercase;
    }

    .brand-ceo {
      color: var(--silver);
      font-size: 0.74rem;
      letter-spacing: 1px;
      margin-top: 4px;
    }

    .nav-link,
    .btn {
      border: 1px solid var(--border);
      padding: 10px 16px;
      border-radius: 999px;
      background: rgba(255,255,255,0.055);
      color: var(--text);
      font-size: 0.9rem;
      transition: 0.3s ease;
      cursor: pointer;
    }

    .nav-link:hover,
    .btn:hover {
      transform: translateY(-3px);
      background: var(--gold);
      color: #160005;
      box-shadow: 0 12px 30px rgba(215,170,50,0.25);
    }

    .btn-primary {
      background: linear-gradient(135deg, var(--gold), var(--yellow));
      color: #180006;
      font-weight: 800;
      border-color: rgba(255,255,255,0.5);
    }

    .btn-dark {
      background: linear-gradient(135deg, #7b062a, var(--burgundy));
      color: var(--white);
    }

    .hero {
      min-height: calc(100vh - 92px);
      display: grid;
      grid-template-columns: 1.05fr 0.95fr;
      align-items: center;
      gap: 50px;
      padding: 80px 0;
    }

    .eyebrow {
      display: inline-flex;
      gap: 10px;
      align-items: center;
      color: var(--light-gold);
      border: 1px solid var(--border);
      background: rgba(255,255,255,0.07);
      padding: 9px 15px;
      border-radius: 999px;
      letter-spacing: 2px;
      font-size: 0.78rem;
      text-transform: uppercase;
      margin-bottom: 22px;
    }

    .hero h1 {
      font-family: Georgia, serif;
      font-size: clamp(3.2rem, 8vw, 7.2rem);
      line-height: 0.95;
      color: var(--white);
      letter-spacing: -2px;
    }

    .hero h1 span {
      display: block;
      color: var(--gold);
      text-shadow: 0 0 45px rgba(215,170,50,0.35);
    }

    .hero p {
      color: var(--muted);
      font-size: 1.08rem;
      line-height: 1.8;
      max-width: 650px;
      margin: 24px 0 0;
    }

    .hero-actions {
      display: flex;
      gap: 14px;
      margin-top: 34px;
      flex-wrap: wrap;
    }

    .hero-stats {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 14px;
      margin-top: 38px;
      max-width: 650px;
    }

    .stat {
      padding: 18px;
      border: 1px solid var(--border);
      border-radius: 22px;
      background: var(--glass);
    }

    .stat strong {
      color: var(--gold);
      font-size: 1.8rem;
      display: block;
      font-family: Georgia, serif;
    }

    .stat small {
      color: var(--silver);
    }

    .visual-stage {
      position: relative;
      min-height: 560px;
    }

    .camera-3d {
      position: absolute;
      inset: 40px 0 0;
      border-radius: 42px;
      background:
        radial-gradient(circle at 52% 43%, #111 0 13%, #050505 14% 19%, var(--silver) 20% 21%, #111 22% 31%, transparent 32%),
        radial-gradient(circle at 52% 43%, rgba(215,170,50,0.35), transparent 38%),
        linear-gradient(145deg, #393939, #060606 48%, #1b1b1b);
      border: 2px solid rgba(215,170,50,0.65);
      box-shadow: var(--shadow), inset 0 0 80px rgba(255,255,255,0.06);
      transform: rotate(-2deg);
      overflow: hidden;
    }

    .camera-3d::before {
      content: "";
      position: absolute;
      width: 260px;
      height: 80px;
      top: 72px;
      left: 50%;
      transform: translateX(-50%);
      border-radius: 30px 30px 8px 8px;
      background: linear-gradient(135deg, #1c1c1c, #5a5a5a, #111);
      border: 1px solid rgba(255,255,255,0.2);
    }

    .camera-3d::after {
      content: "CINEMATIC WEDDING FILMS";
      position: absolute;
      bottom: 44px;
      left: 0;
      right: 0;
      text-align: center;
      color: var(--gold);
      letter-spacing: 5px;
      font-size: 0.9rem;
      font-weight: 800;
    }

    .floating-card {
      position: absolute;
      left: 0;
      bottom: 35px;
      width: 260px;
      padding: 22px;
      border: 1px solid var(--border);
      border-radius: 24px;
      background: rgba(20,0,8,0.78);
      backdrop-filter: blur(18px);
      box-shadow: var(--shadow);
    }

    .floating-card h3 {
      color: var(--gold);
      margin-bottom: 8px;
    }

    .floating-card p {
      color: var(--muted);
      line-height: 1.6;
      font-size: 0.92rem;
    }

    section {
      padding: 90px 0;
    }

    .section-title {
      text-align: center;
      margin-bottom: 48px;
    }

    .section-title .mini {
      color: var(--light-gold);
      text-transform: uppercase;
      letter-spacing: 4px;
      font-size: 0.78rem;
    }

    .section-title h2 {
      margin-top: 12px;
      font-family: Georgia, serif;
      font-size: clamp(2.3rem, 5vw, 4.8rem);
      color: var(--white);
    }

    .section-title h2 span {
      color: var(--gold);
    }

    .section-title p {
      max-width: 720px;
      margin: 16px auto 0;
      color: var(--muted);
      line-height: 1.8;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 24px;
    }

    .grid-2 {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 24px;
    }

    .card {
      border: 1px solid var(--border);
      border-radius: 30px;
      padding: 30px;
      background:
        linear-gradient(145deg, rgba(255,255,255,0.11), rgba(255,255,255,0.035)),
        radial-gradient(circle at top right, rgba(215,170,50,0.18), transparent 35%);
      box-shadow: 0 22px 65px rgba(0,0,0,0.35);
      transition: 0.35s ease;
      position: relative;
      overflow: hidden;
    }

    .card::before {
      content: "";
      position: absolute;
      top: 0;
      left: -100%;
      width: 80%;
      height: 100%;
      background: linear-gradient(90deg, transparent, rgba(255,255,255,0.12), transparent);
      transform: skewX(-20deg);
      transition: 0.7s ease;
    }

    .card:hover::before {
      left: 120%;
    }

    .card:hover {
      transform: translateY(-8px);
      border-color: rgba(255,226,138,0.8);
      box-shadow: 0 32px 85px rgba(215,170,50,0.18);
    }

    .card h3 {
      color: var(--gold);
      font-size: 1.5rem;
      margin-bottom: 14px;
      font-family: Georgia, serif;
    }

    .card p,
    .card li {
      color: var(--muted);
      line-height: 1.8;
    }

    .card ul {
      margin: 16px 0 0 20px;
    }

    .rating {
      color: var(--yellow);
      font-weight: 900;
      letter-spacing: 2px;
      margin-bottom: 14px;
    }

    .tag {
      display: inline-block;
      padding: 7px 11px;
      border-radius: 999px;
      border: 1px solid var(--border);
      color: var(--light-gold);
      font-size: 0.75rem;
      margin-bottom: 16px;
      background: rgba(255,255,255,0.05);
    }

    .planning-box {
      display: grid;
      grid-template-columns: 1.1fr 0.9fr;
      gap: 26px;
      align-items: stretch;
    }

    .lux-box {
      border: 1px solid var(--border);
      border-radius: 36px;
      padding: 36px;
      background:
        linear-gradient(135deg, rgba(75,0,22,0.75), rgba(255,255,255,0.07)),
        radial-gradient(circle at 20% 10%, rgba(215,170,50,0.22), transparent 32%);
      box-shadow: var(--shadow);
    }

    .lux-box h2 {
      color: var(--gold);
      font-family: Georgia, serif;
      font-size: clamp(1.8rem, 4vw, 3.3rem);
      margin-bottom: 15px;
    }

    .lux-box p {
      color: var(--muted);
      line-height: 1.8;
      margin-bottom: 20px;
    }

    form {
      display: grid;
      gap: 16px;
    }

    .form-grid {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 16px;
    }

    input,
    select,
    textarea {
      width: 100%;
      padding: 15px 16px;
      border-radius: 16px;
      border: 1px solid rgba(215,170,50,0.38);
      background: rgba(255,255,255,0.075);
      color: var(--white);
      outline: none;
      font: inherit;
    }

    input:focus,
    select:focus,
    textarea:focus {
      border-color: var(--light-gold);
      box-shadow: 0 0 0 4px rgba(215,170,50,0.13);
    }

    input::placeholder,
    textarea::placeholder {
      color: #c8b9be;
    }

    select option {
      color: #111;
    }

    .success {
      display: none;
      margin-top: 15px;
      padding: 15px;
      border-radius: 16px;
      border: 1px solid rgba(215,170,50,0.7);
      background: rgba(215,170,50,0.13);
      color: var(--light-gold);
      font-weight: 700;
    }

    .portfolio {
      min-height: 300px;
      display: flex;
      flex-direction: column;
      justify-content: flex-end;
      border-radius: 32px;
      padding: 28px;
      border: 1px solid var(--border);
      background:
        linear-gradient(to top, rgba(15,0,5,0.92), rgba(15,0,5,0.15)),
        radial-gradient(circle at 50% 35%, rgba(255,255,255,0.18), transparent 12%),
        linear-gradient(135deg, rgba(215,170,50,0.38), rgba(192,192,192,0.2), rgba(75,0,22,0.9));
      box-shadow: var(--shadow);
      position: relative;
      overflow: hidden;
    }

    .portfolio::before {
      content: "";
      position: absolute;
      inset: 20px;
      border: 1px solid rgba(255,255,255,0.22);
      border-radius: 24px;
    }

    .portfolio h3,
    .portfolio p {
      position: relative;
      z-index: 1;
    }

    .portfolio h3 {
      color: var(--gold);
      font-family: Georgia, serif;
      font-size: 1.45rem;
      margin-bottom: 8px;
    }

    .portfolio p {
      color: var(--text);
      line-height: 1.7;
    }

    .contact-info p {
      margin: 11px 0;
      color: var(--muted);
      line-height: 1.6;
    }

    .contact-info strong {
      color: var(--gold);
    }

    footer {
      padding: 60px 0 35px;
      background: #070002;
      border-top: 1px solid var(--border);
      text-align: center;
    }

    .footer-brand {
      color: var(--gold);
      font-family: Georgia, serif;
      font-size: 2.4rem;
      margin-bottom: 10px;
    }

    .socials {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 10px;
      margin: 26px 0;
    }

    .socials a {
      padding: 10px 16px;
      border: 1px solid var(--border);
      border-radius: 999px;
      color: var(--silver);
      background: rgba(255,255,255,0.04);
      transition: 0.3s;
    }

    .socials a:hover {
      color: #160005;
      background: var(--gold);
    }

    .thank {
      margin-top: 28px;
      color: var(--light-gold);
      letter-spacing: 2px;
      text-transform: uppercase;
    }

    .floating-whatsapp {
      position: fixed;
      right: 22px;
      bottom: 22px;
      z-index: 900;
      padding: 15px 20px;
      border-radius: 999px;
      background: linear-gradient(135deg, var(--gold), var(--yellow));
      color: #150005;
      font-weight: 900;
      box-shadow: 0 18px 45px rgba(215,170,50,0.35);
    }

    @media (max-width: 980px) {
      .navbar {
        grid-template-columns: 1fr;
        text-align: center;
        padding: 16px 0;
      }

      .nav-left,
      .nav-right {
        justify-content: center;
      }

      .hero,
      .planning-box,
      .grid-2 {
        grid-template-columns: 1fr;
      }

      .visual-stage {
        min-height: 440px;
      }

      .grid {
        grid-template-columns: 1fr 1fr;
      }
    }

    @media (max-width: 640px) {
      .grid,
      .hero-stats,
      .form-grid {
        grid-template-columns: 1fr;
      }

      section {
        padding: 70px 0;
      }

      .hero {
        padding-top: 50px;
      }

      .camera-3d {
        inset: 20px 0 0;
      }

      .floating-card {
        width: calc(100% - 20px);
        left: 10px;
      }
    }
  </style>
</head>

<body>
  <div
// Import the functions you need from the SDKs you need
import { initializeApp } from "firebase/app";
import { getAnalytics } from "firebase/analytics";
// TODO: Add SDKs for Firebase products that you want to use
// https://firebase.google.com/docs/web/setup#available-libraries

// Your web app's Firebase configuration
// For Firebase JS SDK v7.20.0 and later, measurementId is optional
const firebaseConfig = {
  apiKey: "AIzaSyDjRvSW_RrnLeo08nosi6LFD1MgPCks5UY",
  authDomain: "centered-accord-493503-q7.firebaseapp.com",
  projectId: "centered-accord-493503-q7",
  storageBucket: "centered-accord-493503-q7.firebasestorage.app",
  messagingSenderId: "1026150752142",
  appId: "1:1026150752142:web:15ff92bb7b037f97fb8edf",
  measurementId: "G-S9F96R11RG"
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);
const analytics = getAnalytics(app);
/S.R.K-Studio
│
├── index.html        (Home)
├── vendor.html       (Wedding Vendors)
├── wedding.html      (Real Wedding Page)
├── gallery.html      (Photo/Video Gallery)
├── admin.html        (Admin Dashboard)
├── firebase.js       (Backend connection)
├── style.css        (Luxury UI)
└── app.js           (All logic)
import { db } from "./firebase.js";
import { collection, addDoc } from "https://www.gstatic.com/firebasejs/10.7.1/firebase-firestore.js";

async function saveBooking(){
    await addDoc(collection(db, "weddingBookings"), {
        name: document.getElementById("name").value,
        number: document.getElementById("number").value,
        email: document.getElementById("email").value,
        state: document.getElementById("state").value,
        district: document.getElementById("district").value,
        date: new Date()
    });

    alert("🔥 Booking Saved Successfully!");
}
<h1>🔥 S.R.K ADMIN DASHBOARD</h1>
<div id="data"></div>

<script type="module">
import { db } from "./firebase.js";
import { collection, getDocs } from "https://www.gstatic.com/firebasejs/10.7.1/firebase-firestore.js";

const snap = await getDocs(collection(db, "weddingBookings"));

snap.forEach(doc => {
    let d = doc.data();
    document.getElementById("data").innerHTML += `
        <div style="background:#222;margin:10px;padding:10px;border-radius:10px;">
            <h3>${d.name}</h3>
            <p>${d.number}</p>
            <p>${d.email}</p>
        </div>
    `;
});
</script>
import { getAuth, createUserWithEmailAndPassword, signInWithEmailAndPassword } 
from "https://www.gstatic.com/firebasejs/10.7.1/firebase-auth.js";

const auth = getAuth();

// SIGN UP
function signup(email, password){
  createUserWithEmailAndPassword(auth, email, password)
  .then(user => {
    console.log("User Created", user);
  });
}

// LOGIN
function login(email, password){
  signInWithEmailAndPassword(auth, email, password)
  .then(user => {
    console.log("Logged In", user);
  });
}
import { db } from "./firebase.js";
import { doc, getDoc } from "https://www.gstatic.com/firebasejs/10.7.1/firebase-firestore.js";

async function checkRole(uid){
    const snap = await getDoc(doc(db, "users", uid));

    if(snap.data().role === "admin"){
        window.location.href = "admin.html";
    } else {
        window.location.href = "index.html";
    }
}
import { storage } from "./firebase.js";
import { ref, uploadBytes, getDownloadURL } 
from "https://www.gstatic.com/firebasejs/10.7.1/firebase-storage.js";

async function uploadMedia(file){
    const fileRef = ref(storage, "gallery/" + file.name);
    await uploadBytes(fileRef, file);
    const url = await getDownloadURL(fileRef);

    console.log("Uploaded URL:", url);
}
<canvas id="scene"></canvas>

<script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js"></script>

<script>
let scene = new THREE.Scene();
let camera = new THREE.PerspectiveCamera(75, window.innerWidth/window.innerHeight, 0.1, 1000);

let renderer = new THREE.WebGLRenderer({canvas: document.getElementById("scene")});
renderer.setSize(window.innerWidth, window.innerHeight);

let geometry = new THREE.TorusGeometry();
let material = new THREE.MeshBasicMaterial({color: 0xffd700, wireframe:true});
let torus = new THREE.Mesh(geometry, material);

scene.add(torus);
camera.position.z = 5;

function animate(){
    requestAnimationFrame(animate);
    torus.rotation.x += 0.01;
    torus.rotation.y += 0.01;
    renderer.render(scene, camera);
}
animate();
</script>
body {
    margin:0;
    font-family:Arial;
    background: radial-gradient(circle, #0d0d0d, #000);
    color:white;
}

.glass {
    background: rgba(255,255,255,0.05);
    backdrop-filter: blur(10px);
    border-radius: 15px;
    padding: 20px;
    margin: 10px;
    box-shadow: 0 0 20px gold;
}

button {
    background: gold;
    border:none;
    padding:10px;
    border-radius:8px;
    cursor:pointer;
    font-weight:bold;
}

button:hover {
    transform:scale(1.05);
}
body {
    background: black;
    overflow-x: hidden;
}

.hero {
    height: 100vh;
    background: url('https://images.unsplash.com/photo-1520857014576-2c4f4c972b57') center/cover;
    display:flex;
    align-items:center;
    justify-content:center;
    color:white;
    font-size:40px;
    text-shadow:0 0 20px black;
    animation: zoom 10s infinite alternate;
}

@keyframes zoom {
    from {transform: scale(1);}
    to {transform: scale(1.1);}
}
<canvas id="scene"></canvas>

<div class="overlay">
    <h1>S.R.K STUDIO</h1>
    <p>Premium Cinematic Wedding Experience</p>
</div>

<script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js"></script>

<script>
let scene = new THREE.Scene();
let camera = new THREE.PerspectiveCamera(75, innerWidth/innerHeight, 0.1, 1000);

let renderer = new THREE.WebGLRenderer({canvas: document.getElementById("scene")});
renderer.setSize(innerWidth, innerHeight);

let geometry = new THREE.SphereGeometry(2, 32, 32);
let material = new THREE.MeshBasicMaterial({wireframe:true, color:0xffd700});
let sphere = new THREE.Mesh(geometry, material);

scene.add(sphere);
camera.position.z = 5;

function animate(){
    requestAnimationFrame(animate);
    sphere.rotation.y += 0.01;
    renderer.render(scene, camera);
}
animate();
</script>
function recommendWedding(budget, style){
    if(budget < 50000){
        return "Basic photography package (1 camera, simple shoot)";
    }
    if(budget < 150000){
        return "Premium cinematic wedding + drone + 2 cameras";
    }
    if(style === "luxury"){
        return "Netflix style cinematic wedding film + 5 camera setup + drone + live streaming";
    }

    return "Custom wedding package";
}
import { getAuth, createUserWithEmailAndPassword, signInWithEmailAndPassword } 
from "https://www.gstatic.com/firebasejs/10.7.1/firebase-auth.js";

const auth = getAuth();

// SIGN UP
function signup(email, password){
  createUserWithEmailAndPassword(auth, email, password)
  .then(user => {
    console.log("User Created", user);
  });
}

// LOGIN
function login(email, password){
  signInWithEmailAndPassword(auth, email, password)
  .then(user => {
    console.log("Logged In", user);
  });
}
import { db } from "./firebase.js";
import { addDoc, collection } from "https://www.gstatic.com/firebasejs/10.7.1/firebase-firestore.js";

function payNow(amount){
    var options = {
        key: "YOUR_KEY",
        amount: amount * 100,
        currency: "INR",
        name: "S.R.K Studio",
        handler: async function (response){

            await addDoc(collection(db, "payments"), {
                paymentId: response.razorpay_payment_id,
                status: "PAID",
                amount: amount,
                date: new Date()
            });

            alert("Payment Verified & Saved!");
        }
    };

    var rzp = new Razorpay(options);
    rzp.open();
}
app.post("/whatsapp", async (req, res) => {
    const msg = req.body.message;

    let reply = "S.R.K Studio Assistant: How can I help?";

    if(msg.includes("book")){
        reply = "Send your details for wedding booking 📸";
    }

    await fetch("https://graph.facebook.com/v19.0/YOUR_PHONE_ID/messages", {
        method: "POST",
        headers: {
            "Authorization": "Bearer YOUR_TOKEN",
            "Content-Type": "application/json"
        },
        body: JSON.stringify({
            messaging_product: "whatsapp",
            to: req.body.from,
            text: { body: reply }
        })
    });

    res.send("ok");
});
app.post("/lead", async (req, res) => {
    let msg = req.body.message.toLowerCase();

    let reply = "S.R.K Studio Assistant: How can I help?";

    if(msg.includes("price")){
        reply = "Wedding packages start from ₹25,000 🎥";
    }
    if(msg.includes("book")){
        reply = "Send your name + date for booking 📸";
    }

    await fetch("https://graph.facebook.com/v19.0/PHONE_ID/messages", {
        method: "POST",
        headers: {
            "Authorization": "Bearer TOKEN",
            "Content-Type": "application/json"
        },
        body: JSON.stringify({
            messaging_product: "whatsapp",
            to: req.body.from,
            text: { body: reply }
        })
    });

    res.send("ok");
});
import { db } from "./firebase.js";
import { collection, addDoc, onSnapshot } 
from "https://www.gstatic.com/firebasejs/10.7.1/firebase-firestore.js";

// SEND MESSAGE
function sendMsg(text){
    addDoc(collection(db, "chat"), {
        msg: text,
        time: new Date()
    });
}

// LIVE LISTEN
onSnapshot(collection(db, "chat"), snap => {
    snap.forEach(doc => {
        console.log(doc.data().msg);
    });
});
import express from "express";
import fetch from "node-fetch";

const app = express();
app.use(express.json());

app.post("/chat", async (req, res) => {
    const userMsg = req.body.message;

    const response = await fetch("https://api.openai.com/v1/chat/completions", {
        method: "POST",
        headers: {
            "Authorization": "Bearer YOUR_OPENAI_KEY",
            "Content-Type": "application/json"
        },
        body: JSON.stringify({
            model: "gpt-4o-mini",
            messages: [{ role: "user", content: userMsg }]
        })
    });

    const data = await response.json();
    res.json(data.choices[0].message);
});

app.listen(3000);
function weddingAI(budget){
    if(budget < 50000){
        return "Basic photography + 1 camera setup";
    }
    else if(budget < 150000){
        return "Premium DSLR + cinematic video + drone";
    }
    else{
        return "Luxury wedding package + full cinematic film + 5 cameras";
    }
}
function generateInvoice(name, amount){
    const invoice = `
    S.R.K STUDIO INVOICE
    ----------------------
    Name: ${name}
    Amount: ₹${amount}
    Status: PAID/PENDING
    Contact: 9110066743
    `;

    const blob = new Blob([invoice], {type:"text/plain"});
    const link = document.createElement("a");
    link.href = URL.createObjectURL(blob);
    link.download = "invoice.txt";
    link.click();
}
import { db } from "./firebase.js";
import { collection, query, where, getDocs } 
from "https://www.gstatic.com/firebasejs/10.7.1/firebase-firestore.js";

async function loadMyBookings(userEmail){
    const q = query(collection(db, "bookings"), where("email", "==", userEmail));
    const snap = await getDocs(q);

    snap.forEach(doc => {
        console.log("Booking:", doc.data());
    });
}
const recognition = new (window.SpeechRecognition || window.webkitSpeechRecognition)();

recognition.onresult = function(event){
    let text = event.results[0][0].transcript;

    let response = "";

    if(text.includes("budget")){
        response = "Wedding packages start from 25,000 rupees";
    }
    else if(text.includes("book")){
        response = "Please fill booking form or contact 9110066743";
    }
    else{
        response = "I am S.R.K Studio AI assistant";
    }

    let speech = new SpeechSynthesisUtterance(response);
    speechSynthesis.speak(speech);
};

function startVoice(){
    recognition.start();
}
import jsPDF from "jspdf";

function generateInvoice(name, amount){
    const doc = new jsPDF();

    let gst = amount * 0.18;
    let total = amount + gst;

    doc.text("S.R.K STUDIO INVOICE", 10, 10);
    doc.text("Name: " + name, 10, 20);
    doc.text("Amount: " + amount, 10, 30);
    doc.text("GST (18%): " + gst, 10, 40);
    doc.text("Total: " + total, 10, 50);

    doc.save("invoice.pdf");
}
let peer = new RTCPeerConnection();

navigator.mediaDevices.getUserMedia({video:true,audio:true})
.then(stream => {
    document.getElementById("video").srcObject = stream;
    stream.getTracks().forEach(track => peer.addTrack(track, stream));
});
import { db } from "./firebase.js";
import { collection, getDocs } 
from "https://www.gstatic.com/firebasejs/10.7.1/firebase-firestore.js";

async function loadCRM(){
    const snap = await getDocs(collection(db, "bookings"));

    let revenue = 0;

    snap.forEach(doc => {
        let data = doc.data();
        revenue += 5000; // example package value
    });

    document.getElementById("crm").innerHTML = `
        <h2>Total Clients: ${snap.size}</h2>
        <h2>Total Revenue: ₹${revenue}</h2>
    `;
}
function seoMeta(title){
    document.title = title;

    let meta = document.createElement("meta");
    meta.name = "description";
    meta.content = "S.R.K Studio - Premium Wedding Photography & Videography";
    document.head.appendChild(meta);
}
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXX"></script>
<script>
window.dataLayer = window.dataLayer || [];
function gtag(){dataLayer.push(arguments);}
gtag('js', new Date());
gtag('config', 'G-XXXX');
</script>
S.R.K-STUDIO-PROJECT.zip
│
├── index.html
├── admin.html
├── client.html
├── gallery.html
├── vendor.html
├── firebase.js
├── auth.js
├── billing.js
├── ai.js
├── seo.js
├── style.css
├── app.js
└── /assets
import { db } from "./firebase.js";
import { collection, getDocs } from "https://www.gstatic.com/firebasejs/10.7.1/firebase-firestore.js";

async function loadCRM(){
    const bookings = await getDocs(collection(db, "bookings"));
    const payments = await getDocs(collection(db, "payments"));

    document.getElementById("crm").innerHTML = `
        <h2>Total Leads: ${bookings.size}</h2>
        <h2>Total Payments: ${payments.size}</h2>
        <h2>Conversion Rate: ${(payments.size/bookings.size*100).toFixed(2)}%</h2>
    `;
}
function autoSystem(){
    // 1. Lead capture
    // 2. WhatsApp reply
    // 3. CRM update
    // 4. Payment tracking
    // 5. Invoice generation

    console.log("S.R.K Studio Automation Running...");
}
<footer style="
text-align:center;
padding:15px;
font-size:12px;
color:#aaa;
background:#111;
border-top:1px solid #333;
letter-spacing:1px;
">
  <span style="
    animation: glow 2s infinite alternate;
    color: gold;
    text-shadow: 0 0 5px gold, 0 0 10px gold;
  ">
    website builder: krishna yadav
  </span>
</footer>

<style>
@keyframes glow {
  from {
    text-shadow: 0 0 5px gold, 0 0 10px gold;
    opacity: 0.7;
  }
  to {
    text-shadow: 0 0 15px gold, 0 0 25px orange;
    opacity: 1;
  }
}
</style>
button {
    background: gold;
    color: black;
}

button:hover {
    background: black;
    color: gold;
    box-shadow: 0 0 15px gold;
}body {
    background: radial-gradient(circle, #111, #000);
}.box {
    background: rgba(255,255,255,0.05);
    backdrop-filter: blur(10px);
    border: 1px solid rgba(255,215,0,0.2);
    border-radius: 12px;
}.glow {
    text-shadow: 0 0 10px gold;
}
/* BACKGROUND */
body {
    background: linear-gradient(135deg, #800020, #1a0000);
    color: white;
    font-family: Arial;
}

/* HEADER */
header {
    background: #800020;
    color: #ffd700;
}

/* BUTTON */
button {
    background: #ffd700;
    color: black;
    border: none;
    padding: 10px;
    border-radius: 6px;
    cursor: pointer;
}

button:hover {
    background: #ff4d4d;
    color: white;
    box-shadow: 0 0 15px #ffd700;
}

/* BOX / CARD */
.box {
    background: rgba(255,255,255,0.05);
    border: 1px solid rgba(255,215,0,0.3);
    border-radius: 12px;
    padding: 15px;
    margin: 10px;
}

/* HEADING */
h1, h2 {
    color: #ffd700;
}

/* TEXT */
p {
    color: #ffffff;
}

/* GLOW TEXT */
.glow {
    color: #ffd700;
    text-shadow: 0 0 10px #ffd700, 0 0 20px #ff4d4d;
}
.gradient-text {
    background: linear-gradient(45deg, #ffd700, #ff4d4d, #800020);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
}
<h1 class="gradient-text">S.R.K STUDIO</h1>
