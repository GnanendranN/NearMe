# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:

### Step 1:

Clone the github repository into Theia IDE.
### Step 2:

Create a new Django project
### Step 3:

Write the needed HTML code.
### Step 4:

Run the Django server and execute the HTML files.

## Code:

```

map.html

<IDOCTYPE html>
<html lang="en">
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Namakkal,-Namakkal Fort</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Gnanendran N (23006661)</b></font>
</h3>
<center>
<img src="/static/image/map.jpg" width="1307" height="705"usemap="MyCity"/>
<map name="MyCity">
<area shape="rect"  title="Namakkal Sree Anjaneyar Temple" href="/static/html/sat.html"  coords="233,231,283,281"/>
<area shape="rect"  title="JAI SMAART AQUAA SYSTEMS" href="/static/html/jai.html"  coords="136,488,186,538"/>
<area shape="rect"  title="Hotel Ananda Bhavan" href="/static/html/hab.html"  coords="661,303,711,353"/>
<area shape="rect"  title="Namakkal Abacus Kids Centre" href="/static/html/akc.html"  coords="384,479,434,529"/>
<area shape="rect"  title="AARONS My bag My style" href="/static/html/amb.html"  coords="689,517,739,567"/>
<area shape="rect"  title="KUTTI PETS AND VET SERVICES" href="/static/html/pets.html"  coords="923,76,972,124"/>
</map>
</center>
</body>
</html>


akc.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>Hotel</title>
</head> 
<body bgcolor="green">
<h1 align="center">
<font color="red"><b>Namakkal - Namakkal Fort</b></font>
</h1>
<h3 align="center"> 
<font color="blue"><b></b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Courier New" size="5">
<b>
    Abacus Kids Centre is a centre that provides fun and interactive learning activities for children aged 3 to 12. 
    We are a team of qualified and experienced educators, who are passionate about helping children develop their cognitive, creative, and social skills. 
    Our goal is to inspire children to love learning and explore their potential.
</b>
</font>
</p>
</body>
</html>


amb.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>Bag Shop</title>
</head> 
<body bgcolor="green">
<h1 align="center">
<font color="red"><b>Namakkal - Namakkal Fort</b></font>
</h1>
<h3 align="center"> 
<font color="blue"><b>Namakkal Sree Anjaneyar Temple</b></font>
</h3>
<hr size="3" color="red">
<p align="justify"> 
<font face="Courier New" size="5">
<b>
    We specialize in creating high-quality bags that are both stylish and practical. 
    Our bags are made from the finest materials and are designed to last. 
    We offer a wide range of bags to suit every need, from backpacks and messenger bags to tote bags and duffel bags. 
    Our bags are perfect for work, travel, or everyday use. 
    We take pride in our work and are committed to providing our customers with the best possible products and service. 
    If you have any questions or would like to learn more about our company, please don’t hesitate to contact us.
</b>
</font>
</p>
</body>
</html>


hab.html

<!DOCTYPE html>

<html lang="en">

<head>

<title>Hotel</title>

</head> 

<body bgcolor="green">

<h1 align="center">

<font color="red"><b>Namakkal - Namakkal Fort</b></font>

</h1>

<h3 align="center"> 

<font color="blue"><b></b></font>

</h3>

<hr size="3" color="red">
 
<p align="justify">

<font face="Courier New" size="5">

<b>

    Adyar Ananda Bhavan is a popular chain of casual dining restaurants that serves vegetarian food and outstanding sweets. 
    They have a very pleasant ambiance and their eclectic menu includes North Indian, Chinese and South Indian cuisines. 
    Their decent and bright interiors make the dining experience way more comfortable. 
    This place is a paradise for hardcore chaat lovers. 
    Adyar Ananda Bhavan is located in Royapuram, North Chennai. 
    The nearest landmark of the place is G.K. Jain schools. 
    This light-on-pocket place is perfect for casual outings with family and friends

</b>

</font>

</p>

</body>

</html>


jai.html

<!DOCTYPE html>

<html lang="en">

<head>

<title>Hotel</title>

</head> 

<body bgcolor="green">

<h1 align="center">

<font color="red"><b>Namakkal - Namakkal Fort</b></font>

</h1>

<h3 align="center"> 

<font color="blue"><b></b></font>

</h3>

<hr size="3" color="red">
 
<p align="justify">

<font face="Courier New" size="5">

<b>

    JAI SMAART AQUAA SYSTEMS is a company that provides innovative solutions for water purification and management. 
    We are a team of experts in water technology, engineering, and environmental science, who are committed to delivering high-quality products and services to our customers. 
    Our vision is to make clean and safe water accessible to everyone, while preserving the natural resources and environment.

</b>

</font>

</p>

</body>

</html>


pets.html

<!DOCTYPE html>

<html lang="en">

<head>

<title>Hotel</title>

</head> 

<body bgcolor="green">

<h1 align="center">

<font color="red"><b>Namakkal - Namakkal Fort</b></font>

</h1>

<h3 align="center"> 

<font color="blue"><b></b></font>

</h3>

<hr size="3" color="red">
 
<p align="justify">

<font face="Courier New" size="5">

<b>

    Kutti Pets and Vet Services is a company that provides loving care and medical attention for your furry friends. 
    We are a team of passionate and professional veterinarians, groomers, trainers, and pet sitters, who are dedicated to making your pets happy and healthy. 
    Our mission is to offer the best possible service and experience for you and your pets.

</b>

</font>

</p>

</body>

</html>


sat.html

<!DOCTYPE html>

<html lang="en">

<head>

<title>Temple</title>

</head> 

<body bgcolor="cyan">

<h1 align="center">

<font color="red"><b>Namakkal - Namakkal Fort</b></font>

</h1>

<h3 align="center"> 

<font color="blue"><b>Namakkal Sree Anjaneyar Temple</b></font>

</h3>

<hr size="3" color="red">

<p align="justify">

<font face="Courier New" size="5">

<b>

Namakkal Anjaneyar temple is located in Namakkal, a town in Namakkal district in Tamil Nadu, India and is dedicated to the Hindu god Hanuman. 
It is constructed in the Tamil style of architecture. 
The legend of the temple is associated with Narasimha, an avatar of Hindu god Vishnu appearing for Hanuman and Lakshmi. 
The image of Anjaneyar is 18 ft (5.5 m) tall, making it one of the tallest images of Hanuman in India. 
The Agamam is followed by "Sri Vaikhanasam". 
The temple has a pillared hall leading to the sanctum. 
Four daily rituals and many yearly festivals are held at the temple.
The temple is maintained and administered by the Hindu Religious and Charitable Endowments Department of the Government of Tamil Nadu.

</b>

</font>

</p>

</body>

</html>

```

## Output:
![Output](./output.jpg)

### HTML VALIDATOR
![HTML VALIDATOR](./valid.jpg)

## Result:
The program for implementing image map is executed successfully