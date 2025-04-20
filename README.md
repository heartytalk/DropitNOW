<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <title>자음 모음 게임판</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      background-color: #f9f9f9;
      text-align: center;
      padding: 20px;
    }

    h1 {
      margin-bottom: 20px;
    }

    .game-board {
      display: grid;
      grid-template-columns: repeat(6, 80px);
      grid-auto-rows: 80px;
      gap: 10px;
      justify-content: center;
      margin: 0 auto;
    }

    .card {
      display: flex;
      align-items: center;
      justify-content: center;
      background-color: #fff;
      border: 2px solid #333;
      border-radius: 12px;
      font-size: 28px;
      font-weight: bold;
      box-shadow: 2px 2px 6px rgba(0, 0, 0, 0.2);
    }

    .card.empty {
      border: none;
      background: transparent;
      box-shadow: none;
    }
  </style>
</head>
<body>
  <h1>자음 · 모음 게임판</h1>
  <div class="game-board">
    <!-- 1행 -->
    <div class="card">ㄱ</div>
    <div class="card">ㄴ</div>
    <div class="card">ㄷ</div>
    <div class="card">ㄹ</div>
    <div class="card">ㅁ</div>
    <div class="card">ㅂ</div>

    <!-- 2행 -->
    <div class="card">ㅅ</div>
    <div class="card">ㅇ</div>
    <div class="card">ㅈ</div>
    <div class="card">ㅊ</div>
    <div class="card">ㅋ</div>
    <div class="card">ㅌ</div>

    <!-- 3행 -->
    <div class="card">ㅍ</div>
    <div class="card">ㅎ</div>
    <div class="card empty"></div>
    <div class="card empty"></div>
    <div class="card empty"></div>
    <div class="card empty"></div>

    <!-- 4행 -->
    <div class="card">ㅏ</div>
    <div class="card">ㅑ</div>
    <div class="card">ㅓ</div>
    <div class="card">ㅕ</div>
    <div class="card">ㅗ</div>
    <div class="card">ㅛ</div>

    <!-- 5행 -->
    <div class="card">ㅜ</div>
    <div class="card">ㅠ</div>
    <div class="card">ㅡ</div>
    <div class="card">ㅣ</div>
    <div class="card empty"></div>
    <div class="card empty"></div>
  </div>
</body>
</html>
