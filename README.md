# Ex04 Places Around Me
## Date: 18.10.2025

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

<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <center>
        <h1 >
        <font color="purple" >GUDUVANCHERRY</font>
        </h1>
        <h3 > <font color ="black" > Mageshwaran T A</font></h3>

            <img src="map.png" usemap="#MyCity" height ='610' width="1450">
            <map name="MyCity">
                <area shape="rect" coords="909,562,1084,644" href="home.html" title="MY HOME">
                <area shape="rect" coords="600,12,900,20" href="theatre.html" title="Vekateswara theatre ">
                <area shape="rect" coords="600,400,1000,50" href="med.html" title="MT med">
                <area shape="rect" coords="600,40,1073,181" href="Star.html" title="Star king chicken fries">
                <area shape="rect" coords="223,392,456,455" href="motel.html" title="The Premium Chennai">       
            </map>
        </center>
    </body>
</html

home.html
<!DOCTYPE html>
<html>
<head>
    <title>My Home</title>
    <style>
        body {
            background-color:rgb(33, 99, 132);
            color: white;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            text-align: center;
        }
        h2 {
            margin: 10px;
        }
        hr {
            color: white;
        }
    </style>
</head>
<body>
    <h2>MY HOME</h2>
    <h2>A PLACE OF LOVE AND COMFORT</h2>
    <hr>
    <p>
        My home is located in GUDUVANCHERRY, Chengalpattu a peaceful neighborhood filled with greenery and friendly people.
    </p>
    <p>
        Our house has a cozy living room, a bright kitchen, two bedrooms, and a small garden where we grow flowers and vegetables. 
    </p>
    <p>
        In the evenings, we often sit outside to enjoy the fresh air and talk with our neighbors.
    </p>
    <p>
        My home is close to schools, parks, and shops. What makes it truly special is the love and togetherness shared by everyone in the family.
    </p>
    <p>
        What makes it truly special is the love and togetherness shared by everyone in the family.
    
    </p>
</body>
</html>

theatre.html
<!DOCTYPE html>
<html>
<head>
    <title>Sri Venkateswara</title>
    <style>
        body {
            background-color: rgb(33, 99, 132);
            color: white;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            text-align: center;
        }
        h2 {
            margin: 10px;
        }
        hr {
            color: white;
        }
    </style>
</head>
<body>
    <h2>GUDUVANCHERRY</h2>
    <h2>Sri Venkateswara Theatre</h2>
    <hr>
    <p>
        Sri Venkateswara Theatre, located in Guduvanchery, Chennai, is a popular theatre known for offering an affordable and enjoyable movie-watching experience. 
    </p>
    <p>
        It features comfortable seating, digital sound systems, and a good selection of Tamil, Telugu, and Hindi films.
    </p>
    <p>
        The cinema is loved by local residents for its convenient location, reasonable ticket prices, and clean environment. 
    </p>
    <p>
        With regular showtimes and online booking options, it's a go-to spot for families and movie lovers in the neighborhood.
    </p>
    <p>
        Whether it's a weekend blockbuster or a casual weekday show, Sri Venkateswara Theatre delivers a great cinematic experience close to home.
    </p>
</body>
</html>

star.html
<!DOCTYPE html>
<html>
<head>
    <title>Star King Chicken Fries</title>
    <style>
        body {
            background-color:rgb(33, 99, 132);
            color: white;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            text-align: center;
        }
        h2 {
            margin: 10px;
        }
        hr {
            color: white;
        }
    </style>
</head>
<body>
    <h2> GUDUVANCHERRY</h2>
    <h2>Star King Chicken Fries</h2>
    <hr>
    <p>
        Fast Food, Burger, Sandwich, Shake
12, Periyakulam Street, Nandhivaram, Guduvanchery, Chengalpat, GST Road, Chennai
    </p>
    <p>
       This restaurant is serving zesty fast food delicacies. It has a simple and elegant ambiance.
    </p>
    <p>
        The menu is affordable and offers a wide variety of fast food options. It is the perfect place to enjoy with friends and family.
    </p>
    <p>
        I just tried Star King Chicken Fries and they were awesome!<br>
         The chicken fries were crispy and flavorful, and the hint of lime that I added on top really enhanced the taste. Highly recommend them!
    </p>
</body>
</html>

med.html
<!DOCTYPE html>
<html>
<head>
    <title>MT.DERM Medical Products Private Limited</title>
    <style>
        body {
            background-color: rgb(33, 99, 132);
            color: white;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            text-align: center;
        }
        h2 {
            margin: 10px;
        }
        hr {
            color: white;
        }
    </style>
</head>
<body>
    <h2>GUDUVANCHERRY</h2>
    <h2> Mt Derm Medical Products Pvt Ltd </h2><br>

    <p>
        Manufacturer of Autoclave, Make UP Brushes, Make Up Kit , Laser Tattoo Removal Equipment and Salon, ...
    </p>
    <p>
        Mt Derm Medical Products Pvt Ltd in Guduvanchery, Chengalpattu is known 
        to satisfactorily cater to
         the demands of its customer base
        
    </p>
    <p>
        MT.DERM is the market leader for apparative cosmetics in the field of injecting substances into the skin
    </p>
    <p>
        Service Provider of Tattoo Needles, Makeup Brush & Hair Dryer from Chennai
    </p>
</body>
</html>

motel.html

<!DOCTYPE html>
<html>
<head>
    <title>GUDUVANCHERRY</title>
    <style>
        body {
            background-color: rgb(33, 99, 132);
            color: white;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            text-align: center;
        }
        h2 {
            margin: 10px;
        }
        hr {
            color: white;
        }
    </style>
</head>
<body>
    <h2>GUDUVANCHERRY</h2>
    <h2>The Premium Chennai </h2>
    <hr>
    <p>
        The Premium Chennai offers a modern retreat close to SRM University - Kattankulathur Campus.
    <p>
        With laundry facilities, enjoy the convenience of a restaurant and stay connected with in-room WiFi. The 24-hour front desk is always available.
    </p>
    <p>
        It include rooms with direct access to a parking lot, making it convenient for motorists.
    </p>
    <p>
        Located conveniently near SRM University - Kattankulathur Campus.Rooms typically feature basic amenities, a private bathroom , and are accessible directly from the outside.
    </p>
</body>
</html>


```

## OUTPUT

![alt text](madhu/mapapp/static/map.png)

![alt text](<Screenshot 2025-10-18 112721.png>)

![alt text](<Screenshot 2025-10-18 112741.png>)

![alt text](<Screenshot 2025-10-18 112808.png>)

![alt text](<Screenshot 2025-10-18 112836.png>)

![alt text](<Screenshot 2025-10-18 113322.png>)



## RESULT
The program for implementing image maps using HTML is executed successfully.
