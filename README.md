# wechat_loader2
Wechat-Like Loading Loader 2

<!DOCTYPE html>
<html>
<head>
  <style>
    body {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      background: #f5f5f5;
    }

    .wechat-loader-box {
      width: 120px;
      height: 120px;
      background: rgba(0, 0, 0, 0.7);
      border-radius: 10px;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      gap: 16px;
    }

    .wechat-spinner {
      width: 36px;
      height: 36px;
      border: 3px solid rgba(255, 255, 255, 0.2);
      border-top: 3px solid #07C160; /* WeChat green */
      border-radius: 50%;
      animation: spin 0.8s linear infinite;
    }

    .wechat-loader-text {
      color: white;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
      font-size: 15px;
      font-weight: 400;
    }

    @keyframes spin {
      0% { transform: rotate(0deg); }
      100% { transform: rotate(360deg); }
    }
  </style>
</head>
<body>
  <div class="wechat-loader-box">
    <div class="wechat-spinner"></div>
    <div class="wechat-loader-text">Loading</div>
  </div>
</body>
</html>
