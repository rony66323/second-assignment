# second-assignment
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Assignment</title>

    <style>
.{
    width: 100%;
    height: 100%;
  }


      .head{
                  display: flex;
                  justify-content: space-between;
                margin-left: 50px; 
              
                /* margin-top:20%;    */
                
              }
        nav a{
          text-decoration: none;
          color: black;
          justify-content:flex-end;
          margin-right: 50px;
          align-items: center;  
        }
        nav{
          margin-top:25px;  
        }
        .header{
          text-align: center;
          
        }
        .button{
           display: flex;         
          margin-top: 60px;
          justify-content: flex-end;
          margin-left: 200px;
      
          
          
        }
        .button input{
          text-align: center;
          background-color: #FF900E;
          color: aliceblue;
          border: 0;
          border-radius: 5px;
          font-weight: 300;
        }
        .banner{
          width: 1100px;
          height: 500px;
         margin-left: 30px;
         margin-right: 200px ;
         padding: 40px;
        }
        .box{
          border: 0.5px solid black;
          margin: 0, 15px;
          width: 150px;
          height: 100px;
          padding: 10px;
        }
        .main{
          margin-left: 50px;
        }
        .container{
          display: flex;
          justify-content: center;
          justify-content: space-evenly;
          
        }
        .box{
          text-align: center;
          
        }
        .blogs{
          display: flex;
         margin-left: 80px;
         
        }
        .banner-third{
          display: flex;
          margin: 7%;
          height: 600px;
          text-align: left;
          
        }
        .blog{
          margin-left: 50px;
          height: 10px;
          text-align: left;
          
          
          
        }
        .sub-blog{
          display: grid;
          grid-template-columns: repeat(2,1fr);
          width: ;
          height: ;
        }
        .Feature{
          margin-left: 70px;
          margin-top: 200px;
        }
        .Feature input{
            width: 150px;
            height: 70px;
            background-color: #FF900E;
            color: aliceblue;
            font-weight: 600;
            font-size: large;
            border: none;
            border-radius: 5px;
            
        }
        
       .architect{
         margin-left: 195px;
       }  
       .architect input{
        width: 150px;
        height: 70px;
        margin-right: 30px;
        border: none;
        border-radius: 5px;
       }
       #article{
        margin-left: 10px;
       }
       .sub-container{
          text-align: center;
          margin-top: 60px;
        }
        .sub-container ul{
          display: flex;
          justify-content: center;
          justify-content:space-evenly;
        }
        .sub-container li{
          list-style: none;      
        }
        .footer{
          text-align: center;
          margin-top: 50px;
          background-color: antiquewhite;   
        }

    </style>
</head>
<body>
    <header class="head">
        <h2>G3 Architects </h2>
          <nav>
              <a href="">Home</a>
              <a href="">About</a>
              <a href="">Contact us</a>
              <a href="">Login</a>
          </nav>
          </header>
          <div class="header">
              <h1>Brand New <br> Group of Architects  </h1>
          </div>
          <div class="button">
              <input type="button" value="Explore More">
              <p>iations of passages of Lorem Ipsum available, but the majority have suffered alteration in <br> some form, by injected humour, or randomised words which don't look even.</p>
          </div>
          <img class="banner" src="images/banner.png" alt="">
  
          <div class="blogs">
              <div class="sub-blog">
            <article>
              <img src="images/team1.png" alt="">
  
            </article>
            <article>
              <img src="images/team2.png" alt="">
  
            </article>
            <article>
              <img src="images/team3.png" alt="">
  
            </article>
            <article>
              <img src="images/team4.png" alt="">
  
            </article>
          </div>
          <div class="Feature">
            <h2> <span style="color:#a59d9d ; font-style: normal; font-family: 'Work Sans';"> Quick list</span> of Our <br> <span style="color: #FF900E;"> Features</span></h2>
            <p>There are many variations of passages of Lorem Ipsum available, <br> but the majority have suffered alteration in some form, by injected <br> humour, or randomised words which don't look even </p>
  
            <input type="button" value="Explore More">
          </div>
  
          </div>
  
            <div class=" banner-third">
          <div class="blog">
              <article>
                <h2>Features you will <br> love & enjoy</h2>
                <p> <small> There are many variations of passages of Lorem Ipsum available, but the <br> majority have suffered alteration in some form, by injected humour, or <br> randomised words which don't look even.</small> </p>
                </article>
                <article id="article">
                  <h3>Dexktop & Mobile Version</h3>
                  <p>There are many variations of passages of Lorem Ipsum available, <br> but the majority have suffered alteration in some form, by <br> injected humour, or randomised.........</p>
                  </article>
                  <article id="article">
                    <h3>Awesome Modern Design</h3>
                    <p>There are many variations of passages of Lorem Ipsum available, <br> but the majority have suffered alteration in some form, by <br> injected humour, or randomised...........</p>
                    </article>
                    <article id="article">
                    <h3>Super Easy to Edit</h3>
                    <p>There are many variations of passages of Lorem Ipsum available, <br> but the majority have suffered alteration in some form, by <br> injected humour, or randomised...........</p>
                    </article>
                    </div>
                <div class="architect">
                <img src="images/architect.png" alt="" style="height: 600px; width: 500px;">
                <input type="button" value=" 10+Year
  Experience" style="background-color: #FF900E; height: 30px, width: 30px; border:none, "> 
              </div>
            </div>
          <section>
              <div class="main">
                  <h2>Some Facts</h2>
                  <p>There are many variations of passages of Lorem Ipsum available, but <br> the majority have suffered alteration.</p>
              </div>
              <div class="container">
                  <div class="box"><img src="images/icons/ribon.png" alt=""><br> <strong>54</strong>  <br> <small> Awards Winnings</small>
              </div>
                  <div class="box"><img src="images/icons/projects.png" alt=""><br> <strong>1458</strong>  <br> <small> Project Finished</small>
                      </div>
                  <div class="box"><img src="images/icons/customers.png" alt=""><br> <strong>590</strong>  <br> <small> Clients Worked</small>
                     </div>
                  <div class="box"><img src="images/icons/email.png" alt=""><br> <strong>22578</strong>  <br> <small> Email Send</small>
                      </div>       
              </div>
          </section>
          <div class="sub-container">
            <h2>Our Sponspors</h2>
            <p> <small> There are many variations of passages of Lorem Ipsum available, but <br> the majority have suffered alteration</small></p>
              <ul>
                <li>
                  <img src="images/sponsors/spotify.png" alt="">
                </li>
                <li>
                  <img src="images/sponsors/amazon.png" alt="">
                </li>
                <li> <img src="images/sponsors/google.png" alt=""> </li>
                <li> <img src="images/sponsors/telerama.png" alt=""> </li>
                <li> <img src="images/sponsors/figma.png" alt=""> </li>
              </ul>
  
          </div>
  
          <footer class="footer">
            <p>All rights reserved copyright@2023 startup landing page design</p>
          </footer>
    
</body>
</html>
