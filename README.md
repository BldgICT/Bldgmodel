# Prototype building model for low-income housing

## Background
This is a prototype building model for low-income housing in South Korea and its user guide. The geometry and input data (e.g., U-value, heating and cooling system specifications) of the model are based on the results of field surveys by Korea Energy Foundation (KOREF) and Korea Institute of Energy Research (KIER). This model can be opened with EnergyPlus version 8.9 (https://energyplus.net/).

The main project site is https://bldgict.github.io/construction.
![이미지 alt](/figures/bldg_geo.jpeg)

## Contents
- model: contains model file (.idf)
- weather: contains weather data (.epw) for 4 regions in Korea (source: https://energyplus.net/weather)
- spec: contains specification sheet (.xlsx)

## Model summary
- a box-shaped building
- low airtightness performance
- HVAC systems
  - cooling: air conditioner, standing fan
  - heating: radiant heating+boiler, electric mat

## Copyright
Prototype building model for low-income housing Copyright (c) 2023, Korea Institute of Energy Research. All rights reserved. This model was developed under funding from the Korea Energy Foundation consequently retains certain rights.

## Citation
To cite the model, use

Nam, Hye-Ryeong, Seo-Hoon Kim, Seol-Yee Han, Sung-Jin Lee, Won-Hwa Hong, and Jong-Hun Kim.
Statistical methodology for the definition of standard model for energy analysis of residential buildings in Korea.
_Energies_, 13(21), 5796, 2020.

```
@Article{
  author  =  {Nam, Hye-Ryeong, Seo-Hoon Kim, Seol-Yee Han, Sung-Jin Lee, Won-Hwa Hong, and Jong-Hun Kim},
  title   =  {Statistical methodology for the definition of standard model for energy analysis of residential buildings in Korea},
  journal =  {Energies},
  volume  =  {13},
  number  =  {21},
  pages   =  {5796},
  year    =  {2020},
  doi     =  {10.3390/en13215796},
  url     = "https://doi.org/10.3390/en13215796"
}
```
