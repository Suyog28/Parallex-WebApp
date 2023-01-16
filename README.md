# Parallex-WebApp

*{
margin:0;
padding:0;
box-sizing: border-box;
}

#wrapper{
height:100vh;
overflow-x:hidden;
overflow-y:auto;
perspective:10px;
}

.container{
position:relative;
display: flex;
justify-content:center;
align-items:center;
height:100%;
transform-style: preserve-3d;

}

.background{
transform:translateZ(-40px) scale(5);
}

.foreground{
transform:translateZ(-20px) scale(3);
}

.background, .foreground{
position:absolute;
height:100%;
width:100%;
z-index:-1;
}
