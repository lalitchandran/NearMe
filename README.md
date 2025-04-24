# Ex04 Places Around Me
## Date: 24.4.25

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
map.html
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>KADAPPA ROAD</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>S LALIT CHANDRAN (212223240077)</b></font>
        </h3>
        <center>
            <img src="map.png" usemap="#MyCity" height="610" width="1450">
            <map name="MapCity">
                <area shape="rect" coords="700,250,850,400" href="home.html" title="My Home Town">
                <area shape="circle" coords="570,230,45" href="temple.html" title="Murugan Temple">
                <area shape="circle" coords="640,200,30" href="lake.html" title="Kolathur Lake">
                <area shape="circle" coords="1120,360,25" href="garden.html" title="Garden">
                <area shape="rect" coords="950,120,1100,140" href="stone.html" title="Mahabalipuram">
            </map>
        </center>
    </body>
</html>
```
Home
```
<!DOCTYPE html>
<html>
<head>
    <title>My Home Town</title>
    <style>
        body {
            background-color: yellow;
            font-family: Arial, sans-serif;
            margin: 30px;
        }
        h1 {
            color: red;
            text-align: center;
        }
        h3 {
            text-align: center;
            font-style: italic;
            color: black;
        }
        hr {
            border: 1px solid red;
        }
        p {
            text-align: justify;
            font-size: 16px;
            padding: 0 10px;
        }
    </style>
</head>
<body>
    <h1>My Home Town</h1>
    <h3>Peaceful Living - Heart of Culture</h3>
    <hr>
    <p>
        My hometown is a serene village nestled in the district of [Your District], in Tamil Nadu, India.
        Surrounded by lush green fields and age-old temples, it is known for its cultural heritage and warm-hearted people.
        The village thrives on agriculture, and the major crops include rice and sugarcane. The air is always filled with the
        aroma of fresh earth and the sound of birds singing in harmony with nature.
        My village is just 5km away from the nearest town, which serves as the hub for all major trade and services.
        It's the place where traditions meet simplicity, making it a true haven for anyone seeking peace and purity.
    </p>
</body>
</html>

```
lake
```
<!DOCTYPE html>
<html>
<head>
    <title>Beautiful Lake</title>
    <style>
        body {
            background-color: #add8e6;
            font-family: Arial, sans-serif;
            margin: 30px;
        }
        h1 {
            color: navy;
            text-align: center;
        }
        h3 {
            text-align: center;
            font-style: italic;
        }
        hr {
            border: 1px solid navy;
        }
        p {
            text-align: justify;
            font-size: 16px;
        }
    </style>
</head>
<body>
    <h1>Serene Lake</h1>
    <h3>Nature's Mirror - Calm & Tranquil</h3>
    <hr>
    <p>
        The lake in our village is a serene spot surrounded by gentle hills and lush trees. It serves as a habitat for many birds and aquatic creatures.
        Villagers often gather here in the evenings, and it's a popular spot for relaxation and picnics. The beauty of the lake during sunrise is truly breathtaking.
    </p>
</body>
</html>

```
garden
```
<!DOCTYPE html>
<html>
<head>
    <title>Green Garden</title>
    <style>
        body {
            background-color: #ccffcc;
            font-family: Arial, sans-serif;
            margin: 30px;
        }
        h1 {
            color: green;
            text-align: center;
        }
        h3 {
            text-align: center;
            font-style: italic;
        }
        hr {
            border: 1px solid green;
        }
        p {
            text-align: justify;
            font-size: 16px;
        }
    </style>
</head>
<body>
    <h1>Village Garden</h1>
    <h3>Blooming Beauty - A Breath of Fresh Air</h3>
    <hr>
    <p>
        The village garden is full of vibrant flowers, medicinal plants, and fruit trees. It is well maintained by the local community and is a popular place for children to play and elders to relax.
        Seasonal blooms and butterflies make it a magical experience for every visitor.
    </p>
</body>
</html>

```
temple
```
<!DOCTYPE html>
<html>
<head>
    <title>Ancient Temple</title>
    <style>
        body {
            background-color: #f4e2d8;
            font-family: Arial, sans-serif;
            margin: 30px;
        }
        h1 {
            color: brown;
            text-align: center;
        }
        h3 {
            text-align: center;
            font-style: italic;
        }
        hr {
            border: 1px solid brown;
        }
        p {
            text-align: justify;
            font-size: 16px;
        }
    </style>
</head>
<body>
    <h1>Ancient Temple</h1>
    <h3>Spiritual Heritage - The Pride of Our Village</h3>
    <hr>
    <p>
        The temple in our village dates back to centuries and is a fine example of Dravidian architecture. Carvings on the stone walls tell stories of
        our past and traditions. The temple hosts many festivals throughout the year, bringing the community together in celebration and devotion.
    </p>
</body>
</html>

```
stone
```
<!DOCTYPE html>
<html>
<head>
    <title>Mahabalipuram</title>
    <style>
        body {
            background-color: yellow;
            font-family: Arial, sans-serif;
            margin: 30px;
        }
        h1 {
            color: red;
            text-align: center;
        }
        h3 {
            text-align: center;
            font-style: italic;
        }
        hr {
            border: 1px solid red;
        }
        p {
            text-align: justify;
            font-size: 16px;
        }
    </style>
</head>
<body>
    <h1>Gingee</h1>
    <h3>Virpattu Big Stone - The Tourist Attraction</h3>
    <hr>
    <p>
        The granitic rocks in the area were formed towards the end of the Archean Era of the geological time scale, due to magmatic action
        leading to the melting of the older gneissic rocks and intrusion. The thickness of this younger granitic complex varies from 5 to 25 km.
        Virpattu village is located in Gingee taluka of Viluppuram district in Tamil Nadu, India. Viluppuram and Gingee are the district & sub-district
        headquarters of Virpattu village respectively. Gingee is the nearest town to Virpattu for all major economic activities, which is approximately
        5km away.
    </p>
</body>
</html>

```
## OUTPUT
Map
![map](https://github.com/user-attachments/assets/a7caba87-a945-434f-980e-84019266f8e0)

lake
![1](https://github.com/user-attachments/assets/0c72a31d-9d80-42a9-9826-d61e3502bc53)

home
![3](https://github.com/user-attachments/assets/5f45e7ff-cdef-4777-aa6a-453cad078ad8)

temple
![5](https://github.com/user-attachments/assets/9f97a905-7186-4b9a-9219-d0254528df74)

garden
![2](https://github.com/user-attachments/assets/9982b034-738b-4ac4-a891-b8705ce7b2f7)

stone
![4](https://github.com/user-attachments/assets/2eb77b37-88b6-4ec4-a066-e329f2d36ec9)

## RESULT
The program for implementing image maps using HTML is executed successfully.
