<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Commits PWA</title>
  <link rel="stylesheet" type="text/css" href="css/style.css">
</head>
<body>
    <div class="app app__layout">
      <header>
        <span class="header__icon">
          <svg class="menu__icon no--select" width="24px" height="24px" viewBox="0 0 48 48" fill="#fff">
            <path d="M6 36h36v-4H6v4zm0-10h36v-4H6v4zm0-14v4h36v-4H6z"></path>
          </svg>
        </span>

        <span class="header__title no--select">PWA - Home</span>
      </header>

      <div class="menu">
        <div class="menu__header"></div>
        <ul class="menu__list">
          <li><a href="index.html">Home</a></li>
          <li><a href="latest.html">Latest</a></li>
      </div>

      <div class="menu__overlay"></div>

      <div class="app__content">

        <section class="section">
          <h3> Stay Up to Date with R-I-L </h3>
          <img class="profile-pic" src="./images/books.png" alt="Hello, World!">

          <p class="home-note">Latest Commits on Resources I like!</a></p>
        </section>


        <div class="fab fab__push">
          <div class="fab__ripple"></div>
          <img class="fab__image" src="./images/push-off.png" alt="Push Notification" />
        </div>

        <!-- Toast msg's  -->
        <div class="toast__container"></div>
      </div>
    </div>

    <script src="./js/app.js"></script>
    <script src="./js/toast.js"></script>
    <script src="./js/offline.js"></script>
    <script src="./js/menu.js"></script>
</body>
</html>
