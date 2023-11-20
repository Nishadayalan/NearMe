# Ex04 Places Around Me
## Date: 18.11.2023

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
<h1 align ="center">
<font color="green"><b>NEYVELI</b></font>
</h1>
<h2 align="center">
<font color="maroon"><b>NISHA.D(23012927)</b></font>       
</h2>
<center>
<img src="map.png" usemap="#MyCity" height="600" width="1400">
<map name="MyCity">
<area shape="circle" coords="960,470,70" href="home.html" title="My Home Town">
<area shape="circle" coords="650,500,80" href="mine.html" title="Mine-II">
<area shape="circle" coords="920,150,70" href="airport.html" title="Neyveli Airport">
<area shape="circle" coords="700,70,70" href="college.html" title="Jawahar Science College">
<area shape="circle" coords="1000,300,70" href="vadalur.html" title="Vadalur">
</map>
</center>
</body>
</html>

home.html
<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="blue"><b>NEYVELI</b></font>
</h1>
<h2 align="center">
<font color="red"><b>SEPLANATHAM(Mettukupam)</b></font>
</h2>
<hr size="6" color="cyan">
<p align="justify">
<font face="Comic Sans MS" size="5">
Neyveli is located in virudhachalam taluk in cuddalore districtin Tamil Nadu. Near neyveli there is a small village named 
seplanatha(south) that is my home town. It is a village in kammapuram block in cuddalore district of Tamil nadu state,India. 
It is located 50 km towards west from district headquarters cuddalore. Seplanatham(south) is surrounded by neyveli block towards north,virudhachalam
block towards west, keerapalayam block towards east, melbhuvanagiri block towards east. Jayapriya theatre and mahalakshmi palace
are the nearby theatre to seplanatham. Jawahar Science College and Vivekananda polytechnic College are the colleges in seplanatham. Thermal Power
plant(neyveli) is located near seplanatham. From there electricity is provided to some other ststews like Andhra pradesh. I like my village more than any another
place.
</font>
</p>
</body>
</html>

airport.html
<html>
<head>
<title>Airport</title>
</head>
<body bgcolor="cyan">
<h1 align="center">
<font color="green"><b>NEYVELI AIRPORT</b></font>
</h1>
<h2 align="center">
<font color="red"><b>VONY</b></font>
</h2>
<hr size="6" color="black">
<p align="justify">
<font face="Gabriola" size="6">
Neyveli Airport(IATA:NVY,ICAO:VONY) is located in neyveli,Tamil Nadu,India. The airport is owned by the neyveli lignite corporation(NLC)
and is located at National Highway 45C,adjacent to the NLC township . The airport is spread over 220 acres and has a 3000 
square meter apart suitable for onr ATR-72 sized aircraft . Vayudoot used to operate flights to chennai airport with their 
donrnier do 228-100 from here in the NVY, and the administration responsible to manage it is called airports authority of India,
also recognized as AAI,A hint that neyveli may soon be commisioned came when minister of state for civil aviation, Hardeep singh puri,
said in response to a question parliament that airlines have bid for routes from neyveli.
</font>
</p>
</body>
</html>

vadalur.html
<html>
<head>
<title>vadalur</title>
</head>
<body bgcolor="green">
<h1 align="center">
<font color="Blue"><b>VADALUR</b></font>
</h1>
<h2 align="center">
<font color=""><b>Nearest place to my home town</b></font>
</h2>
<hr size="6" color="cyan">
<p align="justify">
<font face="Times New Roman" size="5">
Vadalur is a town and 2nd grade municipality in cuddalore district,Tamil Nadu. It is 208 km (129mi) from chennai. It is famous 
for satya gnana sabhan, is a major tourist and spiritual center in vadalur. Satya gnana sabha (temple of wisdom is a temple 
constructed (25.01.1872) by the saint sri raamalinga swaamigal(vallalar)). vadalur is also home for iyyan lake and sacred heart church.
The NLC mines can be seen from the observation site in the kattukolai area of vadalur. S.D.Eaden,S.D.Sion,Saint Fathima are
the schools located in vadalur. It consists of many marriage mahals like mangaiyarkarasi mahal,dhanalakshmi srinivasan mahal and etc. Many 
super markets are the like National,royal,radha super markets. Nearby vadalur trends,unlimited,max,hots trends are there. nearest banks 
SBI,canara,karur vysya and CUB banks. Many famous temples are located near vadalur.
</font>
</p>
</body>
</html>

college.html
<html>
<head>
<title>college</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="blue"><b>JAWAHAR SCIENCE COLLEGE</b></font>
</h1>
<h2 align="center">
<font color="black"><b>Township(block21)</b></font>
</h2>
<hr size="6" color="green">
<p align="justify">
<font face="Times New Roman" size="5">
Jawahar Science College is a co-educational institution strated under the care of the jawahar education society. The college 
is affiliated with Thiruvalluvar university. It is established in 1997 and a renowned institution of higher learnings located near 
neyveli, Tamil nadu. Institute offers 15 courses which are degree in full time mode. Overall ,institute enjoys a good reputation
for courses like BBA,B.A.,BCA,B.Com,B.Sc,MSW,M.Com,M.Sc,M.A. in the streams of business & management studies,Humanities & social
sciences ,IT & software,Accounting & Commerce and Science students can opt courses from those. Over the period ,Jawahar Science
College has gained expertize through its trained and experienced faculty in the field of Engliush,Chemistry,Computer Science,
Geology,Mathematics,Physics. Institute has a well supported campus with facilities like auditorium,cafeteria,Gym,Hostel,Library,
labs,hospital/medical,sports complex,Wi-fi campus.
</font>
</p>
</body>
</html>

mine.html
<html>
<head>
<title>Mine-II</title>
</head>
<body bgcolor="teal">
<h1 align="center">
<font color="magenta"><b>MINE-II</b></font>
</h1>
<h2 align="center">
<font color="maroon"><b>Neyveli Lignite Corporation</b></font>
</h2>
<hr size="6" color="black">
<p align="justify">
<font face="Tahoma" size="6">
In February , 1978 Government of India scantioned the second Lignite Mine of capacity 4.7 milliontones of lignite per annum and 
in February '83, Government of india sacntioned the expansion of Second Mine of capacity from 4.7 MT to 10.5 million tones. The ligniteseam in Mine-II was first exposed
in september 1984 and the excavation of lignite commenced in march,1985. mine-II expansion project was completed on 12th march 2010.
The lignite excavated from mine-II meets the fuel requirements of Thermal Power Station-II and Thermal Power station-II expansion
under implementation. The mine is located in a predominantly monsoonic and cyclonic area. It is located in neyveli(township).
</font>
</p>
</body>
</html>
```


## OUTPUT
![Alt text](<Screenshot (52).png>)
![Alt text](<Screenshot (47).png>)
![Alt text](<Screenshot (50).png>)
![Alt text](<Screenshot (49).png>)
![Alt text](<Screenshot (51).png>)
![Alt text](<Screenshot (48).png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
