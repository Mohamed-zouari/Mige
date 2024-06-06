# Mige
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Audio Waveform Visualizer</title>
  <style>
    body {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      background-color: #f0f0f0;
      font-family: Arial, sans-serif;
    }

    #waveform-container {
      width: 80%;
      height: 200px;
      background-color: #fff;
      border-radius: 8px;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
      overflow: hidden;
    }

    #waveform {
      width: 100%;
      height: 100%;
      display: flex;
      align-items: flex-end;
    }

    .bar {
      width: 2px;
      margin: 0 1px;
      background-color: #4CAF50;
      animation: wave 2s infinite linear;
    }

    @keyframes wave {
      0% {
        transform: scaleY(0.2);
      }
      50% {
        transform: scaleY(1);
      }
      100% {
        transform: scaleY(0.2);
      }
    }
  </style>
</head>
<body>
  <div id="waveform-container">
    <div id="waveform">
      <div class="bar"></div>
      <div class="bar"></div>
      <div class="bar"></div>
      <div class="bar"></div>
      <div class="bar"></div>
      <div class="bar"></div>
      <div class="bar"></div>
      <div class="bar"></div>
      <div class="bar"></div>
      <div class="bar"></div>
    </div>
  </div>
</body>
</html>
