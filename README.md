# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:

### Step 1:
Open up a terminal in your preffered location, and start a django project using djang-admin startproject <your-project-name> Next setup an app inside the project folder using django-admin startapp <your-app-name>

### Step 2:
Once Created ,link your app to the project by adding it in the list of apps in settings.py file located inside the project folder. Add access to your host in allowed host setting and add static folders path to your settings.py file.

### Step 3:
Create a static folder and template folder and add all your required files for the project - Images .etc in your static folder. In the Template folder add your html files required for the pages.

### Step 4:
Head to the views.py in your app folder and create required functions to render a particular page or template when requested by the client. Next go to the urls.py and route the correct view functions to each particular request as needed.

### Step 5:
Next start the server from the projects main directory using python3 manage.py runserver 0:<portnumber>. Now the pages can be accessed from all the routed addresses in urls.py .

## CODE:
## map.html
```
<!DOCTYPE html>
<html>
    <head>
        <title>Imagemaps</title>
    </head>
    <body>
        <h4>My Locality</h4>
        <p style="text-align:center;">
        <img align= "\right"\ img src="my locality.png" usemap="#image_map">
        </p>
<map name="image_map">
  <area alt="Wildcraft" title="Wildcraft" href="Wildcraft.html" coords="50,47,34" shape="circle">
  <area alt="Phoenix Marketcity" title="Phoenix Marketcity" href="Phoenix Marketcity.html" coords="306,161,36" shape="circle">
  <area alt="StarBucks" title="StarBucks" href="StarBucks.html" coords="254,293,33" shape="circle">
  <area alt="WowMomo" title="WowMomo" href="WowMomo.html" coords="370,311,37" shape="circle">
  <area alt="GlobalDesi" title="GlobalDesi" href="GlobalDesi.html" coords="187,454,48" shape="circle">
</map>


    </body>
</html>
```
## GlobalDesi.html
```
<!DOCTYPE html>
<html>
<head>
    <title>
        GlobalDesi
    </title>
</head>
<body>
    <h1>It is a coveted fashion brand which is free-spirited, creative, open-minded, and avant-garde attitude. </h1>
</body>
</html>
```

## PhoenixMarketCity.html
```
<!DOCTYPE html>
<html>
<head>
    <title>
        PhoenixMarketCity
    </title>
</head>
<body>
    <h1>Phoenix Marketcity in Chennai is a prominent shopping and entertainment complex featuring a wide range of retail stores, dining options and entertainment activities. </h1>
</body>
</html>
```
## Starbucks.html
```
<!DOCTYPE html>
<html>
<head>
    <title>
        Starbucks
    </title>
</head>
<body>
    <h1>Starbucks is an American company that operates the largest coffeehouse chain and one of the most recognizable brands in the world.
    </h1>
</body>
</html>
```
## Wildcraft.html
```
<!DOCTYPE html>
<html>
<head>
    <title>
        Wildcraft
    </title>
</head>
<body>
    <h1>Wildcraft is India's premier head-to-toe products manufacturer and distributor, for all trek-to-travel solutions.
    </h1>
</body>
</html>
```
## WowMomo.html
```
<!DOCTYPE html>
<html>
<head>
    <title>
        WowMomo
    </title>
</head>
<body>
    <h1>WowMomo is an Indian chain of fast food restaurants that specializes in momos, momo-filled burgers (MoBurgs) and momo-based desserts. 
    </h1>
</body>
</html>
```
## OUTPUT:
## map.html
![Screenshot from 2023-12-12 10-35-54](https://github.com/gowriganeshns/places-around-me/assets/139754526/4e16bf72-553a-4149-823b-e5d92f572309)
## GlobalDesi.html



