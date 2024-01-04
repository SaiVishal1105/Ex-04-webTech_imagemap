# Ex-06-Places Around Me
NAME: SAI VISHAL D<BR>
REG.NO: 212223230180

## Aim:
To develop a website to display details about the places around my house.

## Design Steps:
### Step 1
Create a Django admin interface.

### Step 2
Download your city map from Google.

### Step 3
Create a Django project and start an app.

### Step 4
Open the file in VS code and create and edit the html files for each place in the map.

### Step 5
Make migrations and run the program using python manage.py runserver 8000.


## Program:
```
map.html
<html>
    <head>
        <title>My Area</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>Kolathur</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>Sai Vishal D (23013576)</b></font>
        </h3>
        <center>
            <img src="map.png" usemap="#MyArea" height="610" width="1450">
            <map name="MyArea">
                <area shape="rect" coords="637,292,833,402" href="kolathur.html" title="My Area">
                <area shape="rect" coords="150,601,451,730" href="donbosco.html" title="Don Bosco School">
                <area shape="rect" coords="145,231,294,321" href="l1gaming.html" title="L1 Gaming Cafe">
                <area shape="rect" coords="175,402,342,504" href="policestation.html" title="Rajamangalam Police Staion">
                <area shape="rect" coords="735,27,955,122" href="kolathurfishmarket.html" title="Kolathur Fish Market">
                <area shape="rect" coords="911,188,11157,283" href="srigangacinemas.html" title="Sri Ganga Cinemas">

            </map>
        </center>
    </body>
</html>
```
```
kolathur.html
<html>
    <head>
        <title>Kolathur</title>
    </head>
    <body bgcolor="black">
        <h1 align="center">
            <font color="yellow"><b>Kolathur</b></font>
        </h1>
        <h2 align="center">
            <font color="yellow">My Area</font>
        </h2>
        <hr size="3" color="yellow">
        <center><img src="kolathur.png"></center>
        <p align="justify">
            <font face="Kolathur" size="5">
            <font color="yellow">   
            <h3 align="center">
                Kolathur is a neighborhood located in the northwestern region of Chennai, Tamil Nadu, India.
                It is a place surrounded by a lot of lakes and most popular for its fish market. 
                Kolathur has many schools within it self Don Bosco, Everwin and St.John's are some of them
            </h3>
            </font>
            </font>
        </p>
    </body>
</html>
```
```
donbosco.html
<html>
    <head>
        <title>Don Bosco School</title>
    </head>
    <body bgcolor="white">
        <h1 align="center">
            <font color="blue"><b>Don Bosco School</b></font>
        </h1>
        <h2 align="center">
            <font color="blue">My School</font>
        <hr size="3" color="red">
        <center>
        <img align="middle" src="donbosco.jpg" height="400" width="350">
        </center>
        <p align="justify">
            <font face="My School" size="5">
                <font color="blue">
                <h3 align="center">  
                This is a popular school in Kolathur, located at Srinivasa Nagar. 
                This school offers matriculation syllabus from kindergarden to higher secondary schooling.
                This school has a moderate infrastructure with good teachers.
                I completed my schooling here.
                </h3>
                </font>
            </font>
        </p>
    </body>
</html>
```
```
policestation.html
<html>
    <head>
        <title>Rajamangalam Police Station</title>
    </head>
    <body bgcolor="red">
        <h1 align="center">
            <font color="white"><b>Rajamangalam Police Staion</b></font>
        </h1>
        <h2 align="center">
            <font color="white">Police station</font>
        <hr size="3" color="white">
        <img align="middle" src="rajamangalam.jpg">
        <p align="justify">
            <font face="Police Station" size="5">
            <font color="white">
                <h3 align="center">
                A local Police Station in the Kolathur neighborhood, located in Rajamangalam.
                </h3>
            </font>
            </font>
        </p>
    </body>
</html>


```
```
fishmarket.html
<html>
    <head>
        <title>Kolathur Fish Market</title>
    </head>
    <body bgcolor="cyan">
        <h1 align="center">
            <font color="blue"><b>Kolathur Fish Market</b></font>
        </h1>
        <h2 align="center">
            <font color="blue">Famous in Kolathur</font>
        </h2>
        <hr size="3" color="blue">
        <center>
        <img align="middle" src="fishmarket.jpg" height="320" width="540">
        </center>
        <p align="justify">
            <font face="Popular Fish Market" size="5">
                <font color="blue">   
                <h3 align="center">
               A popular fish market where wide variety of pet fishes are sold, many people from all over chennai purchase here the pet fishes.
               </h3>
               </font>
            </font>
        </p>
    </body>
</html>
```
```
srigangacinemas.html
<html>
    <head>
        <title>Sri Ganga Cinemas</title>
    </head>
    <body bgcolor="black">
        <h1 align="center">
            <font color="red"><b>Sri Ganga Cinemas</b></font>
        </h1>
        <h2 align="center">
            <font color="red">Popular Cinema Theatre</font>
        </h2>
        <hr size="3" color="yellow">
        <center>
        <img align="middle" src="cinemas.png">
        </center>
        <p align="justify">
            <font face="Ganga Cinemas" size="5">
                <font color="yellow">   
                    <h3 align="center">
                Sri Ganga Cinema - Kolathur is a popular theatre has 3 screens.
                It is the popular theatre in the locality
                </h3>
                </font>
            </font>
        </p>
    </body>
</html>
```
```
l1gaming.html
<html>
    <head>
        <title>L1 Gaming Cafe</title>
    </head>
    <body bgcolor="black">
        <h1 align="center">
            <font color="green"><b>L1 Gaming cafe</b></font>
        </h1>
        <h2 align="center">
            <font color="green">Popular gaming spot</font>
        </h2>
        <hr size="3" color="green">
        <center>
        <img align="middle" src="l1.jpg" height="480" width="280">
        </center>
        <p align="justify">
            <font face="Gaming Paradise" size="5">
                <font color="green">   
                    <h3 align="center">
                A small business resembling an Internet cafe but with an emphasis on computer games.
                Games are often networked and visitors can play against each other.
                It has both console gaming and PC gaming, namely Playstation 5 and Gaming PCs.
                </h3>
                </font>  
            </font>
        </p>
    </body>
</html>
```


## Output:
![Alt text](<Screenshot 2023-11-22 141358.png>)
![Alt text](<Screenshot 2023-11-22 141421.png>)
![Alt text](<Screenshot 2023-11-22 141458.png>)
![Alt text](<Screenshot 2023-11-22 141516.png>)
![Alt text](<Screenshot 2023-11-22 141536.png>)
![Alt text](<Screenshot 2023-11-22 141609.png>)
![Alt text](<Screenshot 2023-11-22 141648.png>)

## Result:
The program for implementing image maps using HTML is executed successfully.

