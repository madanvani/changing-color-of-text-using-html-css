# changing-color-of-text-using-html-css


#HTML:=


<!DOCTYPE html>
<html>

<head>
    <link rel="stylesheet" href="madan.css">
</head>
<body>
    <h1 class="header">
you're Beautiful! You know that right?

    </h1>
    </body>



    </html>


#CSS:=


body{
    height:100vh;
    background: #151515;
    display: grid;
    place-items:center;
    box-sizing: border-box;
}

@-webkit-keyframes hue {
    from {
        -webkit-filter: hue-rotate(0deg);
    }
    to {
        -webkit-filter: hue-rotate(-360deg);
    }
}

.header{
    font-family: "Montserrat", sans-serif;
    font-size: 4rem;
    letter-spacing: 2px;
    text-align: center;
    color: #26cb52;
    background-image: -webkit-linear-gradient(92deg, #f35626, #feab3a, #262626);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    -webkit-animation: hue 10s infinite linear;

}
