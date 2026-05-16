# BMSO All sky DIY camera

![Picture of BMSO all-sky cam](pictures/resized/PXL_20251212_172710690.jpg) ![Screenshot2](pictures/resized/screenshot2.png) 

## Introduction
BMSO is the name of my personnal mobile observatory. I wanted a small portable "all-sky" camera to put on the roof of my van during the nights I spend astrophotographing the dark skies. The goal is to monitor the sky and environmental data (humidity/temperature/dew point, clouds, comming rain,...) and by the way make some nice timelapses of the rotating sky. Such a camera is generally expensive and not very easy to use as a mobile device. So, here's my own DIY all-sky camera. I's build around a [ZWO ASI 224MC](https://www.zwoastro.com/product/zwo-asi224mc/), but you can use any other [Indi](https://indilib.org/) supported device. The advantage of this 224MC model is that it already comes with a small wide angle objective that you can directly use in this setup, and it's relatively inexpensive. I found mine as a second hand for 150 €.

The case of the camera is made with a 3D printer in PETG and the "brain" is a [Raspberry-Pi 5](https://www.raspberrypi.com/products/raspberry-pi-5/) with 2 GB of RAM, but it should work with a less expensive model RP-4.

The software stack is fully opensource: [Raspbery Pi OS](https://www.raspberrypi.com/software/operating-systems/) (Linux Debian based) with [Indi](https://indilib.org/) and the excellent [Indi allsky](https://github.com/aaronwmorris/indi-allsky) project.

The whole thing may cost you less than 200 €

![Picture of BMSO all-sky cam](pictures/resized/PXL_20251214_080326178.jpg) 

You can check some sample timelapses [here](sample_timelapses/)

## List of supplies

- [ZWO ASI 224MC](https://www.zwoastro.com/product/zwo-asi224mc/) camera or any [Indi](https://drivers.indilib.org/cameras/) compatible device. As any astronomy camera, the more sensible the best. Avoid too small sensors as it will reduce the field of view.
- A [Raspberry-Pi](https://www.raspberrypi.com/). A Pi 5 is great but a v4 should also work. The more RAM the best. Mine is a PI 5 with 2 GB and it works perfectly. Boght [here](https://www.elektor.fr/products/raspberry-pi-5-2-gb-ram) for 50 €.
- A case for Raspberry-Pi. This is not mandatory, but best to prevent from a bad cooling. I used a passive cooling aluminium case as the BMSO all-sky cam provides cooling with a fan that is also used for best efficiency of the humidity sensor. The exact model I used is the Geekworm [Raspberry Pi 5 Heavy-duty Aluminum Passive Cooling Case (P573)](https://www.amazon.fr/Geekworm-Raspberry-bo%C3%AEtier-Aluminium-Passive/dp/B0CNPL3V55). 
- A transparent plastic dome generally used for CCTV cameras. I used [this one](https://a.aliexpress.com/_EvziIdy), but if you have a slighter different one, you may choose to modify the "adapter" piece of the body in the 3D parts. To use the provided adapter, you have to choose a dome that has an exact **84.5** mm external diameter at the base.


