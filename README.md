<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Bharat_Educate - Transforming online Education Center</title>

	<style>
	@import url('https://fonts.googleapis.com/css2?family=Pacifico&family=Ubuntu&display=swap');

      *{
		margin: 0;
		padding: 0;
	  }

	  html{
	  	scroll-behavior: smooth;
	  }

	  .navbar{
       	display: flex;
       	align-items: center;
       	justify-content: center;
       	position: sticky;
       	top: 0;
       	cursor: pointer;
       } 

	  .logo{
	  	width: 30%;
	  	display: flex;
	  	justify-content: center;
	  	align-items: center;
       }

       .logo img{
       	width: 26%;
       	border: 3px solid white;
       	border-radius: 50px;
       	margin: 5px;
       }

	  .nav-list{
        width: 70%;
        display: flex;
        align-items: center;
	  }

	  .nav-list li{
		list-style: none;
		padding: 25px 18px;
	  }

	  .nav-list li a{
	  	text-decoration: none;
	  	color: white;
	  	font-size: 20px;
	  	font-family: 'Ubuntu', sans-serif;
	  }

	  .nav-list li a:hover{
	  	color: grey;
	  }

	  .rightnav{
	  	width: 30%;
	  	text-align: right;
	  	padding: 0 23PX;
	  }

	  #search{
	  	padding: 5px;
	  	font-size: 17px;
	  	border: 2px solid grey;
	  	border-radius: 9px;
	  }

	  .background{
	  	background: rgba(0, 0, 0, 0.7) url('p2.jpg');
	  	background-size: cover;
	  	background-blend-mode: darken;
	  }
	  .box-main{
	  	display: flex;
	  	justify-content: center;
	  	align-items: center;
	  	color: white;
	  	font-family: 'segoe UI', Tahoma, Geneva, verdana, sans-serif;
	  	max-width: 50%;
	  	margin: auto;
	  	height: 80%;
	  }

	  .firstsection{
	  	height: 100vh;
	  }

	  .firstHalf{
        width: 80%;
        display: flex;
        flex-direction: column;
        justify-content: center;
	  }

	  .secondHalf{
        width: 40%;
	  }

	  .secondHalf img{
	  	width: 70%;
	  	border: 4px solid white;
	  	border-radius: 150px;
	  	display: block;
	  	margin: auto;
	  }

	  .text-big{
        font-size: 41px;
	  }

	  .text-small{
        font-size: 18px;
	  }

	  .btn{
	  	padding: 8px 20px;
	  	margin: 8px 3px;
	  	border: 2px solid white;
	  	border-radius: 8px;
	  	background: none;
	  	color: white;
	  	cursor: pointer;
	  	font-family: 'Ubuntu', sans-serif;
	  	font-size: 20px;
	  }

	  .btn-sm{
	  	padding: 6px 10px;
	  	vertical-align: middle;
	  	font-size: 16px;
	  }

	  .btn-dark{
	  	color: black;
	  	border: 2px solid gray;
	  }

	  .Section{
	  	display: flex;
	  	align-items: center;
	  	justify-content: space-evenly;
	  	max-width: 90%;
	  	margin: auto;
	    font-family: 'Ubuntu', sans-serif;
	    padding: 10px;
	  }

	  .Section-left{
	    flex-direction: row-reverse;
	  }

	  .paras{
       padding: 0 65px;
	  }

	  .sectionTag{
	  	padding: 16px 0;
	  }

	  .sectionSubTag{
	  	font-family: 'segae UI', Tahoma, Geneva, Vardana, sans-serif;
	  }

	  .thumbnail img{
	  	width: 250px;
	  	border: 2px solid black;
	  	border-radius: 26px;
	  	margin-top: 19px;
	  }

	  .contact{
	  	background-color: #f6f5f4;
	  	height: 115vh;
	  }
	  .text-center{
	  	text-align: center;
	  	padding-top: 30px;
	  	font-family: 'Ubuntu', sans-serif;
	  	font-size: 35px;
	  }

	  .form{
	  	max-width: 62%;
	  	margin: 25px auto;
	  }

	  .form-input{
	  	margin: 14px 0;
	  	padding: 5px 3px;
	  	width: 100%;
	  	font-size: 19px;
	  	border: 2px solid grey;
	  	border-radius: 6px;
	  	font-family: 'segae UI', Tahoma, Geneva, Vardana, sans-serif;
	  }

	  .text-footer{
        text-align: center;
	  	padding: 30px 0;
	  	font-family: 'Ubuntu', sans-serif;
	  	display: flex;
	  	justify-content: center;
	  	color: white;
	  }

	  .burger{
	  	display: none;
        position: absolute;
        cursor: pointer;
        right: 5%;
        top: 15px;
	  }

	  .line{
	  	width: 33px;
	  	background-color: white;
	  	height: 5px;
	  	margin: 3px 3px;
	  }

	  @media only screen and (max-width: 1140px){
	  	.nav-list{
	  		flex-direction: column;
	  	}
	  	.navbar{
	  	   flex-direction: column;
	  	   transition:all 0.7s ease-out;
	  	}
	  	.rightnav{
	  		text-align: center;
	  	}
	  	.box-main{
	  		flex-direction: column-reverse;
	  		max-width: 100%;
	  	}
	  	#search{
	  		width: 100%;
	  	}
	  	.burger{
	  		display: block;
	  	}
	  	.h-nav-resp{
	  		height: 72px;
	  	}
	  	.v-class-resp{
	  		opacity: 0;
	  	}
	  	.navbar{
	  		height: 447px;
	  	}
	  	.section{
	  		flex-direction: column-reverse;
	  	}
	  	.text-small{
	  		text-align: center;
	  	}
	  	.text-big{
	  		text-align: center;
	  	}
	  	.button{
	  		text-align: center;
	  	}
	  	.paras{
	  		padding: 0px;
	  	}
	  }

    </style>

    <script>
        burger = document.querySelector('.burger')
        navbar = document.querySelector('.navbar')
        rightnav = document.querySelector('.rightnav')
        navlist = document.querySelector('.nav-list')
        burger.addEventListener('click', () => {
           rightnav.classList.toggle('v-class-resp');
           navlist.classList.toggle('v-class-resp');
           navbar.classList.toggle('h-nav-resp');           
        })
    </script>
    <script type="burger"></script>
    
</head>
<body>
	<nav class="navbar background h-nav-resp">
		<ul class="nav-list v-class-resp">
			<div class="logo"><img src="p1.jpg" alt="logo"></div>
			<li><a href="#home">Home</a></li>
			<li><a href="#about">About</a></li>
			<li><a href="#services">Services</a></li>
			<li><a href="#contact">Contact Us</a></li>
		</ul>
		<div class="rightnav v-class-resp">
			<input type="tesxt" name="search" id="search">
			<button class="btn btn-sm">Search</button>
		</div>
		<div class="burger">
			<div class="line"></div>
			<div class="line"></div>
			<div class="line"></div>
		</div>
	</nav>
	<section class="background firstsection">
		<div class="box-main">
			<div class="firstHalf">
				<p class="text-big">The Future of Education is here.</p>
				<p class="text-small">In this world of 7 billion people we need to educate all od them. This is the future of educated world and we are proud to say that the future of education is here.</p>
				<div class="button">
					<button class="btn">Suscribe</button>
					<button class="btn">Watch Video</button>

				</div>				
			</div>
			<div class="secondHalf">
				<img src="p1.jpg" alt="Leptop Image">
			</div>
		</div>
	</section>

	<section class="Section">
		<div class="paras">
		<p class="sectionTag text-big">The end of search if here.</p>
        <p class="sectionSubTag text-small">The definition of education has been explored by theorists from various fields.Many agree that education is a purposeful activity aimed at achieving certain goals, which include the transmission of knowledge, skills, and character traits.However, there is extensive debate regarding its exact nature beyond these general features. Some theorists view education primarily as a process that occurs during educational events such as schooling, teaching, and learning.Others perceive it not as a process but as the product resulting from this process, emphasizing the mental states and dispositions of educated persons.Additionally, the term may also refer to an academic field that studies the methods, processes, and social institutions involved in teaching and learning.The term "education" is derived from the Latin words educare, meaning "bring up, rear, educate", primarily related to the mind, and educere, meaning "bring out, lead forth", and refers to the bodily level.</p>
        </div>
        <div class="thumbnail">
        	<img src="https://source.unsplash.com/900x900/?coading,apple,html" alt="Leptop Image" class="imgFluid">
        </div>
	</section>

	<section class="Section Section-left">
		<div class="paras">
		<p class="sectionTag text-big">Transforming Education in India.</p>
        <p class="sectionSubTag text-small">Education is often divided into types. The most common division is between formal, non-formal, and informal education.However, some theorists only distinguish between formal and informal education.Formal education happens in a complex institutional framework. Such frameworks have a chronological and hierarchical order. For instance, the modern schooling system has classes based on the student's age and progress, all the way from primary school to university. Formal education is usually controlled and guided by the government. It is normally compulsory up to a certain age.</p>
        </div>
        <div class="thumbnail">
        	<img src="https://source.unsplash.com/900x900/?coading,apple,css" alt="Leptop Image" class="imgFluid">
        </div>
	</section>

	<section class="Section">
		<div class="paras">
		<p class="sectionTag text-big">Lets Grow Togeather.</p>
        <p class="sectionSubTag text-small">Alternative education is an umbrella term for forms of schooling that differ from the mainstream traditional approach. For example, they may use a different learning environment, teach different subjects, or promote a different teacher-student relationship. Alternative schooling is characterized by voluntary participation, relatively small class and school sizes, and personalized instruction. This often results in a more welcoming and emotionally safe atmosphere. It encompasses many types like charter schools and special programs for problematic or gifted children. It also includes homeschooling and unschooling. For instance, Montessori schools, Waldorf schools, and Round Square schools are alternative schools. Further examples are Escuela Nueva schools, free schools, and democratic schools.Alternative education also includes indigenous education. It focuses on the transmission of knowledge and skills from an indigenous heritage. Its method gives more emphasis to narration and storytelling.</p>
        </div>
        <div class="thumbnail">
        	<img src="https://source.unsplash.com/900x900/?javascript,apple" alt="Leptop Image" class="imgFluid">
        </div>
	</section>
	<hr>

	<section class="contact" id="contact">
		<h1 class="text-center">Contact Us</h1>
		<div class="form">
			<input class="form-input" type="text" name="name" id="name" placeholder="Enter your name">
			<input class="form-input" type="text" name="Phone" id="Phone" placeholder="Enter your Phone">
			<input class="form-input" type="Email" name="Email" id="Email" placeholder="Enter your Email">
	        <textarea class="form-input" name="text" id="text" cols="30" rows="10" placeholder="Ellobrate your concer"></textarea>
			<button class="btn btn-sm btn-dark">Submit</button>
		</div>
	</section>

	<footer class="background">
		<p class="text-footer">
			Copyright &copy; 2030 - www.Bharat_Educate.com- All rights reserved
		</p>
	</footer>

</body>
</html>
