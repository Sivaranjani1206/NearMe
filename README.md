# Ex03 Places Around Me
## Date: 24.05.2026

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
```
map.html

<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>CHENNAI</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>SIVARANJANI M (212225220099)</b></font>
        </h3>
        <center>
<img src="map.png" usemap="#image-map" height="610" width="1450">

<map name="image-map">
    <area shape="rect" coords="700 250 850 400"
    <area target="" alt="MARINA BEACH" title="MARINA BEACH" href="beach.html" coords="614,256,729,327" shape="rect">
    <area target="" alt="KAPALEESHWARAR TEMPLE" title="KAPALEESHWARAR TEMPLE" href="temple.html" coords="910,224,1034,281" shape="rect">
    <area target="" alt="DR.MGR AND DR.JAYALALITHA MEMORIAL" title="DR.MGR AND DR.JAYALALITHA MEMORIAL" href="memorial.html" coords="1044,421,1299,494" shape="rect">
    <area target="" alt="SUPER SARAVANA STORES" title="SUPER SARAVANA STORES" href="store.html" coords="533,617,777,724" shape="rect">
    <area target="" alt="MADRAS MEDICAL MISSION HOSPITAL" title="MADRAS MEDICAL MISSION HOSPITAL" href="hospital.html" coords="817,636,973,712" shape="rect">
</map>

             
        </center>
    </body>
</html>

beach.html

<html>
    <head>
        <title>My hometown</title>
    </head>
    <body bgcolor= "lightskyblue">
        <h1 align="center">
            <font color="maroon"><b>CHENNAI</b></font>
        </h1>
        <h3 align="center">
            <font color="maroon"><b>MARINA BEACH</b></font>
            <hr size="3" color="purple">
        </h3>
        <p align="justify">
            <font face="Georgia" size="5">
                Marina Beach is a famous natural urban beach in Chennai, Tamil Nadu, stretching for 13 km along the Bay of Bengal.<br>
                Known as India's longest and the world's second-longest urban beach, it is a vibrant cultural hub that serves
                as both a relaxing promenade and a lively local fairground.
            </font>
        </p>
    </body>
</html>

temple.html

<html>
    <head>
        <title>My hometown</title>
    </head>
    <body bgcolor="lightskyblue">
        <h1 align="center">
            <font color="maroon"><b>CHENNAI</b></font>
        </h1>
        <h3 align="center">
            <font color="maroon"><b>KAPALEESHWARAR TEMPLE</b></font>
            <hr size="3" color="purple">
        </h3>
        <p align="justify">
            <font face="Georgia" size="5">
                The Kapaleeshwarar Temple is a historic and prominent Hindu temple dedicated to Lord Shiva, located in the cultural hub of 
                Mylapore, Chennai. <br> Built in the 7th-century Dravidian architectural style, it features a towering gopuram and is renowned for its
                self-manifested Shiva Lingam and shrines dedicated to Goddess Parvati.
            </font>
        </p>
    </body>
</html>

memorial.html

<html>
    <head>
        <title>My hometown</title>
    </head>
    <body bgcolor="lightskyblue">
        <h1 align="center">
            <font color="maroon"><b>CHENNAI</b></font>
        </h1>
        <h3 align="center">
            <font color="maroon"><b>DR.MGR AND DR.JAYALALITHA MEMORIAL</b></font>
            <hr size="3" color="purple">
        </h3>
        <p align="justify">
            <font face="Georgia" size="5">
                The Dr. M.G.R. and Dr. J. Jayalalithaa Memorial is an iconic 8.25-acre mausoleum complex located on Marina Beach in Chennai, Tamil Nadu.<br>
                It is dedicated to two of the state's most revered former Chief Ministers and cultural icons: M.G. Ramachandran (M.G.R.) and J. Jayalalithaa.
            </font>
        </p>
    </body>
</html>

hospital.html

<html>
    <head>
        <title>My hometown</title>
    </head>
    <body bgcolor="lightskyblue">
        <h1 align="center">
            <font color="maroon"><b>CHENNAI</b></font>
        </h1>
        <h3 align="center">
            <font color="maroon"><b>MADRAS MEDICAL MISSION HOSPITAL</b></font>
            <hr size="3" color="purple">
        </h3>
        <p align="justify">
            <font face="Georgia" size="5">
                The Madras Medical Mission (MMM) is a renowned, 300-bed charitable tertiary care hospital located in Mogappair, Chennai.<br> 
                Founded in 1982 by the Malankara Orthodox Church, it is internationally recognized for its excellence in cardiology, multi-organ transplants, 
                and advanced medical care, combining cutting-edge technology with compassionate service.
            </font>
        </p>
    </body>
</html>

store.html

<html>
    <head>
        <title>My hometown</title>
    </head>
    <body bgcolor="lightskyblue">
        <h1 align="center">
            <font color="maroon"><b>CHENNAI</b></font>
        </h1>
        <h3 align="center">
            <font color="maroon"><b>SUPER SARAVANA STORES</b></font>
            <hr size="3" color="purple">
        </h3>
        <p align="justify">
            <font face="Georgia" size="5">
                Super Saravana Stores is a legendary Indian retail chain based in Tamil Nadu, known as one of the largest family-owned business 
                retail networks in the country. <br> It operates massive, multi-story department stores offering an extensive range of goods including clothing, jewelry, 
                groceries, and electronics at highly affordable, wholesale-style prices.
            </font>
        </p>
    </body>
</html>
```

## OUTPUT
![alt text](<Screenshot (203).png>)
![alt text](<Screenshot (204).png>)
![alt text](<Screenshot (206).png>)
![alt text](<Screenshot (208).png>)
![alt text](<Screenshot (207).png>)
![alt text](<Screenshot (205).png>)
## RESULT
The program for implementing image maps using HTML is executed successfully.
