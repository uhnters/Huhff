<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <title>আমার প্রথম ওয়েব পেজ</title>
  <style>
    body {
      background-color: #f0f8ff;
      font-family: Arial, sans-serif;
      text-align: center;
      padding: 50px;
    }h1 {
  color: #2c3e50;
  font-size: 40px;
}

button {
  background-color: #3498db;
  color: white;
  padding: 10px 20px;
  border: none;
  border-radius: 8px;
  font-size: 18px;
  cursor: pointer;
}

button:hover {
  background-color: #2980b9;
}

#message {
  margin-top: 20px;
  font-size: 20px;
  color: green;
}

  </style>
</head>
<body>  <h1>আমার ওয়েবসাইটে স্বাগতম</h1>
  <button onclick="showMessage()">জাদু দেখতে হলে এখনে ক্লিক করো</button>
  <p id="message"></p>  <script>
    function showMessage() {
      document.getElementById("message").innerText = "তুমি একজন অথেন্টিক বলদ!";
    }
  </script></body>
</html>
