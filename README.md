/* ===========================
   HACK & SNACK
=========================== */

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Orbitron',sans-serif;
scroll-behavior:smooth;
}

body{

background:#14071F;
color:white;
overflow-x:hidden;

}

/* NAVBAR */

header{

position:fixed;
width:100%;
top:0;
left:0;
z-index:1000;
backdrop-filter:blur(12px);
background:rgba(15,8,25,.8);

}

nav{

width:90%;
margin:auto;
display:flex;
justify-content:space-between;
align-items:center;
padding:18px 0;

}

.logo img{

height:75px;
transition:.3s;

}

.logo img:hover{

transform:scale(1.08);

}

nav ul{

display:flex;
list-style:none;
gap:35px;

}

nav ul li a{

color:white;
text-decoration:none;
font-weight:600;
transition:.3s;

}

nav ul li a:hover{

color:#FF8C00;

}

.btn-nav{

background:#FF8C00;
padding:12px 25px;
border-radius:40px;
text-decoration:none;
color:white;
font-weight:bold;
transition:.3s;

}

.btn-nav:hover{

background:#A63DFF;
transform:scale(1.05);

}

/* HERO */

.hero{

min-height:100vh;
display:flex;
justify-content:space-around;
align-items:center;
padding:120px 8%;
background:linear-gradient(rgba(20,7,31,.85),rgba(20,7,31,.95)),
url("img/hero.jpg");
background-size:cover;
background-position:center;

}

.hero-text{

max-width:600px;

}

.hero-logo{

width:220px;
margin-bottom:20px;
filter:drop-shadow(0 0 20px #FF8C00);

}

.hero h1{

font-size:65px;
margin-bottom:20px;

}

.hero h1 span{

color:#FF8C00;

}

.hero p{

font-size:20px;
line-height:1.7;
color:#ddd;
margin-bottom:35px;

}

.hero-img img{

width:520px;
filter:drop-shadow(0 0 25px #FF8C00);

}

.btn{

display:inline-block;
background:#A63DFF;
padding:15px 35px;
border-radius:50px;
color:white;
text-decoration:none;
font-weight:bold;
transition:.3s;

}

.btn:hover{

background:#FF8C00;
transform:translateY(-4px);

}

/* ESTADISTICAS */

.stats{

display:grid;
grid-template-columns:repeat(4,1fr);
padding:80px 10%;
background:#1B0D2C;

}

.stat{

text-align:center;

}

.stat h2{

font-size:45px;
color:#FF8C00;

}

.stat p{

margin-top:10px;
color:#ccc;

}

/* TITULOS */

section h2{

font-size:45px;
text-align:center;
margin-bottom:50px;
color:#FF8C00;

}

/* CARDS */

.cards{

display:grid;
grid-template-columns:repeat(auto-fit,minmax(270px,1fr));
gap:35px;

}

.card{

background:#241239;
padding:25px;
border-radius:25px;
text-align:center;
transition:.35s;
border:2px solid transparent;

}

.card:hover{

transform:translateY(-12px);
border-color:#FF8C00;
box-shadow:0 0 25px rgba(255,140,0,.4);

}

.card img{

width:100%;
height:220px;
object-fit:cover;
border-radius:18px;

}

.card h3{

margin:20px 0;
font-size:25px;

}

.card p{

color:#ddd;
line-height:1.7;

}

.card h4{

margin:20px 0;
font-size:30px;
color:#FFD54F;

}

.card button{

background:#FF8C00;
padding:12px 30px;
border:none;
border-radius:40px;
color:white;
font-size:16px;
cursor:pointer;
transition:.3s;

}

.card button:hover{

background:#A63DFF;

}

/* MENU */

.menu{

padding:110px 8%;

}

/* PROMO */

.promo{

padding:100px 8%;

}

.promo-box{

background:linear-gradient(45deg,#A63DFF,#FF8C00);
padding:60px;
border-radius:30px;
text-align:center;

}

.promo-box h1{

font-size:65px;
margin:20px 0;

}

/* ARCADE */

.arcade{

padding:100px 8%;
background:#1A0B28;

}

/* GALERIA */

.gallery{

padding:100px 8%;

}

.grid{

display:grid;
grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
gap:20px;

}

.grid img{

width:100%;
height:250px;
object-fit:cover;
border-radius:20px;
transition:.35s;

}

.grid img:hover{

transform:scale(1.04);

}

/* FOOTER */

footer{

background:#0F0618;
padding:60px;
text-align:center;

}

footer img{

width:120px;
margin-bottom:20px;

}

.redes{

margin:30px 0;

}

.redes a{

text-decoration:none;
color:white;
margin:0 20px;
transition:.3s;

}

.redes a:hover{

color:#FF8C00;

}

.copy{

margin-top:30px;
color:#888;

}

/* RESPONSIVE */

@media(max-width:900px){

.hero{

flex-direction:column;
text-align:center;

}

.hero-img img{

width:90%;
margin-top:40px;

}

.stats{

grid-template-columns:repeat(2,1fr);
gap:30px;

}

nav ul{

display:none;

}

}

@media(max-width:600px){

.hero h1{

font-size:45px;

}

.hero-logo{

width:160px;

}

.stats{

grid-template-columns:1fr;

}

}
