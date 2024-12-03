# Ex04 Places Around Me
## Date: 02/12/2024

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using <map> tag name the map.

### STEP 4
Create clickable regions in the image using <area> tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
```
map.html

<html>
    <head>
        <title>My city</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>Trichy</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>M.krishna kumaran (24004032)</b></font>
        </h3>
        <center>
            <img src="map.png" usemap="#Mycity" height="650" width="1450">
            <map name="Mycity">
                <area title="Tiruchirappalli city" href="city.html" coords="750,331,912,386" shape="rect">
                <area title="Lal gudi" href="town.html"+ coords="1035,187,1182,257" shape="rect">
                <area title="Thuva kudi district" href="district.html" coords="873,390,1064,536" shape="rect">
                <area title="Samayapuram temple" href="temple.html" coords="655,20,889,118" shape="rect">
                <area title="Teppakulam lake" href="lake.html" coords="601,225,748,289" shape="rect">
            </map>
        </center>
    </body>
</html>

city.html

<html>
    <head>
        <title>My home town</title>
    </head>
    <body bgcolor="purple">
        <h1 align="center">
            <font color="red"><b>Tiruchirappalli</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>Tiruchirapalli</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
        <font face="Georgia" size="5">
            Tiruchirappalli's recorded history begins in the 3rd century BC, when it was under the rule of the Cholas. The city has also been ruled by the Mutharaiyars, Pallavas, Pandyas, Vijayanagar Empire, Nayak Dynasty, the Carnatic state and the British. The most prominent historical monuments in Tiruchirappalli include the Rockfort at Teppakulam, the Ranganathaswamy temple at Srirangam dedicated to the reclining form of Hindu God Vishnu, and is also the largest functioning temple in the world, and the Jambukeswarar temple at Thiruvanaikaval, which is also the largest temple for the Hindu God Shiva in the world. The archaeologically important town of Uraiyur, capital of the Early Cholas, is now a neighbourhood in Tiruchirappalli. The city played a critical role in the Carnatic Wars (1746–1763) between the British and the French East India companies.
        </font>
    </p>    
    </body>
</html>

district.html


<html>
    <head>
        <title>My home town</title>
    </head>
    <body bgcolor="lime">
        <h1 align="center">
            <font color="red"><b>Tiruchirappalli</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>Thuvakudi district</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
        <font face="Georgia" size="5">
        Thuvakudi comes under the Thiruverumbur (State Assembly Constituency) which elects a member to the Tamil Nadu Legislative Assembly once every five years and it is a part of the Tiruchirappalli Lok Sabha constituency which elects its Member of Parliament (MP) once in five years. The town is administered by the Thuvakudi municipality, which covers an area of 14.37 km2 (5.55 sq mi). In 2001, the town had a population of 38,887. The town is a part of the fertile Cauvery delta region, but manufacturing industries and stone quarrying are the major occupations. Roadways are the major mode of transportation to Thuvakudi and the nearest Airport is Tiruchirapalli Airport, located 25 km (16 mi) away from the town.    
        </font>
    </p>    
    </body>
</html>

lake.html


<html>
    <head>
        <title>My home town</title>
    </head>
    <body bgcolor="cyan">
        <h1 align="center">
            <font color="red"><b>Tiruchirappalli</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>Teppakulam</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
        <font face="Georgia" size="5">
            Teppakulam is a locality near the centre of the Indian city of Tiruchirappalli. It consists of a large artificial tank surrounded by bazaars, prominent among which is a flower market.It contains the Thayumanavar Temple and the Sri Naganathar Swamy Temple, the St. Joseph College Church and Holy Cross Church, and Srimathi Indira Gandhi College for Women.The historic Rockfort is situated nearby.A large monolithic figure of Ganesh, Mukkuruni Vinayaka, was reportedly found during an excavation of the Mariamman Teppakulam tank. The Teppam Floating Festival is held here on boats in January or February and it is a common time and place for marriages.[5]
        </font>
    </p>    
    </body>
</html>

temple.html

<html>
    <head>
        <title>My home town</title>
    </head>
    <body bgcolor="pink">
        <h1 align="center">
            <font color="red"><b>Tiruchirappalli</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>Samyapuram Temple</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
        <font face="Georgia" size="5">
        The main deity, Samayapuram Mariamman, a form of Adi Parashakti and Mariamman, is made of sand and clay with extractions of medicinal herbs unlike many of the traditional stone idols and is considered as most powerful Goddess, and hence unlike many other Hindu deities there are no abhishekams (sacred bathing) conducted.
        One of the most significant pilgrimage places is Samayapuram Mariamman temple. It is one of the well-known temples to goddess Sakthi and it is where her followers worship her as Mariamman affectionately known as “samayapurathu Amma”
        </font>
    </p>    
    </body>
</html>

town.html

<html>
    <head>
        <title>My home town</title>
    </head>
    <body bgcolor="yellow">
        <h1 align="center">
            <font color="red"><b>Tiruchirappalli</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>Lal gudi</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
        <font face="Georgia" size="5">
            Lalgudi is a prominent municipality located in the Tiruchirapalli district of Tamil Nadu, India. This region has historical and cultural significance, serving as the administrative center for various divisions including Lalgudi taluk, Lalgudi Educational District, and Lalgudi DSP. Its importance stems from its governance structure, educational institutions, and constituency representation, as it has been part of the legislative assembly since 1952.
        </font>
    </p>    
    </body>
</html>
```
## OUTPUT

![alt text](<Screenshot (21).png>)
![alt text](<Screenshot (22).png>)
![alt text](<Screenshot (23).png>)
![alt text](<Screenshot (24).png>)
![alt text](<Screenshot (25).png>)
![alt text](<Screenshot (26).png>)


## RESULT
The program for implementing image maps using HTML is executed successfully.