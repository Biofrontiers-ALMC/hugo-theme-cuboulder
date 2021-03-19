---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: false

#Set the type of equipment:
#    "microscope" - Microscopes
#    "workstation" - Workstations
equipment: "microscope"

#Set manufacturer metadata (all equipment types have this)
manufacturer: "Nikon"
model: "Ti-E with Perfect Focus System"

#Equipment components (Microscope only)
# List all components enclosed by square brakets (e.g. [item1, item2, ...]. Do this even if there is only one component. The values are the FOLDER NAME of the corresponding component.
# Example: There is an objective lens under the folder content/component/obj-1. This should be listed as "obj-1" in the list under objectives.
# Quotation marks can be used but are not necessary.
objectives: [obj-1, obj-2]
filters: [cube-1]
cameras: [camera-1]
lightsrcs: []
envctrls: []

#Workstation metadata
#You can delete these entries for a microscope
ram: "64 gb"
cpu: "Intel CPU"
os: "Windows 10"
graphicscard: GeForce GTX 690
#Hard drives must be a list, enclosed in square brackets
harddrives: [2 TB 7200 rpm, 512 GB SSD]

#List software as a list: [item1, item2]. This information will appear for both microscopes and workstations
software: [Fiji v1.2, Elements v1.2.3]

#Display a list of images:
#  - Copy files into a new subfolder "/images" in this directory
#  - Insert the shortcut {{< image_list>}} where you want the gallery to appear
---
