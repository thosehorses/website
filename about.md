<style>
  
  body{
    padding: 3rem;
    line-height: 1.314;
    overflow: hidden;
}

::selection{
   background: rgba(195, 239, 143, 0.5);
}

.glitch {
    min-height: 100vh;
    background: #252926;
    color: #c3ef8f;
    font-family: Monaco, "Courier New", Courier, monospace;
    animation: crt 5ms infinite;
    text-shadow:
        0 0 1px #c3ef8f,
        1px 1px 1px blue,
        -1px -1px 1px red;
    
    &::after {
        position: fixed;
        top: 0;
        right: 0;
        bottom: 0;
        left: 0;
        background:
            repeating-linear-gradient(
                top, transparent 0px,
                transparent 2px,
                rgba(0, 0, 0, 0.2) 2px,
                rgba(0, 0, 0, 0.2) 4px
            );
        background-size: 100% 4px;
        box-shadow:
            inset 0 0 10em rgba(0, 0, 0, 0.5),
            inset 0 0 2em rgba(0, 0, 0, 0.1);
        z-index: -1;
        content: "";
    }

    h2,h3,h4 {
        font-weight: 400;
        color: #c3ef8f;
    }
    
    a {
        color: #c3ef8f;
        background: rgba(195, 239, 143, 0.5);
        border-color: rgba(195, 239, 143, 0.5);
        &:hover {
            border-color: transparent !important;
        }
    }
     
}

.container {
    position: relative;
    z-index: 99999;
    width: 100%;
    height: 100&;
    *{
        filter: blur(3px);
        animation:
            5s distort 6s infinite alternate,
            blur 30ms infinite,
            flick 50ms infinite,
            jump 50ms infinite;
    }
}

@keyframes crt {
    28% {
        background: #202421;
    }
    30% {
        background: #202421;
    }
    33% {
        background: #202421;
    }
    34% {
        background: #272c28;
    }
    35% {
        background: #202421;
    }
}
@keyframes blur {
    0% {
        filter: blur(1px);
        opacity: 0.9;
    }
    50% {
        filter: blur(1px);
        opacity: 1;
    }
    100% {
        filter: blur(1px);
        opacity: 0.9;
    }
}
@keyframes flick {
    50% {
        left: 1px;
    }
    51% {
        left: 0;
    }
}
@keyframes jump {
    30% {
        top: 10px;
    }
    31% {
        top: 0;
    }
}


@keyframes appear {
    0% {
        filter: blur(5px);
        opacity: 0.85;
    }
    50% {
        filter: blur(3px);
        opacity: 0.85;
    }
    100% {
        filter: blur(4px);
        opacity: 0.85;
    }
}
@keyframes snapped {
    0% {
        filter: blur(5px);
        opacity: 0.85;
    }
    50% {
        filter: blur(3px);
        opacity: 0.85;
    }
    100% {
        filter: blur(4px);
        opacity: 0.85;
    }
}
@keyframes beersip {
    0% {
        top: 0;
    }
    10% {
        top: -10%;
    }
    12% {
        top: 0;
    }
    54% {
        top: 0;
    }
    55% {
        top: -30%;
    }
    56% {
        top: 0;
    }
    86% {
        top: 0;
    }
    87% {
        top: -60%;
    }
    88% {
        top: 0;
    }
}
  
  </style>
  
  <body class="glitch hacktheplanet">
    <div class="container">
        <audio autoplay src=""></audio>
        <p>Miloš Fath<br><br>
            
            VISUALIZATION , INSTALLATION , MOVEMENT CONSTRUCTION build upon <br>memory in soil / loop in system / .<br>
       
            
        </p><br>
        <hr />
        <p>For portfolio & work inquiries please contact:<br>

            mail@milosfath.com / +381 63 8200991</p>
    </div>
</body>