
Qom
===

Qom is a new lumped rainfall-runoff hydrologic model intended to separate and quantify the volumes of losses and excesses of rainwater falling in a river basin, and it is featured by a limited set of continuous decision variables associated with soil moisture and direct runoff. It described in the paper `[ZGN20] <https://doi.org/10.3390/app10010251>`_, where a multi-objective optimization approach is used for the calibration of the model.

The simplified conceptual perception of the model allows the simple reproduction of those physical phenomena involved in the complex hydrological cycle.  The results are mathematically validated by means of three calibratable parameters and exponential functions that relate evapotranspiration, water stored on the surface, and water stored in the soil with the processes of infiltration and percolation. Qom considers antecedent humidity, it is applicable to urban and rural basins, for permeable and impermeable soils, and considers simple and continuous rain events for prolonged series of time of several years, including dry and humid periods with records spaced in time from minutes to one day. The purpose of Qom is to contribute to the prediction of hydrographs and to determine direct runoff. Qom requires association with some attenuation and transit model, so Qom was associated with Clark.

In this project we provide Qom as a standalone Java problem, that can be executed from the command line with the only requirement of having a JRE 8+ (Java Runtime Environment version 8 or higher) installed. There is another version called Qom-opt to find the parameters automatically through calibration and validation methods (see project https://github.com/Qom-Hydrology/Qom-optimization). For the calibration, multi-objective optimization has been used through two objective functions to be minimized with adjustment indicators between observed and estimated hydrographs. 

References
----------
[ZGN20]: Gustavo R. Zavala, José García-Nieto, Antonio J. Nebro. Qom—A New Hydrologic Prediction Model Enhanced with Multi-Objective Optimization. Applied Sciences 2020, 10(1), 251; `DOI <https://doi.org/10.3390/app10010251>`_.


Project structure
----------------- 

To be developed ...

Running Qom
-----------

To be developed ...

Analysis of the results
-----------------------

To be developed ...

