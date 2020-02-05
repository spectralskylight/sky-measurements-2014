# Sky Measurements
![](pcg.png)

This repository is the data from the follow work:

ACM TOG 33(6) - Proceedings of ACM SIGGRAPH ASIA (**2014**)<BR>
**A Framework for the Experimental Comparison of Solar and Skydome Illumination**<BR>
[Joseph T. Kider Jr.](http://www.josephkider.com/), [Daniel T. Knowlton](http://www.danknowlton.com/), [Jeremy Newlin](http://www.jeremynewlin.info/), [Yining Karl Li](https://www.yiningkarlli.com/), and [Donald P. Greenberg](http://www.graphics.cornell.edu/people/director.html)


![](paper.png)



##### Abstract
---
The illumination and appearance of the solar/skydome is critical for many applications in computer graphics, computer vision, and daylighting studies. Unfortunately, physically accurate measurements of this rapidly changing illumination source are difficult to achieve, but necessary for the development of accurate physically-based sky illumination models and comparison studies of existing simulation models.

To obtain baseline data of this time-dependent anisotropic light source, we design a novel acquisition setup to simultaneously measure the comprehensive illumination properties. Our hardware design simultaneously acquires its spectral, spatial, and temporal information of the skydome. To achieve this goal, we use a custom built spectral radiance measurement scanner to measure the directional spectral radiance, a pyranometer to measure the irradiance of the entire hemisphere, and a camera to capture high-dynamic range imagery of the sky. The combination of these computer-controlled measurement devices provides a fast way to acquire accurate physical measurements of the solar/skydome. We use the results of our measurements to evaluate many of the strengths and weaknesses of several sun-sky simulation models. We also provide a measurement dataset of sky illumination data for various clear sky conditions and an interactive visualization tool for model comparison analysis available online.

##### Data
---

All data was captured on the roof of [Rhodes Hall](https://www.fs.cornell.edu/fs/facinfo/fs_facilinfo.cfm?facil_cd=2051) at [Cornell University](https://www.cornell.edu/).<BR>
latitude : 42.443449 <BR>
longitude : -76.481962


| Capture Time | Spectral Data | HDR Imagery | Pyranometer | Rapid Refresh (3D grid) | Ground Stations
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| **2013_05-27__09-30** | [Radiance Files](data/2013-05-27/RADIANCE/2013-05-27___09.30.00.7z)  | [HDR data](data/2013-05-27/HDR/2013_05-27__09-30-48.7z)  | [Irradiance](data/2013-05-27/IRRADIANCE/2013.05.27.09.30.00.txt)  | [3D Grid Data](data/2013-05-27/RR/RR_CONUS_13km_20130527_1300.grib2)  | [Station Data](data/2013-05-27/GROUNDSTATIONS/20130527_0000.7z)  |
| **2013_05-27__09-45** | [Radiance Files](data/2013-05-27/RADIANCE/2013-05-27___09.45.00.7z)  | [HDR data](data/2013-05-27/HDR/2013_05-27__09-45-48.7z)  | [Irradiance](data/2013-05-27/IRRADIANCE/2013.05.27.09.45.00.txt)  | [3D Grid Data](data/2013-05-27/RR/RR_CONUS_13km_20130527_1300.grib2)  | [Station Data](data/2013-05-27/GROUNDSTATIONS/20130527_0000.7z)  |
