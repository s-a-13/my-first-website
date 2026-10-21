
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>موقعي الأول</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f0f4f8;
      text-align: center;
      padding: 40px 15px;
      color: #183153;
    }
    .card {
      background: white;
      max-width: 420px;
      margin: 30px auto;
      padding: 30px 20px;
      border-radius: 20px;
      box-shadow: 0 4px 18px #0001;
    }
    button {
      background: #1769ff;
      color: white;
      border: 0;
      border-radius: 10px;
      padding: 12px 22px;
      font-size: 17px;
      margin: 8px;
    }
  </style>
</head>
<body>
  <div class="card">
    <h1 id="title">أهلًا بك في موقعي!</h1>
    <p id="message">هذا أول موقع إلكتروني لي.</p>
    <button onclick="changeLanguage()">English</button>
  </div>

  <script>
    let english = false;

    function changeLanguage() {
      english = !english;
      document.documentElement.lang = english ? "en" : "ar";
      document.documentElement.dir = english ? "ltr" : "rtl";
      document.getElementById("title").textContent =
        english ? "Welcome to my website!" : "أهلًا بك في موقعي!";
      document.getElementById("message").textContent =
        english ? "This is my first website." : "هذا أول موقع إلكتروني لي.";
      document.querySelector("button").textContent =
        english ? "العربية" : "English";
    }
  </script>
</body>
</html>

