*{
    margin: 0px;
    padding: 0px;
    font-family: Century;
}

header{
    background-image: url("./images/Beach.jpg.jpg");
    height: 100vh;
    width: 100vw;
    background-size: cover;
    background-position: center;
}
ul{
    float: right;
    list-style-type: none;
    margin-top: 30px;
    min-height: 400px;
    margin-right: 40px;
    font-size: 20px;
}

ul li{
    display: inline-block;
}

ul li a{
    text-decoration: none;
    color: #fff;
    padding: 5px 20px;
    border: 1px solid transparent;
    transition: 0.5 ease;
}

ul li a:hover{
    background-color: #fff;
    color: #000
}

ul li.active a{
    background-color: #fff;
    color: #000
}

.main{
    max-width: 1200px;
    margin: auto;
}

.title{
    position: absolute;
    top: 46%;
    left: 50%;
    transform: translate(-50%,-50%);
}

.title h1{
    color: #fff;
    font-size: 70px;
}

.button{
    position: absolute;
    top: 54%;
    left: 50%;
    transform: translate(-50%,-50%);
}

.btn{
    border: 1px solid #fff;
    padding: 5px 20px;
    color:#fff;
    transition: 0.5 ease;
    font-size: 18px;
    text-decoration: none;
}

.btn:hover{
    background-color: #fff;
    color:#000;
}

.sub-menu{
    display: none;
    top: 6%;
    position: relative;
}

.sub-menu ul{
    position: absolute;
}

.main ul li:hover .sub-menu{
    display: block;
    position: absolute;
    background-color: blue (0, 45, 117);
    margin-top: 12px;
    margin-left: 8px;
}





























