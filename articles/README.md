#article
ニュースとか記事とかアレ

テンプレ☟
<html lang="ja"><head>
  <meta charset="UTF-8">

<title>UMJ｜記事名</title>
<meta name="viewport" content="width=device-width, initial-scale = 1.0, maximum-scale=1.0, user-scalable=no">
<meta property="og:type" content="article">
<meta property="og:site_name" content="UNIVERSAL MINECRAFT JAPAN">
<meta property="og:title" content="ユニバーサル・マインクラフト・ジャパン">
<meta property="og:url" content="https://umj.genserver.work/">
<meta property="og:description" content="記事名">
<meta property="og:image" content="https://umj.genserver.work/img/記事画像">
<meta name="keywords" content="ユニバーサル・マインクラフト・ジャパン,umj">
<meta name="theme-color" content="#acb242">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<link rel="shortcut icon" href="https://umj.genserver.work/img/icon.png">


  <!--  js -->
  <script src="https://code.jquery.com/jquery-3.4.1.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
  <!--  js -->
  <!--  original -->
  <script src="https://umj.genserver.work/masonry.pkgd.min.js"></script>
  <script src="https://umj.genserver.work/imagesloaded.pkgd.min.js"></script>
  <link rel="stylesheet" href="https://umj.genserver.work/style.css">
  <script src="https://umj.genserver.work/menu.js"></script>
<style>
.btn-close{
  display: inline-block;
  padding:25px 0;
}

.btn-close::before,
.btn-close::after {
display: block;
content: "";
width: 50px;
height: 1px;
background: #000;
}
.btn-close::before {
transform: rotate(-45deg);
}
.btn-close::after {
transform: rotate(45deg);
}

.close {
    position: absolute;
    top: 15%;
    right: 5%;
    width: 50px;
    height: 50px;
    z-index: 10;
}

.content {
    background-color: #f6f6f6;
    margin: 7%;
}
</style>
  <!--  original -->
</head>
<body>


<div id="header">
<h1><a href="https://umj.genserver.work/"><img class="logo" src="https://umj.genserver.work/img/icon.png" width="56" height="56" alt="GenServer"></a></h1>
<nav>
<ul id="navi">
<li class="sen"><a href="https://umj.genserver.work/">トップ</a></li>
<li class="sen"><a href="https://umj.genserver.work/about/">サーバーについて</a></li>
<li class="sen"><a href="https://umj.genserver.work/how-to-join/">接続方法</a></li>
<li class="sen"><a href="https://umj.genserver.work/today/">営業時間</a></li>
<li class="sen"><a href="https://umj.genserver.work/support/">サポート</a></li>
<li class="sen"><a href="https://umj.genserver.work/terms/">利用規約</a></li>
</ul>
</nav>

<div class="nav_btn" id="nav_btn">
<span class="hamburger_line hamburger_line1"></span>
<span class="hamburger_line hamburger_line2"></span>
<span class="hamburger_line hamburger_line3"></span>
</div>
<div class="nav_bg" id="nav_bg"></div>

</div>
<div class="content">
<p class="close">
  <a href="https://umj.genserver.work/">
    <span class="btn-close">
    </span>
  </a>
</p>

<p class="detail_date">20xx.yy.zz</p>
<p class="detail_title">記事名</p>
<p class="detail_text">
記事内容
</p>
</div>
  </div>

  <!--  javascript   -->
  <script type="text/javascript">
    $(function(){
    
      var $grid = $('.grid').imagesLoaded( function() {
        $grid.masonry({
          isAnimated: true
        });
      });
    
    });
  </script>
  <!--  javascript   -->

</body></html>