# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:
### Step 1:
Fork the repository to your github and clone it into a folder in github
### Step 2:
Then make sure that django is activated and then start a new django project
### Step 3:
Now create a folder called static and within that folder create a folder called html
### Step 4:
Now create a file called map.html in that folder
### Step 5:
Now open google maps and take a screenshot of your hometown
### Step 6:
Now open "imagemap.org" and upload your image there and generate image maps of that using the rectangular or circle tool
### Step 7:
Now inside the html folder create the necessary html files that you've included in the href of the image maps
### Step 8:
Now push the folder and commit the changes in the github
## Code:
map.html
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
Wildcraft.html
```
<!DOCTYPE html>
<html>
<head>
    <title>
        Wildcraft
    </title>
</head>
<body>
    <br><br><br>
   <center> <img src="wildcraft-india-pvt-ltd-lindsay-street-kolkata-6eax0.avif" width="500px" height="400px"></center>
    <h3 style="font-size: 2rem; font-family: Arial; text-align: justify; font-weight: 100;">Wildcraft is India's premier head-to-toe products manufacturer and distributor,
for all trek-to-travel solutions.Wildcraft is a renowned outdoor gear brand, originating from Bangalore, India, and has emerged as a leading name in the adventure equipment
 industry. Since its establishment in the early 1990s, Wildcraft has been dedicated to crafting high-quality products tailored for outdoor enthusiasts. The brand's diverse
range includes backpacks, tents, jackets, footwear, and accessories, all designed with a keen focus on durability, functionality, and style. With a commitment to innovation,
Wildcraft continually integrates the latest technology and eco-friendly materials into its products. The brand actively engages with the outdoor community through events and
workshops, fostering a sense of camaraderie. Notably, Wildcraft embraces sustainability and social responsibility, contributing to environmental conservation and community
development. With a robust retail presence and a strong online platform, Wildcraft provides global access to reliable and adventure-ready gear, making it a preferred choice
for those seeking quality outdoor equipment.
    </h3>
</body>
</html>
```
Phoenix Marketcity.html
```
<!DOCTYPE html>
<html>
<head>
    <title>
        PhoenixMarketCity
    </title>
</head>
<body>
    <br><br><br>
   <center> <img src="/home/sec/myproj/fwad/ex04/places-around-me/Phoenix-MArket-City.jpg" width="432px" height="273px"></center>
    <h1 style="font-size: 2rem; font-family: Arial; text-align: justify; font-weight: 100;">Phoenix Market City in Velachery, Chennai, is a bustling and vibrant shopping and entertainment destination that epitomizes modern retail and lifestyle experiences. 
        Spread across acres of space, this sprawling mall houses an extensive array of national and international brands, catering to diverse tastes and preferences. With its contemporary architecture and upscale ambiance, Phoenix Market City Velachery offers
 a luxurious and enjoyable shopping atmosphere. Beyond retail therapy,the mall boasts a diverse culinary landscape, featuring a wide range of restaurants, cafes, and food courts serving delectable cuisines from around the world. Entertainment options abound, 
 including a state-of-the-art multiplex cinema and engaging recreational activities, making it a go-to destination for families and individuals alike. The mall's strategic location in Velachery, a bustling suburb of Chennai, enhances its accessibility and 
 popularity, solidifying Phoenix Market City as a premier lifestyle and entertainment hub in the city.
        </h1>
</body>
</html>

```
Starbucks.html
```
<!DOCTYPE html>
<html>
<head>
    <title>
        Starbucks
    </title>
</head>
<body>
    <br><br><br>
   <center> <img src="/home/sec/myproj/fwad/ex04/places-around-me/starbucks.jpeg" width="500px" height="400px"></center>
    <h1 style="font-size: 2rem; font-family: Arial; text-align: justify; font-weight: 100;">Starbucks is an American company that operates the largest coffeehouse chain
and one of the most recognizable brands in the world.Starbucks in Velachery, Chennai, is a welcoming haven for coffee enthusiasts and a social hub for individuals seeking
 a cozy and contemporary ambiance. Situated in the bustling Phoenix Market City, this Starbucks outlet provides a retreat for patrons to indulge in a diverse range of
meticulously crafted coffee beverages. The interior is adorned with the iconic Starbucks aesthetic – a blend of modern design and warm tones, creating a comfortable
space for both work and leisure. The aroma of freshly brewed coffee fills the air as customers savor their favorite brews, from classic espressos to signature lattes.
The friendly and skilled baristas ensure a personalized experience, while the cozy seating arrangements make it an ideal spot for casual meetings or solo relaxation.
 Starbucks Velachery has seamlessly integrated into the fabric of the shopping and entertainment experience at Phoenix Market City, making it a popular choice for those
seeking a delightful coffee break in the heart of Chennai.
    </h1>
</body>
</html>

```
WowMomo.html
```
<!DOCTYPE html>
<html>
<head>
    <title>
        WowMomo
    </title>
</head>
<body>
    <br><br><br>
    <center> <img src="/home/sec/myproj/fwad/ex04/places-around-me/wowmomo.jpg" width="500px" height="400px"></center>
    <h1 style="font-size: 2rem; font-family: Arial; text-align: justify; font-weight: 100;">WowMomo is an Indian chain of fast food restaurants that specializes in momos,
 momo-filled burgers (MoBurgs) and momo-based desserts. Wow! Momo is a popular and innovative fast-food chain that has gained prominence for its delicious and diverse
offerings of momos. Originating in Kolkata, India, Wow! Momo has expanded its presence across the country, delighting food lovers with its unique take on the traditional
Tibetan dumpling. The menu features an extensive range of momo fillings, including classic options like chicken and vegetarian, as well as creative variations like chocolate
and paneer. The brand's success lies not only in its diverse flavors but also in its contemporary and vibrant ambiance, creating a welcoming space for customers.
Wow! Momo's commitment to quality ingredients, quick service, and an ever-evolving menu has made it a go-to destination for those seeking a delightful and flavorful
momo experience in a casual and modern setting.
    </h1>
</body>
</html>

```
GlobalDesi.html
```
<!DOCTYPE html>
<html>
<head>
    <title>
        GlobalDesi
    </title>
</head>
<body>
    <br><br><br>
    <center> <img src="/home/sec/myproj/fwad/ex04/places-around-me/global desi.jpg" width="500px" height="400px"></center>
    <h2 style="font-size: 2rem; font-family: Arial; text-align: justify; font-weight: 100;">
        Global Desi is the ultimate fashion destination for the modern woman who is always on the lookout for exquisitely crafted ladies wear online. Today, modern fashion
is all about the beautiful amalgamation of diverse styles and cultures—we strive to integrate different cultures through vibrant prints & colours in our ladies fashion wear
 just for you to stay on trend. We bring to you fusion fashion with women apparel in distinct styles that adds loads of appeal to your look andalso lets you stand out from
the crowd. At Global Desi stores, you’ll find a variety of women’s clothing online. From dresses to designer suits, Indian wear for women to western summer clothes, we have
it all for you. Not to forget our stylish ladies accessories that complement your outfit—ladies bags, sunglasses, stoles, designer earrings, and footwear. At Global Desi,
you experience true variety in fashion. Say goodbye to your old wardrobe and embrace the power of fusion in style.
        
          </h2>
</body>
</html>
```

## Output:
#### map.html
![Screenshot from 2023-12-24 16-54-05](https://github.com/SaravananPV3010/places-around-me/assets/139754526/95fd0175-90bb-4363-b193-d31d8358f4fa)
#### Wildcreaft.html
![Screenshot from 2023-12-24 16-57-44](https://github.com/SaravananPV3010/places-around-me/assets/139754526/5b1eaf4c-3c1f-4a98-9fe8-69d731ecf804)
#### PhoenixMarketcity.html
![image](https://github.com/SaravananPV3010/places-around-me/assets/139754526/75127fed-3aa2-4493-92b6-0f91a58d2863)
#### Starbucks.html
![Screenshot from 2023-12-24 17-00-15](https://github.com/SaravananPV3010/places-around-me/assets/139754526/f1f055d2-b1b9-47b3-a2d5-52478cd18092)
#### WowMomo.html
![Screenshot from 2023-12-24 17-01-07](https://github.com/SaravananPV3010/places-around-me/assets/139754526/b93cf2f4-96bd-42b8-b2dc-57b713b7de4b)
#### GlobalDesi.html
![Screenshot from 2023-12-24 17-02-09](https://github.com/SaravananPV3010/places-around-me/assets/139754526/c4edbbe8-5734-416b-a0b8-f045f9744489)







## Result:
Image maps have been sucessfully developed
