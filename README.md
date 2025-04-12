<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Basic Portfolio</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-image: url(https://cdna.artstation.com/p/assets/images/images/045/993/458/large/amber-tiger-asset.jpg?1644028026);
            background-size: cover;
            background-attachment: fixed;
            height: 100vh;
            

            
        }
        header {
            background: linear-gradient(to right, rgb(63, 17, 122), #000000);
            padding: 20px;
            text-align: center;
            position: relative;
            overflow: hidden;
        }
        h1 {
            margin: 0;
            font-size: 2.5em;
            color: white;
            animation: slideDown 2s ease-out;
        }
        nav {
            margin-top: 10px;
        }
        nav a {
            margin: 0 15px;
            color: white;
            text-decoration: none;
            font-size: 1.2em;
        }
        nav a:hover {
            color:rgb(63, 17, 122);
        }
        @keyframes slideDown {
            from {
                transform: translateY(-100%);
            }
            to {
                transform: translateY(0);
            }
        }
        #intro {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 80vh;
            text-align: center;
        }
        #intro .card {
            padding: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
        }
        #intro h2 {
            margin-top: 0;
            color: white;
        }
        #intro button {
            background: #000000;
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
            transition: background 0.3s ease;
        }
        #intro button:hover {
            background: rgb(63, 17, 122);
        }
        #projects {
            padding: 40px 20px;
            
            
        }
        #projects h2 {
            text-align: center;
            margin-bottom: 20px;
            color: white;
        }
        .project-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }
        .project-card {
           
            padding: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
            transition: transform 0.3s ease;
        }
        .project-card:hover {
            transform: scale(1.05);
        }
        footer {
            background: linear-gradient(to right, rgb(63, 17, 122), #000000);
            color: white;
            padding: 20px;
            text-align: center;
        }
        .social-links a {
            margin: 0 10px;
            color: white;
            text-decoration: none;
            font-size: 1.5em;
            transition: color 0.3s ease, transform 0.3s ease;
        }
        .social-links a:hover {
            color: rgb(63, 17, 122);
            animation: bounce 0.5s;
        }
        @keyframes bounce {
            0%, 20%, 50%, 80%, 100% {
                transform: translateY(0);
            }
            40% {
                transform: translateY(-10px);
            }
            60% {
                transform: translateY(-5px);
            }
        }
       
        body.dark-mode {
            background-color: #000000;
            color: #000000;
        
        }
        header.dark-mode {
            background: linear-gradient(to right, #000000, #000000);
        }
        .project-card.dark-mode {
            background: #020202;
        }
        footer.dark-mode {
            background: #050505;
        }
        
        .img{
            height:200px;
            width: 200px;
        }
        h3{
            color: white;
            text-align: center;
        }
        p{
            color: white;
        }

    </style>
</head>
<body>
    <header>
        <h1>ALAM MO HA!</h1>
        <nav>
            <a href="#about">About</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>
    <section id="intro">
        <div class="card">
            <h2>Welcome to My Portfolio</h2>
 <p>I'm JOHNLESTER I'm a web developer passionate about crafting <span>user-friendly</span> websites. I have a keen eye for detail and a strong commitment to creating seamless user experiences.</p>
            <button onclick="toggleDarkMode()">Dark Mode</button>
        </div>
    </section>
    <section id="projects">
        <h2>My Projects</h2>
        <div class="project-grid">
            <div class="project-card">
                <a href="Edunews.html"target="_blank"><h3> edunews</h3></a>
            </div>
            
            <div class="project-card">
               
                <a href="Landing.html"target="_blank"><h3> landing</h3></a>
            </div>

            <div class="project-card">
               
                <a href="Technical.html"target="_blank"><h3> technical</h3></a>
            </div>

            <div class="project-card">
               
                <a href="catpainting.html"target="_blank"><h3>catpainting</h3></a>
            </div>

            <div class="project-card">
               
                <a href="piano.html"target="_blank"><h3> piano</h3></a>
            </div>

            <div class="project-card">
                
                <a href="Building.html"target="_blank"><h3> building</h3></a>
            </div>

            <div class="project-card">
            
                <a href="Magazine.html"target="_blank"><h3> magazine</h3></a>
            </div>

            
            <div class="project-card">
              
                <a href="Ferriswheel.html"target="_blank"><h3> Ferriswheel</h3></a>
            </div>

            
            <div class="project-card">
                
                <a href="Penguin.html"target="_blank"><h3> penguin</h3></a>
            </div>

            
            <div class="project-card">
               
                <a href="BalanceSheet.html"target="_blank"><h3> BalanceSheet</h3></a>
            </div>

            <div class="project-card">
                
                <a href="Tributepage.html"target="_blank"><h3> Tributepage</h3></a>
            </div>

            <div class="project-card">
             
                <a href="BuildingAQuiz.html"target="_blank"><h3> BuildingAQuiz</h3></a>
            </div>

            <div class="project-card">
             
                <a href="NutritionLabel.html"target="_blank"><h3> NutritionLabel</h3></a>
            </div>

            <div class="project-card">
                
                <a href="PhotoGallary.html"target="_blank"><h3> PhotoGallary</h3></a>
            </div>

            <div class="project-card">
                
                <a href="RothkoPainting.html"target="_blank"><h3> RothkoPainting</h3></a>
            </div>

            <div class="project-card">
                
                <a href="SurveyForm.html"target="_blank"><h3>SurveyForm</h3></a>
            </div>

            <div class="project-card">
                
                <a href="RegistrationForm.html"target="_blank"><h3> RegistrationForm</h3></a>
            </div>

            <div class="project-card">
               
                <a href="ColoredMarkers.html" target="_blank"><h3>ColoredMarkers</h3></a>
            </div>

            <div class="project-card">
               
                <a href="CafeMenu.html"target="_blank"><h3> CafeMenu</h3></a>
            </div>
            
            <div class="project-card">
                 
                <a href="CatphotoAPP.html"target="_blank"><h3> CatphotoAPP</h3></a>
            </div>

            <div class="project-card">
                 
                <a href="Music Player.html"target="_blank"><h3> music-player</h3></a>
            </div>

            <div class="project-card">
                 
                <a href="Rock,paper.html"target="_blank"><h3> Rock,paper,scissors</h3></a>
            </div>

            <div class="project-card">
                 
                <a href="Calorie Counter.html"target="_blank"><h3> calorie-counter</h3></a>
            </div>

            <div class="project-card">
                 
                <a href="Color-changer.html"target="_blank"><h3> Color-changer</h3></a>
            </div>

            <div class="project-card">
                 
                <a href="Playing-Game.html"target="_blank"><h3> Playing-Game</h3></a>
            </div>

            <div class="project-card">
                 
                <a href="Pyramid generator.html"target="_blank"><h3>Pyramid</h3></a>
            </div>

            <div class="project-card">
                 
                <a href="BuildingGradebook.html"target="_blank"><h3>Gradebook</h3></a>
            </div>






        </div>
    </section>
    <footer id="footer">
        <p>&copy; 2025 Añonuevo. All rights reserved.</p>
        <div class="social-links">
            <a href="https://www.facebook.com/johnlesteranonuevo07">Facebook</a>
            <a href="#twitter">Twitter</a>
            <a href="#linkedin">LinkedIn</a>
        </div>
    </footer>

   <!-- incase 
    <section id="contact">
        <h2>Contact Us</h2>
        <ul>
          <li><a href="https://www.facebook.com/johnlesteranonuevo07" target="_blank">Visit Our Facebook Page</a></li>
          <li><a href="mailto:johnlester07@gmail.com">Send an email</a></li>
          <li><a href="Anoñuevo 07" target="_blank">Follow Us on Instagram</a></li>
          <li>09091234567</li>
        </ul>
      </section>
     -->


   
    <script>
        function toggleDarkMode() {
            document.body.classList.toggle('dark-mode');
            document.querySelector('header').classList.toggle('dark-mode');
            document.querySelectorAll('.project-card').forEach(card => card.classList.toggle('dark-mode'));
            document.querySelector('footer').classList.toggle('dark-mode');
        }

     

    </script>
</body>
</html>
