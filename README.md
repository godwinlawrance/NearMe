# Ex04 Places Around Me
## Date: 

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
<h1 align="center">
<font color="red"><b>Chembarabakkam</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Godwin Lawrance L (25015487)</b></font>
</h3>
<center>
<img src="map.jpeg" usemap="#MyCity" >
<map name="MyCity">
<area shape="rect" coords="778,498,625,348" href="home.html" title="MY INSTITUTION">
<area shape="rect" coords="773,169,915,293" href="SEC.html" title="SAVEETHA ENGINNERING COLLEGE">
<area shape="rect" coords="584,484,782,565" href="MEDICAL.html" title="SAVEETHA MEDICAL COLLEGE">
<area shape="rect" coords="652,618,817,682" href="TEMPLE.html" title="BALAMURUGAN TEMPLE">
<area shape="rect" coords="1263,113,1473,220" href="QUEENSLAND.html" title="QUEENSLAND AMUSEMENT PARK">
</map>
</center>
</body>
</html>

home.html

<html>
<head>
<title>MY INSTITUTION</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>THANDALAM</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>SAVEETHA INSTITUTION</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Saveetha Institute of Medical and Technical Sciences (SIMATS), formerly known as Saveetha University, is a private deemed-to-be university located at Poonamallee and 
Thandalam in Chennai, Tamil Nadu. It originated from Saveetha Dental College started in 1988 and was granted deemed university status in 2005 under the Saveetha Medical 
and Educational Trust. The institution now comprises multiple disciplines, including medicine, dentistry, engineering, law, management, nursing, physiotherapy, pharmacy, 
liberal arts and allied health sciences. The university has NAAC A++ accreditation, UGC approval and a large multi-campus setup spread over roughly 180 to 245 acres with 
thousands of students and staff. SIMATS is recognised nationally and internationally for strong clinical exposure, high research output, numerous patents and awards, and 
good rankings in areas like dentistry and medical education.
</font>
</p>
</body>
</html>

SEC.html

<html>
<head>
<title>MY INSTITUTION</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>THANDALAM</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>SAVEETHA ENGINNERING COLLEGE(AUTONOMOUS)</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Saveetha Engineering College is an autonomous institution located at Thandalam on the Chennai to Bengaluru highway, 
affiliated to Anna University and approved by AICTE. It was established in 2001 by the Saveetha Medical and Educational Trust 
and is accredited with an A grade by NAAC. The college offers multiple undergraduate and postgraduate programmes in 
engineering and management, including popular B.E./B.Tech and MBA courses. The campus spans about 120 acres with modern infrastructure 
such as well-equipped laboratories, libraries, hostels, sports facilities and WiFi-enabled classrooms. 
The institution also has strong placement training and records, with many students placed in reputed companies and 
high salary packages reported in recent years.
</font>
</p>
</body>
</html>

MEDICAL.html

<html>
<head>
<title>MY INSTITUTION</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>THANDALAM</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>SAVEETHA MEDICAL COLLEGE</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Saveetha Medical College and Hospital is a private deemed medical institution established in 2008 at Kanchipuram near Chennai, 
affiliated to Saveetha Institute of Medical and Technical Sciences and approved by the National Medical Commission. 
It offers a wide range of undergraduate, postgraduate, superspeciality and doctoral programs in medicine and allied health sciences. 
The campus spans about 68 acres and includes extensive infrastructure such as teaching blocks, hostels, sports facilities and 
a large central library. The attached teaching hospital has more than 1700 beds with advanced facilities, providing students with
strong clinical exposure and serving a high volume of patients daily. The college emphasizes research and innovation and 
has gained national recognition through rankings, international accreditations and notable achievements in areas like robotic surgery 
and medical education technology.
</font>
</p>
</body>
</html>

TEMPLE.html

<html>
<head>
<title>MY INSTITUTION</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>THANDALAM</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>ARULMIGU BALAMURUGAN TEMPLE</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Arulmigu Bala Murugan Temple inside Saveetha campus is a prominent shrine dedicated to Lord Muruga, located at Thandalam within 
the Saveetha Medical College and University premises near Chennai. The temple is famous for its towering 40 foot monolithic granite statue
of Bala Murugan, weighing around 150 tonnes and regarded as one of the tallest stone Murugan icons in the world. The idol stands on a 
star shaped pedestal (shatkona) with a meditation hall beneath, symbolising peace and spiritual elevation for devotees and students. 
The temple complex is artistically laid out, and from above it is designed to resemble the sacred syllable Om, adding deeper 
spiritual significance to the site. Situated just off the Chennai to Bengaluru highway, it has also become a popular devotional and 
tourist attraction for visitors from Chennai and beyond.
</font>
</p>
</body>
</html>

QUEENSLAND.html

<html>
<head>
<title>MY INSTITUTION</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>THANDALAM</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>QUEENSLAND AMUSEMENT PARK</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Queensland is a large amusement and water park located on the Chennai to Bengaluru Highway near Poonamallee on the outskirts of Chennai. 
It spreads over about 70 acres and features around 51 rides, including major roller coasters, water slides and family attractions. 
The park is known for its affordable entry fee for a full day of unlimited rides, making it popular with school and college groups. 
Facilities such as food courts, parking, lockers and changing rooms are available to make day trips comfortable. With greenery, 
a big lake and a mix of dry and water rides, it is a favourite weekend getaway spot for people of all ages from Chennai and nearby areas.
</font>
</p>
</body>
</html>

```


## OUTPUT




<img width="1915" height="803" alt="Screenshot 2025-12-15 111620" src="https://github.com/user-attachments/assets/ba8f3de5-1e8e-43a6-9047-7073d7619424" />
<img width="1919" height="813" alt="Screenshot 2025-12-15 111557" src="https://github.com/user-attachments/assets/7ba275c6-7ccd-4282-92e5-8daa23511b75" />
<img width="1920" height="802" alt="Screenshot 2025-12-15 111541" src="https://github.com/user-attachments/assets/89e6f0e8-6f85-4b61-9726-da08bbd02345" />
<img width="1722" height="849" alt="Screenshot 2025-12-15 111520" src="https://github.com/user-attachments/assets/14335401-b61d-459c-a7ae-9ecd49f3e0b8" />





## RESULT
The program for implementing image maps using HTML is executed successfully.
