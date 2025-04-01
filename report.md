# DJI Terra Aerial Triangulation Quality Report

---
## Image Information Overview

| Item                    | Value           |
| :---: | :---: |
| # Input Images          |              238|
| # Image With Position   |              238|
| # Calibrated Images     |              238|
| Use Image Position | True|
| Georeferencing RMSE |   0.691 m|
| # Connected Components     |            1|
| # Max Component Images     |          238|
| Use Cluster    | No|
| Generate XML   | No|
| Use Stereo Mode    | No|
| # feature quantity | Medium|
| SFM Time          |        2.577 min|


## RTK Status

| Status  | Number of Images |
| :---: | :---: |
| FIX     |              237|
| FLOAT   |                0|
| SINGLE  |                0|
| NONE    |                1|



## Camera Calibration Information

Camera Model ZenmuseP1 

Camera SN 3XMDH9W0010067 

Lens SN 08LY106G003P 

| Item     | Focal   | Cx      | Cy      |   K1  |   K2  |   K3  |   K4  |   P1  |   P2  |
| :---:    | :---:   | :---:   | :---:   | :---: | :---: | :---: | :---: | :---: | :---: |
| Initial  | 8192.00| 4096.00| 2730.00| 0.00000000| 0.00000000| 0.00000000| 0.00000000| 0.00000000| 0.00000000|

| Block     | Item     | Focal   | Cx      | Cy      | K1    |   K2  |   K3  |   K4  |   P1  |  P2   |
| :---:     | :---:    | :---:   | :---:   | :---:   | :---: | :---: | :---: | :---: | :---: | :---: |
|     0 | Optimized| 8205.57| 4059.89| 2766.96| -0.04613059| 0.02401441| -0.10743707| 0.00000000| 0.00196281| -0.00160610|


Coefficients and correlation matrix 

|      | Error | F     | Cx    | Cy    | K1    | K2    | K3    | P1    | P2    |
|:---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| F  | 1.40386904| 1.00000000| 0.58010119| 0.61065894| -0.24303135| 0.06057060| -0.16175699| 0.03656280| -0.20760207|
| Cx  | 0.08415908| 0.58010119| 1.00000000| 0.36217227| -0.13722471| 0.04064788| -0.10590571| 0.03065843| 0.60029020|
| Cy  | 0.07541106| 0.61065894| 0.36217227| 1.00000000| -0.13322081| 0.02395778| -0.08676384| 0.72390309| -0.11277434|
| K1  | 0.00007241| -0.24303135| -0.13722471| -0.13322081| 1.00000000| -0.95613898| 0.92204828| 0.00436375| 0.02712832|
| K2  | 0.00042900| 0.06057060| 0.04064788| 0.02395778| -0.95613898| 1.00000000| -0.98003123| -0.00798227| 0.01526682|
| K3  | 0.00077752| -0.16175699| -0.10590571| -0.08676384| 0.92204828| -0.98003123| 1.00000000| 0.00505650| -0.00065761|
| P1  | 0.00000256| 0.03656280| 0.03065843| 0.72390309| 0.00436375| -0.00798227| 0.00505650| 1.00000000| 0.00478846|
| P2  | 0.00000292| -0.20760207| 0.60029020| -0.11277434| 0.02712832| 0.01526682| -0.00065761| 0.00478846| 1.00000000|


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
| TDOM GSD               |        0.084 m|
| Coverage Area          | 5.550657 sq km|
| Average Flight Altitude|      681.065 m|
## Performance Overview

| Pipeline              | time cost (min) |
| :---:                 | :---:           |
| Image Correction      |        1.225|
| Densification         |       17.490|
| TDOM Generate         |       12.614|

## DSM Preview 
<img alt="DSM Preview" src="./dsm_screennail.png" width=1125 height=1000/>

## Scene Overlap Analyze
<img alt="Overlap" src="./overlap_render.png" width=1125 height=1000/>

