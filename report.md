# DJI Terra Aerial Triangulation Quality Report

---
## Image Information Overview

| Item                    | Value           |
| :---: | :---: |
| # Input Images          |              262|
| # Image With Position   |              262|
| # Calibrated Images     |              262|
| Use Image Position | True|
| Georeferencing RMSE |   1.037 m|
| # Connected Components     |            1|
| # Max Component Images     |          262|
| Use Cluster    | No|
| Generate XML   | No|
| Use Stereo Mode    | No|
| # feature quantity | Medium|
| SFM Time          |        2.311 min|


## RTK Status

| Status  | Number of Images |
| :---: | :---: |
| FIX     |                0|
| FLOAT   |                0|
| SINGLE  |              223|
| NONE    |               39|



## Camera Calibration Information

Camera Model M3E_WideCamera 

Camera SN 1581F5FHB226H00102XQ 

| Item     | Focal   | Cx      | Cy      |   K1  |   K2  |   K3  |   K4  |   P1  |   P2  |
| :---:    | :---:   | :---:   | :---:   | :---: | :---: | :---: | :---: | :---: | :---: |
| Initial  | 3713.29| 2647.02| 1969.28| -0.11257524| 0.01487443| -0.02706411| 0.00000000| -0.00008572| 0.00000010|

| Block     | Item     | Focal   | Cx      | Cy      | K1    |   K2  |   K3  |   K4  |   P1  |  P2   |
| :---:     | :---:    | :---:   | :---:   | :---:   | :---: | :---: | :---: | :---: | :---: | :---: |
|     0 | Optimized| 3713.13| 2648.76| 1954.26| -0.10921560| 0.00572047| -0.02148286| 0.00000000| -0.00032165| 0.00004071|


Coefficients and correlation matrix 

|      | Error | F     | Cx    | Cy    | K1    | K2    | K3    | P1    | P2    |
|:---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| F  | 0.24076555| 1.00000000| 0.11412283| 0.30456384| -0.31580503| 0.02094190| -0.13977447| -0.24628017| -0.09108559|
| Cx  | 0.04500039| 0.11412283| 1.00000000| 0.03194802| -0.01723178| -0.01552092| 0.00181815| -0.02059873| -0.38162709|
| Cy  | 0.04414801| 0.30456384| 0.03194802| 1.00000000| -0.08159367| -0.00820774| -0.03145791| -0.46761419| -0.01733752|
| K1  | 0.00004351| -0.31580503| -0.01723178| -0.08159367| 1.00000000| -0.76216951| 0.66098727| 0.28067415| 0.13492873|
| K2  | 0.00008447| 0.02094190| -0.01552092| -0.00820774| -0.76216951| 1.00000000| -0.96550527| 0.00081832| -0.02376437|
| K3  | 0.00006273| -0.13977447| 0.00181815| -0.03145791| 0.66098727| -0.96550527| 1.00000000| -0.02839597| 0.00816716|
| P1  | 0.00000193| -0.24628017| -0.02059873| -0.46761419| 0.28067415| 0.00081832| -0.02839597| 1.00000000| 0.07728157|
| P2  | 0.00000194| -0.09108559| -0.38162709| -0.01733752| 0.13492873| -0.02376437| 0.00816716| 0.07728157| 1.00000000|


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
<img alt="TDOM Preview" src="./dom_screennail.png" height=1125 width=1000/>

## Map Information Overview

| Item                   | Value           |
| :---: | :---: |
| TDOM GSD               |        0.053 m|
| Coverage Area          | 0.852537 sq km|
| Average Flight Altitude|      182.742 m|
## Performance Overview

| Pipeline              | time cost (min) |
| :---:                 | :---:           |
| Image Correction      |        0.684|
| Densification         |        6.713|
| TDOM Generate         |        4.206|

## DSM Preview 
<img alt="DSM Preview" src="./dsm_screennail.png" width=1125 height=1000/>

## Scene Overlap Analyze
<img alt="Overlap" src="./overlap_render.png" width=1125 height=1000/>

