# FireRadiativePower
Research thesis code <br>
<b> Introduction </b>
Increasing fire in the Western US [1] has led to increased interested in wildfire emissions, including carbon dioxide, carbon monoxide, methane, nitrogen oxides, and aerosols [2-5]. Fire emissions have imporant impacts on atmospheric chemistry, radiative forcing, and local and regional air quality.
Fire Radiative Power (FRP) measured using remotely sensed data provides a means for quantifying burned biomass and estimating fire emissions. FRP has been utilized in examples such as quantifying burned biomass in the Amazonian region of Brazil [6], and even for assessing gas flaring heat from industries [7]. FRP is based on Planck's function, which explains the spectral radiance distribution of a theoretical blackbody as a function of temperature. The parameterization of FRP can be seen in the 'FRP Formulation' section.

<b> Case Study: William's Flats Fire </b>
In the summer and fall of 2019, NASA and NOAA flew the FIREX-AQ campaign to collect novel datasets over the Western US wildfires with various airborne instruments, thereby presenting a unique opportunity to compare different FRP retrievals. For this work, we utilize data collected over the Williams Flats Fire in Washington state on 6 August 2019. Multispectral data were collected by the MASTER (MODIS/ASTER Airborne Simulator) instrument on the DC-8 aircraft. Multispectral eMAS (Enhanced MODIS Airborne Simulator) and hyperspectral AVIRIS (Airborne Visible Infrared Imaging Spectrometer) data were collected instruments on the ER-2 aircraft. Due to the malfunctioning of the eMAS 4.06 μm band, typically used to derive FRP from multispectral instruments, and the limited coincident of fire observations with MASTER, there is a need to investigate the relationship between FRP based on a 2.38 μm shortwave infrared band (on eMAS and AVIRIS) and the traditionally used 4.06 μm mid-infrared band (on MASTER). 
Given that extreme high-temperature events could produce high radiance signals within the SWIR according to Planck’s function, this presents a unique opportunity to explore the SWIR portion of the spectrum for quantifying FRP.

<b> Research Objectives </b>
Compare the non-traditional 2.38 μm band radiance between MASTER, eMAS, and AVIRIS
Compare FRP at 2.38 μm for all three sensors and the traditional 4.06 μm  band with MASTER
An area by area comparison between all three sensors
