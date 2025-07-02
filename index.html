<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>IG Boost Tool | MR SMILE</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body, html {
      height: 100%;
      font-family: 'Segoe UI', sans-serif;
      overflow: hidden;
      color: #fff;
      background: #000;
    }
    #loader {
      position: fixed;
      top: 0; left: 0;
      width: 100vw;
      height: 100vh;
      background: #000;
      display: flex;
      justify-content: center;
      align-items: center;
      z-index: 10000;
      font-size: 1.5rem;
      color: #ff0033;
      text-shadow: 0 0 10px #ff0033;
    }
    video#bgVideo {
      position: fixed;
      top: 0; left: 0;
      width: 100vw;
      height: 100vh;
      object-fit: cover;
      z-index: -1;
    }
    .overlay {
      background: rgba(0, 0, 0, 0.75);
      position: absolute;
      top: 0; left: 0;
      width: 100%;
      height: 100%;
      z-index: 0;
    }
    .container {
      position: relative;
      z-index: 1;
      max-width: 450px;
      margin: 80px auto;
      padding: 30px 25px;
      background: rgba(30, 0, 0, 0.85);
      border-radius: 15px;
      box-shadow: 0 0 20px #ff0033;
      text-align: center;
    }
    .icon {
      width: 70px;
      margin-bottom: 10px;
      filter: drop-shadow(0 0 5px #ff0033);
    }
    h1 {
      font-size: 2rem;
      color: #ff0033;
      text-shadow: 0 0 10px #ff0033;
      margin-bottom: 8px;
    }
    .typewriter {
      font-family: monospace;
      overflow: hidden;
      border-right: 2px solid #ff0033;
      white-space: nowrap;
      letter-spacing: .1em;
      margin: 0 auto 20px;
      animation: typing 3s steps(30, end), blink .75s step-end infinite;
      color: #ff0033;
    }
    @keyframes typing {
      from { width: 0 }
      to { width: 100% }
    }
    @keyframes blink {
      50% { border-color: transparent }
    }
    input, select, button {
      width: 100%;
      padding: 12px;
      margin: 12px 0;
      border-radius: 10px;
      font-size: 1rem;
      border: none;
    }
    input, select {
      background: #330000;
      color: #fff;
      border: 1px solid #aa0000;
    }
    button {
      background: #ff0033;
      color: #fff;
      font-weight: bold;
      cursor: pointer;
      box-shadow: 0 0 10px #ff0033;
      transition: 0.3s;
    }
    .loading, .success {
      display: none;
      margin-top: 15px;
      font-size: 1rem;
      font-weight: bold;
    }
    .loading { color: #f33; }
    .success { color: #39ff14; font-size: 1.2rem; }
    #priceEstimate {
      color: #00cc66;
      font-weight: bold;
    }
    footer {
      text-align: center;
      margin-top: 40px;
      color: #999;
      font-size: 0.85rem;
      position: relative;
      z-index: 1;
    }

    /* Profile Button */
    #profileBtn {
      position: fixed;
      top: 20px;
      right: 20px;
      z-index: 100;
      cursor: pointer;
      border-radius: 50%;
      background: rgba(255, 255, 255, 0.1);
      padding: 6px;
      box-shadow: 0 0 10px #ff0033;
      display: none;
    }
    #profileBtn img {
      width: 38px;
      height: 38px;
      border-radius: 50%;
    }

    /* Dashboard Modal */
    #userDashboard {
      display: none;
      position: fixed;
      top: 0; left: 0;
      width: 100vw; height: 100vh;
      background: rgba(0,0,0,0.95);
      z-index: 9999;
      overflow-y: auto;
      padding: 20px;
    }
    .dashboard-box {
      background: #1a0000;
      padding: 20px;
      margin-bottom: 20px;
      border-radius: 12px;
      box-shadow: 0 0 10px #ff0033;
    }
    .dashboard-box h2 {
      color: #ff0033;
      margin-bottom: 10px;
    }
    #userDashboard input {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      background: #330000;
      border: 1px solid #aa0000;
      border-radius: 8px;
      color: #fff;
    }
    .closeDash {
      position: absolute;
      top: 20px;
      right: 30px;
      background: #ff0033;
      color: white;
      border: none;
      padding: 8px 16px;
      border-radius: 6px;
      font-weight: bold;
      cursor: pointer;
    }
  </style>
</head>
<body>

<div id="loader">Loading, please wait...</div>

<video autoplay muted loop id="bgVideo">
  <source src="https://files.catbox.moe/yuhyp5.mp4" type="video/mp4">
</video>
<div class="overlay"></div>

<!-- Profile Button (initially hidden) -->
<div id="profileBtn" onclick="toggleDashboard()">
  <img id="profileImage" src="https://img.icons8.com/fluency/48/user-male-circle.png" alt="Profile" />
</div>

<!-- User Dashboard -->
<div id="userDashboard">
  <button class="closeDash" onclick="toggleDashboard()">Close ✖</button>
  <div class="dashboard-box">
    <h2>👤 USER INFO</h2>
    <input type="email" id="updateEmail" placeholder="Change Email" />
    <input type="password" id="updatePass" placeholder="Change Password" />
    <input type="text" id="updatePic" placeholder="Profile Picture URL" />
    <button onclick="updateUserInfo()">Update Info</button>
  </div>
  <div class="dashboard-box">
    <h2>📈 DASHBOARD / ACTIVITY</h2>
    <p>No boost activity found yet.</p>
  </div>
  <div class="dashboard-box">
    <h2>⚙️ SETTINGS</h2>
    <button onclick="logout()">Logout</button>
    <button onclick="deleteAccount()">Delete Account</button>
  </div>
</div>

<!-- Your existing content remains unchanged -->
<!-- Login/signup container -->
<div class="container" id="authContainer">
  <h1>Welcome to MR SMILE IG BOOST</h1>
  <div class="typewriter">Login or Sign Up to Continue</div>
  <select id="authMode" onchange="switchAuthMode()">
    <option value="login">Login</option>
    <option value="signup">Sign Up</option>
  </select>
  <input type="email" id="authEmail" placeholder="Email address" />
  <input type="password" id="authPassword" placeholder="Password" />
  <input type="password" id="confirmPassword" placeholder="Confirm Password" style="display:none;" />
  <div id="mathCaptcha">
    <label id="mathQuestion">🧮 What is 5 + 2?</label>
    <input type="number" id="mathAnswer" placeholder="Answer" />
  </div>
  <button onclick="handleAuth()">Continue</button>
</div>

<!-- Boost app UI -->
<div class="container" id="appContainer" style="display: none;">
  <h1>IG Boost Tool</h1>
  <div class="typewriter">Boost Followers or Likes Fast!</div>
  <input type="url" id="igLink" placeholder="Instagram Post/Profile URL" />
  <select id="boostType">
    <option value="followers">Followers</option>
    <option value="likes">Likes</option>
  </select>
  <input type="number" id="amount" placeholder="Enter amount (e.g. 100)" />
  <div id="priceEstimate">Required Amount: KES 0</div>
  <button onclick="startBoost()">Boost Now</button>
  <div class="loading" id="loadingText">🚀 Boosting in progress... Please wait</div>
  <div class="success" id="successText">✅ Boost completed successfully!</div>
</div>

<footer>&copy; 2025 IG Booster | MR SMILE</footer>

<script>
  const users = JSON.parse(localStorage.getItem("users") || "{}");
  const num1 = Math.floor(Math.random() * 10 + 1);
  const num2 = Math.floor(Math.random() * 10 + 1);
  const correctAnswer = num1 + num2;
  document.getElementById("mathQuestion").innerText = `🧮 What is ${num1} + ${num2}?`;

  function switchAuthMode() {
    const mode = document.getElementById("authMode").value;
    document.getElementById("confirmPassword").style.display = mode === "signup" ? "block" : "none";
  }

  function handleAuth() {
    const email = document.getElementById("authEmail").value.trim().toLowerCase();
    const password = document.getElementById("authPassword").value;
    const confirm = document.getElementById("confirmPassword").value;
    const userAnswer = parseInt(document.getElementById("mathAnswer").value.trim());
    const mode = document.getElementById("authMode").value;

    if (!email || !password || isNaN(userAnswer)) return alert("❌ Fill all fields correctly.");
    if (userAnswer !== correctAnswer) return alert("❌ Wrong math answer.");

    if (mode === "signup") {
      if (users[email]) return alert("❌ Email already registered.");
      if (password !== confirm) return alert("❌ Passwords do not match.");
      users[email] = { password, pic: "", email };
      localStorage.setItem("users", JSON.stringify(users));
      alert("✅ Account created!");
    } else {
      if (!users[email]) return alert("❌ Email not found.");
      if (users[email].password !== password) return alert("❌ Wrong password.");
      alert("✅ Logged in!");
    }

    localStorage.setItem("currentUser", email);
    document.getElementById("authContainer").style.display = "none";
    document.getElementById("appContainer").style.display = "block";
    document.getElementById("profileBtn").style.display = "block";

    const user = users[email];
    document.getElementById("profileImage").src = user.pic || "https://img.icons8.com/fluency/48/user-male-circle.png";
  }

  function toggleDashboard() {
    const dash = document.getElementById("userDashboard");
    dash.style.display = dash.style.display === "flex" ? "none" : "flex";
    dash.style.flexDirection = "column";
  }

  function updateUserInfo() {
    const email = localStorage.getItem("currentUser");
    const user = users[email];
    const newEmail = document.getElementById("updateEmail").value.trim().toLowerCase();
    const newPass = document.getElementById("updatePass").value;
    const newPic = document.getElementById("updatePic").value;

    if (newEmail) user.email = newEmail;
    if (newPass) user.password = newPass;
    if (newPic) {
      user.pic = newPic;
      document.getElementById("profileImage").src = newPic;
    }

    users[email] = user;
    localStorage.setItem("users", JSON.stringify(users));
    alert("✅ Info updated!");
  }

  function logout() {
    localStorage.removeItem("currentUser");
    location.reload();
  }

  function deleteAccount() {
    const email = localStorage.getItem("currentUser");
    if (confirm("❌ Delete your account?")) {
      delete users[email];
      localStorage.setItem("users", JSON.stringify(users));
      logout();
    }
  }

  document.getElementById("amount").addEventListener("input", function () {
    const amount = parseInt(this.value.trim());
    const priceBox = document.getElementById("priceEstimate");
    if (!amount || amount < 100) {
      priceBox.innerText = "❌ Minimum boost is 100";
      return;
    }
    const extra = Math.ceil((amount - 100) / 50);
    const price = 150 + (extra * 50);
    priceBox.innerText = `Required Amount: KES ${price}`;
  });

  window.addEventListener("load", () => {
    setTimeout(() => document.getElementById("loader").style.display = "none", 1500);
  });
</script>

</body>
</html>
