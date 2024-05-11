## Ex04 Places Around Me

## Date: 30.3.2024

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

STEP 1: Create a Django admin interface.

STEP 2: Download your city map from Google.

STEP 3: Using ```<map>``` tag name the map.

STEP 4: Create clickable regions in the image using ```<area>``` tag.

STEP 5: Write HTML programs for all the regions identified.

STEP 6: Execute the programs and publish them.

## Program
~~~
<html>
    <head>
        <title align="center">THIRUVANNAMALAI</title>
    </head>
    <body>
        <h1 align ="center">THIRUVANNAMALAI</h1>
        <h2 align ="center">PREETHI.B [212221220040]</h2>
    </body>
</html>
<img src="Screenshot 2024-03-21 141746.png" width="1500" height="550" usemap="#image-map">
<map name="image-map">
    <area target="_self" alt="Kilnathur" title="Kilnathur" href="Kilnathur.html" coords="377,203" shape="rect">
    <area target="_self" alt="Arunachaleswarar" title="Arunachaleswarar" href="Arunachaleswarar.html" coords="200,218" shape="poly">
    <area target="_self" alt="Reliance" title="Reliance" href="Reliance.html" coords="380,89,NaN" shape="circle">
    <area target="_self" alt="KuberaLingam" title="KuberaLingam" href="Kubera.html" coords="173,40" shape="rect">
    <area target="_self" alt="Nassipatti" title="Nassipatti" href="Nassipatti.html" coords="339,523,NaN" shape="circle">
</map>
<html>
<body bgcolor="pink">
    <head>
        <h1 align="center"> Thiruvannamalai</h1>
        <h2 align="center"> Arunachaleswarar Temple</h2>
    </head>
<p align="center" spacing="center">Built in the traditional Dravidian style of architecture, the temple is believed to be the eighth-largest Hindu temple in the world. The temple complex houses many halls and the most popular one is the thousand-pillared hall, which was constructed during the Vijayanagar period (1336-1646).</p>
</body>
</html>
<html>
<body bgcolor="blue">
    <head>
        <h1 align="center">Thiruvannamalai</h1>
        <h2 align="center"> Kilnathur</h2>
    </head>
<p align ="center">Kilnathur is a village located in the Thiruvannamalai district of Tamil Nadu, India. Thiruvannamalai is known for its famous Arunachaleswarar Temple, one of the largest temple complexes in India dedicated to the Hindu god Shiva.
</body>
</html>
<html>
<body bgcolor="cyan">
    <head>
        <h1 align="center">Thiruvannamalai</h1>
        <h2 align="center"> Kubera Lingam</h2>
    </head>
<p align="center">The Kubera Lingam is a sacred lingam (an abstract representation of the Hindu deity Shiva) located in the Arunachaleswarar Temple in Thiruvannamalai, Tamil Nadu, India.
~~~
~~~
</body>
</html>
<html>
<body bgcolor="peach">
    <head>
        <h1 align="center"> Thiruvannamalai</h1>
        <h2 align="center"> Nassipatti</h2>
    </head>
<p align="center">Nassipatti is a small village located in the Thiruvannamalai district of Tamil Nadu, India. Like many villages in the region, it likely has its own local economy primarily based on agriculture and small-scale industries.
</body>
</html>
<html>
<body bgcolor="orange">
    <head>
        <h1 align="center">Thiruvannamalai</h1>
        <h2 align="center"> Reliance</h2>
    </head>
<p align="center">Reliance Industries, led by Mukesh Ambani, is one of India's largest conglomerates with interests in various sectors including petrochemicals, refining, oil & gas exploration, telecommunications, and retail. 
</body>
</html>
~~~~
## OUTPUT
![image](https://github.com/niranjanadevi-s/NearMe/assets/141748873/e5b319c3-9562-4c88-a0a6-3feb37b7f731)
![image](https://github.com/niranjanadevi-s/NearMe/assets/141748873/5fe31ff7-61d3-47c0-b57e-75e66c506285)
## RESULT
The program for implementing image maps using HTML is executed successfully.
