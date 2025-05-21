# Bijoux
Le site Ben Omar est une boutique en ligne élégante dédiée à la vente de bijoux de luxe. Il a été conçu pour mettre en valeur l’esthétique haut de gamme et l’héritage artisanal de la marque, active depuis 1980.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MindCraftAI</title>
    <link rel="stylesheet" href="ai.css">
    <link rel="website icon" type="png"
    href="Screenshot_2025-03-01_at_23.22.57-removebg-preview.png"    width="100%">
</head>
<body>
    <div class="header1">
    <div class="logo">
        <img src="Screenshot_2025-03-01_at_23.22.57-removebg-preview.png" alt="image">
    </div>
   
        <div class="highlight"></div>
    </nav>
    <div class="nom">
      <h1>MindCraftAI</h1>
    </div>
    <div class="log_in">
        <a href="ai1.html" class="login-btn">Log In</a>
    </div>
    <div class="menu">
   <a href="#"> <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="currentColor" class="bi bi-menu-button-wide" viewBox="0 0 16 16">
    <path d="M0 1.5A1.5 1.5 0 0 1 1.5 0h13A1.5 1.5 0 0 1 16 1.5v2A1.5 1.5 0 0 1 14.5 5h-13A1.5 1.5 0 0 1 0 3.5zM1.5 1a.5.5 0 0 0-.5.5v2a.5.5 0 0 0 .5.5h13a.5.5 0 0 0 .5-.5v-2a.5.5 0 0 0-.5-.5z"/>
    <path d="M2 2.5a.5.5 0 0 1 .5-.5h3a.5.5 0 0 1 0 1h-3a.5.5 0 0 1-.5-.5m10.823.323-.396-.396A.25.25 0 0 1 12.604 2h.792a.25.25 0 0 1 .177.427l-.396.396a.25.25 0 0 1-.354 0M0 8a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v5a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2zm1 3v2a1 1 0 0 0 1 1h12a1 1 0 0 0 1-1v-2zm14-1V8a1 1 0 0 0-1-1H2a1 1 0 0 0-1 1v2zM2 8.5a.5.5 0 0 1 .5-.5h9a.5.5 0 0 1 0 1h-9a.5.5 0 0 1-.5-.5m0 4a.5.5 0 0 1 .5-.5h6a.5.5 0 0 1 0 1h-6a.5.5 0 0 1-.5-.5"/>
  </svg>
    </a>
    </div>
    <nav class="navi">
        <ul>
            <li><a href="#" class="active">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Services</a></li>
            <li><a href="#">Portfolio</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
        <div class="highlight"></div>
    </nav>
    <div class="wrapper">
        <div class="container">
            <input type="radio" name="slide" id="c1" checked>
            <label for="c1" class="card">
                <div class="row">
                  
                    <div class="icon">1</div>
                   
                    <div class="description">
                        <h4> Scale and collaborate  </h4>
                        <p>15,000 websites are published with Webflow every hour. 
                            Confidently scale your site with tools for </p>
                           
                    </div>
                </div>
            </label>
            <input type="radio" name="slide" id="c2" >
            <label for="c2" class="card">
                <div class="row">
                    <div class="icon">2</div>
                    <div class="description">
                        <h4>Design and build</h4>
                        <p>Designers can take control of 
                            HTML, CSS, and JavaScript in a </p>
                    </div>
                </div>
            </label>
            <input type="radio" name="slide" id="c3" >
            <label for="c3" class="card">
                <div class="row">
                    <div class="icon">3</div>
                    <div class="description">
                        <h4>Publish and edit </h4>
                        <p>Choose how you want to add, edit,
                             and update content at scale with Webflow's CMS </p>
                    </div>
                </div>
            </label>
            <input type="radio" name="slide" id="c4" >
            <label for="c4" class="card">
                <div class="row">
                    <div class="icon">4</div>
                    <div class="description">
                        <h4>Publish and edit </h4>
                        <p>Choose how you want to add, edit,
                             and update content at scale with Webflow's CMS </p>
                    </div>
                </div>
            </label>
         
        </div>
    </div>
   
 



<div class="free">
    <h1>MindCraft<span>AI</span><br> Without the<br> Complexity</h1>
    <br>
    <h5>Design launch and grow<br> your website—all from one platform.</h5>
    <button><a herf="#"> Create with MindCraftAI</a> </button>
    
</div>

  








<script>
    const items = document.querySelectorAll(".navi a");
    const highlight = document.querySelector(".highlight");

    function moveHighlight(item) {
        highlight.style.width = item.offsetWidth + "px";
        highlight.style.left = item.offsetLeft + "px";
    }

    // Déplacer le surlignage sur le lien actif au chargement de la page
    window.addEventListener("load", () => {
        const activeItem = document.querySelector(".navi a.active");
        if (activeItem) {
            moveHighlight(activeItem);
        }
    });

    // Ajouter un événement à chaque lien
    items.forEach((item) => {
        item.addEventListener("click", (e) => {
            e.preventDefault();

            items.forEach((el) => el.classList.remove('active'));
            item.classList.add('active');

            moveHighlight(item);
        });
    });





        </script>
</body>
</html>
<styl>
  @import url('https://fonts.googleapis.com/css2?family=Merriweather:ital,opsz,wght@0,18..144,300..900;1,18..144,300..900&family=Sigmar&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Merriweather:ital,opsz,wght@0,18..144,300..900;1,18..144,300..900&family=Sigmar&family=Spicy+Rice&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Kanit:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Merriweather:ital,opsz,wght@0,18..144,300..900;1,18..144,300..900&family=Sigmar&family=Spicy+Rice&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Kanit:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Merriweather:ital,opsz,wght@0,18..144,300..900;1,18..144,300..900&family=Sigmar&family=Spicy+Rice&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Emblema+One&family=Kanit:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Merriweather:ital,opsz,wght@0,18..144,300..900;1,18..144,300..900&family=Sigmar&family=Spicy+Rice&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Emblema+One&family=Kanit:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Merriweather:ital,opsz,wght@0,18..144,300..900;1,18..144,300..900&family=Sigmar&family=Spicy+Rice&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Abril+Fatface&family=Bitter:ital,wght@0,100..900;1,100..900&family=Dancing+Script:wght@400..700&family=Libre+Baskerville:ital,wght@0,400;0,700;1,400&family=Playfair+Display:ital,wght@0,400..900;1,400..900&family=Playwrite+IN:wght@100..400&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Boldonse&display=swap');

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    background-color: black;
}
.header1{
    position: fixed;
    margin-top: 50px;
   
}
.logo img{
  
    width: 180px;
border-radius: 30px;
background-color: #fff;
margin-left: 30px;
margin-top: 20px;


    
}
.logo{
   
    background-color: blueviolet;
    border-radius: 30px;
    height: 150px;
    width: 1670px;
    margin-top: -30px;
}
.nom{
   
  background-color: blueviolet;
  

}
.nom h1{
   
    background-color: blueviolet;
    font-family: "Spicy Rice", serif;
    font-weight: 400;
    font-style: normal;
margin-top: -90px;
margin-left: 230px;
color: #fff;
}

.log_in{
 
margin-top: -10px;
background-color: blueviolet;
   
}
.login-btn {
  
    background-color: #fff;
    color: blueviolet;
    padding: 10px 15px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    text-decoration: none;
    user-select: none; /* Empêche la sélection du bouton */
    margin-left: 1450px;

 
   
}
.login-btn:hover {
    background-color: rgb(213, 168, 255);
}
/* Style for the menu icon */
.menu a {
    display: inline-block;
    padding: 10px;
    background-color: #ffffff;
    border-radius: 5px;
    transition: background-color 0.3s ease;
  
  }
  
  .menu a:hover {
    background-color: #ffffff;
  }
  
  /* Style for the SVG icon */
  .menu svg {
    width: 30px; /* Adjust the width of the icon */
    height: 18px; /* Adjust the height of the icon */
    
   background-color: #fff;
    transition: fill 0.3s ease;

    
  }
  
  .menu a:hover  {
    background-color: rgb(213, 168, 255); /* Change icon color on hover */
  }
  .menu a:hover svg {
    background-color: rgb(213, 168, 255); /* Change icon color on hover */
  }
  .menu{
    background-color:blueviolet ;
    margin-left: 1560px;
    margin-top: -30px;
  }


.wrapper {
    width: 100%;
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    margin-top: 43px;
    margin-left: -290px;
}

.container {
    height: 400px;
    display: flex;
    flex-wrap: nowrap;
    justify-content: start;
}

.card {
    width: 80px;
    border-radius: .75rem;
    background-size: cover;
    cursor: pointer;
    overflow: hidden;
    border-radius: 2rem;
    margin: 0 10px;
    display: flex;
    align-items: flex-end;
    transition: .6s cubic-bezier(.28,-0.03,0,.99);
    box-shadow: 0px 10px 30px -5px rgba(0,0,0,0.8);
}

.card > .row {
    color: white;
    display: flex;
    flex-wrap: nowrap;
}

.card > .row > .icon {
    background: blueviolet;
    color: white;
    border-radius: 50%;
    width: 50px;
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 15px;
}

.card > .row > .description {
    display: flex;
    justify-content: center;
    flex-direction: column;
    overflow: hidden;
    height: 80px;
    width: 520px;
    opacity: 0;
    transform: translateY(30px);
    transition-delay: .3s;
    transition: all .3s ease;
}

.description p {
    color: #b0b0ba;
    padding-top: 5px;
}

.description h4 {
    text-transform: uppercase;
}

input {
    display: none;
}

input:checked + label {
    width: 600px;
}

input:checked + label .description {
    opacity: 1 !important;
    transform: translateY(0) !important;
}

.card[for="c1"] {
    background-image: url('DALL·E\ 2025-03-16\ 01.54.09\ -\ A\ visual\ representation\ of\ Webflow\ CMS\ content\ management.\ Show\ a\ person\ using\ Webflow’s\ platform\,\ creating\ and\ editing\ content\ visually\,\ with\ an\ inte.webp');
}
.card[for="c2"] {
    background-image: url('DALL·E\ 2025-03-16\ 01.43.52\ -\ A\ visual\ canvas\ for\ designers\ working\ with\ HTML\,\ CSS\,\ and\ JavaScript\,\ while\ marketers\ use\ pre-made\ design-approved\ building\ blocks.\ The\ image\ shows\ tw.webp');
}
.card[for="c3"] {
    background-image: url('DALL·E\ 2025-03-16\ 02.31.01\ -\ A\ futuristic\ office\ space\ with\ professionals\ collaborating\ on\ a\ large\ digital\ display.\ The\ environment\ is\ sleek\ and\ modern\,\ featuring\ holographic\ char.webp');
}
.card[for="c4"] {
    background-image: url('DALL·E\ 2025-03-16\ 02.07.40\ -\ A\ detailed\ diagram\ illustrating\ the\ process\ of\ analyzing\ and\ optimizing\ code.\ The\ image\ should\ feature\ a\ flowchart\ with\ elements\ like\ input\,\ analysis\,.webp');
}
 

 
  
  .navi {
    position: relative;
    display: flex;
    justify-content: center;
    gap: 30px;
    padding: 20px;
    background:  blueviolet;
    width: 190px;
    margin-top: -90px;
    margin-left: 790px;
}

.navi ul {
    display: flex;
    gap: 30px;
    padding: 0;
    margin: 0;
    list-style: none;
    position: relative;
    background:  blueviolet;
}

.navi li {
    list-style: none;
    position: relative;
    background:  blueviolet;
}

.navi a {
    text-decoration: none;
    padding: 10px 15px;
    display: block;
    color: rgb(255, 255, 255);
    font-size: 18px;
    position: relative;
    background:  blueviolet;
    font-family: "Boldonse", system-ui;
  font-weight: 400;
  font-style: normal;
}

.navi a.active {
    color: rgb(255, 0, 204);
    font-weight: bold;
}

  .free {
    display: none;
  

    
}
.free {
    display: block;
    color: rgb(255, 255, 255);
    font-size: 2em;
    text-align: center;
   margin-top: -630px;
    margin-left: 1000px;
   text-overflow: ellipsis;
}

.free h5{
    color: blueviolet;
}
.free button a{

    color: #fff;

    border-radius: 30px;
    padding: 30px 10px;
    margin-left: 100px;
font-size: 19px;
background-color:rgb(226, 43, 183) ;









    
    

   
}
.free button{
    
    all: unset;
    padding: 0px ;
    
    font-size: 1rem;
    margin-top: 90px;
    
}
</styl>
