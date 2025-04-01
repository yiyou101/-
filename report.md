# DJI Terra Aerial Triangulation Quality Report

---
## Image Information Overview

| Item                    | Value           |
| :---: | :---: |
| # Input Images          |              175|
| # Image With Position   |              175|
| # Calibrated Images     |              175|
| Use Image Position | True|
| Georeferencing RMSE |   0.051 m|
| # Connected Components     |            1|
| # Max Component Images     |          175|
| Use Cluster    | No|
| Generate XML   | No|
| Use Stereo Mode    | No|
| # feature quantity | Medium|
| SFM Time          |        9.859 min|


## RTK Status

| Status  | Number of Images |
| :---: | :---: |
| FIX     |              175|
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
|     0 | Optimized| 8196.17| 4046.58| 2760.36| -0.04670310| 0.02317898| -0.10388370| 0.00000000| 0.00191186| -0.00171663|


Coefficients and correlation matrix 

|      | Error | F     | Cx    | Cy    | K1    | K2    | K3    | P1    | P2    |
|:---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| F  | 0.07575355| 1.00000000| 0.02616886| -0.06278944| -0.39867399| 0.37111281| -0.34017992| -0.05045285| 0.01440423|
| Cx  | 0.07829212| 0.02616886| 1.00000000| 0.04472509| -0.00919818| 0.01658867| -0.02225674| 0.03280577| 0.90834834|
| Cy  | 0.06943822| -0.06278944| 0.04472509| 1.00000000| 0.00461101| -0.00491922| 0.00515972| 0.89708773| 0.04539886|
| K1  | 0.00007995| -0.39867399| -0.00919818| 0.00461101| 1.00000000| -0.97239274| 0.92118642| 0.00975075| -0.02055987|
| K2  | 0.00048359| 0.37111281| 0.01658867| -0.00491922| -0.97239274| 1.00000000| -0.98462718| -0.01066680| 0.02782305|
| K3  | 0.00086883| -0.34017992| -0.02225674| 0.00515972| 0.92118642| -0.98462718| 1.00000000| 0.01189821| -0.03653303|
| P1  | 0.00000297| -0.05045285| 0.03280577| 0.89708773| 0.00975075| -0.01066680| 0.01189821| 1.00000000| 0.02227725|
| P2  | 0.00000320| 0.01440423| 0.90834834| 0.04539886| -0.02055987| 0.02782305| -0.03653303| 0.02227725| 1.00000000|


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
| TDOM GSD               |        0.083 m|
| Coverage Area          | 3.973803 sq km|
| Average Flight Altitude|      671.353 m|
## Performance Overview

| Pipeline              | time cost (min) |
| :---:                 | :---:           |
| Image Correction      |        1.136|
| Densification         |       15.841|
| TDOM Generate         |       11.974|

## DSM Preview 
<img alt="DSM Preview" src="./dsm_screennail.png" width=1125 height=1000/>

## Scene Overlap Analyze
<img alt="Overlap" src="./overlap_render.png" width=1125 height=1000/>

