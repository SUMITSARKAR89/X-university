# X-university

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>X univercity project</title>
    <style>
        *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body{
    background: linear-gradient(rgb(180, 181, 241), rgb(176, 176, 218));
      
}

.header{
    background-image: url(img/main\ img.jpg) ;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    padding: 300px 100px;
    
}
.heading{
    text-align: center;
    font-size: xx-large;
    border: 1px solid #fffffffd;
    background-color: #ffffff3a;
    margin:20px;
    border-radius: 40px;
    padding: 20px;
     
}
.heading:hover{
    box-shadow: 1px 1px 0 rgb(199, 16, 16);
}
.row{
    display: flex;
    
}
.navbar{
    background-color: rgba(46, 46, 179, 0.808);
    border: 2px solid grey;
    margin:0;
    padding: 2px 15px;
    display: flex;
    border-radius: 10px;
}
.navbar a{
    text-align: center;
    text-decoration: none;
    display: block;
    color: aliceblue;
    padding: 20px;
    font-size: xx-large;
    transition: 0.6s;

}
.navbar a:hover{
    background-color: rgba(125, 126, 221, 0.87);
    border-radius: 10px;
    font-weight: bold;
    transition: 0.8s;
}
p{
    padding: 2px;
    text-align: justify;
    font-size: large;
}
.side .main,h2, h3{
    padding: 10px;
}
h2{
    font-size: 35px;
    color:rgb(9, 17, 90)
}
h4{
    text-align: right;
    font-size: larger;
    color:rgb(41, 3, 3);
    cursor: pointer;

}
h4:hover{
    font-size: x-large;
}
.side{
    flex: 30%;
    background-color: rgb(172, 185, 224);
    padding: 1px; 
    border-radius: 20px;
    transition: 0.5s;
}

.sideimg{
    width: 100%;
    padding: 2px 2px;
    border: 2px solid grey;
    border-radius: 8px;
    box-shadow:0 0.6px 1px 0 ;
  
}
.sideimg:hover{
    background-color: rgb(173, 195, 216);
    
}
.main{
    flex: 70%;
    padding: 3px;
    transition: 0.5s;
}
.main>p{
    color: rgb(53, 4, 4);
    font-size: x-large;
    font-weight: bold;
}


button{
    padding: 10px 32px;
    margin:4px;
    font-size: large;
    font-weight: bold;
    background-color: rgba(8, 240, 112, 0.185);
    border-radius: 6px;
    border:0.5px solid #fff;
    cursor: pointer;
    transition: 0.6s;
}
button:active{
    background-color: azure;
}
button:hover{
    font-size: x-large;
    
}
.footer{
    padding:5px;
    text-align: center;
}
@media screen and (max-width: 700px) {
    .row, .navbar, .header {   
      flex-direction: column;
    }
  }
    </style>
</head>
<body>
    <div style="background-color: rgba(63, 63, 194, 0.959); padding: 60px; border-radius: 10px;">
        <p style="font-size: xx-large; text-align: center; color: yellow; font-weight: bold;">Resize the browser window to see the responsive effect. </p>
    </div><hr><hr><hr>
    <div class="header">
        <div class="heading">
        <h1 style="color: rgb(112, 1, 1);">Welcome to X university</h1><br>
        <h2 style="color: rgb(4, 247, 44);"><b >Admission</b> is going on</h2>
        </div>
    </div><hr>

<div class="navbar">
        <a href="#" target="_blank"> Home</a>
        <a href="#" target="_blank"> Campus</a>
        <a href="#" target="_blank">Admission </a>
        <a href="#" target="_blank">Contract us</a> </div><hr>
    <!--header end-->
<!--main start-->
    <div class="row">
        <div class="side">
            <h2>About Us</h2><hr>
            <h3>Discription: <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempore, inventore</p></h3><br>
            <div class="sideimg"><img src="/img/about me.jpg"  alt="about us" height="600px" width="100%"> <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Magnam placeat perspiciatis cum sapiente quis rem adipisci deserunt, rerum, quibusdam nulla molestias praesentium possimus facere, nostrum nisi laborum quos illo accusamus!
            </p><h4>see more...</h4></div><br>
            
  <h2>More Info:</h2>
        <div class="sideimg"><img src="/img/image 1.jfif" alt="" height="400px" width="100%" >
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Inventore beatae rerum necessitatibus autem doloremque. Ratione totam illo veniam ipsum dignissimos.</p><h4>See more...</h4></div><br>     
  <div class="sideimg" ><img src="/img/Profile-building-tips-for-students.jpg" alt="" height="400px" width="100%"><p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quis, autem maxime sint unde praesentium fuga.</p><h4>See more...</h4></div><br>
<div class="sideimg" ><img src="/img/images.jfif" alt="" height="400px" width="600px"> <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Minima iste consequuntur repellat accusantium delectus architecto?</p><h4>See more...</h4></div><br></div>
<div class="main">
 <h2>Title Heading 1</h2><hr>
            <h3>Discription 1<sup>st</sup>, January 2023.</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eos, voluptate sint. Quia veritatis ipsam magnam nostrum neque quaerat fugiat dolorem?</p>
            
<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quaerat vero porro, maiores dolorem ea velit nobis, nostrum officia et alias, corrupti reiciendis! Aut officiis, nobis facilis accusantium libero voluptatem cum non, eum odit illum architecto nihil laboriosam ab nesciunt quibusdam minus! Exercitationem, nisi laboriosam natus iste veniam voluptatibus incidunt blanditiis autem unde doloribus dicta ducimus aliquam illo cum voluptatum corrupti esse soluta molestias accusamus fugiat sint eveniet. Blanditiis magni laboriosam ipsum est a. Adipisci, exercitationem magnam! Aliquam quos sed sunt minima accusantium, veniam consectetur sint facilis magni animi fugit rem autem ab saepe eos architecto voluptatem minus voluptates possimus voluptas?</p><br>
            
 <div class="sideimg" ><img src="/img/main image1.jpg" alt="" height="100%" width="100%"   style="background-position: center; background-size: cover;"><button> click here</button></div><br>

 <h2>Title Heading 2</h2>
            <h3>Discription 2<sup>nd</sup>, January 2023.</h3>
            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Pariatur possimus facilis unde. Qui omnis reprehenderit, aliquid, ex, fuga reiciendis recusandae esse autem ipsam quae rerum odit animi! Dolore sequi, doloribus quae ipsum, nam at corrupti quaerat nulla cum maxime veniam aspernatur. Quos tenetur minima temporibus, omnis eaque error quasi saepe?</p>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Harum eligendi magni voluptates vitae amet commodi aperiam eveniet accusantium id. Quidem expedita deserunt illo nulla ipsam laudantium praesentium reprehenderit dolorem voluptates suscipit. Nobis, corrupti natus excepturi tempore veniam esse porro reprehenderit odit quam, harum quos, dignissimos temporibus placeat vel quas nam quibusdam laudantium sapiente recusandae maxime. Nemo magni doloribus, dignissimos magnam corrupti id iusto ab tempore ea adipisci sapiente? Officiis earum atque minima eos culpa id reprehenderit molestias asperiores consequatur fugit suscipit mollitia, laboriosam obcaecati beatae iure blanditiis quos delectus voluptatibus alias nesciunt accusamus? Minima accusantium aliquid voluptatem error. Animi, alias.</p>
            
 <div class="sideimg"><img src="/img/Classroom_Leanne-Taylor-1024x683.jpg" alt=""height="100%" width="100%"   style="background-position: center; background-size: cover;" ><button> click here</button></div>
 </div>
<!--main end-->
 <!--footer start-->
    </div><hr>
    <div class="footer">
        <h2 style="color: blue;">This is footer</h2>
        <p style="text-align: center;">All reserve on &copy; <B style="color: red;">X university</B></p>
    </div>
    <!--footer end-->
</body>
</html>
