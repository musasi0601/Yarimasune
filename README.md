# Yarimasune
<html lang="ja">
 
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta name="title" content="Light" />
    <meta name="description" content="A fast, simple, and highly customizable proxy." />
    <title>Bing</title>
    <link rel="stylesheet" href="/assets/css/main.css" />
    <link rel="icon" href="https://www.google.com/favicon.ico" type="image/x-icon" />
</head>
 
<body onload="startTime()">
    <center>
        <h3 style="
                    margin-bottom: 30px;
                    text-align: left;
                    margin-left: 1%;
                    margin-top: 10px;
                ">
        </h3>
        Japanese Proxy Web
        <div class="card" style="position: fixed">
            
                </h2>
                <div class="searchbar" style="
                            position: absolute;
                            left: 50%;
                            top: 50%;
                            transform: translate(-50%, -50%);
                        ">
                    <div class="searchbar-wrapper">
                        <div class="searchbar-left">
                            <div class="search-icon-wrapper">
                                <span class="search-icon searchbar-icon">
                                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                        <path
                                            d="M15.5 14h-.79l-.28-.27A6.471 6.471 0 0 0 16 9.5 6.5 6.5 0 1 0 9.5 16c1.61 0 3.09-.59 4.23-1.57l.27.28v.79l5 4.99L20.49 19l-4.99-5zm-6 0C7.01 14 5 11.99 5 9.5S7.01 5 9.5 5 14 7.01 14 9.5 11.99 14 9.5 14z">
                                        </path>
                                    </svg>
                                </span>
                            </div>
                        </div>
 
                        <form id="uv-form" class="searchbar-center">  
                          <div class="searchbar-input-spacer"></div>
                            <input id="uv-address" type="text" class="searchbar-input"
                                maxlength="2048" autocapitalize="off" autocomplete="off" title="Search" role="combobox"
                                placeholder="Search Anything" />
                        </form>
                    </div>
                </div>
            </div>
            <div class="blob"></div>
        </div>
        <center></center>
    </center>
    <div style="position: absolute; bottom: 20px; left: 20px">
        <label class="container" title="Click for dark/light mode">
            <input checked="checked" type="checkbox" id="backgroundToggle" />
            
        </label>
         <div
                class="group"
                style="
                    position: fixed;
                    bottom: 4px;
                    left: 43px;
                    padding-top: 2px;
                    padding-left: 2px;
                    padding-right: 2px;
                ">
                
            </div>   
        </div>
        <div style="position: absolute; top: 10px; right: 10px" class="group">
            <img
                src="/assets/imgs/help.png"
                alt="Question mark"
                title="What is Light?"
                class="icon"
                style="width: 23px"
                onclick="alert('ようこそJapanese Proxy Web略してJPWへ！履歴無しで見るには右上の目を押してね。');" />
            <img
                src="/assets/imgs/hide.png"
                alt="Cloak"
                title="Cloak"
                class="icon"
                style="width: 23px"
                onclick="openGame();" />
        </div>
        <div
            style="
                position: absolute;
                bottom: 10px;
                right: 10px;
                padding-top: 5px;
                padding-bottom: 2px;
            ">
            <div id="background"></div>
            <input type="file" id="file-input" accept="image/*" />
        </div></body>
<script src="/uv/uv.bundle.js"></script>
<script src="/uv/uv.config.js"></script>
<script src="/assets/js/index.js"></script>
<script src="/assets/js/main.js"></script>
 
 
</html>
