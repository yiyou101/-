# DJI Terra Aerial Triangulation Quality Report

---
## Image Information Overview

| Item                    | Value           |
| :---: | :---: |
| # Input Images          |              979|
| # Image With Position   |              979|
| # Calibrated Images     |              977|
| Use Image Position | True|
| Georeferencing RMSE |   0.058 m|
| # Connected Components     |            1|
| # Max Component Images     |          977|
| Use Cluster    | No|
| Generate XML   | No|
| Use Stereo Mode    | No|
| # feature quantity | Medium|
| SFM Time          |       24.192 min|


## RTK Status

| Status  | Number of Images |
| :---: | :---: |
| FIX     |              979|
| FLOAT   |                0|
| SINGLE  |                0|
| NONE    |                0|



## Camera Calibration Information

Camera Model M3E_WideCamera 

Camera SN 1581F5FHB226H00102XQ 

| Item     | Focal   | Cx      | Cy      |   K1  |   K2  |   K3  |   K4  |   P1  |   P2  |
| :---:    | :---:   | :---:   | :---:   | :---: | :---: | :---: | :---: | :---: | :---: |
| Initial  | 3713.29| 2647.02| 1969.28| -0.11257524| 0.01487443| -0.02706411| 0.00000000| -0.00008572| 0.00000010|

| Block     | Item     | Focal   | Cx      | Cy      | K1    |   K2  |   K3  |   K4  |   P1  |  P2   |
| :---:     | :---:    | :---:   | :---:   | :---:   | :---: | :---: | :---: | :---: | :---: | :---: |
|     0 | Optimized| 3719.91| 2648.95| 1954.68| -0.10931220| 0.00527658| -0.02160813| 0.00000000| -0.00032900| 0.00002989|


Coefficients and correlation matrix 

|      | Error | F     | Cx    | Cy    | K1    | K2    | K3    | P1    | P2    |
|:---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| F  | 0.03246689| 1.00000000| 0.06432883| 0.03518181| -0.30059588| 0.18130733| -0.20044220| -0.02091374| -0.05406477|
| Cx  | 0.01170831| 0.06432883| 1.00000000| -0.00482405| 0.01226281| -0.01948635| 0.01687025| 0.01049272| 0.48181897|
| Cy  | 0.01064439| 0.03518181| -0.00482405| 1.00000000| -0.00384227| -0.00027521| -0.00143667| 0.36257744| -0.00635756|
| K1  | 0.00001566| -0.30059588| 0.01226281| -0.00384227| 1.00000000| -0.96737773| 0.91897318| -0.00380655| 0.03505646|
| K2  | 0.00003839| 0.18130733| -0.01948635| -0.00027521| -0.96737773| 1.00000000| -0.98368444| 0.00329349| -0.03181041|
| K3  | 0.00002781| -0.20044220| 0.01687025| -0.00143667| 0.91897318| -0.98368444| 1.00000000| -0.00114234| 0.03354333|
| P1  | 0.00000057| -0.02091374| 0.01049272| 0.36257744| -0.00380655| 0.00329349| -0.00114234| 1.00000000| 0.01256712|
| P2  | 0.00000063| -0.05406477| 0.48181897| -0.00635756| 0.03505646| -0.03181041| 0.03354333| 0.01256712| 1.00000000|


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
<img alt="TDOM Preview" src="./dom_screennail.png" height=1125 width=914/>

## Map Information Overview

| Item                   | Value           |
| :---: | :---: |
| TDOM GSD               |        0.053 m|
| Coverage Area          | 1.709079 sq km|
| Average Flight Altitude|      183.995 m|
## Performance Overview

| Pipeline              | time cost (min) |
| :---:                 | :---:           |
| Image Correction      |        2.505|
| Densification         |       29.112|
| TDOM Generate         |       11.309|

## DSM Preview 
<img alt="DSM Preview" src="./dsm_screennail.png" width=1125 height=914/>

## Scene Overlap Analyze
<img alt="Overlap" src="./overlap_render.png" width=1125 height=914/>

