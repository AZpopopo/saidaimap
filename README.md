<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <title>埼玉大学 構内図マップ</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #f4f4f4;
      color: #333;
    }

    header {
      background-color: #0066cc;
      color: white;
      padding: 15px;
      text-align: center;
    }

    main {
      padding: 20px;
    }

    h1 {
      font-size: 22px;
      margin-bottom: 10px;
    }

    .map-container {
      text-align: center;
      margin-bottom: 20px;
    }

    .map-container img {
      max-width: 100%;
      height: auto;
      border: 2px solid #ccc;
      border-radius: 8px;
    }

    .buildings {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 10px;
    }

    .building-card {
      background-color: white;
      padding: 10px 15px;
      border-radius: 6px;
      box-shadow: 0 0 6px rgba(0,0,0,0.1);
      width: 160px;
      text-align: center;
      font-size: 14px;
    }

    .pdf-link {
      text-align: center;
      margin-top: 30px;
    }

    .pdf-link a {
      background-color: #0066cc;
      color: white;
      padding: 12px 20px;
      border-radius: 6px;
      text-decoration: none;
      font-weight: bold;
      display: inline-block;
      transition: background-color 0.3s ease;
    }

    .pdf-link a:hover {
      background-color: #004c99;
    }

    footer {
      text-align: center;
      font-size: 13px;
      color: #888;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <header>
    <h2>埼玉大学 構内図マップ</h2>
  </header>

  <main>
    <div class="map-container">
      <!-- 構内図の画像（任意）を配置 -->
      <img src="saitama-campus-map.jpg" alt="埼玉大学構内図">
    </div>

    <h1>主な建物案内</h1>
    <div class="buildings">
      <div class="building-card">教養学部棟</div>
      <div class="building-card">工学部棟</div>
      <div class="building-card">教育学部棟</div>
      <div class="building-card">図書館</div>
      <div class="building-card">生協・食堂</div>
      <div class="building-card">学生センター</div>
    </div>

    <div class="pdf-link">
      🔗 <a href="https://www.saitama-u.ac.jp/access/map.pdf" target="_blank">
        公式PDFキャンパスマップを開く
      </a>
    </div>
  </main>

  <footer>
    &copy; 2025 Saitama University Campus Map Viewer（非公式）
  </footer>

</body>
</html>
