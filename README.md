<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>18+ Offer</title>
  <style>
    /* Styling for the page */
    body {
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
      color: white;
      background: url('https://imagex1.sx.cdn.live/images/pinporn/2019/06/01/21247122.gif') no-repeat center center fixed;
      background-size: cover;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      position: relative;
    }
    .overlay {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: url('https://i.gifer.com/7efs.gif') no-repeat center center;
      background-size: contain;
      opacity: 0.6;
      z-index: 0;
    }
    .container {
      background-color: rgba(0, 0, 0, 0.7);
      padding: 20px;
      border-radius: 15px;
      text-align: center;
      max-width: 90%;
      width: 400px;
      z-index: 1;
    }
    button {
      padding: 10px 20px;
      margin-top: 15px;
      font-size: 16px;
      border: none;
      border-radius: 5px;
      background-color: crimson;
      color: white;
      cursor: pointer;
    }
    .hidden {
      display: none;
    }
  </style>
</head>
<body>
  <div class="overlay"></div>

  <div class="container" id="step1">
    <h2>আপনার লিঙ্গ নির্বাচন করুন</h2>
    <button onclick="nextStep('male')">পুরুষ</button>
    <button onclick="nextStep('female')">মহিলা</button>
  </div>

  <div class="container hidden" id="step2">
    <h2>আপনি কি ১৮+?</h2>
    <button onclick="nextStep2()">হ্যাঁ</button>
  </div>

  <div class="container hidden" id="step3">
    <h2>BotLA_Rocket</h2>
    <button onclick="window.location.href='https://rb.gy/acw2xb'">START</button>
  </div>

  <script>
    function nextStep(gender) {
      document.getElementById('step1').classList.add('hidden');
      document.getElementById('step2').classList.remove('hidden');
    }
    function nextStep2() {
      document.getElementById('step2').classList.add('hidden');
      document.getElementById('step3').classList.remove('hidden');
    }
  </script>
</body>
</html>
