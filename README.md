<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bitcoin Clicker Game</title>
  <!-- Google AdSense Script -->
  <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      background-color: #111;
      color: #fff;
      padding: 50px;
    }
    button {
      font-size: 20px;
      padding: 10px 20px;
      background-color: #f7931a;
      border: none;
      border-radius: 10px;
      color: white;
      cursor: pointer;
      margin: 10px;
    }
    button:hover {
      background-color: #d58209;
    }
    #btc-counter {
      font-size: 2em;
      margin: 20px 0;
    }
    .ad-container {
      margin: 20px auto;
    }
  </style>
</head>
<body>
  <h1>Bitcoin Clicker Game</h1>
  <p>Click to Earn BTC Rewards! Cash Out with PayPal or Cash App.</p>

  <!-- Ad Container: Top Banner -->
  <div class="ad-container">
    <ins class="adsbygoogle"
         style="display:block"
         data-ad-client="ca-pub-XXXXXXXXXXXXXXX" <!-- Replace with your Publisher ID -->
         data-ad-slot="1234567890" <!-- Replace with your Ad Slot -->
         data-ad-format="auto"></ins>
    <script>
      (adsbygoogle = window.adsbygoogle || []).push({});
    </script>
  </div>

  <div id="btc-counter">BTC: 0</div>
  <button id="mine-btn">⛏️ Mine Bitcoin</button>

  <script>
    let btcCount = 0;
    const btcCounter = document.getElementById('btc-counter');
    const mineBtn = document.getElementById('mine-btn');

    mineBtn.addEventListener('click', function() {
        btcCount += 1;
        btcCounter.innerText = `BTC: ${btcCount}`;
    });
  </script>
</body>
</html>
