<!DOCTYPE html>
<html lang="no">
<head>
  <meta charset="utf-8" />
  <title>Spider-Man Grid</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #1a1a1a;
      color: white;
      margin: 0;
      padding: 20px;
    }

    h1 {
      text-align: center;
      color: #e62429;
    }

    .grid-container {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 15px;
      margin-top: 20px;
    }

    .grid-item {
      background-color: #333;
      border: 1px solid #555;
      padding: 15px;
      text-align: center;
      border-radius: 8px;
    }

    .grid-item img {
      max-width: 100%;
      border-radius: 6px;
    }

    .title {
      font-weight: bold;
      margin-top: 10px;
    }
  </style>
</head>
<body>
  <h1>Tom Holland som Spider-Man</h1>

  <div class="grid-container">
    <div class="grid-item">
      <img src="https://upload.wikimedia.org/wikipedia/en/0/00/Spider-Man_No_Way_Home_poster.jpg" alt="No Way Home">
      <div class="title">No Way Home</div>
    </div>
    <div class="grid-item">
      <img src="https://upload.wikimedia.org/wikipedia/en/f/f9/Spider-Man_Homecoming_poster.jpg" alt="Homecoming">
      <div class="title">Homecoming</div>
    </div>
    <div class="grid-item">
      <img src="https://upload.wikimedia.org/wikipedia/en/0/00/Spider-Man_Far_From_Home_poster.jpg" alt="Far From Home">
      <div class="title">Far From Home</div>
    </div>
  </div>
</body>
</html>
