# BirdMesh
Series of bird houses. One meant to be a neat little covert router. And the oher is meant for monitoring the bird population in the area.
## Versions
### BirdMesh Health edition
It's a smart birdhouse with a LoRa radio along with a bunch of sensors meant for monitoring bird population.  
With usefull sensors like:  
- Double temperature sensors for knowing temperature of the bird cavity and the ambient air as well
- IR gate to know when something eneters the bird house
- Light sensor for knowing how much light the solar pannels are recieving
- And an accelerometer to detect changes in behavior like chicks getting hungary or mum bringing them food
### BirdMesh Health edition
A small covert birdhouse-style mesh router that extends the network so the health edition can reach the monitoring station, even in areas that would otherwise be unreachable without disturbing the environment.

## Motivation for this project
It's simple extending MeshTastic or MeshCore coverage in our area.  
But it turned into a way more fun adventure. With extending the coverage and monitoring bird population. Win Win for the bird and Mesh nerds.

## Building
Evherything you need to make the project should be in the /production folder.

![CAD](/Images/CAD%20drawing.png)
![BM Re](/Images/BirdMesh%20Router%20edition.jpg)

A big thanks to HackClub for helping many great project's like mines.

## BOM
| Item                                                          | Qty | Price (USD) | Link & Source                                                                         |
|---------------------------------------------------------------|-----|-------------|---------------------------------------------------------------------------------------|
| BirdMesh-Health_edition                                       | 1   |             | BirdCAD.FCStd                                                                         |
| Lumber W150                                                   |     | -           | I already have it                                                                     |
| Lumber W200                                                   | -   | 23.11       | https://www.bauhaus.cz/hoblovane-prkno-31587637                                       |
| Wood screw                                                    | -   |             |                                                                                       |
|                                                               |     |             |                                                                                       |
| "XIAO nRF52840 & Wio-SX1262                                   |     |             |                                                                                       |
| System with MT"                                               | 1   | 13.74       | "https://www.seeedstudio.com/XIAO-nRF52840-Wio-SX1262-Kit-for-Meshtastic-p-6400.html  |
| https://www.aliexpress.com/item/1005008760784706.html"        |     |             |                                                                                       |
| Seed studio shipping + VAT                                    | -   | 12.9        |                                                                                       |
| INA219                                                        | 1   | 1.76        | https://www.aliexpress.com/item/1005007533576335.html                                 |
| LoRa Antennas 868                                             | 1   | 9.55        | https://www.aliexpress.com/item/1005009210548173.html  868MHz Gray                    |
| N female to ipex1                                             | 1   | 5.82        | https://www.aliexpress.com/item/1005004544654739.html  N F PM to RF-1 F 25cm          |
| Solar panel 200x170 or 140x220                                | 2   | 11.86       | https://www.aliexpress.com/item/4000393330799.html                                    |
| Adjustable MPPT Charger                                       | 1   | 5.92        | https://www.aliexpress.com/item/1005006026796945.html  12V                            |
| Shotky diode min. 2A                                          | 2   | 2.52        | https://www.aliexpress.com/item/1005003336587072.html                                 |
| 2S LTO Battery (super safe)                                   | 2   | 13.79       | https://www.aliexpress.com/item/1005009179422202.html  2PCS                           |
| Cable                                                         | -   |             | BYO                                                                                   |
|                                                               |     |             |                                                                                       |
| SHT30 temperature + humidity                                  | 2   | 3.75        | https://www.aliexpress.com/item/1005005039058968.html                                 |
| LIS3DH accelerometer                                          | 1   | 1.95        | https://www.aliexpress.com/item/1005010373628490.html LIS3DH Blue                     |
| IR light gate                                                 | 1   | 3.02        | https://www.aliexpress.com/item/1005008380273543.html|
| BSS138 N channel mosfet                                       | 1   | 2.46        | https://www.aliexpress.com/item/1005006996598577.html BSS138                          |
| VEML7700 light sensor                                         | 1   | 2.3         | https://www.aliexpress.com/item/1005007482226626.html                                 |
| Groove cables                                                 | 4   | 5.54        | https://www.aliexpress.com/item/1005005682847096.html PH 2.0MM, 4P, 30CM              |
| 6 port groove hub                                             | 1   | 3.99        | "https://www.aliexpress.com/item/1005007166918060.html                                |
| https://www.seeedstudio.com/Grove-I2C-Hub-6-Port-p-4349.html" |     |             |                                                                                       |
| Total                                                         |     | 123.98      |                                                                                       |

> This BOM is intended for Blueprint [BOM.ods](/BOM.ods) is the general one. You may skip the lumber if you already have it at hand.
