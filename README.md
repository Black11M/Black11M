* {
            box-sizing: border-box;

        }
    body{
        background-color: gray;
    }
    i {
        display: inline-block;
        width: 30px;
        height: 30px;
        background-image: url(images/icons.png);
        margin-bottom: -5px;
    }
    a {
        font-size: smaller;
        text-align: start;
    }

    .dd {
        position: relative;
        display: inline-block;
        

    }
    .dd-btn {
        padding: 15px;
        background: #7099cf;
        border-radius: 25px;
        width: 30px;
        height: 30px;
        color: #f8f9f9;
        text-indent: 0.001px;
        text-align: 1px;


    }
    .dd-content {
        position: absolute;
        width: 100%;
        box-shadow: 0 10px 18px rgba(164, 78, 235, 0.22), 0 14px 11px rgba(164, 78, 235, 0.22);
        height: 0px;
        transition: height 1s;
        overflow: hidden;
        border-radius: 25px;
        background-color: aqua;

    }
    .dd:hover > .dd-content {
        height: 300px;
        width: min-content;
    }
    .dd-content > a {
        display: block;
        height: 60px;
        padding: 15px;
        text-decoration: none;
        color: black;
        position: relative;
    }
    </style>
</head>
<body>
    <h1>Initial</h1>
    <div class="dd">
        <button class="dd-btn" type="menu"> T </button>
        <div class="dd-content">
        <a href="BK.html"> Home </a>
        <a href="google.html">Black.M </a>
        <a href="ez.html">Wallpaper </a>
        <a href="code.html"> Codes </a>
        <a href="principl.html"> principl </a>
        </div>
    </div>
