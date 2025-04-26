# Ex04 Places Around Me
## Name:HASMITHA V NANCY
## Reg No:212224040111
## Date:26-04-2025 

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
~~~
<html>
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Kanyakumari</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Hasmitha V Nancy(24004046)</b></font>
</h3>
<center>
<img src="map.png" usemap="#MyCity" height="610" width="1450">
<map name="MyCity">
<area target="_blank" alt="home " title="home " href="home.html" coords="836,543,688,656" shape="rect">
<area target="_blank" alt="temple" title="temple" href="temple.html" coords="324,363,168" shape="circle">

</map>
</center>
</body>
</html>
~~~
home.html
~~~
<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="lightseagreen">
<h1 align="center">
<font color="red"><b>Kanyakumari</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Nagercoil - My Home Town</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Nagercoil is located in the southern part of Tamil Nadu, near Kanyakumari.<br>
The name "Nagercoil" means "Temple of the Nāgas," related to an ancient serpent temple.<br>
It is the headquarters of Kanyakumari district.<br>
The town is surrounded by the Western Ghats, fertile fields, and coconut groves.<br>
Famous tourist spots nearby include Vivekananda Rock Memorial, Suchindram Temple, and Padmanabhapuram Palace.<br>
Nagercoil has a tropical climate with heavy rainfall during the southwest monsoon.<br>
Agriculture is important here, with crops like rice, banana, coconut, and rubber.<br>
It has growing industries such as rubber production, coir manufacturing, and software services.<br>
The town has a rich cultural mix, with people of Hindu, Christian, and Muslim faiths.<br>
Nagercoil Junction is a major railway station connecting different parts of South India.
</font>
</p>
</body>
</html>
~~~
temple.html
~~~
<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="lavender">
<h1 align="center">
<font color="red"><b>Kuzhithurai</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Suchindram temple - Devotional Centre</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Suchindram Temple is located near Nagercoil in the Kanyakumari district of Tamil Nadu.<br>
It is dedicated to a unique trinity of Hindu gods: Shiva, Vishnu, and Brahma, worshipped together as "Sthanumalayan."<br>
The temple is famous for its tall white gopuram (tower) which is around 40 meters high and beautifully sculpted.<br>
Suchindram Temple is believed to be over 1,000 years old, with contributions from several dynasties like the Cholas, Pandyas, and Travancore kings.<br>
Inside the temple, there is a remarkable 18-feet tall monolithic Hanuman statue, one of the tallest of its kind.<br>
The temple is rich in carvings, with thousands of detailed sculptures on its pillars and walls.<br>
It is believed that Indra, the king of the gods, was purified of a curse here, making the temple highly sacred.<br>
Traditional musical pillars, which produce different musical notes when tapped, are a major attraction inside the temple.<br>
The temple celebrates many festivals, especially the "Car Festival," which draws large crowds.<br>
Non-Hindus are allowed to visit the outer corridors but may have limited access to the inner sanctum.
</font>
</p>
</body>
</html>
~~~

## OUTPUT
![Screenshot 2025-04-26 131138](https://github.com/user-attachments/assets/9df5b053-c361-4397-97f9-50b603d859a6)


![1](https://github.com/user-attachments/assets/163da3ac-9ad4-4289-92d7-e5cdc5735f06)


![2](https://github.com/user-attachments/assets/d390cc4a-c51c-4ee0-abea-f6c2fcbab908)




## RESULT
The program for implementing image maps using HTML is executed successfully.
