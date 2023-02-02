# CSS-dev-3-
https://app.patika.dev/courses/css/cssodev3
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Google</title>
    <link rel="stylesheet" href="CSS/google.css">
</head>
<body>
    <!-- <div class="about">
        <a href="https://about.google/?utm_source=google-TR&utm_medium=referral&utm_campaign=hp-footer&fg=1">About</div> -->
    <!--Header Start -->
  <div class="panel">
    <nav aria-label="">
        <ul class="header">
            <li class="pic headerli">
                <a href="https://github.com/sukurerbay" target="_blank">
                    <img src="images/fotoğrafım.jpeg" alt style="margin-right: 1px">
                </a>
            </li>
            <li style="margin: 8px" class="headerli">
                <a href="https://www.google.com.tr/intl/en/about/products?tab=wh">
                    <img src="images/appsbutton.svg" alt="" style="width: 16px; height: 16px; margin-right: 3px" >
                </a>
            </li>
            <li style="margin: 8px; margin-left: -2px" class="headerli">
                <a href="https://www.google.com.tr/imghp?hl=en&tab=wi&authuser=0&ogbl">Images</a>
            </li>
            <li style="margin: 8px" class="headerli">
                <a href="https://mail.google.com/mail/?tab=wm&authuser=0&ogbl">Gmail</a>
            </li>
        </ul>
    </nav>
    <!--Header End -->
    <!-- Container Start-->
    <div class="container">
        <img src="images/logo.png" width="272px" alt="">
    </div>
    <div class="search-area">
        <div class="search">
            <div class="search-img">
                <span>
                    <svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                        <path d="M15.5 14h-.79l-.28-.27A6.471 6.471 0 0 0 16 9.5 6.5 6.5 0 1 0 9.5 16c1.61 0 3.09-.59 4.23-1.57l.27.28v.79l5 4.99L20.49 19l-4.99-5zm-6 0C7.01 14 5 11.99 5 9.5S7.01 5 9.5 5 14 7.01 14 9.5 11.99 14 9.5 14z">
                        </path>
                    </svg>
                </span>
            </div>
            <div class="input-enter">
                <div class="input-area">
                    <input type="text" class="input" maxlength="2048" autofocus="true">
                </div>
            </div>
            <div class="micDiv">
                <img src="images/voicelogo.png" alt="" width="24">
            </div>
        </div>
    </div>
    <div class="buttons">
        <a href>
            <button class="googlesearch">Google Search</button>
        </a>
        <a href>
            <button class="feelinglucky">I'm Feeling Lucky</button>
        </a>
    </div>
</div>
<nav aria-label>
    <!-- Container End -->
    <!-- Footer Start -->
    <ul class="footer">
        <li class="footerli"><a href="https://www.google.com/intl/en_tr/ads/?subid=ww-ww-et-g-awa-a-g_hpafoot1_1!o2&utm_source=google.com&utm_medium=referral&utm_campaign=google_hpafooter&fg=1">Advertising</a></li>
        <li class="footerli"><a href="https://www.google.com/services/?subid=ww-ww-et-g-awa-a-g_hpbfoot1_1!o2&utm_source=google.com&utm_medium=referral&utm_campaign=google_hpbfooter&fg=1">Business</a></li>
        <li class="footerli"><a href="https://about.google/?utm_source=google-TR&utm_medium=referral&utm_campaign=hp-footer&fg=1">About</a></li>
        <li class="footerli"><a href="https://google.com/search/howsearchworks/?fg=1">How Search works</a></li>
        <li class="footerli" style="float: right; margin-right: 35px;"><a href="https://www.google.com/preferences?hl=en">Settings</a></li>
        <li class="footerli" style="float: right;"><a href="https://policies.google.com/terms?hl=en-TR&fg=1">Terms</a></li>
        <li class="footerli" style="float: right;"><a href="https://policies.google.com/privacy?hl=en-TR&fg=1">Privacy</a></li>
    </ul>
    <!-- Footer End -->
</nav>
</body>
</html>
