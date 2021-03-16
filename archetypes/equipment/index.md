---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: false

#Set the type of equipment:
#    "microscope" - Microscopes
#    "workstation" - Workstations
equipment: "microscope"

#Microscope metadata
objectives: ["obj-1", "obj-2"]
filters: ["cube-1"]
cameras: ["camera-1"]
lightsrcs: []

#Workstation metadata
ram: "64 gb"
cpu: "Intel CPU"
os: "Windows 10"
#List software as a list: ["item1", "item2"]
software: ["Fiji v1.2", "Elements v1.2.3"]

#Display a list of images:
#  - Copy files into "/images" in this directory
#  - Insert the shortcut {{< image_list>}}
---
