<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>ラーメン店｜公式ホームページ</title>
  <style>
    body { font-family: sans-serif; margin: 0; padding: 0; background: #faf7f2; }
    header { background: #c62828; color: white; padding: 20px; text-align: center; }
    nav { background: #8e0000; padding: 10px; text-align: center; }
    nav a { color: white; margin: 0 15px; text-decoration: none; font-weight: bold; }
    .hero { background: url('ramen.jpg') center/cover no-repeat; height: 300px; display: flex; align-items: center; justify-content: center; color: white; font-size: 2.5rem; text-shadow: 2px 2px 5px #000; }
    .container { max-width: 900px; margin: auto; padding: 20px; }
    h2 { border-left: 8px solid #c62828; padding-left: 10px; }
    .menu-item { background: white; margin: 15px 0; padding: 15px; border-radius: 8px; box-shadow: 0 2px 5px rgba(0,0,0,0.1); }
    footer { background: #333; color: white; padding: 20px; text-align: center; margin-top: 40px; }
  </style>
</head>
<body>
  <header>
    <h1>ラーメン屋 ○○</h1>
    <p>こだわりの一杯をご提供します</p>
  </header>

  <nav>
    <a href="#about">当店について</a>
    <a href="#menu">メニュー</a>
    <a href="#access">アクセス</a>
  </nav>

  <div class="hero">
    本格派ラーメン
  </div>

  <div class="container">
    <section id="about">
      <h2>当店について</h2>
      <p>ラーメン屋○○は、地元食材にこだわったスープと自家製麺で、多くのお客様に愛されているラーメン店です。毎日丹精込めて仕込みを行い、安心・安全で美味しいラーメンを提供しています。</p>
    </section>

    <section id="menu">
      <h2>メニュー</h2>

      <div class="menu-item">
        <h3>醤油ラーメン …… 850円</h3>
        <p>昔ながらのあっさり醤油スープに特製チャーシュー。</p>
      </div>

      <div class="menu-item">
        <h3>味噌ラーメン …… 900円</h3>
        <p>濃厚ながらもまろやかな味噌スープが人気。</p>
      </div>

      <div class="menu-item">
        <h3>豚骨ラーメン …… 950円</h3>
        <p>コクのある豚骨スープと自家製細麺。</p>
      </div>
    </section>

    <section id="access">
      <h2>アクセス</h2>
      <p>〒000-0000 東京都〇〇区〇〇1-2-3<br />
      最寄駅：〇〇駅から徒歩5分</p>
      <p>営業時間：11:00〜22:00（定休日：火曜日）</p>
    </section>
  </div>

  <footer>
    © 2025 ラーメン屋 ○○
  </footer>
</body>
</html>
