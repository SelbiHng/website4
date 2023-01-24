@import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');
*{


    margin:0;
    padding:0;
    font-family: 'Josefin Sans',sans-serif;
    box-sizing: border-box;
}

.container{
    background:url(bakery-2961613__340.jpg);
    height: 100vh;
    background-size: 100% 97%;

}
.container .navbar{
    width: 100%;
    height: 80px;
    background-color: #83648dbd
}
.navbar .logo{
    display: inline-block;
    margin-left: 50px;
    margin-top: 20px;
}

.navbar .logo a{
    text-decoration: none;
    font-size: 30px;
    font-family: sans-serif;
    color: black;

}
.navbar ul{
    float: right;
    margin-right: 20px;
}
.navbar ul li{
    list-style: none;
    display: inline-block;
    margin:0 15px;
    line-height: 80px;
}
.navbar ul li a{
    color: black;
    text-decoration: none;
    font-size: 20px;
    padding: 6px 13px;
    font-family: Roboto;
}
.navbar ul li a.active,
.navbar ul li a:hover{
    background:#be3a3a;
    border-radius: 2px;
}
.container .center{
    position:absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%);
    font-family: sans-serif;
    user-select: none;
}
.center h1{
    color: blue;
    font-size: 55px;
    font-weight: bold;
    width: 650px;
    text-align: center;
    margin-top: -200px;
}
.center .button{
    margin: 35px 280px;
}
.button button{
    height: 50px;
    width: 150px;
    font-size: 18px;
    font-weight:bold;
    color: rgb(1, 1, 12);
    background: rgb(86, 155, 219);
    border:solid 1px rgb(0, 60, 255) ;
    cursor: pointer;
    outline: none;
    border-radius: 25px; 
}
.button button:hover{
    background: #fff;
}
