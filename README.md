<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>I'm Sorry ❤️</title>
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; font-family: 'Segoe UI', sans-serif; }
    body {
      min-height: 100vh;
      background: linear-gradient(135deg, #ff9a9e, #fad0c4);
      display: flex;
      align-items: center;
      justify-content: center;
      color: #333;
    }
    .card {
      background: #fff;
      width: 90%;
      max-width: 500px;
      padding: 30px;
      border-radius: 20px;
      box-shadow: 0 20px 40px rgba(0,0,0,0.15);
      text-align: center;
      animation: fadeIn 1.5s ease;
    }
    h1 {
      color: #e63946;
      margin-bottom: 15px;
    }
    p {
      font-size: 1.05rem;
      line-height: 1.6;
      margin-bottom: 20px;
    }
    .heart {
      font-size: 60px;
      animation: beat 1.2s infinite, float 4s ease-in-out infinite;
      margin-bottom: 20px;
    }
    @keyframes float {
      0% { transform: translateY(0); }
      50% { transform: translateY(-10px); }
      100% { transform: translateY(0); }
    }
    button {
      background: #e63946;
      color: #fff;
      border: none;
      padding: 12px 22px;
      border-radius: 25px;
      font-size: 1rem;
      cursor: pointer;
      transition: transform 0.2s, background 0.2s;
    }
    button:hover {
      transform: scale(1.08) rotate(-1deg);
      background: #d62839;
    }
    .hidden {
      display: none;
      margin-top: 20px;
      color: #2a9d8f;
      font-weight: 600;
    }
    @keyframes beat {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.2); }
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>
  <div class="card">
    <div class="heart">❤️</div>
    <h1>I'm Really Sorry, Supriyaa</h1>
    <p>
      Supriyaa, I want to say this from my heart. I made a mistake and I told you a lie.
      There is no excuse for that. You deserve honesty, respect, and truth.
    </p>
    <p>
      I never wanted to hurt you. If my words caused pain, I'm truly sorry.
      I hope one day you can forgive me, even a little.
    </p>
    <button onclick="showMessage()">Please read this</button>
    <div id="msg" class="hidden">
      Supriyaa, you matter to me more than my mistakes. 🌸
    </div>
  </div>  <script>
    function showMessage() {
      const msg = document.getElementById('msg');
      msg.classList.remove('hidden');
      msg.style.animation = 'fadeIn 1s ease';
    }
  </script></body>
</html>
