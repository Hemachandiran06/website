# Ex.07 Restaurant Website
# Date:14-11-2024
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
```
coffee.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Coffee | shop </title>
</head>
<body>
     <div class="container">
        <div class="nav-bar">
            <h1 class="title">Cof<span>fee</span></h1>
            <ul class="menu">
                <li><a href="https://roasterycoffee.co.in/">HOME</a></li>
                <li><a href="#">MENU</a></li>
                <li><a href="#">PRODUCT</a></li>
                <li><a href="#">SERVICES</a></li>
                <li><a href="#">ABOUT    </a></li>
            </ul>
        </div>

        <div class="home">
            <h1 class="title-1">Good <span>Coffee</span> will always <br> Find the audience</h1>
            <p>We provide a variety of uniques and best Coffees</p>
            <button type="button">Shop Now</button>
        </div>



     </div>
</body>
</html>

style.css

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

.container{
    height: 100vh;
    width: 100%;
    background: linear-gradient(rgba(0,0,0,0.7),rgba(0,0,0,0.7)),url(WhatsApp\ Image\ 2024-10-12\ at\ 12.31.44_e401b292.jpg);
    background-size: cover  ;
    background-position: center;
    font-family: Arial, Helvetica, sans-serif;
}
.nav-bar{
    display: flex;
    align-items: center;
    justify-content: space-between ;
    padding: 30px 80px;  
}
.nav-bar  .title{
    color: white;
    font size: 67px;
    font-weight:700;
    cursor: pointer;
}       
 
span{
    color: crimson;
}
.menu li{
    list-style: none;
    display: inline-block;
}
.menu li a{
    text-decoration: none;
    color: white;
    font-size: 27px;
    margin-left: 25px;
    font-weight: 600;
    transition: .4s  ease;
}
    
.menu li a:hover{
    color:crimson;
    padding: 5px 10px;
    border: 2px solid white;
}
.home{
    height: 400px;
    padding: 70px;
}
.title-1{
    font-size: 56px;
    color: white;
    font-weight: 600;
}

.home p{
    color: lemonchiffon;
    font-size: 20px;
    padding-top: 10px;
}
.home button{
    height: 40px;
    color: white;
    background: crimson;
    padding: 5px 30px;
    margin-top: 20px;
    border: none;
    border-radius: 5px;
    font-size: 22px;
    transition: .4s ease;
    cursor: pointer;
}
.home button:hover{
    background: none;
    border: 2px solid crimson;
}
```
# OUTPUT:
![alt text](<Screenshot (33).png>)

# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
