# DJI Terra Aerial Triangulation Quality Report

---
## Image Information Overview

| Item                    | Value           |
| :---: | :---: |
| # Input Images          |             2230|
| # Image With Position   |             2230|
| # Calibrated Images     |             2111|
| Use Image Position | True|
| Georeferencing RMSE |   0.030 m|
| # Connected Components     |            1|
| # Max Component Images     |         2111|
| Use Cluster    | No|
| Generate XML   | No|
| Use Stereo Mode    | No|
| # feature quantity | Medium|
| SFM Time          |       26.429 min|


## RTK Status

| Status  | Number of Images |
| :---: | :---: |
| FIX     |             2230|
| FLOAT   |                0|
| SINGLE  |                0|
| NONE    |                0|



## Camera Calibration Information

Camera Model ZenmuseP1 

Camera SN 3XMDH9W0010067 

Lens SN 08LY106G003P 

| Item     | Focal   | Cx      | Cy      |   K1  |   K2  |   K3  |   K4  |   P1  |   P2  |
| :---:    | :---:   | :---:   | :---:   | :---: | :---: | :---: | :---: | :---: | :---: |
| Initial  | 8192.00| 4096.00| 2730.00| 0.00000000| 0.00000000| 0.00000000| 0.00000000| 0.00000000| 0.00000000|

| Block     | Item     | Focal   | Cx      | Cy      | K1    |   K2  |   K3  |   K4  |   P1  |  P2   |
| :---:     | :---:    | :---:   | :---:   | :---:   | :---: | :---: | :---: | :---: | :---: | :---: |
|     0 | Optimized| 8201.14| 4053.32| 2751.79| -0.04651179| 0.02238728| -0.10119734| 0.00000000| 0.00191459| -0.00164883|


Coefficients and correlation matrix 

|      | Error | F     | Cx    | Cy    | K1    | K2    | K3    | P1    | P2    |
|:---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| F  | 0.48441697| 1.00000000| 0.85403504| 0.77656311| -0.02379197| 0.01718871| -0.01784895| -0.05082693| -0.36454300|
| Cx  | 0.03446301| 0.27960810| 1.00000000| 0.32010809| -0.00090395| -0.00029823| -0.00029136| -0.01432598| 0.39598051|
| Cy  | 0.02924315| 0.27597589| 0.35977251| 1.00000000| -0.00154697| 0.00026974| -0.00098723| -0.03339573| -0.24858474|
| K1  | 0.00002422| -0.25770080| -0.20049211| -0.17299190| 1.00000000| -0.97128223| 0.91967375| 0.02829266| 0.06090634|
| K2  | 0.00014550| 0.06103768| 0.04756464| 0.02502031| -0.97256736| 1.00000000| -0.98459151| -0.01967571| 0.00860874|
| K3  | 0.00026162| -0.15546318| -0.13805915| -0.10088399| 0.92004333| -0.98368564| 1.00000000| 0.02693482| 0.02224931|
| P1  | 0.00000041| -0.71552395| -0.25936225| 1.63992009| 0.02067517| -0.01767834| 0.02225391| 1.00000000| -0.17613055|
| P2  | 0.00000107| -0.52548713| 0.47669503| -0.26882126| -0.01803868| 0.01301093| -0.01059119| 0.02590316| 1.00000000|


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
<img alt="TDOM Preview" src="./dom_screennail.png" height=1125 width=987/>

## Map Information Overview

| Item                   | Value           |
| :---: | :---: |
| TDOM GSD               |        0.048 m|
| Coverage Area          | 8.264586 sq km|
| Average Flight Altitude|      390.676 m|
## Performance Overview

| Pipeline              | time cost (min) |
| :---:                 | :---:           |
| Image Correction      |       11.593|
| Densification         |      193.407|
| TDOM Generate         |      105.987|

## DSM Preview 
<img alt="DSM Preview" src="./dsm_screennail.png" width=1125 height=987/>

## Scene Overlap Analyze
<img alt="Overlap" src="./overlap_render.png" width=1125 height=987/>

