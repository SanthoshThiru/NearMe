# Ex04 Places Around Me
## Date: 27-03-2024

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
MAP.HTML
<html>
    <head>
        <title>
            Erode
        </title>
    </head>
    <body>
        <h1 align="center">City of ERODE</h1>
        <h2 align="center">SANTHOSH.T (212223220100)</h2>
<img src="map1.png" usemap="#image-map" align="center">

<map name="image-map">
    <area target="" alt="Lotus Hospital- Emergency" title="Lotus Hospital- Emergency" href="lotus.htm" coords="746,623,896,720" shape="rect">
    <area target="" alt="Erode Train Junction " title="Erode Train Junction " href="erodejn.html" coords="338,451,506,530" shape="rect">
    <area target="" alt="Aanoor Dolby Atmos Theatre" title="Aanoor Dolby Atmos Theatre" href="aanoor.htm" coords="653,172,48" shape="circle">
    <area target="" alt="Kalaimaadu Statue" title="Kalaimaadu Statue" href="kaalaistatue.html" coords="589,304,26" shape="circle">
    <area target="" alt="Railway Colony " title="Railway Colony " href="railwaycolony.htm" coords="508,383,544,451,689,377,568,340" shape="poly">
</map>
    </body>
</html>

ERODEJN.HTML
<html>
    <head>
        <title>
            Erode Junction
        </title>
    </head>
    <body bgcolor="tomato">
        <h1 align="center">ERODE</h1>
        <h1 align="center">Erode Railway Station</h1>
        <hr color="white"  >
       <h3> <p align="center">
            <b>*</b> Standing tall since 1862, Erode Junction is the beating heart of Erode's transportation network.<br><b>*</b> This bustling hub, with its 22 tracks, seamlessly connects the city to various corners of India. <br><b>*</b> Not only is it a major junction on the Southern Railway zone, but it's also one of the few stations boasting both a diesel and an electric locomotive shed. <br>
       <b>*</b> This impressive facility houses hundreds of locomotives, keeping the wheels of progress turning. <br><b>*</b> Erode Junction is a testament to the city's rich railway heritage and a vital link for travelers and commerce.</p>
    </h3>
    </body>
</html>

RAILWAY COLONY.HTML
<html>
    <head>
        <title>
            Railway Colony
        </title>
    </head>
    <body bgcolor="aqua">

        <h1 align="center">ERODE</h1>
        <h1 align="center">Railway Colony</h1>
        <hr color="white"  >
<ul>
      <li>  <h3>Erode Railway Colony is a Locality in Erode City in Tamil Nadu State, India.
            Erode Railway Colony Pin code is 638002 and postal head office is Erode Railway Colony .
        </li>
        <li> Sidco Industrial Estate , Vinay Nagar , Nadarmedu , Lic Nagar , Jaganathapuram Colony are the nearby Localities to Erode Railway Colony.
             Erode , Periyasemur , Suriyampalayam , Bhavani are the nearby Cities to Erode.
           <br> </li>
           <p>
           <li> Demographics of Erode Railway Colony
            Tamil is the Local Language here.
            <br></li>
        <ol> <h3>Polling Stations /Booths near Erode Railway Colony:</h3>
           <li> 1)Sengundhar Community Hall Jaganathapuram-638009</li>
           <li> 2)St.reeta Elementary School Railwaycolony638002</li>
           <li> 3)St.reeta High School Railwaycolony638002</li>
           <li> 4)St.reeta Elementary School Railwaycolony638002</li>
           <li> 5)St.reeta Elementary School Railwaycolony638002</li>
        </ol>
            <li><p>
            HOW TO REACH Erode Railway Colony
            By Rail
            Erode Junction Rail Way Station , Cauvery Rail Way Station are the very nearby railway station to Erode Railway Colony.
           <br> 
            
            Govt Health Centers near Erode Railway Colony
            1) ERODE ORTHO CENTER , Old No.803, New No.384 , Evn Road , Near Railway Station
            2) ACCHUTHA EYE CARE , H-3 , Evn Road , Periyar Nagar
            3) LKM HOSPITAL , 61/1 , Mosuvanna Street , Kaikolar Thottam
           <br> </p></li>
            
           <li><p> Sub Localities in Erode Railway Colony
            Institute Road, Erode Railway ColonyBus Bay, Erode Railway ColonyErode-dharapuram Road, Erode Railway Colony1st Street, Erode Railway ColonyOuter Ring Road, Erode Railway ColonyErode-chennimalai Road, Erode Railway ColonyHospital Road 3, Erode Railway Colony5th Main Road, Erode Railway ColonyBhavani Avenue Road, Erode Railway ColonySixth Main Road, Erode Railway Colony1st Main, Erode Railway ColonyInner Ring Road, Erode Railway ColonySeventh Main Road, Erode Railway ColonyVinay Nagar, Erode Railway ColonyKalukadimedu, Erode Railway Colony
        </p></li>
          <li><p>     Bus Stops in Erode Railway Colony,Erode
            Surampatti Naal Roads Bus Stop
            EVN Rd; Periyar Nagar; Erode; Tamil Nadu 638001; India
            0.3 KM distance      Detail
            Erode Railway Station Bus Stop
            Erode-Chennimalai Rd; Periyar Nagar; Erode; Tamil Nadu 638001; India
            0.6 KM distance      Detail
            Jaganathapuram Colony Bus Stop
            Jaganathapuram Colony; Erode; Tamil Nadu 638001; India
            0.7 KM distance      Detail
            Erode Railway Station Bus Stop
            Bus Bay; Erode Railway Colony; Erode; Tamil Nadu 638002; India
            0.7 KM distance      Detail
        </p> </li>  
        </h3>
    </ul>
    </body>
</html>

KAALAI STATUE.HTML
<html>
    <head>
        <title>
            Kalaimaadu Silai
        </title>
    </head>
    <body bgcolor="skyblue">
         <h1 align="center">ERODE</h1>
        <h1 align="center">Kaalaimaadu Silai</h1>
        <hr color="white" >
        <img src="bullandman.jpg" align="right" height="400" width="400" >  
        <h3>
            <ol><li>"Kaalai Maadu" translates to "Bull" in Tamil, and considering Erode's connection to agriculture and its historical significance as a center for bull taming (Jallikattu)</li>
            <li>Erode’s first-ever Jallikattu was held at the AET School grounds in the city, where 122 tamers attempted to tame 192 bulls in front of 40,000 spectators.</li>
            <li> The event was largely incident-free and marked an important cultural tradition in the region34.</li>
            <li>Both Erode and Jallikattu offer a glimpse into the vibrant heritage and festivities of Tamil Nadu.</li></ol>
           <ul> Jallikattu in Erode:
<li>Date: January 20, 2019.</li>
<li>Location: AET School grounds at Pavalathampalayam, Erode.</li>
<li>Participants: A total of 122 tamers attempted to tame 192 bulls.</li>
<li>Audience: Approximately 40,000 spectators witnessed the event.</li>
<li>Incident-Free: The first-ever Jallikattu in Erode was largely incident-free.</li>
<li>Inauguration: The sport was inaugurated by notable dignitaries, including Minister for School Education, Youth and Sports Development K.A. Sengottaiyan, Minister for Animal Husbandry Udumalai K. Radhakrishnan, and Minister for Environment K.C. Karuppannan. </li>
</ul>
        </h3>
    </body>
</html>

AANOOR.HTML
<html>
    <head>
        <title>
            Aanoor Theatre
        </title>
    </head>
    <body bgcolor="Yellow">
        <h1 align="center">ERODE</h1>
        <h1 align="center">Aanoor DOLBY ATMOS Theatre</h1>
        <hr color="white"  >
        <img src="aanoor.jpeg" height="400" width="600" align="right">
        <h3><ol><li>Aanoor Cinemas is a well known theatre in Erode. Cinema is equipped with comfortable push backed enabled Seating and fully air conditioned.</li> 
         <li>The theatre has ample car and two-wheeler Parking and the canteen caters fresh and quality food items.</li>
        <li> A cinema hall which provides redefining movie going experience.</li>
        <li>Comfortable Seating: Aanoor Theatre provides well-cushioned seats, ensuring a cozy and relaxing environment for viewers.</li>
    <li>Advanced Sound System: The theatre boasts a state-of-the-art Dolby Atmos sound system. You’ll feel immersed in the movie with crystal-clear audio.</li>
<li>Spacious Lobby: The spacious lobby area allows for easy movement and socializing before or after the film.</li>
<li>Concession Stand: Grab your favorite snacks and beverages from the concession stand. Popcorn, nachos, and soft drinks are readily available.</li>
<li>Online Booking: Aanoor Theatre offers convenient online booking through platforms like BookMyShow. Skip the queues and secure your seats in advance!</li>
<li>Whether you’re a cinephile or just looking for a fun outing, Aanoor Theatre ensures an enjoyable cinematic experience. Lights, camera, action!</li>
        </ol>    
        </h3>
    </body>
</html>

LOTUS.HTML
<html>
    <head>
        <title>
            Lotus Hospital
        </title>
    </head>
    <body bgcolor="PINK">
        <h1 align="center">ERODE</h1>
        <h1 align="center">LOTUS HOSPITAL</h1>
        <hr color="white"  >
        <h3><ul><li>Lotus hospital is situated at Poondurai Main Road near to Erode Railway Station, which is major rail route junction of southern railways.</li>
         <li>Hence, it is most conveniently located to reach by train or bus.</li>
        <li> It is a First Corporate & One stop Hospital in Erode, with multi disciplinary specialties and all diagnostic facilities made available under one roof.</li>
        <li>Lotus Hospital, located in Erode, Tamil Nadu, is a multi-specialty hospital that provides high-quality secondary and tertiary care.</li><li>Accredited by NABH, it offers a wide range of medical services under one roof. </li><li>Specialties include cardiology, orthopedics, pediatrics, and more. </li><li>The hospital’s commitment to compassionate care makes it a trusted healthcare destination in the region12.</li>

Here’s what patients have to say:

<li>Dr. Selvan Rathnasamy (pediatrician) is highly appreciated for his conservative management approach.</li>
<li>Dr. Basha (dentist) is ethical and prefers conservative treatments.</li>
<li>The hospital is well-equipped, moderately priced, and has caring doctors</li>
        </ul>
        </h3>
    </body>
</html>
```

## OUTPUT
![alt text](<Screenshot 2024-03-27 211620.png>)
![alt text](<Screenshot 2024-03-27 211634.png>) 
![alt text](<Screenshot 2024-03-27 211647.png>)
![alt text](<Screenshot 2024-03-27 211700.png>)
![alt text](<Screenshot 2024-03-27 211718.png>)
![alt text](<Screenshot 2024-03-27 211735.png>) 

## RESULT
The program for implementing image maps using HTML is executed successfully.
