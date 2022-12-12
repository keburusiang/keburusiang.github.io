<!doctype html>
                        <html>
                            <head>
                                <meta charset='utf-8'>
                                <meta name='viewport' content='width=device-width, initial-scale=1'>
                                <title>Snippet - GoSNippets</title>
                                <link href='' rel='stylesheet'>
                                <link href='' rel='stylesheet'>
                                <style>*,
*::before,
*::after {
    padding: 0;
    margin: 0 auto;
    box-sizing: border-box;
}

body {
    background-color: #222;
    background-image: radial-gradient(circle at center, #222, #111 300px);
    color: #fff;
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    perspective: 420px;
    overflow: hidden;
}

.flower {
    position: relative;
    transform-style: preserve-3d;
    -webkit-animation: rotateFlower 60s infinite linear;
    animation: rotateFlower 60s infinite linear;
}

@-webkit-keyframes rotateFlower {
    to {
        transform: rotateY(360deg);
    }
}

@keyframes rotateFlower {
    to {
        transform: rotateY(360deg);
    }
}

.leaf {
    position: absolute;
    height: 120px;
    transform-origin: top;
    transform-style: preserve-3d;
    -webkit-clip-path: polygon(0 100%, 50% 0, 100% 100%, 0 100%);
    clip-path: polygon(0 100%, 50% 0, 100% 100%, 0 100%);
    background-image: linear-gradient(#000e, #fff1);
    border-radius: 100px;
    -webkit-animation: leafOpen 12s infinite ease-in-out, ocLeafWidth 6s infinite alternate ease-in-out;
    animation: leafOpen 12s infinite ease-in-out, ocLeafWidth 6s infinite alternate ease-in-out;
}

.leaf:nth-child(0) {
    --leafAngle: 0deg;
    -webkit-animation-delay: 0s;
    animation-delay: 0s;
    background-color: #ef8f8f;
}

.leaf:nth-child(1) {
    --leafAngle: 30deg;
    -webkit-animation-delay: -0.2s;
    animation-delay: -0.2s;
    background-color: #ef998f;
}

.leaf:nth-child(2) {
    --leafAngle: 60deg;
    -webkit-animation-delay: -0.4s;
    animation-delay: -0.4s;
    background-color: #efa38f;
}

.leaf:nth-child(3) {
    --leafAngle: 90deg;
    -webkit-animation-delay: -0.6s;
    animation-delay: -0.6s;
    background-color: #efac8f;
}

.leaf:nth-child(4) {
    --leafAngle: 120deg;
    -webkit-animation-delay: -0.8s;
    animation-delay: -0.8s;
    background-color: #efb68f;
}

.leaf:nth-child(5) {
    --leafAngle: 150deg;
    -webkit-animation-delay: -1s;
    animation-delay: -1s;
    background-color: #efbf8f;
}

.leaf:nth-child(6) {
    --leafAngle: 180deg;
    -webkit-animation-delay: -1.2s;
    animation-delay: -1.2s;
    background-color: #efc98f;
}

.leaf:nth-child(7) {
    --leafAngle: 210deg;
    -webkit-animation-delay: -1.4s;
    animation-delay: -1.4s;
    background-color: #efd28f;
}

.leaf:nth-child(8) {
    --leafAngle: 240deg;
    -webkit-animation-delay: -1.6s;
    animation-delay: -1.6s;
    background-color: #efdc8f;
}

.leaf:nth-child(9) {
    --leafAngle: 270deg;
    -webkit-animation-delay: -1.8s;
    animation-delay: -1.8s;
    background-color: #efe68f;
}

.leaf:nth-child(10) {
    --leafAngle: 300deg;
    -webkit-animation-delay: -2s;
    animation-delay: -2s;
    background-color: #efef8f;
}

.leaf:nth-child(11) {
    --leafAngle: 330deg;
    -webkit-animation-delay: -2.2s;
    animation-delay: -2.2s;
    background-color: #e6ef8f;
}

.leaf:nth-child(12) {
    --leafAngle: 360deg;
    -webkit-animation-delay: -2.4s;
    animation-delay: -2.4s;
    background-color: #dcef8f;
}

.leaf:nth-child(13) {
    --leafAngle: 390deg;
    -webkit-animation-delay: -2.6s;
    animation-delay: -2.6s;
    background-color: #d2ef8f;
}

.leaf:nth-child(14) {
    --leafAngle: 420deg;
    -webkit-animation-delay: -2.8s;
    animation-delay: -2.8s;
    background-color: #c9ef8f;
}

.leaf:nth-child(15) {
    --leafAngle: 450deg;
    -webkit-animation-delay: -3s;
    animation-delay: -3s;
    background-color: #bfef8f;
}

.leaf:nth-child(16) {
    --leafAngle: 480deg;
    -webkit-animation-delay: -3.2s;
    animation-delay: -3.2s;
    background-color: #b6ef8f;
}

.leaf:nth-child(17) {
    --leafAngle: 510deg;
    -webkit-animation-delay: -3.4s;
    animation-delay: -3.4s;
    background-color: #acef8f;
}

.leaf:nth-child(18) {
    --leafAngle: 540deg;
    -webkit-animation-delay: -3.6s;
    animation-delay: -3.6s;
    background-color: #a3ef8f;
}

.leaf:nth-child(19) {
    --leafAngle: 570deg;
    -webkit-animation-delay: -3.8s;
    animation-delay: -3.8s;
    background-color: #99ef8f;
}

.leaf:nth-child(20) {
    --leafAngle: 600deg;
    -webkit-animation-delay: -4s;
    animation-delay: -4s;
    background-color: #8fef8f;
}

.leaf:nth-child(21) {
    --leafAngle: 630deg;
    -webkit-animation-delay: -4.2s;
    animation-delay: -4.2s;
    background-color: #8fef99;
}

.leaf:nth-child(22) {
    --leafAngle: 660deg;
    -webkit-animation-delay: -4.4s;
    animation-delay: -4.4s;
    background-color: #8fefa3;
}

.leaf:nth-child(23) {
    --leafAngle: 690deg;
    -webkit-animation-delay: -4.6s;
    animation-delay: -4.6s;
    background-color: #8fefac;
}

.leaf:nth-child(24) {
    --leafAngle: 720deg;
    -webkit-animation-delay: -4.8s;
    animation-delay: -4.8s;
    background-color: #8fefb6;
}

.leaf:nth-child(25) {
    --leafAngle: 750deg;
    -webkit-animation-delay: -5s;
    animation-delay: -5s;
    background-color: #8fefbf;
}

.leaf:nth-child(26) {
    --leafAngle: 780deg;
    -webkit-animation-delay: -5.2s;
    animation-delay: -5.2s;
    background-color: #8fefc9;
}

.leaf:nth-child(27) {
    --leafAngle: 810deg;
    -webkit-animation-delay: -5.4s;
    animation-delay: -5.4s;
    background-color: #8fefd2;
}

.leaf:nth-child(28) {
    --leafAngle: 840deg;
    -webkit-animation-delay: -5.6s;
    animation-delay: -5.6s;
    background-color: #8fefdc;
}

.leaf:nth-child(29) {
    --leafAngle: 870deg;
    -webkit-animation-delay: -5.8s;
    animation-delay: -5.8s;
    background-color: #8fefe6;
}

.leaf:nth-child(30) {
    --leafAngle: 900deg;
    -webkit-animation-delay: -6s;
    animation-delay: -6s;
    background-color: #8fefef;
}

.leaf:nth-child(31) {
    --leafAngle: 930deg;
    -webkit-animation-delay: -6.2s;
    animation-delay: -6.2s;
    background-color: #8fe6ef;
}

.leaf:nth-child(32) {
    --leafAngle: 960deg;
    -webkit-animation-delay: -6.4s;
    animation-delay: -6.4s;
    background-color: #8fdcef;
}

.leaf:nth-child(33) {
    --leafAngle: 990deg;
    -webkit-animation-delay: -6.6s;
    animation-delay: -6.6s;
    background-color: #8fd2ef;
}

.leaf:nth-child(34) {
    --leafAngle: 1020deg;
    -webkit-animation-delay: -6.8s;
    animation-delay: -6.8s;
    background-color: #8fc9ef;
}

.leaf:nth-child(35) {
    --leafAngle: 1050deg;
    -webkit-animation-delay: -7s;
    animation-delay: -7s;
    background-color: #8fbfef;
}

.leaf:nth-child(36) {
    --leafAngle: 1080deg;
    -webkit-animation-delay: -7.2s;
    animation-delay: -7.2s;
    background-color: #8fb6ef;
}

.leaf:nth-child(37) {
    --leafAngle: 1110deg;
    -webkit-animation-delay: -7.4s;
    animation-delay: -7.4s;
    background-color: #8facef;
}

.leaf:nth-child(38) {
    --leafAngle: 1140deg;
    -webkit-animation-delay: -7.6s;
    animation-delay: -7.6s;
    background-color: #8fa3ef;
}

.leaf:nth-child(39) {
    --leafAngle: 1170deg;
    -webkit-animation-delay: -7.8s;
    animation-delay: -7.8s;
    background-color: #8f99ef;
}

.leaf:nth-child(40) {
    --leafAngle: 1200deg;
    -webkit-animation-delay: -8s;
    animation-delay: -8s;
    background-color: #8f8fef;
}

.leaf:nth-child(41) {
    --leafAngle: 1230deg;
    -webkit-animation-delay: -8.2s;
    animation-delay: -8.2s;
    background-color: #998fef;
}

.leaf:nth-child(42) {
    --leafAngle: 1260deg;
    -webkit-animation-delay: -8.4s;
    animation-delay: -8.4s;
    background-color: #a38fef;
}

.leaf:nth-child(43) {
    --leafAngle: 1290deg;
    -webkit-animation-delay: -8.6s;
    animation-delay: -8.6s;
    background-color: #ac8fef;
}

.leaf:nth-child(44) {
    --leafAngle: 1320deg;
    -webkit-animation-delay: -8.8s;
    animation-delay: -8.8s;
    background-color: #b68fef;
}

.leaf:nth-child(45) {
    --leafAngle: 1350deg;
    -webkit-animation-delay: -9s;
    animation-delay: -9s;
    background-color: #bf8fef;
}

.leaf:nth-child(46) {
    --leafAngle: 1380deg;
    -webkit-animation-delay: -9.2s;
    animation-delay: -9.2s;
    background-color: #c98fef;
}

.leaf:nth-child(47) {
    --leafAngle: 1410deg;
    -webkit-animation-delay: -9.4s;
    animation-delay: -9.4s;
    background-color: #d28fef;
}

.leaf:nth-child(48) {
    --leafAngle: 1440deg;
    -webkit-animation-delay: -9.6s;
    animation-delay: -9.6s;
    background-color: #dc8fef;
}

.leaf:nth-child(49) {
    --leafAngle: 1470deg;
    -webkit-animation-delay: -9.8s;
    animation-delay: -9.8s;
    background-color: #e68fef;
}

.leaf:nth-child(50) {
    --leafAngle: 1500deg;
    -webkit-animation-delay: -10s;
    animation-delay: -10s;
    background-color: #ef8fef;
}

.leaf:nth-child(51) {
    --leafAngle: 1530deg;
    -webkit-animation-delay: -10.2s;
    animation-delay: -10.2s;
    background-color: #ef8fe6;
}

.leaf:nth-child(52) {
    --leafAngle: 1560deg;
    -webkit-animation-delay: -10.4s;
    animation-delay: -10.4s;
    background-color: #ef8fdc;
}

.leaf:nth-child(53) {
    --leafAngle: 1590deg;
    -webkit-animation-delay: -10.6s;
    animation-delay: -10.6s;
    background-color: #ef8fd2;
}

.leaf:nth-child(54) {
    --leafAngle: 1620deg;
    -webkit-animation-delay: -10.8s;
    animation-delay: -10.8s;
    background-color: #ef8fc9;
}

.leaf:nth-child(55) {
    --leafAngle: 1650deg;
    -webkit-animation-delay: -11s;
    animation-delay: -11s;
    background-color: #ef8fbf;
}

.leaf:nth-child(56) {
    --leafAngle: 1680deg;
    -webkit-animation-delay: -11.2s;
    animation-delay: -11.2s;
    background-color: #ef8fb6;
}

.leaf:nth-child(57) {
    --leafAngle: 1710deg;
    -webkit-animation-delay: -11.4s;
    animation-delay: -11.4s;
    background-color: #ef8fac;
}

.leaf:nth-child(58) {
    --leafAngle: 1740deg;
    -webkit-animation-delay: -11.6s;
    animation-delay: -11.6s;
    background-color: #ef8fa3;
}

.leaf:nth-child(59) {
    --leafAngle: 1770deg;
    -webkit-animation-delay: -11.8s;
    animation-delay: -11.8s;
    background-color: #ef8f99;
}

.leaf:nth-child(60) {
    --leafAngle: 1800deg;
    -webkit-animation-delay: -12s;
    animation-delay: -12s;
    background-color: #ef8f8f;
}

@-webkit-keyframes leafOpen {
    from {
        transform: translateZ(-30px) rotate(var(--leafAngle)) rotateX(-90deg) rotateY(-15deg);
    }

    to {
        transform: translateZ(30px) rotate(var(--leafAngle)) rotateX(90deg) rotateY(45deg);
    }
}

@keyframes leafOpen {
    from {
        transform: translateZ(-30px) rotate(var(--leafAngle)) rotateX(-90deg) rotateY(-15deg);
    }

    to {
        transform: translateZ(30px) rotate(var(--leafAngle)) rotateX(90deg) rotateY(45deg);
    }
}

@-webkit-keyframes ocLeafWidth {
    from {
        width: 0;
    }

    to {
        width: 60px;
    }
}

@keyframes ocLeafWidth {
    from {
        width: 0;
    }

    to {
        width: 60px;
    }
}</style>
                                <script type='text/javascript' src=''></script>
                                <script type='text/javascript' src='https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js'></script>
                                <script type='text/javascript' src=''></script>
                            </head>
                            <body oncontextmenu='return false' class='snippet-body'>
                            <div class="flower">
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
    <div class="leaf"></div>
</div>
                            <script type='text/javascript'></script>
                            </body>
                        </html>
