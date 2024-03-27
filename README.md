# Ex04 Places Around Me
## Date: 27.03.2024

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
Map.html
```
<!DOCTYPE html>
<head>
    <title>MY CITY</title>

</head>
<body>
<center>
<h2>
    <font color="voilet">virudachalam</font></h2>
        <h3><font color="green">kavi(212223220044)</font> </h3>
  
<img src="Screenshot 2024-03-19 112616.png" usemap="#MyCity" height="610" width="1450">
<map name="MyCity">
<area shape="circle" coords="300,150,50" href="bus.html" title="Bus stand">
<area shape="circle" coords="250,300,50" href="mob.html" title="poorvika mobiles">
<area shape="circle" coords="5,600,50" href="jel.html" title="jain jewels">
<area shape="circle" coords="600,500,50" href="school.html" title="gov school">
<area shape="circle" coords="1100,500,50" href="thaluk.html" title="taluk">


    </center>


</body>
</html>
```
mob.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    
    <title>MY CITY</title>

</head>

<body bgcolor="orange">
    <center>
        <h2> <font color="red">virudachalam</font></h2>
    <h1><font color="blue">poorvika</font></h1>  
</center>
<hr>
<p align="justify">"Poorvika is the Largest Tech Retailer in India, spanning across 460+ showrooms in and around Tamil Nadu, Karnataka, Pondicherry, Mumbai and Pune, famous for their touch & feel Live Demo experience before buying. Poorvika sells a wide category of devices in its showrooms and Online portal, ranging from the Best Smartphones, Laptops, Computers, Smart Devices, and Smart TVs to Accessories. Smartphone lovers await an enthralling experience at Poorvika. Having served over 5 Crore+ Happy Customers, Poorvika takes pride in being India's leading retailer for Top Brands like Apple, Samsung, Oppo, Vivo, Xiaomi, OnePlus, Redmi, Realme, Nokia, etc."</p> 
</body>
</html>
```
bus.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    
    <title>MY CITY</title>

</head>

<body bgcolor="blue">
    <center>
        <h2> <font color="red">virudachalam</font></h2>
    <h1><font color="yellow">bus stand</font></h1>  
</center>
<hr>
<p align="justify">"Vriddhachalam Junction railway station is located in Cuddalore district in the Indian state of Tamil Nadu and serves Virudhachalam. Vriddhachalam Junction railway station is situated 1½ km northwest of Virdhachalam Bus StandVriddhachalam Junction railway station is located in Cuddalore district in the Indian state of Tamil Nadu and serves Virudhachalam. Vriddhachalam Junction railway station is situated 1½ km northwest of Virdhachalam Bus Stand"</p> 
</body>
</html>
```
jel.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    
    <title>MY CITY</title>

</head>

<body bgcolor="grey">
    <center>
        <h2> <font color="red">virudachalam</font></h2>
    <h1><font color="yellow">jewels</font></h1>  
</center>
<hr>
<p align="justify">"The founders and promoters of Thangamayil Jewellery Limited have inherited the business from their late father Shri. Balusamy Chettiar who carried out the trade in the name of Balu Jewellery. From the time of its inception in 2000 as Thangamayil Jewellery Private Limited, the company grew exponentially to turn out as a public limited company in 2007. It released its equity shares in 2010 which were listed in Bombay Stock Exchange Limited(BSE) and National Stock Exchange Limited(NSE), Mumbai. TMJL takes pride in having 5072 shareholders, including mutual funds like SBI Magnum Balanced Fund.

    With 58 stores spread out in Tamil Nadu, as of today, the company envisages a bigger share in the competitive market segment among organized sectors through its operational stores, the strategy to attract customers through consistent efforts at improving brand recall and by providing the best available quality, service and exhibiting a great assortment of ornaments through these outlets."</p> 
</body>
</html>
```
school.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    
    <title>MY CITY</title>

</head>

<body bgcolor="blue">
    <center>
        <h2> <font color="red">virudachalam</font></h2>
    <h1><font color="yellow">school</font></h1>  
</center>
<hr>
<p align="justify">"🏫 Virudhachalam Government School Overview There are multiple government schools in Virudhachalam, Cuddalore district, Tamil Nadu, India. These schools offer primary and secondary education to students. 

    📚 Educational Programs Government schools in Virudhachalam follow the Tamil Nadu state board curriculum and offer subjects such as Tamil, English, Mathematics, Science, and Social Studies. They also provide extracurricular activities like sports and cultural events. 
    
    🏫 School Facilities The infrastructure and facilities of government schools in Virudhachalam vary depending on the specific school. Some schools have well-equipped classrooms, libraries, and playgrounds, while others may have limited resources."</p> 
</body>
</html>
```
taluk.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    
    <title>MY CITY</title>

</head>

<body bgcolor="blue">
    <center>
        <h2> <font color="red">virudachalam</font></h2>
    <h1><font color="yellow">thaluk</font></h1>  
</center>
<hr>
<p align="justify">"🏢 Virudhachalam Taluk Office Overview The Virudhachalam Taluk Office is a government office located in Virudhachalam, Cuddalore district, Tamil Nadu, India. It is responsible for the administration of the taluk, which includes revenue collection, land records maintenance, and other related services. 

    📞 Contact Information The Virudhachalam Taluk Office can be contacted by phone at 04143-238289 or by email at tsocud[dot]vridachalam[at]tn[dot]gov[dot]in. 
    
    🌐 Online Presence The Virudhachalam Taluk Office has a Facebook page where they post updates and announcements."</p> 
</body>
</html>
```
## OUTPUT
![WhatsApp Image 2024-03-27 at 09 14 19_f5ab7d09](https://github.com/Kavi45-msk/NearMe/assets/147457752/1532f428-41bc-4283-ba72-c231c0af4910)
![WhatsApp Image 2024-03-27 at 09 45 06_2f2199c5](https://github.com/Kavi45-msk/NearMe/assets/147457752/45dacd5e-e8e1-461c-8538-9bedc19c7002)
![WhatsApp Image 2024-03-27 at 09 45 12_b44d6141](https://github.com/Kavi45-msk/NearMe/assets/147457752/a2240129-0133-4bbd-b761-6283a9138117)
![WhatsApp Image 2024-03-27 at 09 45 06_7e7d2c67](https://github.com/Kavi45-msk/NearMe/assets/147457752/bba36567-7e4d-45a6-887d-a1810712283e)
![WhatsApp Image 2024-03-27 at 09 45 06_8fe68459](https://github.com/Kavi45-msk/NearMe/assets/147457752/190f8b79-d23f-440c-ab9b-6a1c53d7dfe4)
![WhatsApp Image 2024-03-27 at 09 45 09_f7ba543a](https://github.com/Kavi45-msk/NearMe/assets/147457752/9f3e5f67-59eb-44af-b2a1-6a34eacfb2f8)


## RESULT
The program for implementing image maps using HTML is executed successfully.
