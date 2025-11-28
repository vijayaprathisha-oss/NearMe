# Ex03 Places Around Me
## Date:28.11.2025 

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google as an image.

### STEP 3
Insert the image using ```<img>``` tag and link it to the map.

### STEP 4
Using ```<map>``` tag name the map.

### STEP 5
Create clickable regions in the image using ```<area>``` tag.

### STEP 6
Write HTML programs for all the regions identified.

### STEP 7
Execute the programs and publish them.

## CODE
```
map.html

<html>
    <head>
        <title>IMAGE MAPPING</title>
    </head>
    <body bgcolor="lightgreen">
        <h1 align="center">PONDICHERRY</h1>
        <h2 align="center">VIJAYAPRATHISHA J (25008497)</h2>
        <img src="Screenshot 2025-11-26 113627.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="ROCK BEACH" title="ROCK BEACH" href="rock.html" coords="1686,335,1498,413" shape="rect">
    <area target="" alt="PERUMAL TEMPLE" title="PERUMAL TEMPLE" href="temple.html" coords="1456,81,80" shape="circle">
    <area target="" alt="BOTANICAL GARDEN" title="BOTANICAL GARDEN" href="garden.html" coords="968,613,1137,529" shape="rect">
    <area target="" alt="TRAIN STATION" title="TRAIN STATION" href="station.html" coords="1218,791,79" shape="circle">
    <area target="" alt="LOTUS BAY VIEW HOTEL" title="LOTUS BAY VIEW HOTEL" href="hotel.html" coords="1544,676,1684,571,1686,783" shape="poly">
</map>
    </body>
</html>

rock.html

<html>
    <head>
        <title>rock.html.site</title>
    </head>
    <body bgcolor="cyan">
        <h1 align="center">PONDICHERRY</h1>
        <h2 align="center">ROCK BEACH</h2>
        <hr>
        <h3>DESCRIPTION</h3>
        <p>Rock Beach is a rocky coastline in Pondicherry, India, known for its scenic promenade, colonial-era buildings, and lively atmosphere, especially in the evenings. It features a rocky shoreline with large boulders, a promenade ideal for walking and enjoying sunsets, and is bordered by French colonial architecture. Popular activities include strolling, photography, and observing street performers, while the site is also home to the French War Memorial and a Mahatma Gandhi statue.</p>
    </body>
</html>

temple.html

<html>
    <head>
        <title>temple.html.site</title>
    </head>
    <body bgcolor="pink">
        <h1 align="center">PONDICHERRY</h1>
        <h2 align="center">SRI VARADARAJA PERUMAL TEMPLE</h2>
        <hr>
        <h3>DESCRIPTION</h3>
        <p>Varadaraja Perumal Perundevi Thayar Temple in Puducherry, is dedicated to the Hindu god Vishnu and Hindu goddess Lakshmi. It is located heritage town region of the city. Constructed in the Dravidian style of architecture, the temple is a storehouse of Chola and Pandya architecture.</p>
    </body>
</html>

garden.html

html>
    <head>
        <title>temple.html.site</title>
    </head>
    <body bgcolor="pink">
        <h1 align="center">PONDICHERRY</h1>
        <h2 align="center">SRI VARADARAJA PERUMAL TEMPLE</h2>
        <hr>
        <h3>DESCRIPTION</h3>
        <p>The Botanical Garden in Pondicherry is a 22-acre public garden established in 1826, known for its diverse collection of over 1,500 plant species, including exotic, medicinal, and endangered flora. It features themed plots, a toy train, a small aquarium, and hosts an annual flower show. Recent renovations have enhanced its appeal as a recreational and educational site, making it a popular spot for families and nature enthusiasts.</p>
        
    </body>
</html>

station.html

<html>
    <head>
        <title>station.html.site</title>
    </head>
    <body bgcolor="red">
        <h1 align="center">PONDICHERRY</h1>
        <h2 align="center">TRAIN STATION</h2>
        <hr>
        <h3>DESCRIPTION</h3>
        <P>Puducherry Railway Station (PDY) is an Indian railway station in the Tiruchirappalli division of Southern Railway, serving as a key transportation hub for the city. It is an NSG–4 category station with platforms, a station building for services like ticket sales and waiting rooms, and tracks. The original railway line to connect the port of Pondicherry with South India was constructed in 1879.</P>
    </body>
</html>

hotel.html

<html>
    <head>
        <title>hotel.html.site</title>
    </head>
    <body bgcolor="green">
        <h1 align="center">PONDICHERRY</h1>
        <h2 align="center">LOTUS BAY VIEW HOTEL</h2>
        <hr>
        <h3>DESCRIPTION</h3>
        <P>Lotus Bay View Hotel is a hotel in Pondicherry situated very close to Rock Beach, offering sea views from some rooms and a convenient location for exploring the area. It provides various amenities, including air conditioning, room service, and laundry service, although some reviews indicate it does not have a spa or restaurant on-site. Parking is available nearby. </P>
    </body>
</html>
```

## OUTPUT
![alt text](<Screenshot (35).png>)

![alt text](<Screenshot (37).png>)

![alt text](<Screenshot (38).png>)

![alt text](<Screenshot (39).png>)

![alt text](<Screenshot (40).png>)

![alt text](<Screenshot (41).png>)
## RESULT
The program for implementing image maps using HTML is executed successfully.
