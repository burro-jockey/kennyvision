
![alt text](https://github.com/burro-jockey/kennyvision/blob/main/Screenshot%202023-03-10%20193829.png?raw=true)
# Im not sure what to call this project
This is fork (for lack of a better term) of a beta made by s3ktor. 

The purpose of this project was to create a more modular platform for use in testing. There are so many different options it makes it hard decide which is the best. With spec sheets often sketchy, some brave soul will often have to just buy the thing to try it out. 

This project aims to make it easy to test multiple configurations of both input and output.
For example, I currently can switch to these inputs:
- hdmi capture card
- runcam
- foxeer
- raspberry pi zero
- drone cam  *<i>soon</i>

I can also swap outputs (more on this later?)

## The basics

*Most diy night vision devices have two primary components.
- a display
- a camera

Most projects assume that their solution is the best which is cool, and maybe even correct but depending on regional availability and cost, can make contribution harder than it has to be. An additional consequence of this direction is that most designs have wiring internally. as to be more low-drag. This makes it difficult to change inputs or test other inputs. Our approach differs by moving the connection externally. In doing this you can take advantage of the digital nature of your night vision, by being able to easily record, change and eventually add more information to your nvgs.

The key to the solution is the  [5 Pin Electrical Connector 24AWG IP65 Male & Female Connector 15mm Nut Small Size](https://www.amazon.com/Hysmigor-Electrical-Connector-Extension-Outdoor/dp/B09NDWYJG8?th=1) 
![Connectors](https://m.media-amazon.com/images/I/61fWOq+JjCL._AC_SX679_.jpg)

Since analog video only requires one wire, it is very easy to do the wiring for most analog video. Additionally, this project currently only uses three of the five wires - the other two being ground and power. 
Using these (or another type of) connectors you can quickly hot swap video by unscrewing and pulling apart. You can also you add male and female to make an inline recorder or caster. its water proof and makes wiring so mf simple anyone could do it. If you must make it high speed low drag, you can always zip-tie or one wrap the cable to the monocular.

## Rough parts list:
Thanks to s3ktor for putting this together
 -  9x  ~10mm M4 thread insert
 -  6x  16mm M4 Bolts 
 - 1x  [Runcam Night Eagle 3](https://www.amazon.com/RunCam-Night-Camera-1000TVL-Support/dp/B09JVG2D5W?th=1)
 - 1x [Foxeer Micro Night Cat 3](https://www.amazon.com/Camera-Foxeer-1200TVL-Starlight-Version/dp/B08YJM6BY2/r%20ef=asc_df_B08YJM6BY2/?tag=hyprod-20&linkCode=df0&hvadid=532264129191&hvpos%20=&hvnetw=g&hvrand=18269617691742280319&hvpone=&hvptwo=&hvqmt=&hvdev=c&%20hvdvcmdl=&hvlocint=&hvlocphy=9015893&hvtargid=pla-1457765313588&psc=1) 
 - 1x [Eisco Labs Double Convex 38mm Lens](https://www.amazon.com/Eisco-Labs-Glass-Lenses-Diameter/dp/B01F9KXRX2/ref=asc_%20df_B01F9KXRX2/?tag=hyprod-20&linkCode=df0&hvadid=533569884196&hvpos=&hvne%20tw=g&hvrand=17421257220302603976&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcm%20dl=&hvlocint=&hvlocphy=9015893&hvtargid=pla-1433339617896&psc=1) 
- 1x [NTSC/PAL 1.5” Display](https://www.adafruit.com/product/910?gclid=CjwKCAiAuaKfBhBtEiwAht6H73BhqQJnrVt%20ZlSRwMnLciBqbX9lu-s3oQICrhE7PcoC5mKbb3_VwxRoCOs8QAvD_BwE) 
- 1x [5 Pin Electrical Connector 24AWG IP65 Male & Female Connector 15mm Nut Small Size](https://www.amazon.com/Hysmigor-Electrical-Connector-Extension-Outdoor/dp/B09NDWYJG8?th=1) 

## Housing Info
Currently the housing is intended to be very modular, almost certainly at the cost of functionality. 

There are 2 primary modules which are the display and input source (camera).

The camera module is designed to thread into the housing. 

![A low quality render of the camera module](https://github.com/burro-jockey/kennyvision/blob/main/assets_for_svgs/design-1d6498e2-0f23-4470-9448-55e2e745eac2.png?raw=true)

I'm really not sure about the practical strength of this method but it works good so far.

Here is the display module.

![render of display module](https://github.com/burro-jockey/kennyvision/blob/main/assets_for_svgs/kennyvision_2023-Apr-13_04-34-54AM-000_CustomizedView17057100467-removebg-preview%20-%20Copy.png?raw=true)

as you can see if you are in the beta I completely stole the geometry of this. That way it can use the same display and lens as the beta while also being slightly easier to print in my opinion. We can also make this water tight easily using this a 1-3/16th(I.D.),  1/16th wide o-ring. (Thanks Ace)

Basically these 2 connect and make this device. Which is your night vision.

![crude night vision device](https://raw.githubusercontent.com/burro-jockey/kennyvision/65cee863611397dc537811bfa0f7913ac8b36d72/assets_for_svgs/image0.jpeg)
