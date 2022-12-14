# ShashankA.github.io
#gh repo clone uihilab/WaterBench#

#CWC is currently doing rainfall-based mathematical modelling for flood forecasting which uses both the hydrologic (rainfall-runoff) and hydrodynamic modelling technique for real-time water level and inflow prediction in the river and reservoirs respectively. The five day advance forecast generated is derived from various available rainfall data products and the forecasted rainfall (QPF) provided by IMD, which is used as a major input into the model.

metholodogy
This web portal has been totally developed in-house by CWC for its advisory forecast dessimination. Though the portal shows the model results in its simplest form, what is more important is to understand the activity which is going on in the background. Currently there are 18 river basin models running in the background covering the entire FF network of CWC. These models run every three hours, day and night and display the results. The best part is that the entire process from data collection to results dessimination is automatic with no human intervention.

The process flow of various activities involved in forecast formulation is governed by various scripts which are scheduled to do the required task seamlessly. The system automatically downloads the rainfall data from various sources (both satellite and rain gauge data), processes it in the required format and then injects it into the model automatically. Then all the 18 river models run in sequence and generate the results which then automatically gets displayed on the web.

Hydrologic models
Hydrologic Cycle
Hydrologic models are simplified, conceptual representations of a part of the hydrologic cycle. They are primarily used for hydrologic prediction and for understanding hydrologic processes. Hydrologic models are instrumental in doing Rainfall-Runoff conversion for a basin. These models try to represent the physical processes observed in the real world. Typically, such models contain representations of surface runoff, subsurface flow, evapotranspiration, and channel flow. These models are known as deterministic hydrology models which could be either single event or continuous simulation models.

Hydrodynamic models
Hydrodynamics is the study of motion of liquids, and in particular, water. A hydrodynamic model is a tool able to describe or represent in some way the motion of water. Before the advent of widely available computer systems, a hydrodynamic model could in fact be a physical model built to scale. However, virtually all hydrodynamic models in use today are computational numerical models.

With the technological development of numerical models along with advanced computational systems, hydrodynamic modeling has become part of the larger field of computational fluid dynamics (CFD). The basis for all hydrodynamic modeling activity is the numerical solution of the governing equations of conservation of momentum and mass in a fluid.

HydrodynamicRiver hydrodynamic modeling focuses on the movement of water in the river. The hydrodynamic models used in CWC today, simulate river water flow in all the major river basins of the country. Such hydrodynamic modeling has been accomplished through skillful development combined with understanding of the physical system. CWC models are limited to systems with the properties described by the governing equations, by the capability of the numerical algorithm solving the equations, and by the capacity of the computational system. These factors define the ability of the model to represent a physical system in its numerical framework and require that a user understand the limitations of the modeling approach.

How do hydrodynamic models work?
The basis of computational hydrodynamic models is the set of equations that describe the motion of fluids: the Navier-Stokes equations. These equations are derived from Newton's laws of motion and describe the action of force applied to the fluid; that is, the resulting changes in flow. This is the property of conservation of momentum and is simply Newton's second law: acceleration is dependent upon the force exerted and proportional to its mass. Computational hydrodynamics also imposes the continuity principle: mass and energy are conserved unless they pass out of the domain.

The complexity of the system of prevents solution of the governing equations analytically. Scientific computing has enabled researchers to address these complex problems through numerical methods. However, computers can only perform discrete calculations and therefore the continuous governing equations must be broken into small individual problems that can be quickly solved on a computer. This procedure is governed by the numerical method used for a particular model. Two classes are common in hydrodynamic models: structured grid approaches (primarily finite difference algorithms) and unstructured grid approaches (including finite element and finite volume methods). The numerical methods deal with the domain by separating it into numerous components through a discretization process that produces in a model grid. Structured grid models tend to use quadrilateral grid cells that limit the grid's flexibility in resolving the complex shoreline but are characterized by their straightforward and efficient algorithms. Unstructured grid models have much more flexibility in their grid resolution by employing variable triangular elements, but tend to be more time consuming to run and more sensitive to numerical errors. Both types of numerical methods have been applied to high performance computing systems, enabling simulation of complex river systems at high resolution.

The accuracy of a river hydrodynamic model is closely related to the input provided to it, such as bathymetry and meteorological conditions. These models use a wide range of observational and meteorological data to define the forcing for the model. Similarly, data such as river cross-section, historical discharge and water levels are required for driving the model. The model developers at CWC apply the best data sources available to generate high quality output. However, the accuracy of the model is limited by the quality of data available.

How are hydrodynamic models used?
The main use of hydrodynamic models in CWC is to provide flood forecast guidance for all the 328 Forecasting stations it has on real-time basis. The output include Flood forecast with 120 hours lead time along with a time series of river water surface elevation & discharge on the real-time basis. These results are useful to a wide range of users, provided that sufficient accuracy has been demonstrated from the model. This is generally done by comparing model results to actual site observations.

The CWC flood forecast system is run routinely (three hourly) by a short simulation of the recent past forced by observation data followed by a forecast of the following five days. The model forecast accuracy is primarily governed by accuracy of forecasted rainfall input and decreases the further in time it extends. Hydrodynamic models for flood forecast guidance in CWC are running operationally for all the major flood forecasting stations of the country and continue to be developed and improved further.
Press Information Bureau
Government of India
Ministry of Jal Shakti
03-February-2022 16:52 IST
Challenges of Flood Forecasting 

Flood Forecasting on International & Inter-state Rivers is formulated and issued by Central Water Commission (CWC) using statistical methods for short range forecasting and mathematical modelling for ???veday???s advance ???ood advisory. The main challenge being faced in flood forecasting is to accurately forecast the impending flood sufficiently in advance with high level of accuracy. Mathematical modelling based flood advisory although provide sufficient lead time, its accuracy is dependent on accuracy of weather(rainfall) forecasts. The growing incidents of high intensity rainfall in shorter duration due to likely impact of climate change poses another challenge for flood forecasting.

There is a continuous e???ort for improvement of Flood Forecasting using all the latest technology including space technology tools, Geographical Information System (GIS), web based applications, etc. Following steps have been taken to improve the Flood forecasting system in the country.

Expansion of Flood Forecasting Network: CWC ???ood forecasting network has been expanded to 331 Flood Forecast Stations(199 Level Forecast for Villages/Town on the bank of the rivers and 132In???ow Forecast Stations for Dams and Barrages) covering 23 States &2 UTs in 20 river basins for taking proper mitigation measures by respective State Governments. In the State of Andhra Pradesh, there are 13 level forecasting stations and 10 in ???ow forecasting stations.
Modernization of Flood Forecast Formulation: Flood forecasting is issued up to 5 days in advance for major river basins across the country including the State of Andhra Pradesh. The same is updated every three hours and is available online (https://120.57.99.138/index.php).
Modernization in dissemination of ???ood forecasts: Dissemination of ???ood forecasts has also been modernized through a dedicated website. Daily Flood Situation Report cum Advisory is shared with all stakeholders aswell as general public using social media platforms.
 Bilateral agreements with upper riparian countries Nepal, Bhutan &China have been made for data sharing.

 Common data platform, Water Information Management System(WIMS), under National Water Informatics Centre (NWIC), has been created to ensure seamless data ???ow from States and CWC formodelling work. In addition, arrangements for seamless data ???ow from agencies like INCOIS, NASA, JAXA, etc. have also been made.

This Information was given by the Minister of State for Jal Shakti, Shri Bishweswar Tudu in a written  reply in Lok Sabha today.

