<!DOCTYPE html>
<html>
  <head>
    <title>postMessage-test</title>
    <meta charset="UTF-8" />
  </head>

  <body>
    <h1>操作介面</h1>
    <label for="message">輸入訊息：</label>
    <input
      type="text"
      id="message"
      placeholder="輸入要傳送的訊息"
      value="操作介面回傳訊息"
    />
    <button id="sendMessage">傳送訊息</button>

    <script>
      let messageSent = false; // 是否已發送

      document
        .getElementById("sendMessage")
        .addEventListener("click", function () {
          const message = document.getElementById("message").value;
          if (window.opener) {
            console.log(window.opener);
            window.opener.postMessage(message, "https://cdpn.io");
            messageSent = true; // 訊息已發送，設置標誌
            alert("訊息已傳送：" + message);
          } else {
            alert("無法找到 opener，請確保此頁是由另一個頁面開啟的。");
          }
          window.close();
        });

      // 當頁面準備關閉時發送通知
      window.onbeforeunload = function () {
        if (window.opener && !messageSent) {
          window.opener.postMessage("第二個頁面已關閉", "*");
        }
      };
    </script>
  </body>
</html>
