# Online-Shopping-site-Front-end-
This site will help you to buy any cloths, shoes, etc. This is responsive dynamic website using (HTML, CSS, Bootstrap).

<!DOCTYPE html>
<html>

<head>
    <title>
        Riman.com
    </title>
    <style>
    .nav {
    background-color: rgb(35, 34, 34);
    color: white;
    display: flex;
}

.nav ul {
    list-style-type: none;
    display: flex;
    justify-content: flex-end;
    margin-left: 700px;
    padding: 10px;
}

.nav li {
    padding-left: 60px;
    color: white;
}

.button1 {
    padding: 5px;
    padding-left: 10px;
    padding-right: 10px;
    background-color: rgb(48, 47, 47);
    color: red;
    border: 2px solid;
    border-radius: 10px;
}

.nav h1 {
    padding-left: 60px;
}

.grid-container {
    display: grid;
    grid-template-columns: auto auto auto;
}

.item1 {
    padding-left: 150px;
    padding-right: 50px;
    padding-top: 150px;
    font-size: 30px;
}

.item2 {
    padding-left: 100px;
    padding-top: 100px;
    padding-bottom: 150px;
}

.button2 {
    background-color: rgb(241, 181, 69);
    padding: 15px;
    padding-left: 30px;
    padding-right: 30px;
    ;
    border: 3px solid;
    border-radius: 20px;
}

.img1 {
    padding-right: 100px;
}

.img2 {
    position: absolute;
    top: 500px;
    right: 550px;
}

.nav a {
    color: white;
    text-decoration: none;
}

.nav li a:hover {
    color: red;
}

.button1:hover {
    color: white;
    background-color: red;
}

h2 {
    text-align: center;
    text-decoration: underline;
}

.item3 {
    padding-right: 200px;
    padding-left: 120px;
    padding-top: 120px;
}

.item3 h3 {
    font-size: 30px;
}

.item3 p2 {
    font-size: 20px;
}

.img3 {
    padding-right: 100px;
    padding-top: 50px;
}
    </style>
</head>

<BODY>
    <div class="nav">
        <h1>
            <a href="Riman.com">Riman.Com</a></h1>
        <ul>
            <li>
                <a href=" Heelo.com ">Home</a></li>
            <li>
                <a href="Heelo.com ">About us</a></li>
            <li>
                <a href="Heelo.com ">Contact </a></li>
            <li>
                <button class=" button1 ">Login</button></li>
        </ul>
    </div>
    <div class="grid-container ">
        <div class="item1 ">
            <h1>Your Ideal Destination is waiting for you.</h1>
            <button class="button2 ">Started</button>
        </div>
        <div class="item2 ">
            <img class="img1" src=" pic2.jpg " alt="heelo " width="700px " height="400px ">
            </img>
        </div>
    </div>
    <img class="img2 " src=" pic1.jpg " width="300px " height="200px "></img>
    <figcaption>This is nice Picture.</figcaption>
    <h2>About us</h2>
    <div class="grid-container ">
        <div class="item3 ">
            <h3>Find your perfect property in just one click.</h3>
            <p2>Selling a property can be quite challenging if you do not have the right tools at your disposal. At Go Fourth Wall. We plan to make things a whole lot easier for you.</p2>
        </div>
        <div class="item4 ">
            <img class="img3" src="pic1.jpg " alt="pic1 " width="400px " height="300px "></div>
    </div>

    <script src="index.js"></script>
</BODY>

</html>
