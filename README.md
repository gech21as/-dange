<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>dropdown list pracise</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.4.2/css/fontawesome.min.css">
    <style>
        *{
    padding: 0px;
    margin: 0px;
    box-sizing: border-box;
}
body{
    background-image:url(G.jpg) ;
    background-size: 100%;
    background-size:cover;
    background-position: center;
}
.logo{
    background-color:blue;
    height:100px;
}
.manubar.fa{
    margin-right:8px ;
}
 image{
    align:right;
    height: 50px;
    width: 130px;
}
.manubar{
    background-color:#335599 ;
    text-align: center;
}
.manubar ul{
    display: inline-flex;
    color: white;
}
.manubar ul li{
    margin: 15px;
    padding: 15px;
    list-style: none;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
   
    
}
.manubar ul li a{
    text-decoration: none;
    color: white;
}
 .manubar ul li:hover {
    background-color: green;
    text-color: blu;
}
.manubar:hover{
    color: blue;
}
.submanu11{
    display: none;
}
.manubar ul li:hover .submanu11{
    display: block;
    position: absolute;
    background: rgb(0,100,0);
    margin-top: 15px;
    margin-left: -15px;
}
.manubar ul li:hover .submanu11 ul{
    display: block;
    margin: 10px;
    align:left;
}
    
.manubar ul li:hover .submanu11 ul {
padding: 10px;
padding-bottom:1px ;
    
}



.manubar ul li:hover .submanu11{
    display: block;
    position: absolute;
    background: rgb(0,100,0);
    margin-top: 15px;
    margin-left: -15px;
    
}
{
.manubar ul li:hover .submanu11 ul{
    display: block;
    margin: 10px;
 }
.manubar ul li:hover .submanu11 ul li{
    text-align:left;
    padding: 10px;
    border-bottom:1px dotted #ffffff;
    display:block;
    border-radius: 0;
}
.submanu3{
    display: none;
}

.hi:hover. submanu3{
    display:block;
    position:absolute;
    margin-top:-40px;
    padding:10px ;
}


    </style>
</head>
<body>
    <div class="logo">
        <img src="web.jpg" alt="cant open" align="right" height="130px" width="100%">
    </div>
    <div class="manubar">
        <ul>
            <li class="submanu1" ><a href="#">Home</a> </li>
            <li><a href="#">About Us</a>
              <i class="fa fa-sort-desc"></i>
                <div class="submanu11">
                    <ul>
                        <li><a href="#">Message from President</a></li>
                        <li><a href="#">Mission and Vision</a></li>
                        <li><a href="#">A brief history of BDU</a></li>
                        <li class="hi"><a href="#">Plans</a>
                       <div class="submanu3">
                    <ul>
                        <li><a href="#">for 2050</a></li>
                        <li><a href="#">for this year</a></li>
                        <li><a href="#">for short time</a></li>
                        <li><a href="#">for this millinium</a></li>
                        <li><a href="#">for this century</a></li>
                    </ul>
                </div>
                        </li>
                        <li><a href="#">BDU Board Members</a></li>
                    </ul>
                </div>
            
            </li>
            <li> <a href="#">Acadamics</a>
           <div class="submanu11">
                    <ul>
                        <li><a href="#">Message from President</a></li>
                        <li><a href="#">Mission and Vision</a></li>
                        <li><a href="#">A brief history of BDU</a></li>
                        <li><a href="#">Plans</a></li>
                        <li><a href="#">BDU Board Members</a></li>
                    </ul>
                </div>               
            </li>
            <li><a href="#">Research</a></li>
            <li><a href="#">Outreach</a></li>
            <li><a href="#">BDUTV</a></li>
            <li><a href="#">Administration</a></li>
            <li><a href="#">partners</a></li>
            <li><a href="#">Services</a></li>
            <li><a href="#">Libraries</a></li>
        </ul>
    </div>
</body>
</html>

