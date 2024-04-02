---
title: Selective Colour Tracking Algorithm Using a Webcam and a Pan/Tilt Mechanism
subtitle: Professional
image: assets/img/experience/myTracker.jpg
ImageCaption: Image provided only for illustration purposes.
alt: Selective Colour Tracking Algorithm Using a Webcam and a Pan/Tilt Mechanism

caption:
  title: Selective Colour Tracking Algorithm Using a Webcam and a Pan/Tilt Mechanism
  subtitle: Professional
  thumbnail: assets/img/experience/myTracker.jpg
---
### Solution Description

<iframe width="560" height="315" src="https://www.youtube.com/embed/DrHPyBcQAW8?si=T6THyXByNgTU2xeN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<br>This was a project meant to demonstrate the capabilities of the myRIO. Utilizing only a [myRIO](https://www.ni.com/en-us/shop/model/myrio-1900.html), a webcam and a pan/tilt mechanism - the system was able to accurately track a user selected colour by keeping the camera image centered on the the chosen colour. The colour tracking was done using an in-built machine learning function provided in LabVIEW. The camera feed was divided into 81 areas and each area was tested, if it it's close enough to the selected colour. All of the processing was done on the myRIO.

<br>In addition, the myRIO transmitted the camera image wirelessly to a user interface and allowed the user to control the camera pan and tilt manually. The video was transmited using UDP due to some frame loses being acceptable for playback and [network streams](https://www.ni.com/en/shop/labview/lossless-communication-with-network-streams--components--archite.html) was used for handling commands, to ensure no commands were lost.

<br>The whole project took a couple of weeks to complete.