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
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <front colour="red"><b>Kallakurichi</b></front>
                </h1>
                <h3 align="center">
                    <front color="blue"><b>Mugunthan M (24005593)</b></front>
                </h3>
                <center>
                    <img src="C:\Users\admin\Pictures\Screenshots\map.png"usemap="#MyCity" height="610" width="1450">
                    <map name="MyCity">
                        <area shape="rect" coords="100,100,900,900" href="home.html" title="My Home Town">
                    </map>
                </center>
    </body>
</html>

```
# OUTPUT
![Screenshot 2024-12-04 224055](https://github.com/user-attachments/assets/aec00d9d-17a3-455b-9611-7f381a0b3d31)

# RESULT
The program for implementing image maps using HTML is executed successfully.
