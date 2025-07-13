<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Vaidic Aarogya Sindhu - 100% Cashback Offer</title>
  <style>
    body {
      margin: 0;
      padding: 10px;
      font-family: 'Arial', sans-serif;
      background: linear-gradient(135deg, #FF6B6B 0%, #4ECDC4 100%);
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
    }

    .whatsapp-poster {
      width: 400px;
      background: white;
      border-radius: 20px;
      overflow: hidden;
      box-shadow: 0 20px 40px rgba(0,0,0,0.2);
      position: relative;
    }

    .header {
      background: linear-gradient(135deg, #25D366 0%, #128C7E 100%);
      color: white;
      text-align: center;
      padding: 25px 15px;
      position: relative;
      overflow: hidden;
    }

    .header::before {
      content: '💰';
      position: absolute;
      font-size: 100px;
      opacity: 0.1;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
    }

    .offer-text {
      font-size: 1.1em;
      position: relative;
      z-index: 1;
    }

    .cashback-banner {
      background: linear-gradient(45deg, #FF3838, #FF6B6B);
      color: white;
      text-align: center;
      padding: 20px;
      margin: 0;
      font-size: 1.8em;
      font-weight: bold;
      animation: glow 2s ease-in-out infinite alternate;
      position: relative;
      overflow: hidden;
    }

    .cashback-banner::before {
      content: '🔥';
      position: absolute;
      left: 10px;
      top: 50%;
      transform: translateY(-50%);
      font-size: 1.5em;
      animation: bounce 1s infinite;
    }

    .cashback-banner::after {
      content: '🔥';
      position: absolute;
      right: 10px;
      top: 50%;
      transform: translateY(-50%);
      font-size: 1.5em;
      animation: bounce 1s infinite reverse;
    }

    @keyframes glow {
      from { box-shadow: 0 0 20px rgba(255,56,56,0.5); }
      to { box-shadow: 0 0 30px rgba(255,56,56,0.8); }
    }

    @keyframes bounce {
      0%, 20%, 50%, 80%, 100% { transform: translateY(-50%); }
      40% { transform: translateY(-70%); }
      60% { transform: translateY(-60%); }
    }

    .content {
      padding: 25px 20px;
    }

    .brands-section {
      margin-bottom: 25px;
    }

    .brands-title {
      text-align: center;
      font-size: 1.3em;
      color: #333;
      margin-bottom: 20px;
      font-weight: bold;
    }

    .brand-card {
      background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
      color: white;
      padding: 15px;
      margin: 10px 0;
      border-radius: 15px;
      text-align: center;
      font-weight: bold;
      font-size: 1.1em;
      box-shadow: 0 5px 15px rgba(102,126,234,0.3);
      transform: translateX(-5px);
      transition: all 0.3s ease;
    }

    .brand-card:hover {
      transform: translateX(0px) scale(1.02);
    }

    .brand-card:nth-child(even) {
      background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
      transform: translateX(5px);
    }

    .brand-card:nth-child(odd) {
      background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
    }

    .how-it-works {
      background: #f8f9fa;
      padding: 20px;
      border-radius: 15px;
      margin: 20px 0;
      border-left: 5px solid #25D366;
    }

    .how-it-works h3 {
      color: #25D366;
      margin-bottom: 15px;
      font-size: 1.2em;
    }

    .step {
      display: flex;
      align-items: center;
      margin: 10px 0;
      padding: 8px;
      background: white;
      border-radius: 10px;
      font-size: 0.95em;
    }

    .step-number {
      background: #25D366;
      color: white;
      width: 25px;
      height: 25px;
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      margin-right: 10px;
      font-weight: bold;
      font-size: 0.9em;
    }

    .cta-section {
      text-align: center;
      margin-top: 25px;
    }

    .register-btn {
      background: linear-gradient(135deg, #25D366 0%, #128C7E 100%);
      color: white;
      padding: 15px 30px;
      border-radius: 25px;
      text-decoration: none;
      font-weight: bold;
      font-size: 1.1em;
      display: inline-block;
      box-shadow: 0 5px 15px rgba(37,211,102,0.4);
      transition: all 0.3s ease;
    }

    .register-btn:hover {
      transform: translateY(-3px);
      box-shadow: 0 10px 25px rgba(37,211,102,0.6);
    }

    .share-message {
      background: linear-gradient(135deg, #FF9A9E 0%, #FECFEF 100%);
      padding: 20px;
      margin: 20px 0;
      border-radius: 15px;
      text-align: center;
    }

    .share-message h3 {
      color: #E91E63;
      margin-bottom: 10px;
    }

    .whatsapp-message {
      background: white;
      padding: 15px;
      border-radius: 10px;
      border: 2px dashed #25D366;
      font-style: italic;
      color: #333;
      font-size: 0.9em;
      line-height: 1.4;
    }

    .footer {
      background: #2c3e50;
      color: white;
      text-align: center;
      padding: 15px;
      font-size: 0.9em;
    }

    .urgency {
      background: #FFA726;
      color: white;
      text-align: center;
      padding: 10px;
      font-weight: bold;
      animation: pulse 2s infinite;
    }

    @keyframes pulse {
      0% { opacity: 1; }
      50% { opacity: 0.7; }
      100% { opacity: 1; }
    }
  </style>
</head>
<body>
  <div class="whatsapp-poster">
    <div class="header">
      <div class="offer-text">Hyderabad's #1 Health Store</div>
    </div>

    <div class="cashback-banner">
      💯 100% CASHBACK! 💯
    </div>

    <div class="urgency">
      ⏰ LIMITED TIME OFFER - DON'T MISS OUT!
    </div>

    <div class="content">
      <div class="brands-section">
        <div class="brands-title">🏆 Premium Brands Available:</div>

        <div class="brand-card">
          🌿 BAIDYANATH
          <div style="font-size: 0.9em; margin-top: 5px;">Ayurvedic Excellence</div>
        </div>

        <div class="brand-card">
          💊 DABUR
          <div style="font-size: 0.9em; margin-top: 5px;">Trusted Health Solutions</div>
        </div>

        <div class="brand-card">
          🕉️ VAIDIC
          <div style="font-size: 0.9em; margin-top: 5px;">Traditional Wellness</div>
        </div>
      </div>

      <div class="how-it-works">
        <h3>🚀 How to Get 100% Cashback:</h3>
        <div class="step">
          <div class="step-number">1</div>
          <div>Register on our website</div>
        </div>
        <div class="step">
          <div class="step-number">2</div>
          <div>Purchase any product</div>
        </div>
        <div class="step">
          <div class="step-number">3</div>
          <div>Get 100% money back!</div>
        </div>
      </div>

      <div class="cta-section">
        <a href="https://www.Ayurvedicdava.in/register-now?ul=QUMxMDAwMDE=" class="register-btn">🔗 Register Now</a>
      </div>

      <div class="share-message">
        <h3>📱 Share This Amazing Offer:</h3>
        <div class="whatsapp-message">
          "🔥 Vaidic Aarogya में 100% CASHBACK! 🔥 <br><br>
          Baidyanath, Dabur, Vaidic products पर पूरा पैसा वापस! 💰<br><br>
          मेरे link से register करें: https://www.Ayurvedicdava.in/register-now?ul=QUMxMDAwMDE=<br><br>
          Limited time offer - जल्दी करें! ⏰
        </div>
      </div>
    </div>

    <div class="footer">
      <p>📍 Greater Noida | 📞 Contact: +91-8750360591 , 8470807059</p>
      <p>🌐 Visit: www.ayurvedicdava.in</p>
    </div>
  </div>
</body>
</html>