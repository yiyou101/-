# DJI Terra Aerial Triangulation Quality Report

---
## Image Information Overview

| Item                    | Value           |
| :---: | :---: |
| # Input Images          |              106|
| # Image With Position   |              106|
| # Calibrated Images     |              106|
| Use Image Position | True|
| Georeferencing RMSE |   0.053 m|
| # Connected Components     |            1|
| # Max Component Images     |          106|
| Use Cluster    | No|
| Generate XML   | No|
| Use Stereo Mode    | No|
| # feature quantity | Medium|
| SFM Time          |        1.389 min|


## RTK Status

| Status  | Number of Images |
| :---: | :---: |
| FIX     |              106|
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
|     0 | Optimized| 8197.45| 4047.05| 2757.58| -0.04694787| 0.02363339| -0.10487174| 0.00000000| 0.00192132| -0.00166423|


Coefficients and correlation matrix 

|      | Error | F     | Cx    | Cy    | K1    | K2    | K3    | P1    | P2    |
|:---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| F  | 0.11374082| 1.00000000| -0.00011314| -0.08594880| -0.32869928| 0.31645696| -0.29277112| -0.07080385| -0.00447547|
| Cx  | 0.10287255| -0.00011314| 1.00000000| 0.04755887| -0.00539745| 0.01317749| -0.01808366| 0.03512947| 0.89692492|
| Cy  | 0.09548473| -0.08594880| 0.04755887| 1.00000000| 0.00518434| -0.00860314| 0.00876861| 0.90300673| 0.04899593|
| K1  | 0.00010498| -0.32869928| -0.00539745| 0.00518434| 1.00000000| -0.97210232| 0.92099168| 0.01040504| -0.01943995|
| K2  | 0.00063514| 0.31645696| 0.01317749| -0.00860314| -0.97210232| 1.00000000| -0.98463651| -0.01363830| 0.02505574|
| K3  | 0.00114044| -0.29277112| -0.01808366| 0.00876861| 0.92099168| -0.98463651| 1.00000000| 0.01470969| -0.03159589|
| P1  | 0.00000406| -0.07080385| 0.03512947| 0.90300673| 0.01040504| -0.01363830| 0.01470969| 1.00000000| 0.03144010|
| P2  | 0.00000426| -0.00447547| 0.89692492| 0.04899593| -0.01943995| 0.02505574| -0.03159589| 0.03144010| 1.00000000|


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
| TDOM GSD               |        0.085 m|
| Coverage Area          | 2.404624 sq km|
| Average Flight Altitude|      688.477 m|
## Performance Overview

| Pipeline              | time cost (min) |
| :---:                 | :---:           |
| Image Correction      |        0.560|
| Densification         |        5.369|
| TDOM Generate         |        4.734|

## DSM Preview 
<img alt="DSM Preview" src="./dsm_screennail.png" width=1125 height=1000/>

## Scene Overlap Analyze
<img alt="Overlap" src="./overlap_render.png" width=1125 height=1000/>

