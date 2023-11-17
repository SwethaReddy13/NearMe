# Ex04 Places Around Me

## DATE-13/10/2023

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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>WEB EXPERIMENT</title>
</head>
<body>
    <h1 align="center">
        <font color=""><b>CHITTOOR</b></font>
        </h1>
        <h3 align="center">
        <font color="blue"><b>SWETHA K 212220040167</b></font>
        </h3>
<center>        
<img src="Map.png" usemap="#image-map" height="650" width="1600">
</center>
<map name="image-map">
    <area shape="rectangle" coords="1043,70,1156,108" href="a.html" title="Chittoor Government Hospital">
    <area shape="rectangle" coords="1061,205,908,239" href="b.html" title="Kattamanchi Lake">
    <area shape="rectangle" coords="569,377,693,418" href="c.html" title="Vijayalakshmi Theatre">
    <area shape="rectangle" coords="968,96,913,63" href="d.html" title="Mesonical Grounds">
    <area shape="rectangle" coords="1131,49,977,19" href="e.html" title="Hotel Andra Spice">
</map>
</body>
</html>
```
```
<html>
<head>
<title>Santhapet</title>
</head>
<body bgcolor="white">
<h3 align="center"><font size="+3">Santhapet</font></h3>
<hr size="7" color="red">
<p align="justify">
<font size="+1">This is Santhapet------</font>
</p>
<p>
    
    <font size="+2">Santhapet is well-connected to other parts of Chittoor district and Andhra Pradesh by road, rail, and bus. The Chittoor railway station is located just a short distance from Santhapet.

        Santhapet is a vibrant and growing community with a lot to offer its residents. It is a good place to live, work, and raise a family.
        
        </font>
</p>
</body>
</html>
```
```
<html>
<head>
<title>RR Gardens</title>
</head>
<body bgcolor="Orange">
<h3 align="center"><font size="+3">RR Gardens</font></h3>
<hr size="7" color="black">
<p align="justify">
<font size="+1">Here's RR Gardens------</font>
</p>
<p>
    
    <font size="+2">RR Gardens is a spacious and well-equipped venue that can accommodate a variety of events.
        The banquet hall is well-decorated and has all the modern amenities.
        The lawn is lush green and perfect for outdoor events.
        RR Gardens offers a variety of services, including catering, decoration, photography, videography, transportation, and valet parking.
        RR Gardens is known for its excellent service, affordable rates, and beautiful surroundings.
        If you are looking for a wedding or event venue in Chittoor, RR Gardens is a great option to consider 
        </font>
</p>
</body>
</html>
```
```
<html>
<head>
<title>P.Kothur</title>
</head>
<body bgcolor="Green">
<h3 align="center"><font size="+3">P.Kothur</font></h3>
<hr size="7" color="black">
<p align="justify">
<font size="+1">Here's P.Kothur------</font>
</p>
<p>
    
    <font size="+2">  Kothur is a popular tourist destination, and is known for its temples, scenic beauty, and peaceful atmosphere. It is a good place to visit for a religious pilgrimage, a relaxing vacation, or a combination of both.
        </font>
</p>
</body>
</html>
```
```
<html>
<head>
<title>Durgamma temple</title>
</head>
<body bgcolor="Cyan">
<h3 align="center"><font size="+3">Durgamma temple</font></h3>
<hr size="7" color="black">
<p align="justify">
<font size="+1">Here's Durgamma temple------</font>
</p>
<p>
    
    <font size="+2">  The temple is a popular pilgrimage destination for Hindus from all over the world. The temple is also a popular tourist destination, as it is located in a beautiful setting.

        The temple has a rich history and tradition. It is believed that the temple was built by the Chola kings in the 12th century. The temple was later renovated by the Vijayanagara kings in the 16th century.
        
        The temple is a beautiful example of Dravidian architecture. The temple has a tall gopuram, or entrance tower, that is decorated with intricate carvings. The temple also has a number of other shrines dedicated to other deities, such as Ganesha, Vishnu, and Shiva.
        
        The temple is a vibrant and active place of worship. The temple is open to the public and is a popular place for devotees to come and worship the goddess Durga.
        
        
        </font>
</p>
</body>
</html>
```
```
<html>
<head>
<title>Neva River</title>
</head>
<body bgcolor="Yellow">
<h3 align="center"><font size="+3">Neva River</font></h3>
<hr size="7" color="black">
<p align="justify">
<font size="+1">Here's Neva River------</font>
</p>
<p>
    
    <font size="+2">  
        The Neva River originates in the hills of the Eastern Ghats and flows through the Chittoor district before joining the Palar River in Tamil Nadu. The river is about 100 km long and has a drainage basin of about 2,000 sq km.
        
        The Neva River is an important source of irrigation water for the farmers in the Chittoor district. The river is also used for drinking water and industrial purposes.
        
        The Neva River is a popular tourist destination. The river is known for its scenic beauty and its calm waters. The river is also home to a variety of aquatic life, including fish, turtles, and crocodiles.
        
        </font>
</p>
</body>
</html>
```

## OUTPUT
<img width="960" alt="map" src="https://github.com/SwethaReddy13/NearMe/assets/129032832/89fdfc72-af79-43bc-afdf-72802933940d">
<img width="960" alt="a" src="https://github.com/SwethaReddy13/NearMe/assets/129032832/cbcfdc58-9fa5-45b5-9ef1-80b25b416bb1">
<img width="960" alt="b" src="https://github.com/SwethaReddy13/NearMe/assets/129032832/27a23dd8-6e50-4db1-a075-fad0dada5c9f">
<img width="960" alt="c" src="https://github.com/SwethaReddy13/NearMe/assets/129032832/bc0f997b-95f0-46fa-883b-5b04b1c7fc3c">
<img width="960" alt="d" src="https://github.com/SwethaReddy13/NearMe/assets/129032832/97a2662a-7d97-4a1d-a86c-f157c2876f3c">

<img width="960" alt="e" src="https://github.com/SwethaReddy13/NearMe/assets/129032832/a728b534-6cf1-45f6-a232-bff094284152">





## RESULT
The program for implementing image maps using HTML is executed successfully.
