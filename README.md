# Movie-Ticket-Booking-CSS
This is the CSS code for my Movie Ticket Booking Website HTML Code

Index CSS -
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@100;300;400;500;600&display=swap');

:root{
    --green: #2d69bc ;
    --black:#130f40;
    --light-color:#666;
    --box-shadow:0 .5rem 1.5rem rgba(0,0,0,.1);
    --border:.2rem solid rgba(0,0,0,.1);
    --outline:.1rem solid rgba(0,0,0,.1);
    --outline-hover:.2rem solid var(--black);
}

*{
    font-family: 'Poppins', sans-serif;
    margin:0; padding:0;
    box-sizing: border-box;
    outline: none; border:none;
    text-decoration: none;
    text-transform: capitalize;
    transition: all .2s linear;
}

html{
    font-size: 62.5%;
    overflow-x: hidden;
    scroll-behavior: smooth;
    scroll-padding-top: 7rem;
}

body{
    background:#eee;
}

section{
    padding:2rem 9%;
}

.heading{
    text-align: center;
    padding:2rem 0;
    padding-bottom: 3rem;
    font-size: 3.5rem;
    color:var(--black);
}

.heading span{
    background: var(--green);
    color:#fff;
    display: inline-block;
    padding:.5rem 3rem;
    clip-path: polygon(100% 0, 93% 50%, 100% 99%, 0% 100%, 7% 50%, 0% 0%);
}

.btn{
    margin-top: 1rem;
    display: inline-block;
    padding:.8rem 3rem;
    font-size: 1.7rem;
    border-radius: .5rem;
    border:.2rem solid var(--black);
    color:var(--black);
    cursor: pointer;
    background: none;
}

.btn:hover{
    background: var(--green);
    color:#fff;
}

.header{
    position: fixed;
    top:0; left:0; right: 0;
    z-index: 1000;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding:2rem 9%;
    background:#fff;
    box-shadow: var(--box-shadow);
}

.header .logo{
    font-size: 2.5rem;
    font-weight: bolder;
    color:var(--black);
}

.header .logo i{
    color:var(--green);
}

.header .navbar a{
    font-size: 1.7rem;
    margin:0 1rem;
    color:var(--black);
}

.header .navbar a:hover{
    color:var(--green);
}

.header .icons div{
    height: 4.5rem;
    width: 4.5rem;
    line-height: 4.5rem;
    border-radius: .5rem;
    background: #eee;
    color:var(--black);
    font-size: 2rem;
    margin-left: .3rem;
    cursor: pointer;
    text-align: center;
}

.header .icons div:hover{
    background: var(--green);
    color:#fff;
}

#menu-btn{
    display: none;
}

.header .search-form{
    position: absolute;
    top:110%; right:-110%;
    width: 50rem;
    height:5rem;
    background: #fff;
    border-radius: .5rem;
    overflow: hidden;
    display: flex;
    align-items: center;
    box-shadow: var(--box-shadow);
}

.header .search-form.active{
    right:2rem;
    transition: .4s linear;
}

.header .search-form input{
    height:100%;
    width:100%;
    background: none;
    text-transform: none;
    font-size: 1.6rem;
    color:var(--black);
    padding:0 1.5rem;
}

.header .search-form label{
    font-size: 2.2rem;
    padding-right: 1.5rem;
    color:var(--black);
    cursor: pointer;
}

.header .search-form label:hover{
    color:var(--green);
}

.home{
    display: flex;
    align-items: center;
    justify-content: center;
    background: url(/Bhahmastra_banner_3.webp) no-repeat;
    background-position: center;
    background-size: cover;
    padding-top: 25rem;
    padding-bottom: 7rem;
}

.home .content{
    text-align: center;
    width:60rem;
}

.home .content h3{
    color:var(--black);
    font-size: 3.2rem;
}

.home .content h3 span{
    color:var(--green);
}

.home .content p span{
    color:var(--green);
}

.home .content p{
    color:var(--light-color);
    font-size: 1.7rem;
    padding:1rem 0;
    line-height: 1.8;
}

.challen{
    display: flex;
    align-items: center;
    justify-content: center;
    background: url(/87986960-popcorn-horizontal-banner-red-stripped-paper-cup-and-kernels-lying-on-blue-wooden-background-copy-sp.webp) no-repeat;
    background-position: center;
    background-size: cover;
    padding-top: 12rem;
    padding-bottom: 7rem;
}

.challen .content{
    text-align: center;
    width:160rem;
}

.challen .content h3{
    color:var(--black);
    font-size: 3.2rem;
}

.challen .content h3 span{
    color:rgb(26, 46, 178);
}

.challen .content p span{
    color:var(--green);
}

.challen .content p{
    color:rgb(26, 46, 178);
    font-size: 1.7rem;
    padding:1rem 0;
    line-height: 1.8;
}

.footer{
    background: #fff;
}

.footer .box-container{
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(25rem, 1fr));
    gap:1.5rem;
}

.footer .box-container .box h3{
    font-size: 2.5rem;
    color:var(--black);
    padding:1rem 0;
}

.footer .box-container .box h3 i{
    color:var(--green);
}

.footer .box-container .box .links{
    display: block;
    font-size: 1.5rem;
    color:var(--light-color);
    padding:1rem 0;
}

.footer .box-container .box .links i{
    color:var(--green);
    padding-right: .5rem;
}

.footer .box-container .box .links:hover i{
    padding-right: 2rem;
}


.footer .box-container .box p{
    line-height: 1.8;
    font-size: 1.5rem;
    color:var(--light-color);
    padding:1rem 0;
}

.footer .box-container .box .share a{
    height:4rem;
    width:4rem;
    line-height:4rem;
    border-radius: .5rem;
    font-size: 2rem;
    color:var(--black);
    margin-right: .2rem;
    background: #eee;
    text-align: center;
}

.footer .box-container .box .share a:hover{
    background: var(--green);
    color: #fff;
}

.footer .box-container .box .email{
    width: 100%;
    margin:.7rem 0;
    padding:1rem;
    border-radius: .5rem;
    background: #eee;
    font-size: 1.6rem;
    color:var(--black);
    text-transform: none;
}

.footer .box-container .box .payment-img{
    margin-top: 2rem;
    height: 3rem;
    display: block;
}

.footer .credit{
    text-align: center;
    margin-top: 2rem;
    padding:1rem;
    padding-top: 2.5rem;
    font-size: 2rem;
    color:var(--black);
    border-top: var(--border);
}

.footer .credit span{
    color:var(--green);
}

marquee{
    padding: 1.5rem 1.5rem;
    background: #eee;
    font-size: 2rem;
    color: rgb(26, 46, 178);
}



Products Page CSS -
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@100;300;400;500;600&display=swap');

:root{
  --green: #2d69bc ;
  --black:#130f40;
  --light-color:#666;
  --box-shadow:0 .5rem 1.5rem rgba(0,0,0,.1);
  --border:.2rem solid rgba(0,0,0,.1);
  --outline:.1rem solid rgba(0,0,0,.1);
  --outline-hover:.2rem solid var(--black);
}
*{
  font-family: 'Poppins', sans-serif;
  margin:0; padding:0;
  box-sizing: border-box;
  outline: none; border:none;
  text-decoration: none;
  text-transform: capitalize;
  transition: all .2s linear;
  }

  html{
    font-size: 62.5%;
    overflow-x: hidden;
    scroll-behavior: smooth;
    scroll-padding-top: 7rem;
}

body{
    background:#eee;
}

section{
    padding:2rem 9%;
}

.heading{
    text-align: center;
    padding:2rem 0;
    padding-bottom: 3rem;
    font-size: 3.5rem;
    color:var(--black);
}

.heading span{
    background: var(--green);
    color:#fff;
    display: inline-block;
    padding:.5rem 3rem;
    clip-path: polygon(100% 0, 93% 50%, 100% 99%, 0% 100%, 7% 50%, 0% 0%);
}

.btn{
    margin-top: 1rem;
    display: inline-block;
    padding:.8rem 3rem;
    font-size: 1.7rem;
    border-radius: .5rem;
    border:.2rem solid var(--black);
    color:var(--black);
    cursor: pointer;
    background: none;
}

.btn:hover{
    background: var(--green);
    color:#fff;
}

.header{
    position: fixed;
    top:0; left:0; right: 0;
    z-index: 1000;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding:2rem 9%;
    background:#fff;
    box-shadow: var(--box-shadow);
}

.header .logo{
    font-size: 2.5rem;
    font-weight: bolder;
    color:var(--black);
}

.header .logo i{
    color:var(--green);
}

.header .navbar a{
    font-size: 1.7rem;
    margin:0 1rem;
    color:var(--black);
}

.header .navbar a:hover{
    color:var(--green);
}

.header .icons div{
    height: 4.5rem;
    width: 4.5rem;
    line-height: 4.5rem;
    border-radius: .5rem;
    background: #eee;
    color:var(--black);
    font-size: 2rem;
    margin-left: .3rem;
    cursor: pointer;
    text-align: center;
}

.header .icons div:hover{
    background: var(--green);
    color:#fff;
}

#menu-btn{
    display: none;
}

.header .search-form{
    position: absolute;
    top:110%; right:-110%;
    width: 50rem;
    height:5rem;
    background: #fff;
    border-radius: .5rem;
    overflow: hidden;
    display: flex;
    align-items: center;
    box-shadow: var(--box-shadow);
}

.header .search-form.active{
    right:2rem;
    transition: .4s linear;
}

.header .search-form input{
    height:100%;
    width:100%;
    background: none;
    text-transform: none;
    font-size: 1.6rem;
    color:var(--black);
    padding:0 1.5rem;
}

.header .search-form label{
    font-size: 2.2rem;
    padding-right: 1.5rem;
    color:var(--black);
    cursor: pointer;
}

.header .search-form label:hover{
    color:var(--green);
}
.container{
   max-width: 1200px;
   margin:0 auto;
   padding:3rem 2rem;
}

.container .title{
   font-size: 3.5rem;
   color:#444;
   margin-bottom: 3rem;
   text-transform: uppercase;
   text-align: center;
}

.container .products-container{
   display: grid;
   grid-template-columns: repeat(auto-fit, minmax(30rem, 1fr));
   gap:2rem;
}

.container .products-container .product{
   text-align: center;
   padding:3rem 2rem;
   background: #fff;
   box-shadow: 0 .5rem 1rem rgba(0,0,0,.1);
   outline: .1rem solid #ccc;
   outline-offset: -1.5rem;
   cursor: pointer;
}

.container .products-container .product:hover{
   outline: .2rem solid #222;
   outline-offset: 0;
}

.container .products-container .product img{
   height: 25rem;
}

.container .products-container .product:hover img{
   transform: scale(.9);
}

.container .products-container .product h3{
   padding:.5rem 0;
   font-size: 2rem;
   color:#444;
}

.container .products-container .product:hover h3{
   color:#27ae60;
}

.container .products-container .product .price{
   font-size: 2rem;
   color:#444;
}


.footer{
   background: #fff;
}

.footer .box-container{
   display: grid;
   grid-template-columns: repeat(auto-fit, minmax(25rem, 1fr));
   gap:1.5rem;
}

.footer .box-container .box h3{
   font-size: 2.5rem;
   color:var(--black);
   padding:1rem 0;
}

.footer .box-container .box h3 i{
   color:var(--green);
}

.footer .box-container .box .links{
   display: block;
   font-size: 1.5rem;
   color:var(--light-color);
   padding:1rem 0;
}

.footer .box-container .box .links i{
   color:var(--green);
   padding-right: .5rem;
}

.footer .box-container .box .links:hover i{
   padding-right: 2rem;
}


.footer .box-container .box p{
   line-height: 1.8;
   font-size: 1.5rem;
   color:var(--light-color);
   padding:1rem 0;
}

.footer .box-container .box .share a{
   height:4rem;
   width:4rem;
   line-height:4rem;
   border-radius: .5rem;
   font-size: 2rem;
   color:var(--black);
   margin-right: .2rem;
   background: #eee;
   text-align: center;
}

.footer .box-container .box .share a:hover{
   background: var(--green);
   color: #fff;
}

.footer .box-container .box .email{
   width: 100%;
   margin:.7rem 0;
   padding:1rem;
   border-radius: .5rem;
   background: #eee;
   font-size: 1.6rem;
   color:var(--black);
   text-transform: none;
}

.footer .box-container .box .payment-img{
   margin-top: 2rem;
   height: 3rem;
   display: block;
}

.footer .credit{
   text-align: center;
   margin-top: 2rem;
   padding:1rem;
   padding-top: 2.5rem;
   font-size: 2rem;
   color:var(--black);
   border-top: var(--border);
}

.footer .credit span{
   color:var(--green);
}

@media (max-width:991px){

   html{
      font-size: 55%;
   }

}

@media (max-width:768px){

   .products-preview .preview img{
      height: 25rem;
   }

}

@media (max-width:450px){

   html{
      font-size: 50%;
   }

}
