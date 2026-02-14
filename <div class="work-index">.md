<!DOCTYPE html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width,initial-scale=1.0">
    <title>Sabo Day</title>

    <link href="https://cdnjs.cloudflare.com/ajax/libs/magnific-popup.js/1.1.0/magnific-popup.css" rel="stylesheet">

    <!-- <link rel="shortcut icon" type="image/x-icon" href="http://saboday.com/favicon.ico"> -->
  </head>
  <style>
    :root {
  --sd-red: #ff0000;
  --grid-gap: 3em;
}

* {
  box-sizing: border-box;
}

strong {
  font-weight: normal;
  color: white;
}

html, body {
  height: 100vh;
}

body {
  background: var(--sd-red);

  font-family: Helvetica, Arial, san-serif;
  font-weight: bold;
  font-size: 12px;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;

  margin: 0;
}

main {
  position: absolute;
  top: 0;

  height: 100vh;
}

header {
  position: absolute;
  padding: 2em;

  z-index: 99;
}

.work-index {
  height: 100vh;
  width: 100vw;

  padding: var(--grid-gap);

  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-template-rows: repeat(3, 1fr);
  grid-gap: var(--grid-gap);

  align-items: center;
}

.work-item {
  width: 100%;
  height: 100%;

  text-align: center;

  overflow: hidden;
}

.work-item img {
  width: 100%;
  height: 100%;
  object-fit: contain;
}

.information {
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;

  padding: 2em;

  background: red;

  opacity: 0;
  pointer-events: none;

  overflow-y: scroll;
}

.show {
  opacity: 1;
  z-index: 9999;
  pointer-events: auto;
}

.text {
  width: 25%;
}

header, .close {
  cursor: pointer;
}

header:hover, .close:hover, .mfp-close:hover {
  color: white;
}

.close {
  font-size: 18px;
  font-weight: normal;
  font-family: Arial;
}

.mobile-caption {
  display: none;
}

.reload {
  width: 18px;
  height: 18px;

  background-image: url("../icons/arrow.png");
  background-size: contain;
  background-repeat: no-repeat;

  position: fixed;

  right: calc(2em - 4px);
  top: 2em;

  cursor: pointer;

  z-index: 10;
}

/*================ MAGNIFIC POPUP =================*/

.mfp-wrap {
  background-color: var(--sd-red);
}

.mfp-counter {
  display: none;
}

img.mfp-img {
  padding: 20em 24em;
}

.mfp-content {
  pointer-events: none;
}

.mfp-title {
  position: absolute;
  top: -15.75em;
  text-align: center;
  width: 100%;
  padding-right: 0;

  font-family: "Helvetica", Arial, san-serif;
  font-weight: normal;
  color: black;
}

.mfp-figure:after {
  box-shadow: none;
  background: none;
}

/* .mfp-close {
  left: 0;
  width: 64px;
  height: 64px;
  font-size: 18px;
  font-weight: normal;
  font-family: Arial;
  color: black;
  opacity: 1;
} */

.mfp-zoom-out-cur {
  cursor: pointer!important;
}

.close-area {
  width: 100vw;
  height: 100vh;
  cursor: pointer;
}


/*================ MEDIA QUERIES =================*/

@media (max-width: 720px) {
  :root {
    --grid-gap: 2em;
  }

  .work-index {
    height: auto;

    display: grid;
    grid-template-columns: 1fr;
    grid-template-rows: auto;

    margin-top: 4em;

    pointer-events: none;
  }

  .text {
    width: 100%;
  }

  .mobile-caption {
    display: block;
    text-align: left;
    font-weight: normal;
  }

  .work-item img {
    height: auto;
  }
}

@media (max-height: 900px) {
  img.mfp-img {
    padding: 12em 24em;
  }

  .mfp-title {
    top: -8.25em;
  }
}

@media (min-width: 1600px) {
  img.mfp-img {
    padding: 20em 40em;
  }
}

  </style>
  <body>
    <header>
      Sabo Day <br />
      profile and contact
    </header>
    <div class="reload">

    </div>
    <main>
<div class="work-index">
          <div class="work-item">
          <img alt="" src="1-1.webp">
        </div>
         <div class="work-item">
          <img alt="" src="2-1.jpg">
        </div>
         <div class="work-item">
          <img alt="" src="3-1.jpg">
        </div>
         <div class="work-item">
          <img alt="" src="4-1.gif">
        </div>
         <div class="work-item">
          <img alt="" src="5-1.jpg">
        </div>
         <div class="work-item">
          <img alt="" src="6-1.jpg">
        </div>
         <div class="work-item">
          <img alt="" src="7-1.jpg">
        </div>
         <div class="work-item">
          <img alt="" src="">
        </div>
         <div class="work-item">
          <img alt="" src="">
        </div>

        </div>


</main>
<footer>

<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/magnific-popup.js/1.1.0/jquery.magnific-popup.min.js"></script>
<script src="http://saboday.com/assets/js/main.js"></script>

</body>
</html>

