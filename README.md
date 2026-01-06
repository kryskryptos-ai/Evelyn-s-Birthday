# Evelyn-s-Birthday
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Evelyn’s Birthday</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background: #0f0f0f;
      font-family: "Georgia", serif;
    }

    .whisper {
      color: #ff8fcf;
      font-size: 2.6rem;
      letter-spacing: 2px;
      opacity: 0.8;
      text-shadow: 
        0 0 6px rgba(255, 143, 207, 0.6),
        0 0 14px rgba(255, 143, 207, 0.35);
      animation: fade 4s ease-in-out infinite;
    }

    @keyframes fade {
      0% { opacity: 0.4; }
      50% { opacity: 1; }
      100% { opacity: 0.4; }
    }

    .small {
      font-size: 1.4rem;
      font-style: italic;
    }
  </style>
</head>
<body>
  <div class="whisper">
    happy birthday <span class="small">*whispers*</span>
  </div>
</body>
</html>
