<html>
  <title>Margaret</title>
    <head>
    
    <style>
        body {
    background-color:#21173F;
}

#facecontainer {
  position:absolute;
  top:30%;
  left:50%;
  animation-name: movinghead;
  animation-duration: 8s;
  animation-timing-function: ease-in-out;
  animation-delay: 0s;
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
  animation-play-state: running;
}

@keyframes movinghead {
  0% {
    top: 50%;
  }

  25% {
    top:25%;
  }
  
  50% {
    top:50%;
  }
  
  75% {
    top: 25%;
  }

  100% {
    top: 50%;
  }
  
}


#shadowcontainer {
  top:30%;
  left:50%;
}


#shadow {
  background-color:#0f0923;
  height:20px;
  width:135px;
  top:95%;
  left:50%;
  border-radius:50%;
  position:absolute;
  animation-name: shadowsqueeze;
  animation-duration: 8s;
  animation-timing-function: ease-in-out;
  animation-delay: 0s;
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
  animation-play-state: running;
    text-align: center;
}


@keyframes shadowsqueeze {
  
  0% {
transform: scale(1.25);
  }

  25% {
 transform: scale(0.5);
  }
  
  50% {
 transform: scale(1.25);
  }
  
  75% {
 transform: scale(0.5);
  }

  100% {
transform: scale(1.25);
  }
  
}


#face {
  background-color:#F0BEAE;
  height:128px;
  width:100px;
  border-radius:50%;
  position:relative;
}


#nose {
  width:10px;
  height:17px;
  border-radius:40%;
  background-color:#DB9B99;
  position:absolute;
  top:70px;
  left:45px;
}

#lefteye {
  width:10px;
  height:10px;
  border-radius:50%;
  background-color:#484848;
  position:absolute;
  top:45px;
  left:23px;
}

#righteye {
  width:10px;
  height:10px;
  border-radius:50%;
  background-color:#484848;
  position:absolute;
  top:45px;
  right:23px;
}

#leftglasses {
  width:30px;
  height:20px;
  border-radius:20%;
  background-color:transparent;
  position:absolute;
  top:35px;
  left:9px;
  border: 4px solid #3f2a14;
}


#rightglasses {
  width:30px;
  height:20px;
  border-radius:20%;
  background-color:transparent;
  position:absolute;
  top:35px;
  right:9px;
  border: 4px solid #3f2a14;
}

#glassesbridge {
  width:10px;
  height:5px;
  background-color:#3f2a14;
  position:absolute;
  top:48px;
  left:45px;

}


#leftblush {
  width:15px;
  height:15px;
  border-radius:50%;
  background-color:#EBA8A7;
  opacity: 0.5;
  position:absolute;
  top:75px;
  left:10px;
}

#rightblush {
  width:15px;
  height:15px;
  border-radius:50%;
  background-color:#EBA8A7;
  opacity:0.5 ;
  position:absolute;
  top:75px;
  right:10px;
}


#mouth {
  border-bottom-right-radius: 25px;
  border-bottom-left-radius: 25px;
  border-radius-bottomright: 25px;
  border-radius-bottomleft: 25px;
  border-bottom-right-radius: 25px;
  border-bottom-left-radius: 25px;
  height: 20px;
  background-color:#484848;
  position: absolute;
  width: 40px;
  left: 30px;
  top: 98px;
  overflow:hidden;

}

#tongue {
  border-bottom-right-radius: 25px;
  border-bottom-left-radius: 25px;
  border-radius-bottomright: 25px;
  border-radius-bottomleft: 25px;
  border-bottom-right-radius: 25px;
  border-bottom-left-radius: 25px;
  height: 15px;
  background-color:#DB9B99;
  position: absolute;
  width: 35px;
  left: 3px;
  top: 8px;
  transform: rotate(180deg);
  
}


#hairpart1 {
  border-bottom-right-radius: 60px;
  border-bottom-left-radius: 60px;
  border-radius-bottomright: 60px;
  border-radius-bottomleft: 60px;
  border-bottom-right-radius: 60px;
  border-bottom-left-radius: 60px;
  height: 125px;
  background-color: brown;
  position: absolute;
  width: 160px;
  left: -30px;
  top: -25px;
  transform: rotate(180deg);
}

#hairpart3 {
  height: 60px;
  width: 60px;
  background-color: brown;
  position: absolute;
  left: -20px;
  top: -15px;
  border-radius:50%
}

#hairpart4 {
  height: 50px;
  width: 50px;
  background-color: brown;
  position: absolute;
  left: 15px;
  top: -15px;
  border-radius:50%
}

#hairpart5 {
  height: 50px;
  width: 50px;
  background-color: brown;
  position: absolute;
  right: 10px;
  top: -15px;
  border-radius:50%
}

#leftearring {
  width:15px;
  height:15px;
  border-radius:50%;
  background-color:#E69105;
  /*background: rgb(205,145,83);
  background: radial-gradient(circle, rgba(205,145,83,1)     29%, rgba(158,100,32,1) 87%);*/
  position:absolute;
  top:60px;
  left:-12px;
}

#rightearring {
  width:15px;
  height:15px;
  border-radius:50%;
  background-color:#E69105;
  position:absolute;
  top:60px;
  right:-10px;
}
        
        
        span{
            text-decoration-color:red;
            
        }
        
        </style>
    </head>
  <body>
    <div ID="facecontainer">
      <div ID="hairpart1"></div>
      <div ID="face">
        <div ID="nose"></div>
        <div ID="lefteye"></div>
        <div ID="righteye"></div>
        <div ID="rightblush"></div>
        <div ID="leftblush"></div>
        <div ID="glassesbridge"></div>
        <div ID="rightbrow"></div>
        <div ID="leftglasses"></div>
        <div ID="rightglasses"></div>
        <div ID="mouth">
           <div ID="tongue"></div>
        </div>
        <div ID="hairpart2"></div>
        <div ID="hairpart3"></div>
        <div ID="hairpart4"></div>
        <div ID="hairpart5"></div>
        <div ID="leftearring"></div>
        <div ID="rightearring"></div>
      </div>
    </div>
      <div ID="shadowcontainer">
        <div ID="shadow"><span>@code_sick</span></div>
      </div>
  </body>
</html>
