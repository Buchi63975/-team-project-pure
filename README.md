<!DOCTYPE html>
<html>

<head>
    <meta charset="UTF-8">
    <title>進撃WEBsite</title>
    <link rel="stylesheet" type="text/css" href="styles.css">
    <style>
        body {
            background-image: url("https://shingeki.tv/final/img/home/visual_05.jpg");
            margin: 0;
            padding: 0;
        }

        .container {
            display: flex;
            margin: 0;
            padding: 0;
        }

        #sidebar {
            width: 25%;
            color: #f1f1f1;
            background-color: black;
            z-index: 2;
            margin: 0;
            padding: 0;
            height: 100%;
            transition: .4s;
        }

        .main-content {
            padding: 20px;
            background-repeat: no-repeat;
            height: 1000px;
            flex: 1;
        }

        .a:hover {
                border-bottom: 1px solid #f1f1f1;
                width: fit-content;
        }
        .b:hover {
                border-bottom: 1px solid #f1f1f1;
                width: fit-content;
        }
        h2 {
            color: aliceblue;
        }
        .rogo {
            width: 100%;
            background: #333333;
        }
        summary{
            display: inline-block;
        }
        summary:hover{
            padding-left: 50px;
        }
        #sidebar .a{
            display:block;
            height: 80%;
            width: 100%;
            line-height: 65px;
            font-size: 20px;
            color: white;
            padding-left: 40px;
            box-sizing:border-box;
            border-top: 1px solid rgba(255,255,255,.1);
            border-bottom: 1px solid black;
            transition: .4;
        }
        #sidebar .b{
            display:block;
            height: 80%;
            width: 100%;
            line-height: 65px;
            font-size: 20px;
            color: white;
            padding-left: 40px;
            box-sizing:border-box;
            border-top: 1px solid rgba(255,255,255,.1);
            border-bottom: 1px solid black;
            transition: .4;
        }
        ul li:hover {
            padding-left: 50px;
        }
        .palent {
            text-align: center;
            display: flex;
            justify-content: space-between;
            flex-wrap: wrap;
            width:800px;
            margin: 0px auto;
        }
        .child {
            text-align: center;
            width: 40%;
        }
        .child > iframe {
            width: 470px;
            height: 350px;
        }

        * {
            margin:0; padding:0;
        }
        .c-mainmenu__link--instagram{
            color: white;
            font-size: 25px;
        }
        .c-mainmenu__link--twitter{
            color: white;
            font-size: 25px;
        }
        .c-mainmenu__link--instagram:hover{
            padding-left: 50px;
        }
        .c-mainmenu__link--twitter:hover{
            padding-left:50px;
        }
    </style>
</head>

<body>
    <div class="container">
        <div id="sidebar">
            <a class="logo" href="https://shingeki.tv/final/"><img src="phots/logo.png" class="rogo"></a>
            <h2>進撃の巨人のキャラの魅力</h2>
            <ul>
                <a href="./story.html"><li class="a"><summary>ストーリー概要</summary></li></a>
                <li class="b"><details>
                    <summary>キャラクター詳細</summary>
                    <details>
                        <summary>＜調査兵団＞</summary>
                <ul>
                <li><a href="./eren.html">エレン・イェーガー</a></li>
                <li><a href="./mikasa.html">ミカサ・アッカーマン</a></li>
                <li><a href="./arumin.html">アルミン・アルレルト</a></li>
                <li><a href="./zyan.html">ジャン・キルシュタイン</a></li>
                <li><a href="koni-.html">コニー・スプリンガー</a></li>
                <li><a href="./sasya.html">サシャ・ブラウス</a></li>
                <li><a href="./hanzi.html">ヒストリア・レイス</a></li>
                <li><a href="./sobakasu.html">ユミル</a></li>
                <li><a href="./eruvin.html">エルヴィン・スミス</a></li>
                <li><a href="./rivai.html">リヴァイ・アッカーマン</a></li>
                <li><a href="./hanzi.html">ハンジ・ゾエ</a></li>
                <li><a href="./ki-su.html">キース・シャーディス</a></li>
                </ul>
            </details>
            <details>
                <summary>＜憲兵団＞</summary>
                <ul>
                <li><a href="./nairu.html">ナイル・ドーク</a></li>
                <li><a href="./keni-.html">ケニー・アッカーマン</a></li>
                </ul>
            </details>
            <details>
                <summary>＜駐屯兵団＞</summary>
                <ul>
                <li><a href="./pikusis.html">ドット・ピクシス</a></li>
                <li><a href="./hannesu.html">ハンネス</a></li>
                </ul>
            </details>
            <details>
                <summary>＜マーレ＞</summary>
                <ul>
                <li><a href="./zi-ku.html">ジーク・イェーガー</a></li>
                <li><a href="./raina-.html">ライナー・ブラウン</a></li>
                <li><a href="./berunantoka.html">ベルトルト・フーバー</a></li>
                <li><a href="./ani.html">アニ・レオンハート</a></li>
                <li><a href="./pi-ku.html">ピーク・フィンガー</a></li>
                <li><a href="./pokko.html">ポルコ・ガリアード</a></li>
                <li><a href="./gabi.html">ガビ・ブラウン</a></li>
                <li><a href="./faruko.html">ファルコ・グライス</a></li>
                <li><a href="./teo.html">テオ・マガド</a></li>
                <li><a href="./erenhukurou.html">エレン・クルーガー</a></li>
                <li><a href="./ra-ra.html">ラーラ・ダイバー</a></li>
                <li><a href="./gurisha.html">グリシャ・イェーガー</a></li>
                <li><a href="./daina.html">ダイナ・フリッツ</a></li>
                </ul>
            </details>
            <details>
                <summary>＜その他＞</summary>
                <ul>
                <li><a href="./kiyomi.html">キヨミ・アズマビト</a></li>
                <li><a href="./karura.html">カルラ・イェーガー</a></li>
                </ul>
                    </details>
                </details></li>
                <a href="./example.html"><li class="a"><summary>用語解説</summary></li></a>
                <img src="https://shingeki.tv/final/img/home/staff_02_pc.png?2" alt="原作：諫山 創（別冊少年マガジン／講談社） width="300" height="300" class="u-sz_w_100">
            </ul>
            <li class="c-mainmenu__item c-mainmenu__item--twitter"></li>
            <a href="https://twitter.com/anime_shingeki" class="c-mainmenu__link c-mainmenu__link--twitter" ontouchstart
                target="_blank" rel="noopener noreferrer" data-menu-active data-submenu-opened="false">Twitter</a>
            <li class="c-mainmenu__item c-mainmenu__item--instagram"></li>
            <a href="https://www.instagram.com/anime_shingeki_official"
                class="c-mainmenu__link c-mainmenu__link--instagram" ontouchstart target="_blank"
                rel="noopener noreferrer" data-menu-active data-submenu-opened="false">Instagram</a>
            <ul class="c-banners js-common-banners"
                data-banners="gensaku,anime1,anime2,anime3,movie_1,movie_2,movie_season2,movie_chronicle">
            </ul>
        </div>
        <div class="main-content">
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <div class="palent">
                <div class="child">
                    <iframe width="560" height="315" src="https://www.youtube.com/embed/zr_5aXPDZ_o" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
                </div>
                <div class="child">
                    <iframe width="560" height="315" src="https://www.youtube.com/embed/q3Rk7lPxFU0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
                </div>
            </div>
        </div>
    </div>
</body>

</html>