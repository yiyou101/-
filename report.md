# DJI Terra Aerial Triangulation Quality Report

---
## Image Information Overview

| Item                    | Value           |
| :---: | :---: |
| # Input Images          |              140|
| # Image With Position   |              140|
| # Calibrated Images     |              140|
| Use Image Position | True|
| Georeferencing RMSE |   0.028 m|
| # Connected Components     |            1|
| # Max Component Images     |          140|
| Use Cluster    | No|
| Generate XML   | No|
| Use Stereo Mode    | No|
| # feature quantity | Medium|
| SFM Time          |        1.826 min|


## RTK Status

| Status  | Number of Images |
| :---: | :---: |
| FIX     |              140|
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
|     0 | Optimized| 8196.05| 4047.18| 2758.85| -0.04690946| 0.02231282| -0.10322312| 0.00000000| 0.00197451| -0.00166147|


Coefficients and correlation matrix 

|      | Error | F     | Cx    | Cy    | K1    | K2    | K3    | P1    | P2    |
|:---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| F  | 0.10031209| 1.00000000| 0.02923969| -0.02892618| -0.32492342| 0.30561564| -0.28079421| -0.05747599| -0.03778591|
| Cx  | 0.08927980| 0.02923969| 1.00000000| 0.00443903| -0.00953251| 0.01332715| -0.01579905| 0.00908740| 0.88753315|
| Cy  | 0.07629508| -0.02892618| 0.00443903| 1.00000000| -0.00219496| -0.00035416| 0.00216081| 0.88870930| 0.01537197|
| K1  | 0.00009141| -0.32492342| -0.00953251| -0.00219496| 1.00000000| -0.97228700| 0.92127159| 0.00155200| -0.02260878|
| K2  | 0.00055380| 0.30561564| 0.01332715| -0.00035416| -0.97228700| 1.00000000| -0.98467296| -0.00379609| 0.03391196|
| K3  | 0.00099461| -0.28079421| -0.01579905| 0.00216081| 0.92127159| -0.98467296| 1.00000000| 0.00620673| -0.04066753|
| P1  | 0.00000327| -0.05747599| 0.00908740| 0.88870930| 0.00155200| -0.00379609| 0.00620673| 1.00000000| 0.01711156|
| P2  | 0.00000350| -0.03778591| 0.88753315| 0.01537197| -0.02260878| 0.03391196| -0.04066753| 0.01711156| 1.00000000|


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
| Coverage Area          | 3.000025 sq km|
| Average Flight Altitude|      677.104 m|
## Performance Overview

| Pipeline              | time cost (min) |
| :---:                 | :---:           |
| Image Correction      |        0.675|
| Densification         |        9.172|
| TDOM Generate         |        6.144|

## DSM Preview 
<img alt="DSM Preview" src="./dsm_screennail.png" width=1125 height=1000/>

## Scene Overlap Analyze
<img alt="Overlap" src="./overlap_render.png" width=1125 height=1000/>

