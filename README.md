<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>

<div class="navbar">
    <div class="container">
        <h2>Chetu India</h2>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">Home</a></li>
            <li><a href="#">Home</a></li>
            <li><a href="#">Home</a></li>
            <li><a href="#">Home</a></li>
            <li><a href="#">Home</a></li>
        </ul>
    </div>
</div>





    <div class="contact-us">
        <div class="container">
            <h2>My contact</h2>
            <div class="row">

                <div class="col-3">
                    <div class="card">
                        <img src="images/abc.webp" alt="">
                        <div class="card-boy">
                            <h2>Iamge-1</h2>
                            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Perspiciatis fugit asperiores
                                est iure eaque </p>
                            <button>Add To cart</button>
                        </div>
                    </div>
                </div>



                <div class="col-3">
                    <div class="card">
                        <img src="images/abc.webp" alt="">
                        <div class="card-boy">
                            <h2>Iamge-1</h2>
                            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Perspiciatis fugit asperiores
                                est iure eaque </p>
                            <button>Add To cart</button>
                        </div>
                    </div>
                </div>


                <div class="col-3">
                    <div class="card">
                        <img src="images/abc.webp" alt="">
                        <div class="card-boy">
                            <h2>Iamge-1</h2>
                            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Perspiciatis fugit asperiores
                                est iure eaque </p>
                            <button>Add To cart</button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <div class="about">
   
        <div class="container">
            <h2>About ..........</h2>
            <div class="row">

                <div class="col-6">
                  <div class="card-2">
                     <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Accusantium aspernatur veniam aliquid culpa omnis vel, impedit unde ea commodi! Ad impedit minima quibusdam dolores quia similique quisquam repellat. Asperiores, voluptate.
                     Quae minima tempore blanditiis deserunt unde illo numquam. Est perspiciatis facilis voluptatum laudantium dolorem culpa cum qui suscipit, a pariatur fuga sequi, itaque blanditiis officiis doloribus ab ullam totam. Alias.
                     Assumenda amet aspernatur ipsam eos reprehenderit reiciendis necessitatibus omnis illo suscipit ex, quasi, blanditiis ducimus quis totam expedita sed veritatis molestias inventore dolor quibusdam voluptatem? Quas doloremque inventore eaque ad!
                     Aut cum, quasi magni at suscipit eaque natus quo </p>
                  </div>
                </div>
                <div class="col-6">
                    <div class="card-2">
                        <img src="images/img-1.jpg">
                    </div>
                </div>




            </div>
        </div>
    </div>



</body>

</html>
*{margin:0px; box-sizing: border-box;  font-family: arial;}
.container{max-width:1000px; margin:0px auto; }
.row{display: flex; flex-wrap: wrap;  margin-left:-10px; margin-right:-10px;}
 .navbar{background-color:dodgerblue; padding:10px 0px;}
 .navbar > .container{display: flex; justify-content: space-between; align-items: center;}
.navbar ul{display: flex; list-style: none;}
.navbar ul li a{display: block; padding:12px 20px; text-decoration: none; color:white;}


.col-3{width:33.33%; padding:10px;} 
  img{width:100%;}
.card{background-color: white;}
.card-boy{padding:12px;}

.service{background:dodgerblue; padding:50px 0px;}
.about{background:red; padding:50px 0px;}
.contact-us{background:silver; padding:50px 0px;}

.col-6{width:50%; padding:10px; }
