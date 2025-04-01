# DJI Terra Aerial Triangulation Quality Report

---
## Image Information Overview

| Item                    | Value           |
| :---: | :---: |
| # Input Images          |             1276|
| # Image With Position   |             1276|
| # Calibrated Images     |             1147|
| Use Image Position | True|
| Georeferencing RMSE |   0.029 m|
| # Connected Components     |            1|
| # Max Component Images     |         1147|
| Use Cluster    | No|
| Generate XML   | No|
| Use Stereo Mode    | No|
| # feature quantity | Medium|
| SFM Time          |      244.433 min|


## RTK Status

| Status  | Number of Images |
| :---: | :---: |
| FIX     |             1276|
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
|     0 | Optimized| 8196.78| 4049.68| 2754.55| -0.04661673| 0.02251755| -0.10105898| 0.00000000| 0.00191734| -0.00170090|


Coefficients and correlation matrix 

|      | Error | F     | Cx    | Cy    | K1    | K2    | K3    | P1    | P2    |
|:---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| F  | 0.03562005| 1.00000000| 0.00108873| -0.04543330| -0.31342148| 0.28203414| -0.25427592| -0.01163425| -0.00292422|
| Cx  | 0.02957135| 0.01007950| 1.00000000| -0.00213135| -0.00009577| -0.00013196| 0.00035567| 0.00125951| -0.02841657|
| Cy  | 0.02335890| -0.02319497| -0.00178893| 1.00000000| 0.00002072| 0.00011231| -0.00023426| -0.02786715| 0.00124154|
| K1  | 0.00003024| -0.32267716| -0.01055969| 0.00512055| 1.00000000| -0.97325332| 0.92115582| 0.01013790| -0.01321480|
| K2  | 0.00018557| 0.30264245| 0.01464494| -0.00390092| -0.97267035| 1.00000000| -0.98434447| -0.01480150| 0.01910362|
| K3  | 0.00033833| -0.28219542| -0.01876334| 0.00390698| 0.91991577| -0.98360853| 1.00000000| 0.01835690| -0.02650408|
| P1  | 0.00000048| -0.03073011| -0.02302629| 1.76615322| 0.01064349| -0.01513456| 0.01903360| 1.00000000| -0.04004562|
| P2  | 0.00000047| -0.05680748| 2.32263098| -0.00232604| -0.01560882| 0.01998224| -0.02731891| -0.04018999| 1.00000000|


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
| TDOM GSD               |        0.072 m|
| Coverage Area          | 11.237059 sq km|
| Average Flight Altitude|      584.019 m|
## Performance Overview

| Pipeline              | time cost (min) |
| :---:                 | :---:           |
| Image Correction      |       21.493|
| Densification         |      235.869|
| TDOM Generate         |       88.043|

## DSM Preview 
<img alt="DSM Preview" src="./dsm_screennail.png" width=1125 height=1000/>

## Scene Overlap Analyze
<img alt="Overlap" src="./overlap_render.png" width=1125 height=1000/>

