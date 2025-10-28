# Ex04 Places Around Me
## Date: 23.10.2025

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

<!DOCTYPE html>
<html lang="en">
    <head>
    </head>
    <body>
      
<img src="MAP 2.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="nataraja temple" title="nataraja temple" href="temple.html" coords="851,468,1060,691" shape="rect">
    <area target="" alt="cafe" title="cafe" href="cafe.html" coords="1108,686,15" shape="circle">
    <area target="" alt="lake" title="lake" href="lake.html" coords="451,499,447,521,441,542,431,560,431,580,431,591,425,606,411,614,390,612,375,609,362,601,359,591,372,575,367,553,367,532,372,511,375,496,380,484,397,483,416,483,433,489" shape="poly">
    <area target="" alt="hotel" title="hotel" href="hotel.html" coords="1234,657,17" shape="circle">
    <area target="" alt="kaali temple" title="kaali temple" href="kaali.html" coords="1005,226,19" shape="circle">
</map>

    </body>
</html


cafe.html

<!DOCTYPE html>
<html>
    <BODY>
        It is famous cafe in our area
    </BODY>
</html>


lake.html

<!DOCTYPE html>
<html>
    <BODY>
        It is famous lake in our area
    </BODY>
</html>



kaali.html

<!DOCTYPE html>
<html>
    <BODY>
        It is famous kaali temple in our area
    </BODY>
</html>



hotel.html

<!DOCTYPE html>
<html>
    <BODY>
        It is famous hotel in our area
    </BODY>
</html>



temple.html

<!DOCTYPE html>
<html>
    <BODY>
        It is famous lord shiva temple in our area
    </BODY>
</html>


```

## OUTPUT

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6bc5d842-0e01-4097-9daf-5bd1a32f86f7" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/4085b209-0b3e-45e5-b1cc-22bfba67ba48" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/72325ecd-d700-4bb6-9f95-9be074f71c7b" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/38d60b07-85b5-4a88-b886-9ab887f2e0ad" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/9c9ff208-c251-4119-84d4-a28226e6caf4" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/622a67b8-1162-4a09-ae39-f4c8e3d5a1de" />

## RESULT
The program for implementing image maps using HTML is executed successfully.
