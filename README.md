<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>Button Analisa</title>

  <style>
    body {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      height: 100vh;
      background: #f0f8ff;
      font-family: Arial, sans-serif;
      text-align: center;
    }

    .text-follow {
      font-size: 20px;
      margin-bottom: 20px;
      color: #333;
      font-weight: bold;
      animation: bounce 1.5s infinite;
    }

    /* animasi naik turun */
    @keyframes bounce {
      0%, 100% {
        transform: translateY(0);
      }
      50% {
        transform: translateY(-8px);
      }
    }

    .text-follow span {
      color: #00aaff;
      text-shadow: 0 0 8px rgba(0, 170, 255, 0.6);
    }

    .btn-analisa {
      text-decoration: none;
      background: linear-gradient(135deg, #4facfe, #00c6ff);
      color: white;
      padding: 15px 30px;
      font-size: 18px;
      font-weight: bold;
      border-radius: 50px;
      box-shadow: 0 8px 15px rgba(0, 150, 255, 0.3);
      transition: all 0.3s ease;
      position: relative;
      overflow: hidden;
    }

    .btn-analisa:hover {
      transform: translateY(-5px) scale(1.05);
      box-shadow: 0 12px 20px rgba(0, 150, 255, 0.4);
    }

    .btn-analisa:active {
      transform: scale(0.95);
    }

    .btn-analisa::before {
      content: "";
      position: absolute;
      top: 0;
      left: -75%;
      width: 50%;
      height: 100%;
      background: rgba(255,255,255,0.4);
      transform: skewX(-25deg);
      transition: 0.5s;
    }

    .btn-analisa:hover::before {
      left: 130%;
    }
  </style>
</head>
<body>

  <div class="text-follow">
    🔥 Dont Forget To Follow Tiktok <span>@pixelnian</span>
  </div>

  <a href="https://adavdav.github.io/Saham/saham.html" class="btn-analisa">
    🚀 Analisa Sekarang
  </a>

</body>
</html>
