## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/oyuka565/CV-/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

body
{
 margin: 10px;
 padding: 0;
 font-family: sans-serif;
}
/*-----------header CSS ----------- */
 #header
 {
	height: 100vh;
	background: linear-gradient(rgba(0,0,0,0.6),rgba(0,0,0,0.6)),url(shy.jpg);
	background-position: center;
    background-size: cover;
    background-attachment: fixed;

 }
.user-box
{
     top: 50%;
     left: 50%;
     transform: translate(-50%,-50%);
     position :absolute;
 }
  .user-box img 
  {
 border-radius: 50%;
 width: 250px;
 border: 2px solid #6caed5;
  }
  .user-box h1
  {
    color: white;
    font-weight: bold;
     margin:10px;
  }
  .user-box p
  {
  	color: white;

  }
  .scroll-btn
  {
  	bottom: 30px;
  	position: absolute;
  	left: 50%;
  	transform: translateX(-50%);
     border:1px solid #fff;
     padding: 10px 10px 20px;
     border-radius: 30px;
  }
  .scroll-bar span
{
  border: 2px solid #fff;
  font-size: 10px ;
  border-radius: 30px;
}
.scroll-bar: hover 
{
	animation: infinite alternate;
}

/*----------------about----------*/
 .about
 {
 padding-top: 100px;
 padding-bottom: 80px;
 margin: 20px;

 }
 #col
 {
 	padding-left: 20px;

 }
  .profile-img
  {

  margin: 50px;
  border-radius: 80%%;
 border: 3px solid #c2c2a3;
 border-top-right-radius: 0;
	border-bottom-left-radius: 0;
	border-top-left-radius: 50px;
	border-bottom-right-radius: 50px;
	transition: 1s;
	background: white;}

 .profile-img1{
	float: left;
	margin-left: 30px; 
	margin-right: -15px;
	border: 3px solid #c2c2a3;
    border-top-right-radius: 0;
	border-bottom-left-radius: 0;
	border-top-left-radius: 50px;
	border-bottom-right-radius: 50px;

  }
  #face
  {
  	background-color: #ec4543;
  	border-bottom-left-radius: 0;
	border-top-left-radius: 50px;
	border-bottom-right-radius: 10px;
	padding-top: 20px;
	position: relative;

  }
  #face p
  {
  	text-align: center;
  color: white;
  padding-top: 0px;
  }
#book
{
	border: none;
	background-color: #d30000;
	position: relative;
    float: left;
    margin-left: 20px;

}
#book p
{
text-align: center;
  color: white;
}
#book1 {
	border: none;
	background-color:#ff0000;
	clear: right;
	color: white;
	padding-top:
}
.book3{
	margin-top: 20px;
	background-color:#c2c2a3;
	border-bottom-right-radius: 50px;
	transition: 1s;
	padding-top: 10px; 

}
.book3 li
{
	list-style: none;
	padding-top: 0px;
	 
}
.book3:before
{
	content: '';
	background: black;
	display: inline-block;
	position: absolute;
	left: 37px;
	margin-top: 10px;
	width: 2px;
	height: 80%;
	z-index: 1;
}
.book3 li a :hover
{
	font-size: 1.1em;
	color:brown;
	transform: 0.5s;
	text-decoration-color: brown; 
}
.book3 li:before
{
	content: '';
	background: #fff;
	position: absolute;
	border-radius: 100%;
	border: 3px solid #c2c2a3;
	left: 10px;
	width: 15px;
	height: 15px;
	z-index:1;	
	margin-left: 20px;
	margin-top: 10px;
}
.fa p
{
padding-top: 5px;
color: black;
font-weight: bold;
text-decoration:underline;
text-decoration-color:  gray;
padding-top: 10px;
padding-right: 20px;

}
.social-icons {
    background: black;
}
.social-icons ul{
    margin-left: -10px;
    
}
.social-icons li{
    float: left;
    width: 10%;
    text-align: left;
    list-style-type: none;
    margin-left: 8px;
    margin-top: 30px;
    color:white;
}
.social-icons li a:hover
{
    color: black;
}
.social-icons li a{
    display:black;
    background: url("../img/7.jpg");
    background-repeat: no-repeat;
    background-position: left;
    background-size: cover;
    z-index: 2;
    color: white;

}
  .col-md-6 h3
  {
  margin-top: 20px;
  margin-bottom: 15px;
  font-family: sans-serif;
  font-weight: : bold;
  }
  
  .col-md-6-box
  {
  	background: pink;
  }
   #col h3
  {
  
  border-top-right-radius: 50px;
  border-bottom-left-radius: 50px;
  background-color: #d30000;
  text-align: center;
  font-size: 1.8em;
  font-weight: bold;
  color: white;
  }
  #col h3:hover
  {
 background-color:#d30000; 
 transition: 1s;
 border-top-left-radius: 50px;
	border-bottom-right-radius: 50px;
	 border-top-right-radius:0px;
	border-bottom-left-radius: 0px;
  }
  #col p-1
  {
  	font-weight: bolder;
  	position: relative;
  }
  .nav-bar
  {
  	top: 0;
  	position: sticky;
  	z-index: 2;

  }
  .navbar
  {
  	background-color:#d30000;

  }
 .navbar-brand img
 {
 	height: 30px;
 	width: 80px;
 	margin-top: -10px;

 }
 .nav-bar .fa-bars
 {
 	font-size: 2em;
 	color: #fff;
 }
.navbar-toggler
{
	outline: none !important;
}
.navbar-nav
{
	float: right;
	text-align: right;
}
.nav-link
{
	color: #fff !important;
	font-weight: bold;
	font-size: 1em;
}
.nav-link:hover
{
	background-color:#ec4543;
	border-top-right-radius: 30px;
	border-bottom-left-radius: 30px;
	border-top-left-radius: 30px;
    border-bottom-right-radius: 30px;
    font-size: 1.3em;
    transition: 0.5s;
}

.skills-bar p
{
	margin-bottom: 6px;
	font-weight: 500px
	font-weight:bolder;
}
.progress
{
	border-radius: 16px !important;
	margin-bottom: 10px;

}
#p
{
	font-weight: bold;
	padding-left: 10px;
}
.progress-bar
{
	border-radius: 16px;
	background: #ec4543!important;

}
.Боловсрол-мэргэжил
{
 margin: 20px;
 padding-top: 30px;
 padding-bottom: 30px;
 background:#c2c2a3;
 border-top-right-radius: 30px;
	border-bottom-left-radius: 30px;
	border-top-left-radius: 30px;
    border-bottom-right-radius: 30px;
}
.Боловсрол-мэргэжил h3
{
 	margin-bottom: 40px;
}
.col-md-6
{
	margin-right:0px;
}
.timeline 
{
	list-style-type: none;
	position: relative;
	 margin-left: 10px;
}
.timeline:before
{
	content: '';
	background:#d30000;
	display: inline-block;
	position: absolute;
	left: 29px;
	width: 2px;
	height: 100%;
	z-index: 1;
}
.timeline li
{
	margin-top: 20px;
	margin-bottom: 20px;
	margin-left: 20px;
	background: #fff;

}
.timeline li p
{
	margin-left: 10px;
}
.timeline li b
{
	margin-left: 10px;
}
.timeline li h4
{
	background-color:#c32222;
	padding: 5px 0 5px 20px;
	color: #fff;
	font-size: 15px;
}
.timeline li h4 span 
{
	font-weight: bold;
	color:#ccc;
}
.timeline li:before
{
	content: '';
	background: #fff;
	position: absolute;
	border-radius: 100%;
	border: 3px solid #d30000;
	left: 20px;
	width: 20px;
	height: 20px;
	z-index:1;
}

/*-----------Хувийн мэдээлэл-----------*/
.Хувийн-мэдээлэл
{
   padding-top: 30px;
   padding-bottom:50px;
}
.Хувийн-мэдээлэл h1
{
	margin-bottom: 15px;
   color: black; 
   text-align: center;
   
}
.Хувийн-мэдээлэл p
{
	font-family: sans-serif;
	color: brown;
	font-size: 15px;
	margin-bottom: 10px;
	font-weight: bold;
	 text-decoration:underline;
}
.Хувийн-мэдээлэл-box
{
	background: #c2c2a3;
	padding: 10px;
	margin-top: 20px;
	border-top-right-radius: 50px;
	border-bottom-left-radius: 50px;
	padding-left: 20px;
	padding-bottom: 30px;
}
.Хувийн-мэдээлэл-box .fa
 {
 	padding: 12 10px 0 25px;
 	font-size: 20px;
 	
 } 
 .Хувийн-мэдээлэл-box li p
 {
 	padding-bottom: 0px;
 	padding-top: 8px;
 	margin-left: 20px;
 	padding-left: 15px;
 	position: relative;
 	text-decoration: underline;
 	color:#d30000 ;

 }
  .Хувийн-мэдээлэл-box li
  {
  	list-style: none;
  }
 .Хувийн-мэдээлэл-box li:before
 {
    content: '';
	background: #fff;
	position: absolute;
	border-radius: 100%;
	border: 3px solid #c2c2a3;
	left: 20px;
	width: 15px;
	height: 15px;
	z-index:1;	
	margin-left: 20px;
	margin-top: 10px;
 }

 
 .Хувийн-мэдээлэл-box span
 	
 {
 margin:3px;
 font-size: 20px;
 font-weight: bold;
 }
 .Хувийн-мэдээлэл-box:hover
 {
 	background:#ff6666;
	border-top-right-radius: 0;
	border-bottom-left-radius: 0;
	border-top-left-radius: 50px;
	border-bottom-right-radius: 50px;
	transition: 1s;
 }
 .Хувийн-мэдээлэл-box p:hover
 {
 	color: white;
 }

 /*--------------Холбоо-барих----------*/

.Холбоо-барих
{
	padding-top: 50px;
	background: linear-gradient(rgba(0,0,0,0.8),rgba(0,0,0,0.8)),url(backo.jpg);
	background-position: center;
    background-size: cover;
    background-attachment: fixed;
    color: #fff;
}
.Холбоо-барих p:hover
{
	font-size: 2.5em;
	background-color: black;
	border-top-left-radius: 20px;
border-bottom-right-radius: 20px;
border-bottom-left-radius: 20px;
border-top-right-radius: 20px;


}





