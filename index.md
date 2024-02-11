<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Jarvis AI Assistant</title>
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f9f9f9;
      margin: 0;
      padding: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }
    .container {
      max-width: 600px;
      background-color: #fff;
      border-radius: 15px;
      box-shadow: 0 0 30px rgba(0, 0, 0, 0.1);
      padding: 40px;
    }
    .chat-bubble {
      background-color: #007bff;
      color: #fff;
      border-radius: 20px;
      padding: 15px 20px;
      max-width: 70%;
      margin-bottom: 20px;
      position: relative;
    }
    .chat-bubble.left {
      align-self: flex-start;
      border-top-left-radius: 5px;
    }
    .chat-bubble.right {
      align-self: flex-end;
      background-color: #4caf50;
      border-top-right-radius: 5px;
    }
    .chat-bubble::after {
      content: '';
      position: absolute;
      width: 0;
      height: 0;
      border-top: 10px solid transparent;
      border-bottom: 10px solid transparent;
    }
    .chat-bubble.left::after {
      right: -10px;
      top: 50%;
      border-left: 10px solid #007bff;
      transform: translateY(-50%);
    }
    .chat-bubble.right::after {
      left: -10px;
      top: 50%;
      border-right: 10px solid #4caf50;
      transform: translateY(-50%);
    }
    .welcome-message {
      font-size: 22px;
      font-weight: bold;
      margin-bottom: 30px;
      text-align: center;
    }
    .start-button {
      display: block;
      width: 100%;
      padding: 15px 0;
      border: none;
      border-radius: 30px;
      background-color: #007bff;
      color: #fff;
      font-size: 18px;
      font-weight: bold;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }
    .start-button:hover {
      background-color: #0056b3;
    }
  </style>
</head>
<body>
  <div class="container">
    <p class="welcome-message">Welcome to Jarvis, your personal AI assistant.</p>
    <button class="start-button" onclick="initEmbeddedMessaging()">Start Chatting</button>
  </div>

  <script>
    function initEmbeddedMessaging() {
      try {
        embeddedservice_bootstrap.settings.language = 'en_US'; 
        embeddedservice_bootstrap.init(
          '00D3O0000006Swf',
          'NorthernHub',
          'https://abb--comfsldev.sandbox.my.site.com/ESWNorthernHub1707191425001',
          {
            scrt2URL: 'https://abb--comfsldev.sandbox.my.salesforce-scrt.com'
          }
        );
      } catch (err) {
        console.error('Error loading Embedded Messaging: ', err);
      }
    }
  </script>
</body>
</html>
