body {
    background-color: rgb(201, 198, 219);
    margin: 0px;
    height: 100vh;
    margin: 0;
    background-position: center;
}
.menuArea {
    margin: 0;
    padding: 0;
    list-style: none;
    position: sticky;
}
div ul li {
    list-style: none;
    display: inline;
   
}
div ul li a {
    color: rgb(247, 239, 239);
    margin-right: 15px;
    text-decoration: none;
    float:right;
    font-size: 18px;
}
img {
    height: auto;
    max-width: 100%;
}
nav {
    background: url(images/city.jpg);
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    height: 245px;
    margin-top: -15px;
    margin-bottom: 5px;
    padding: 14px 16px;
}
.top-wrapper {
    height: 150px;
    width: 320px;
    display: grid;
    grid-template-columns: 200px 100px 100px 100px;
    grid-template-rows: 100px 100px 100px;



<!DOCTYPE html>
<html>
    <head>
        <link rel="stylesheet" href="project.css">
        <title>Project</title>
    </head>
    <body>
        <!--Navigation Area-->
        <div class="menuArea">
            <nav class="navArea">
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Services</a></li>
                <li><a href="google.com">Portfolio </a></li>
            </ul>
        </nav>
        </div>
        <!--Sections that house images and texts-->
        <section class="top-section">
            <div class="top-wrapper">
                <div class="top-container">
                    <section><img src="images/beautiful-black-girl-is-engaged-gym_1157-23749.jpg"></section>
                    <section><img src="images/Brandon-Copeland-1024x683.jpg"></section>
                    <section><img src="images/black gymnast.jpg"></section>
                    <section><img src="images/gym-room.jpg"></section>
                    <section><img src="images/mario.png"></section>
                    <section><img src="images/muscular-body-builder-working-out-260nw-352346867.jpg"></section>
                    <section><img src="images/gym.jpg"></section>

                </div>
            </div>
        </section>
    </body>
</html>
