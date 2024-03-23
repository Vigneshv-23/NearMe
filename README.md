# Ex04 Places Around Me
## Date: 22.03.2024

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
<html>
    <head>
        <title>Map</title>
    </head>
    <body>
        <h1 align="center">CHENNAI</h1>
        <h2 align="center">VIGNESH V 212223110062</h2>
       <center> <img  src="area.png" usemap="#image-map"></center>
    <map name="image-map">
        <area target="" alt="Metro station" title="Metro station" href="Mannadi.html" coords="1220,644,1046,718" shape="rect">
        <area target="" alt="Hospital" title="Hospital" href="Stanley.html" coords="1047,146,128" shape="circle">
        <area target="" alt="Railway station" title="Railway station" href="Basin.html" coords="250,263,502,372" shape="rect">
        <area target="" alt="Skating Ring" title="Skating Ring" href="Skating.html" coords="406,829,88" shape="circle">
        <area target="" alt="Food shelter" title="Food shelter" href="Shelter.html" coords="813,458,1061,373" shape="rect">
    </map>
</body>
</html>
```
## Mannadi.html
```
<html>
    <head>
        <title>Metro station</title>
    </head>
    <body bgcolor="violet">
        <center><h1>CHENNAI</h1></center>
        <center><h2>Mannadi Metro</h2></center>
        <hr>
       <font size="+3"> <p align="center">1.Mannadi is an underground metro station on the North-South Corridor of the Blue Line of Chennai Metro in Chennai, India.</p></font>
       <font size="+3"><p align="center">2.The station serves the neighbourhoods of Mannadi and George Town.</p></font>
       <font size="+3"><p align="center">3.This station was opened for public on 10 February 2019. </p></font>
    </body>
</html>
```
## Stanley.html
```
<html>
    <head>
        <title>Hospital</title>
    </head>
    <body bgcolor="orange">
    <center><h1>CHENNAI</h1></center>
    <center><h2>Stanley Hospital</h2></center>
    <hr>
    <center><p>1.Stanley Medical College and Hospitals is one of the oldest centers in India in the field of medical education. </p></center>
    <center><p>2.The seed for this institution was sown as early as 1740 when the East India Company first created the medical department. </p></center>
    <center><p> 3.The Stanley Hospital now stands on the old site of the Monegar Choultry established in 1782.</p></center>
    </body>
</html>
```
## Basin.html
```
<html>
    <head>
        <title>Railway station</title>
    </head>
    <body bgcolor="gray">
    <h1 align="center">CHENNAI</h1>
    <h2 align="center">Basin bridge junction</h2>
    <hr>
        <center><p>1.The lines at the station were electrified in 1979. </p></center>
        <center><p>2.The station is covered by the ₹ 400-million Integrated Security Surveillance System (ISSS) project implemented in 2012. </p></center>
        <center><p>3.As of 2013, the station handles about 10,000 passengers a day</p></center>
    </body>
</html>
```
## skating.html
```
<html>
    <head>
        <title>Skating ring</title>
    </head>
    <body bgcolor="skyblue">
        <h1 align="center">CHENNAI</h1>
        <h2 align="center">Nehru indoor skating rink</h2>
        <hr>
        <center><p>1.Jawaharlal Nehru Stadium, also known as the Marina Arena, is a multi-purpose stadium in Chennai, India.</p></center>
        <center><p>2.The stadium was built on the area where the old Madras Zoo was located before it was shifted to its present location in at Vandalur.</p></center>
        <center><p>3.In 2012, the Government of Tamil Nadu renovated the indoor stadium at a cost of ₹120 million (US$1.5 million) with a new skating rink</p></center>
    </body>
</html>
```
## Shelter.html
```
<html>
    <head>
        <title>Shelter</title>
    </head>
    <body bgcolor="crayon">
        <h1 align="center">CHENNAI</h1>
        <h2 align="center">public food bank</h2>\
        <hr>
        <center><p>1.Chennai Social Service (CSS) is a registered Non Governmental Organization (NGO) working with its motto "Share Your Living..."</p></center>
        <center><p>2.Chennai Social service is a registered non governmental organization (NGO) with about 1400 online members and 75 active volunteers.</p></center>
        <center><p>3.CSS has been rendering its service to chennai city since July 27, 2006. The activities of CSS revolve around five different teams.</p></center>
    </body>
</html>
```
## OUTPUT
![image](https://github.com/Vigneshv-23/NearMe/assets/110780412/d0da4194-9a65-469c-87fb-f0070de62d76)
![image](https://github.com/Vigneshv-23/NearMe/assets/110780412/bba368b9-f1e4-4dc9-b2ff-35c6a65e7101)
![image](https://github.com/Vigneshv-23/NearMe/assets/110780412/fede2e40-793f-4472-b87b-3b54db2b6f91)
![image](https://github.com/Vigneshv-23/NearMe/assets/110780412/a997db84-e74d-4de9-b68a-6c1bcd7a79dc)
![image](https://github.com/Vigneshv-23/NearMe/assets/110780412/9122e4ab-d7d6-4a6b-975d-a640a00775fb)
![image](https://github.com/Vigneshv-23/NearMe/assets/110780412/031de5c2-ccd7-4725-824a-afecff8509da)











## RESULT
The program for implementing image maps using HTML is executed successfully.
