# Ex04 Places Around Me
# Date:
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
map.html
```
<html>
<head>
<title>MY CITY</title>
</head>
<body>
<h1 align="center">
<font color="black"><b>MELUR</b></font>
</h1>
<h3 align="center">
<font color="green"><b>MUGUNTHAN(24005593)</b></font>
</h3>
<center>
<img src="Screenshot 2024-03-24 144347.png" usemap="#image-map">

<map name="image-map">
    <area target="_self" alt="Spartanz Fitness" title="Spartanz Fitness" href="fitness.html" coords="657,687,483,572" shape="rect">
    <area target="_self" alt="Government Hospital" title="Government Hospital" href="hospital.html" coords="464,142,642,231" shape="rect">
    <area target="_self" alt="RTO Office Melur" title="RTO Office Melur" href="office.html" coords="1154,644,69" shape="circle">
    <area target="_self" alt="Ganesh Theatre Complex" title="Ganesh Theatre Complex" href="theatre.html" coords="723,299,840,380" shape="rect">
    <area target="_self" alt="Poorvika Mobiles Melur" title="Poorvika Mobiles Melur" href="mobiles.html" coords="509,322,661,430" shape="rect">
</map>
</center>
</body>
</html>

finess.html

<html>
<head>
<title>MY NATIVE</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="silver"><b>MELUR</b></font>
</h1>
<h3 align="center">
<font color="red"><b>Spartanz Fitness</b></font>
</h3>
<hr size="3" color="green">
<p align="justify">
<font face="Georgia" size="6">
  It is located in melur,madursi district. At Thiruvathoor Road Near Old EB Office.
   Opposite to Meenakshi amma illam.
   </font>
</p>
</body>
</html>

hospital.html

<html>
<head>
<title>MY NATIVE</title>
</head>
<body bgcolor="blue">
<h1 align="center">
<font color="white"><b>MELUR</b></font>
</h1>
<h3 align="center">
<font color="pink"><b>Goverment Hospital</b></font>
</h3>
<hr size="3" color="black">
<p align="justify">
<font face="Georgia" size="6">
It is located near railways station,Madurai Main Rd; Azhagarkovil Road, Nagaikadai Bazaar
 Opposite To Taluk Office madurai district.
It is popular for cardiology. It is Sub-District Hospital.
</font>
</p>
</body>
</html>

mobiles.html

<html>
<head>
<title>MY NATIVE</title>
</head>
<body bgcolor="green">
<h1 align="center">
<font color="brown"><b>MADURAI</b></font>
</h1>
<h3 align="center">
<font color="yellow"><b>Poorvika Mobiles Melur</b></font>
</h3>
<hr size="4" color="black">
<p align="justify">
<font face="Georgia" size="6">
    Poorvika sells a wide category of devices in its showrooms and Online portal.
   It is located at Trichy Main Rd, near Bus Stand,in Arittapatti,Melur, Tamil Nadu
</font>
</p>
</body>
</html>

office.html

<html>
<head>
<title>MY NATIVE</title>
</head>
<body bgcolor="orange">
<h1 align="center">
<font color="white"><b>MELUR</b></font>
</h1>
<h3 align="center">
<font color="pink"><b>RTO office Melur</b></font>
</h3>
<hr size="4" color="white">
<p align="justify">
<font face="Georgia" size="6">
    The RTO Office in Melur, Madurai offers a wide range of services related to vehicle registration, licensing and  t
    the Melur RTO is also responsible for collection of taxes, issuing permits. 
    It is located at Kela St, Kannakudi, Lalkudi,melur at madurai distict.
</font>
</p>
</body>
</html>

theatre.html

<html>
<head>
<title>MY NATIVE</title>
</head>
<body bgcolor="red">
<h1 align="center">
<font color="blue"><b>MELUR</b></font>
</h1>
<h3 align="center">
<font color="grey"><b>Ganesh Theatre</b></font>
</h3>
<hr size="3" color="pink">
<p align="justify">
<font face="Georgia" size="6">
    Melur Ganesh Complex A C Dts 2k 3d is a chain of theatres in India that exhibit a myriad of movies around the year. 
    Cinema featuring a lineup of Tamil films in 3 air-conditioned theatres, plus a canteen.
    Ganesh Theatre Complex is situated southwest of Granite quarry, and northwest of Vellalore Government Hospital,at melur,madurai district.
    </font>
</p>
</body>
</html>

```
# OUTPUT
![Screenshot 2024-12-05 143939](https://github.com/user-attachments/assets/7de17458-40b6-4351-a1bb-56259366c958)
![Screenshot 2024-12-05 143932](https://github.com/user-attachments/assets/bf9efcf6-0fb9-4277-8ce6-db9db63dd4c1)
![Screenshot 2024-12-05 143914](https://github.com/user-attachments/assets/c431f4b0-29e5-4242-866d-a3e441e602d3)
![Screenshot 2024-12-05 143906](https://github.com/user-attachments/assets/ea5c9208-9260-4c5a-a081-8346e2ea798f)
![Screenshot 2024-12-05 143857](https://github.com/user-attachments/assets/40253607-8d54-427e-bbe6-f197643f7320)
![Screenshot 2024-12-05 143922](https://github.com/user-attachments/assets/40b5f8c4-8852-4756-97f3-217f39f922f5)




# RESULT
The program for implementing image maps using HTML is executed successfully.
