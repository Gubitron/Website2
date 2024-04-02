---
title: Prosthetc Hand Control Using EMG Signals and Machine Learning
subtitle: Academic
image: assets/img/experience/EmgDiagram.png
ImageCaption: Image provided only for illustration purposes.
alt: Prosthetc Hand Control Using EMG Signals and Machine Learning

caption:
  title: Prosthetc Hand Control Using EMG Signals and Machine Learning
  subtitle: Academic
  thumbnail: assets/img/experience/EmgDiagram.png
---
### Solution Description

<iframe width="560" height="315" src="https://www.youtube.com/embed/HNtJVrBcj8Q?si=_E7NkV8HDfS6lKDM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<br>This was a final year MEng project. The purpose of the project was to use a publicly available surface EMG signal database to compare a number of machine learning algorithms. Once the best performing algorithm was found - it was used to build and control a prosthetic hand prototype.

The system used a python script to automate the training data acquisition process. The data would then get used by a Matlab script to train a Multilayer Perceptron model. The obtained coefficients would then be used by a control algorithm written in LabVIEW to control the prosthetic hand in real-time. This was achieved by executing pre-defined gestures, by controlling servo motors via an Arduino Uno, based on data received from the Myo armband.

![image tooltip here](/assets/img/experience/RT classification algorithm.png){: width="560" }{: height="315" }