# DJI Terra Aerial Triangulation Quality Report

---
## Image Information Overview

| Item                    | Value           |
| :---: | :---: |
| # Input Images          |             6346|
| # Image With Position   |             6346|
| # Calibrated Images     |             3637|
| Use Image Position | True|
| Georeferencing RMSE |   0.476 m|
| # Connected Components     |            3|
| # Max Component Images     |         2487|
| Use Cluster    | No|
| Generate XML   | No|
| Use Stereo Mode    | No|
| # feature quantity | Medium|
| SFM Time          |      270.584 min|


## RTK Status

| Status  | Number of Images |
| :---: | :---: |
| FIX     |             6300|
| FLOAT   |                0|
| SINGLE  |               44|
| NONE    |                2|



## Camera Calibration Information

Camera Model ZenmuseP1 

Camera SN 3XMDH9W0010067 

Lens SN 08LY106G003P 

| Item     | Focal   | Cx      | Cy      |   K1  |   K2  |   K3  |   K4  |   P1  |   P2  |
| :---:    | :---:   | :---:   | :---:   | :---: | :---: | :---: | :---: | :---: | :---: |
| Initial  | 8192.00| 4096.00| 2730.00| 0.00000000| 0.00000000| 0.00000000| 0.00000000| 0.00000000| 0.00000000|

| Block     | Item     | Focal   | Cx      | Cy      | K1    |   K2  |   K3  |   K4  |   P1  |  P2   |
| :---:     | :---:    | :---:   | :---:   | :---:   | :---: | :---: | :---: | :---: | :---: | :---: |
|     0 | Optimized| 8196.76| 4050.13| 2755.26| -0.04645396| 0.02110525| -0.10028866| 0.00000000| 0.00192949| -0.00162707|


Coefficients and correlation matrix 

|      | Error | F     | Cx    | Cy    | K1    | K2    | K3    | P1    | P2    |
|:---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| F  | 0.02285131| 1.00000000| 0.05088506| 0.00632092| -0.23035041| 0.20779967| -0.18824876| -0.00806955| -0.00339159|
| Cx  | 0.01459312| 0.02815733| 1.00000000| -0.00006440| 0.00001517| -0.00011483| 0.00032832| 0.00048169| -0.03135885|
| Cy  | 0.01200641| 0.00760950| 0.00125045| 1.00000000| -0.00013451| 0.00020616| -0.00031582| -0.02793118| 0.00064304|
| K1  | 0.00001414| -0.26035118| -0.00996631| 0.00257172| 1.00000000| -0.97454978| 0.92439768| 0.01376290| -0.01152620|
| K2  | 0.00008586| 0.22787687| 0.01506263| -0.00300140| -0.97317368| 1.00000000| -0.98512415| -0.01514360| 0.01121998|
| K3  | 0.00015492| -0.21379783| -0.02032086| 0.00342789| 0.92186640| -0.98381576| 1.00000000| 0.01756770| -0.01898621|
| P1  | 0.00000024| -0.02146013| -0.00561360| 1.80926891| 0.01400271| -0.01559801| 0.01857918| 1.00000000| -0.02271787|
| P2  | 0.00000024| -0.08888319| 2.19671336| -0.00002179| -0.01087214| 0.01078371| -0.01853428| -0.02236931| 1.00000000|


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
<img alt="TDOM Preview" src="./dom_screennail.png" height=1125 width=830/>

## Map Information Overview

| Item                   | Value           |
| :---: | :---: |
| TDOM GSD               |        0.064 m|
| Coverage Area          | 15.006159 sq km|
| Average Flight Altitude|      520.796 m|
## Performance Overview

| Pipeline              | time cost (min) |
| :---:                 | :---:           |
| Image Correction      |       66.868|
| Densification         |      356.728|
| TDOM Generate         |      420.350|

## DSM Preview 
<img alt="DSM Preview" src="./dsm_screennail.png" width=1125 height=830/>

## Scene Overlap Analyze
<img alt="Overlap" src="./overlap_render.png" width=1125 height=830/>

