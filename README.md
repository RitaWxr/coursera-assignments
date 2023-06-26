<!DOCTYPE html>
<html>
<head>
  <title>Rita's Menu</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@500&display=swap" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Lato:wght@400&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: "Lato", Arial, sans-serif;
      text-align: center;
    }

    h1 {
      font-family: "Montserrat", Arial, sans-serif;
      font-size: 36px;
      margin-top: 40px;
    }

    .sections {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
    }

    .section {
      background-color: purple;
      color: white;
      padding: 20px;
      position: relative;
      flex: 1;
      border: 0.8px solid #ffa500;
    }

    .section-title {
      position: absolute;
      top: 0;
      right: 0;
      padding: 5px 10px;
      font-size: 16px;
      background-color: #333;
      border: 0.5px solid white;
      color: white;
      margin: 0;
    }

    .section-content {
      margin-top: 20px;
    }

    @media (min-width: 768px) and (max-width: 991px) {
      .sections {
        flex-wrap: wrap;
      }

      .section {
        width: calc(50% - 10px);
      }

      .section:nth-child(3) {
        width: 100%;
        margin-top: 20px;
      }
    }

    @media (max-width: 767px) {
      .section {
        flex: none;
      }
    }
  </style>
</head>
<body>
  <h1>Rita's Menu</h1>

  <div class="sections">
    <div class="section">
      <div class="section-title" style="background-color: #ff5500;">Dimsum</div>
      <div class="section-content">
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
      </div>
    </div>

    <div class="section">
      <div class="section-title" style="background-color: #0077ff;">Ramen</div>
      <div class="section-content">
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
      </div>
    </div>

    <div class="section">
      <div class="section-title" style="background-color: #55aa00;">Jjigae</div>
      <div class="section-content">
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
      </div>
    </div>
  </div>
</body>
</html>
