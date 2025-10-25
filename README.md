# Ex04 Places Around Me
## Date: 24-10-2025
# NAME: JAGAN JP
# REG.NO: 212224230099
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
# AkmMap.html
```

<!DOCTYPE html>
<html>
<head>
<title>Arakkonam Map</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
<h2>Arakkonam Map</h2>
<p>Click any marked spot on the map to know about the place.</p>
<!-- Lock the image size -->
<img src="c:\Users\admin\Downloads\Akmmap.png" alt="Arakkonam Map" usemap="#map" width="1500" height="700" style="border:2px solid black;">

<map name="map">
   

 <area href="akmrailway.html" coords="700,100,737,51" shape="rect">
  <area shape="rect" coords="670,279,517,217" href="insrajali.html" alt="insrajali">
  <area shape="rect" coords="674,385,850,285" href="vgnschool.html" alt="VGN school">
  <area shape="rect" coords="299,448,127,273" href="mrf.html" alt="MRF Tyre factory">
  <area  href="vgnschool.html" coords="1211,298,1021,225" shape="rect">

 
</map>

</body>
</html>

```
# Akmrailway.html
```

<!DOCTYPE html>
<html>
<head>
    <title>akm railway</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
     <style>
    body {
        text-align: center; /* centers everything */
        font-family: Arial, sans-serif;
        margin: 50px;
    }
    img {
        width: 70%;      /* image takes 90% of screen width */
        max-width: 1200px; /* optional max width */
        height: auto;     /* keeps aspect ratio */
        border: 2px solid black;
    }
    p {
        margin-top: 20px;
        font-size: 18px;
    }
</style>
</head>
<body>
    <h2>Arakkonam Railwaystation</h2>
    <img src="c:\Users\admin\Downloads\akmrailway.png" alt="akm railwaystation">
    <p>
        Arakkonam Junction railway station is one of the largest railway junction in Tamil Nadu.
        It is also home to one of the largest and oldest railway workshops for Southern Railway, featuring vintage machinery.
    </p>
</body>
</html>

```
# insrajaliakm.html
```

<!DOCTYPE html>
<html>
<head>
    <title>INS RAJALI</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
    body {
        text-align: center; /* centers everything */
        font-family: Arial, sans-serif;
        margin: 50px;
    }
    img {
        width: 70%;      /* image takes 90% of screen width */
        max-width: 1200px; /* optional max width */
        height: auto;     /* keeps aspect ratio */
        border: 2px solid black;
    }
    p {
        margin-top: 20px;
        font-size: 18px;
    }
</style>
</head>
<body>
    <h2>INS Rajali Arakkonam</h2>
    <img src="c:\Users\admin\Downloads\ins rajali.png" alt="INS Rajali">
    <p>
        The INS Rajali runway is located at the Indian Naval Air Station near Arakkonam, Tamil Nadu, with the ICAO code VOAR. 
        It is a single runway, designated 06/24, that measures (13,460) feet (4,103) meters long and (155) feet (47) meters wide, making it one of the longest military runways in Asia. 
        It is constructed of asphalt and concrete and is equipped with lighting for night operations.  
    </p>
</body>
</html>

```
# vgnschool.html
```

<!DOCTYPE html>
<html>
<head>
    <title>VGN School</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            text-align: center; /* centers content */
            font-family: Arial, sans-serif;
            margin: 50px;
        }
        img {
            max-width: 80%; /* keeps image responsive */
            height: auto;
            border: 2px solid black;
        }
        p {
            margin-top: 20px;
            font-size: 18px;
        }
    </style>
</head>
<body>

    <h2>VGN School Arakkonam</h2>

    <!-- Image of the place -->
    <img src="c:\Users\admin\Downloads\vgn school.png" alt="VGN School">

    <!-- Description text -->
    <p>
        Dr. V. Genguswamy Naidu Matriculation Higher Secondary School (VGN School) is a co-educational institution in Arakkonam, established in 1985. 
        It offers classes from L.K.G. to XII standard and has a focus on creating a multicultural environment to foster students' self-esteem and social skills. 
        The school has modern facilities like smart classrooms, labs, and a large playground, and provides transportation through its own fleet of buses. 
    </p>

</body>
</html>

```
# mrftyre.html
```

<!DOCTYPE html>
<html>
<head>
    <title>MRF factory</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
     <style>
    body {
        text-align: center; /* centers everything */
        font-family: Arial, sans-serif;
        margin: 50px;
    }
    img {
        width: 70%;      /* image takes 90% of screen width */
        max-width: 1200px; /* optional max width */
        height: auto;     /* keeps aspect ratio */
        border: 2px solid black;
    }
    p {
        margin-top: 20px;
        font-size: 18px;
    }
</style>
</head>
<body>
    <h2>MRF Tyre Factory</h2>
    <img src="c:\Users\admin\Downloads\mrf akm.png" alt="MRF Tyre Factory">
    <p>
        The MRF Tyres factory in Arakkonam is a major tyre manufacturing plant located on the Tiruthani Road, established in 1972. 
        It is a large facility covering 125 acres, with a workforce of around 4,500 employees, and produces a high volume of tyres and tubes daily. 
        The plant manufactures a wide range of tyres and has received high employee ratings for its work environment. 
    </p>
</body>
</html>

```
## OUTPUT
# Arakkonam Map

<img width="1919" height="1141" alt="image" src="https://github.com/user-attachments/assets/bef4d5e9-31c2-4b89-9353-dab1129815d4" />

# Arakkonam Railwaystation

<img width="1909" height="1140" alt="image" src="https://github.com/user-attachments/assets/7d32b414-65f8-4189-94d5-b7066a113e5d" />

# INS Rajali AKM

<img width="1917" height="1135" alt="image" src="https://github.com/user-attachments/assets/7f3c16b3-3fb1-42df-99a5-30294342ddc2" />

# VGN School AKM

<img width="1919" height="1135" alt="image" src="https://github.com/user-attachments/assets/803c70cf-5c15-436b-be2e-c21f5b89958c" />

# MRF Factory AKM

<img width="1919" height="1143" alt="image" src="https://github.com/user-attachments/assets/759fd49c-3fa8-4c82-b933-23df3d2dee2c" />

## RESULT
The program for implementing image maps using HTML is executed successfully.
