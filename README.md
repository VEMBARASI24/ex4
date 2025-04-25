# Ex04 Places Around Me
## Date: 26.04.2025
## Name:Vembarasi.A.R
## Register number:212224220120

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
        <title>MY CITY</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>CHENNAI</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b> VEMBARASI A.R (212224220120)</b></font>
        </h3>
        <center>
            <img src="map.pnj" usemap="#MYCITY" height="610" width="1450">
            <map name="MYCITY">
                <area target="_parent" alt="MARINA" title="MARINA" href="marina.html" coords="1328,260,113" shape="circle">
                <area target="_parent" alt="KAPALEESWARAR TEMPLE" title="KAPALEESWARAR TEMPLE" href="temple.html" coords="1004,391,40" shape="circle">
                <area target="_parent" alt="FORT ST. GEORGE" title="FORT ST. GEORGE" href="fort.html" coords="1023,460,90" shape="circle">
                <area target="_parent" alt="GUINDY NATIONAL PARK" title="GUINDY NATIONAL PARK" href="guindy.html" coords="867,190,1290,289" shape="rect">
</map>
        </center>
    </body>
</html>

marina.html

<html>
<head>
<title>CHENNAI</title>
</head>
<body bgcolor="lightblue">
<h1 align="center">
<font color="navy"><b>MARINA BEACH</b></font>
</h1>
<h3 align="center">
<font color="darkblue"><b>MARINA</b></font>
</h3>
<hr size="3" color="blue">
<p align="justify">
<font face="Arial" size="5">
Marina Beach, stretching along the Bay of Bengal, is the longest natural urban beach in India, extending over 13 kilometers. Located in Chennai, it is one of the most popular tourist attractions in Tamil Nadu. The beach is famous not only for its scenic sunrise views and breezy evenings but also for its historical significance. Statues of prominent Tamil personalities such as Mahatma Gandhi, Thiruvalluvar, and Annie Besant adorn the promenade. Street food vendors line the shore, offering traditional snacks like sundal and murukku. The beach also serves as a social and recreational hub, often crowded with families, joggers, and street performers. In recent years, efforts have been made to clean and preserve this iconic stretch of coastline.
</font>
</p>
</body>
</html>

temple.html

<html>
<head>
<title>CHENNAI</title>
</head>
<body bgcolor="lavender">
<h1 align="center">
<font color="purple"><b>KAPALEESWARAR TEMPLE</b></font>
</h1>
<h3 align="center">
<font color="indigo"><b>MYLAPORE</b></font>
</h3>
<hr size="3" color="violet">
<p align="justify">
<font face="Tahoma" size="5">
Kapaleeswarar Temple is a grand example of Dravidian architecture and one of the oldest temples in Chennai. Located in Mylapore, this temple is dedicated to Lord Shiva, worshipped here as Kapaleeswarar, and Goddess Parvati as Karpagambal. The temple's tall gopuram (tower), intricately carved pillars, and vibrant sculptures attract thousands of devotees and tourists. It is believed to have been originally built in the 7th century by the Pallavas and later rebuilt by the Vijayanagar kings. The temple plays a central role during the Panguni Peruvizha festival celebrated in March-April, where a grand procession takes place through the streets of Mylapore. Surrounding the temple are markets and traditional streets, adding to its rich cultural vibe.
</font>
</p>
</body>
</html>

fort.html

<html>
<head>
<title>CHENNAI</title>
</head>
<body bgcolor="linen">
<h1 align="center">
<font color="maroon"><b>FORT ST. GEORGE</b></font>
</h1>
<h3 align="center">
<font color="brown"><b>HISTORICAL MONUMENT</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Verdana" size="5">
Fort St. George was established in 1644 by the British East India Company and marked the beginning of Chennai as a modern city. It served as the base of British military operations and trade activities in southern India. The fort complex houses the St. Mary's Church, one of the oldest surviving churches built by the British in India, and the Fort Museum which showcases artifacts, paintings, coins, and weapons from the colonial era. The architecture of the fort reflects classic British design with strong walls and strategic placements. Today, the fort serves as the administrative office for the Tamil Nadu Legislative Assembly and the Secretariat. Fort St. George is a testament to the colonial past and its impact on the region’s development.
</font>
</p>
</body>
</html>

guindy.html

<html>
<head>
<title>CHENNAI</title>
</head>
<body bgcolor="lightgreen">
<h1 align="center">
<font color="darkgreen"><b>GUINDY NATIONAL PARK</b></font>
</h1>
<h3 align="center">
<font color="forestgreen"><b>GUINDY</b></font>
</h3>
<hr size="3" color="green">
<p align="justify">
<font face="Courier New" size="5">
Guindy National Park is a rare gem, being one of the few national parks located within a city. Spanning about 2.7 square kilometers, the park is home to a variety of flora and fauna including blackbucks, spotted deer, jackals, and over 100 species of birds and butterflies. It was originally part of the Governor's estate during British rule and later declared a national park. Guindy Park also houses the Children's Park and the Snake Park, which are favorite spots for educational visits. The park plays a critical ecological role by preserving biodiversity in the midst of Chennai's urban sprawl. It offers a tranquil escape for nature enthusiasts and a place for environmental awareness.
</font>
</p>
</body>
</html>
```



## OUTPUT
![Screenshot 2025-04-25 205140](https://github.com/user-attachments/assets/79fbd164-0d78-40af-8a8b-6d6d216eaa5d)
![Screenshot 2025-04-26 002511](https://github.com/user-attachments/assets/968787c2-ae53-4c0c-8067-4298b80352b5)
![Screenshot 2025-04-26 005621](https://github.com/user-attachments/assets/bc6c7b30-8e84-4a4d-b39c-7dda902f143b)
![Screenshot 2025-04-26 005750](https://github.com/user-attachments/assets/745d2541-872b-42a3-b549-f3b3afebc31d)
![Screenshot 2025-04-26 005915](https://github.com/user-attachments/assets/d381a742-9e0f-4ba7-a751-c35322cc0bc2)












## RESULT
The program for implementing image maps using HTML is executed successfully.
