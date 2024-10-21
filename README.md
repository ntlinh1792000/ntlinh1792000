body {
    margin: 0;
    padding: 0;
    overflow: hidden;
    font-family: '楷体';
}

html, body {
    height: 100%;
}

#cake {
    display: block;
    position: relative;
    left: 50%;
    margin-top: -10em;
    margin-bottom: 0;
    margin-left: -100px;

}

#isLike {
    transition: all 1s;
}

/* ============================================== Candle
*/
.bg {
    width: 100%;
    height: 100%;
    background: #ee9ca7;
    background: -webkit-linear-gradient(top left, #ee9ca7 0%, #ee9ca7 100%);
    background: linear-gradient(to bottom right, #ee9ca7 0%, #ee9ca7 100%);
}

.velas {
    background: #ffffff;
    border-radius: 10px;
    position: relative;
    top: 247px;
    margin-left: 49.5%;
    width: 5px;
    height: 35px;
    -webkit-transform: translateY(-300px);
    -ms-transform: translateY(-300px);
    transform: translateY(-300px);
    -webkit-backface-visibility: hidden;
    -ms-backface-visibility: hidden;
    backface-visibility: hidden;
    -webkit-animation: in 500ms 6s ease-out forwards;
    animation: in 500ms 6s ease-out forwards;
}

.velas:after,
.velas:before {
    background: rgba(255, 0, 0, 0.4);
    content: "";
    position: absolute;
    width: 100%;
    height: 2.22222222px;
}

.velas:after {
    top: 25%;
    left: 0;
}

.velas:before {
    top: 45%;
    left: 0;
}
