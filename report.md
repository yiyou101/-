# DJI Terra Aerial Triangulation Quality Report

---
## Image Information Overview

| Item                    | Value           |
| :---: | :---: |
| # Input Images          |             2942|
| # Image With Position   |             2942|
| # Calibrated Images     |             2942|
| Use Image Position | True|
| Georeferencing RMSE |   1.122 m|
| # Connected Components     |            1|
| # Max Component Images     |         2942|
| Use Cluster    | No|
| Generate XML   | No|
| Use Stereo Mode    | No|
| # feature quantity | Medium|
| SFM Time          |      116.661 min|


## RTK Status

| Status  | Number of Images |
| :---: | :---: |
| FIX     |             2412|
| FLOAT   |                0|
| SINGLE  |                0|
| NONE    |              530|



## Camera Calibration Information

Camera Model M3E_WideCamera 

Camera SN 1581F5FHD233E00DJ178 

| Item     | Focal   | Cx      | Cy      |   K1  |   K2  |   K3  |   K4  |   P1  |   P2  |
| :---:    | :---:   | :---:   | :---:   | :---: | :---: | :---: | :---: | :---: | :---: |
| Initial  | 3713.29| 2647.02| 1969.28| -0.11257524| 0.01487443| -0.02706411| 0.00000000| -0.00008572| 0.00000010|

| Block     | Item     | Focal   | Cx      | Cy      | K1    |   K2  |   K3  |   K4  |   P1  |  P2   |
| :---:     | :---:    | :---:   | :---:   | :---:   | :---: | :---: | :---: | :---: | :---: | :---: |
|     0 | Optimized| 3726.27| 2657.54| 1918.14| -0.11002725| 0.00746674| -0.02353862| 0.00000000| -0.00051504| -0.00011150|


Coefficients and correlation matrix 

|      | Error | F     | Cx    | Cy    | K1    | K2    | K3    | P1    | P2    |
|:---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| F  | 0.00418840| 1.00000000| -0.04670435| 0.02021750| -0.72518007| 0.65593045| -0.59208193| 0.00645247| 0.00928113|
| Cx  | 0.00508655| -0.01104537| 1.00000000| 0.00108126| 0.00005903| 0.00003756| -0.00009740| 0.00020459| -0.06030477|
| Cy  | 0.00448153| 0.00075984| 0.00229274| 1.00000000| 0.00081032| -0.00095016| 0.00119520| -0.07065069| -0.00011854|
| K1  | 0.00000740| -0.71564948| 0.00035357| -0.00693724| 1.00000000| -0.97418261| 0.92242008| -0.01814903| -0.00488740|
| K2  | 0.00001889| 0.65083394| -0.00228066| 0.01270940| -0.97419187| 1.00000000| -0.98402939| 0.01890282| -0.00083345|
| K3  | 0.00001421| -0.59372714| 0.00403524| -0.01851088| 0.92253153| -0.98413893| 1.00000000| -0.02123042| 0.00426505|
| P1  | 0.00000020| 0.00921094| -0.01160836| 0.71545036| -0.02099496| 0.02209571| -0.02467950| 1.00000000| 0.00065224|
| P2  | 0.00000015| -0.00122444| 1.30333241| 0.00450077| -0.00526970| 0.00111279| 0.00214875| -0.00096568| 1.00000000|


## Hardware Information

- CPU: Intel 11th Gen Intel(R) Core(TM) i7-1165G7 @ 2.80GHz 8 cores
- GPU Number: 1
- GPU0: NVIDIA GeForce MX450
- RAM: 16183 M
# DJI Terra 2D Quality Report


---
## Process Parameters

| Process Parameters    | Value |
| :---: | :---: |
| Mapping Scene        | Urban    |
| Resolution         | High    |
| Use Cluster| No|
| Use Dodging | No|
| Use Dehaze | No|

## TDOM Preview
<img alt="TDOM Preview" src="./dom_screennail.png" height=1125 width=562/>

## Map Information Overview

| Item                   | Value           |
| :---: | :---: |
| TDOM GSD               |        0.173 m|
| Coverage Area          | 11.401369 sq km|
| Average Flight Altitude|      603.670 m|
## Performance Overview

| Pipeline              | time cost (min) |
| :---:                 | :---:           |
| Image Correction      |       11.182|
| Densification         |      180.723|
| TDOM Generate         |       15.423|

## DSM Preview 
<img alt="DSM Preview" src="./dsm_screennail.png" width=1125 height=562/>

## Scene Overlap Analyze
<img alt="Overlap" src="./overlap_render.png" width=1125 height=562/>

