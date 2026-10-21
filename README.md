
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="theme-color" content="#10172a">
  <title>مشروعي | بداية جديدة</title>
  <style>
    * { box-sizing: border-box; }
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #10172a;
      color: white;
      line-height: 1.8;
    }
    header {
      padding: 22px;
      text-align: center;
      border-bottom: 1px solid #28334d;
    }
    header span { color: #65e0c1; font-weight: bold; }
    main {
      max-width: 650px;
      margin: auto;
      padding: 45px 20px;
    }
    .tag {
      display: inline-block;
      background: #203c48;
      color: #65e0c1;
      padding: 5px 14px;
      border-radius: 30px;
      font-size: 14px;
    }
    h1 {
      font-size: clamp(34px, 8vw, 52px);
      line-height: 1.35;
      margin: 22px 0;
    }
    h1 span { color: #65e0c1; }
    p { color: #bdc8dc; font-size: 17px; }
    .card {
      margin-top: 30px;
      padding: 25px;
      border: 1px solid #34425e;
      border-radius: 22px;
      background: #19233a;
    }
    .symbol {
      font-size: 36px;
      background: #263b50;
      width: 65px;
      height: 65px;
      display: grid;
      place-items: center;
      border-radius: 18px;
    }
    button {
      width: 100%;
      padding: 15px;
      margin-top: 15px;
      border: 0;
      border-radius: 12px;
      background: #65e0c1;
      color: #10172a;
      font-size: 17px;
      font-weight: bold;
      cursor: pointer;
    }
    footer {
      text-align: center;
      padding: 25px;
      color: #8998b3;
      font-size: 14px;
    }
  </style>
</head>
<body>
  <header>
    ✦ <span>مشروعي</span>
  </header>

  <main>
    <span class="tag">🚀 بداية رحلتي</span>

    <h1>كل فكرة عظيمة تبدأ <span>بخطوة.</span></h1>

    <p>
      أهلًا بك في مشروعي الأول!
      أبني هذا المشروع خطوة بخطوة،
      وأسعى إلى تطويره ليصبح شيئًا مميزًا.
    </p>

    <section class="card">
      <div class="symbol">💡</div>
      <h2>فكرتي، طموحي، ومستقبلي</h2>
      <p id="details">
        هذه البداية فقط. ترقّبوا المزيد من التطوير
        والميزات الجديدة قريبًا.
      </p>
      <button onclick="showDetails()">اكتشف المزيد ✨</button>
    </section>
  </main>

  <footer>
    صُنع بكل شغف ❤️
  </footer>

  <script>
    function showDetails() {
      document.getElementById("details").textContent =
        "شكرًا لزيارتك! هذا المشروع في بداية رحلته، وسأعمل على تطويره وإضافة ميزات جديدة مع الوقت.";
    }
  </script>
</body>
</html>
