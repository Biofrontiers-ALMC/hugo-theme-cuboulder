---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: false

#Set the type of component:
#    "objective" - Objective lenses
#    "filter" - Filter cubes
#    "camera" - Cameras
#    "lightsrc" - Light sources
component: "objective"

#Set manufacturer metadata 
manufacturer: "Nikon"
model: "AB-123"

#Metadata for objectives
magnification: "20"
immersionmedia: "water"
numericalaperture: "0.65"

#Metadata for filters
magnification: "20"
immersionmedia: "water"
numericalaperture: "0.65"


#Metadata for cameras
magnification: "20"
immersionmedia: "water"
numericalaperture: "0.65"

#Metadata for light sources
magnification: "20"
immersionmedia: "water"
numericalaperture: "0.65"
---