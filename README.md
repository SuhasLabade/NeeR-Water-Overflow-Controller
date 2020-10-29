# NeeR-Water Overflow Controller


### Introduction: 
India's water crisis is often attributed to lack of government planning, increasedcorporate privatization, industrial and ##human waste and government corruption. 
In addition, water scarcity in India is expected to worsen as the overall population is expected 
to increase to 1.6 billion by year 2050. - The water project 

Focusing on human water waste problems - most of city areas wasting water every 
day while filling tanks. Roof top water storage tanks are obeserved to be overflowing many times in city area as well as in rural part of India.That tends to water scarcity problems and loss of energy.
This project aims to resolve water tank overflow problem and saves water and energy wastage. 


### Need : 

This one is news in Hindustan times regarding water crisis in New Delhi. Governement annonucing fine of Rs. 2000/- if water tank overflows.  </br></br>
![](https://github.com/SuhasLabade/NeeR-Water-Overflow-Controller/blob/master/Neer/image1.png)   </br></br>



Also in this journal its stated that - The quantum of water loss of an overflowing tank is estimated using theoretical analysis and experimental methods.
And by a survey of a colony on overflow, it was found out that 7% of the water supplied was lost; and additionally 3.84% of the
energy supplied was also lost; in one of the two colonies of Delhi. 

https://pdfs.semanticscholar.org/463b/479d0e04d463be58b4d9a8d792cfcc444620.pdf

This study also says that if any automatic cutoff controller is introduced then around 90 billion litres of treated water 
and 90 billion kW-hr of energy can be saved in a month in India. This clearly indicates potential and actual need of this project.
Currently these water controllers available in market but not in robust form and in affrodable price.</br>


### Block diagram and working principle :

As shown in below  block diagram two float sensors are placed inside tank 2 at different positions, float 1 is at upper level [where we need 
to restrict waterlevel ] and float 2 placed at bottom level [ where we need to start motor to fill tank again] , Both these are float mechanical 
type switches that turns ON when it drops down [ Here customization of float sensor is done,floating weight of 
all these sensors are placed in reverse direction so that it turns ON when it drops down , initially it was turns ON when it floats up ] 

Float sensor 3 is placed in another tank where motor is placed. This float 3 sensor mainly measures Tank 1 water
level and keeps motor OFF if water level is below the float 3 sensor. </br> </br></br>
![](https://github.com/SuhasLabade/NeeR-Water-Overflow-Controller/blob/master/Neer/image2.png) </br></br>

This device works in following iterations: </br>

Float 1: ON  &nbsp;&nbsp;  Float 2: ON  &nbsp;&nbsp;  Float 3: OFF    &nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;     Motor ON </br>

Float 1: ON  &nbsp;&nbsp;  Float 2: OFF &nbsp;&nbsp;  Float 3: OFF/ON  &nbsp;&nbsp;  Motor OFF </br>

Float 1: OFF &nbsp;&nbsp;  Float 2: OFF &nbsp;&nbsp;  Float 3: OFF/ON  &nbsp;&nbsp;   Motor OFF </br>

Float 1: ON  &nbsp;&nbsp;  Float 2: ON  &nbsp;&nbsp;  Float 3: ON      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;       Motor OFF </br>



This device also has Manual and Auto mode that operates through given toggle switch . 
This device designed upto 2HP motor capacity and requires 230VAC supply for motor and 12V/1AMP DC supply for device. </br></br>

### Bill of material  and specifications : 

Detailed list of material with specifications given on below link:


![](https://github.com/SuhasLabade/NeeR-Water-Overflow-Controller/blob/master/Neer/image4.png)








NeeR installation :

First Intallation on Vigyan ashrams Kitchen Tank : 
Upper Tank is with xxx liter capacity has single phase 1HP motor placed near bottom tank. Installed first device for one month testing August 3rd. 



Temperature sensors comparision            |  Comparision graph
:---------------------------:|:-------------------------:
![](https://github.com/SuhasLabade/my-projects-/blob/master/Images/BME4.png)  |  ![](https://github.com/SuhasLabade/my-projects-/blob/master/Images/BME5.png)






