---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: false

#Set the type of component:
#    "objective" - Objective lenses
#    "filter" - Filter cubes
#    "camera" - Cameras
#    "light-source" - Light sources
#    "environmental-controller" - Environmental controller
component: "objective"

#Set manufacturer metadata (all component types have this)
manufacturer: Nikon
model: AB-123
website: https://www.hamamatsu.com/eu/en/product/type/C14440-20UP/index.html

#Fill out metadata for the type of component (you can delete the others)

#Metadata for objectives
magnification: "20"
immersionmedia: "water"
numericalaperture: "0.65"

#Metadata for filters
filtersets: ["DAPI", "GFP", "TRITC", "Cy5", "DIC"]

#Metadata for cameras
sensorsize: 1024x1024
sensortype: "CMOS"
sensorpxsize: "3.45 um"

#Metadata for light sources
wavelengths: ["405 nm", "445 nm", "Argon (454, 471, 488, 515 nm)"]

#Metadata for environmental controller
envcontrols: ["CO2", "Temperature", "Humidity"]

#To add an image of the component, simply copy the image to this subfolder.
---