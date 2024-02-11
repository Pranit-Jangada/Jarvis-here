<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1, minimum-scale=1">
  <title>Chat with Jarvis</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f0f0f0;
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
      border-radius: 10px;
      box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
      padding: 20px;
    }
    p {
      margin: 0 0 20px;
    }
    .chat-bubble {
      background-color: #007bff;
      color: #fff;
      border-radius: 15px;
      padding: 10px 15px;
      max-width: 70%;
      margin-bottom: 20px;
    }
    .chat-bubble.left {
      align-self: flex-start;
    }
    .chat-bubble.right {
      align-self: flex-end;
      background-color: #4caf50;
    }
  </style>
</head>
<body>
  <div class="container">
    <p>Welcome to Jarvis, your personal AI assistant. click on bubble to get started</p>
    <script type='text/javascript'>
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
      };
    </script>
    <script type='text/javascript' src='https://abb--comfsldev.sandbox.my.site.com/ESWNorthernHub1707191425001/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
  </div>
</body>
</html>
