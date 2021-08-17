.. WeMAST documentation master file, created by
   sphinx-quickstart on Thu Apr 29 23:24:40 2021.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.
******************************************************
Wetland Monitoring and Assessment Service
******************************************************

.. toctree::
   :numbered:
   :maxdepth: 5
   :caption: Contents:



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

****************************************
System Documentation
****************************************  

.. image:: Images/Project_area.png
  :width: 400
  :alt: Alternative text

.. figure:: ..Images/Project_area.png
    :width: 600
    :align: left
    :height: 300
    :alt: WeMAST Data Source
    :figclass: align-left
    
****************************************
1.0 General Information
****************************************  

Wetland Monitoring and Assessment service is a geoportal applied in assessing andmonitoring
Wetland and transboundary health overtime.The various sub indicators used are given a correlation
that assesses the anthropogenic pressures and utilization of wetland resources overtime. The goal is towards
achivement of sustainable use of wetland resources, while ensuring that the resources serves the all the 
players in need.




1.1 Contanct the team
==================================================================================================================
Please contact the `SASSCAL <https://www.sasscal.org/contact-us/>`_ team if in need of any bug reporting, ideas as well as contribution that will
make the service better. 


1.2 Acknowledgement
==================================================================================================================
The feedback provided by users of WeMAST service and by the participants in the webinars and workshops 
held by SASSCAL org have been critical to the development of the Service.
The team included a list of patnering institutions in patnership with the private sector, who were the implemeneters of the assignement.


1.3 Lincenses
==================================================================================================================
WeMAST service is open and free to be used by the plethora of users. The linces is under the GNU General Public User Linceses, version 2.0.0
The WeMAST service product are made available under the Creative Commons Attribution 4.0 International Lincenses (CC YY 4.0).
The names and boundary do not imply official endorsement or acceptance by the South African Development Community, comprosing of the four
Transboundary Basins, i.e Cuvelai, Zambezi, Limpopo and Okavango.


****************************************
2.0 Background
****************************************

.. figure:: ..Images/Project_area.png
    :width: 500
    :align: left
    :height: 300
    :alt: WeMAST Data Source
    :figclass: align-left



2.1 Data Source
========================================================================================================================================
WeMAST Monitoring adn Assessment service is developed in adherance to Open Geospatial Consortium (OGC) standards. The data sources are 
standadized and acquired from open source, that can be accessible by interested players in Wetland Management and Assessment.
The data sources covers the various sub indicators. The sub indicators are largely sub divided into major indicators.
The major indicators include:
The developed sub-indicators were subdivided into three categories, namely the 
	**i.Sensitivity sub indicators**: Sensitivity is described as the degree to which a wetland is affected,
	either adversely or beneficially, by climate-related stimuli, 
	including the following elements of climate change: mean climate characteristics and climate variability (Ramsar Framework).

	**ii.The exposure sub indicators**: Exposure is described as the probability of an ecosystem to be affected by adverse
 	conditions and hazards, as a results of historical mismanagement or conditions that led to reduction in resilience.

	**iii.Resilience sub indicators**: Resilience of an ecosystem is described as the ability to cope against experienced hazards.
The above categirized indicators, had root sub indicators that were defined in ache category. These sub indicators are then used in modelling
the Wetland and Transboundary basin conditions and health. The various sub indicators are listed below.


.. figure:: ..Images/Project_area.png
    :width: 600
    :align: left
    :height: 500
    :alt: WeMAST Data Source
    :figclass: align-left
    
    Table 1: WeMAST Service Data Source 


2.2 Data Preparation
===================================================================================================================================================
Monitoring and assessing the wetland and basin conditions, extents and trends require data preparation and computation integrity. 
This depends on the use of desired data sets, prepared and visualized in a format that is easily interpreted. The outputs generated depends on the input data, thus, it is vital to input a well-preprocessed data in order to visualize a favorable output.

This report is therefore intended to provide a guide to the data preparation and outline the processing chains requirements and visualization procedures. 
Wetland monitoring and assessment is dependent on the satellite imagery products termed as sub indicators that are computed from the combination of specific multi-spectral bands. The desired band combination is used in computations to produce the desired output. The desired products are then uploaded into the WeMAST GeoServer, whereby they are made accessible to the client upon request, in form of Geovisualised maps, charts, time series data, statistics as well as tabulated Metadata. 

Few in-situ computations are however applied in the backend system to generate real time monitoring and assessment results such as burnt areas, flooded zoned areas, vegetation cover and land use land cover change maps based on the availability and temporal frequency of the datasets.
The WeMAST geoportal system is envisioned to provide a monitoring and assessment baseline information for the 4 major basins together with the existing wetland areas within the sub basins. The basins are the Zambezi, Cuvelai, Limpopo and Okavango.

The sub - indicators applied in monitoring wetland and basin conditions are largely categorized into three, in order to capture the sustainable use of the basin resources while assessing their sensitivity, exposure as well as resilience on their continuous use.
The sub indicators that are used to study the above conditions are listed below, with their procedures discussed in the 
`Data Preparation Manual <https://drive.google.com/file/d/1yDdZSvnr14I5uU0nMDh77FSQfpqN5N50/view?usp=sharing/>`_.
	
	* Land Use Land cover 
	* Vegetation Phenometrics 
	* Water Extent 
	* Wetland Inventory 
	* Water Quality Indicators 
	* Flood Mapping
 
Each of these sub indicators have been uniquely prepared in order to give the desired outputs as is visualized for the WeMAST Geoportal.
Please refer `HERE <https://drive.google.com/file/d/1yDdZSvnr14I5uU0nMDh77FSQfpqN5N50/view?usp=sharing/>`_. for data preparation and computation algorithms.


2.3 Data Uploading
=======================================================================================================
Generally, after acquisition and the subsequent steps of data preparation, the next step is to appload the document to the database.
In our case, this prividledge belong to the system administrators, who have the role of preparing data as soon as they are available, and later uploading the same to the system


2.4 Data Downloading
=======================================================================================================

Since we have users who are interested in analysis and undestanding the data that is used to develop and generate the various outputs, the linkage to the backenmd is therefore provided for in the system.
The users can access the data in the backend using the available QGIS plugin or download the raw file as showcased in the system.
This will allow for the user to do further analysis if need be. See the steps below.

****************************************
4.0 WeMAST System Output 
****************************************
WeMAST system is designed to visualize the sub-indicators and allow for on-fly computation.
The computation is designed to output the statistics as well as time series charts and graph of the specific sub indicators.
The specific sub indicators computation are computed as is outlined in the next sub sections.


4.1 Exposure Indicators
=======================================================================================================

4.1.1 Land Use Land Cover LULC
===================================

The LULC is an ESA product.
The integration of the biophysical and human factors plays a leading role in causing land cover 
changes, and is used to explain the dynamics of land usage and trend that occur within an ecosystem.
The analysis of LULC data set overtime, is capable of visualising trends of human actions and impacts on the 
Wetland and basin resources in relation to the vulnerable population. To compute the LULC land cover, the following steps are applied in the system.
 
4.1.2 Vegetation Phenometrics - NDVI
======================================================================
Product derived from indexing the Near Infrared (NIR) band and the Red band from satellite image.
Used to assess the difference in seasonal vegetation characteristics, 
concerning the phenology of the vegetation greenness and productivity overtime. See the `Data Preparation Manual <https://drive.google.com/file/d/1yDdZSvnr14I5uU0nMDh77FSQfpqN5N50/view?usp=sharing/>`_.

4.1.3 **Wetland Inventory** Water Extent
======================================================================
Water extent is assessed through the use of Normalised Difference Water Index (NDWI).
NDWI is a satellite-derived product, achieved after indexing SWIR and NIR bands of a satellite image. It captures the in season pure water pixels. The reduction of water areas correlates to low water quality, while the reverse correlates to increased precipitation and relatively reduced affluent deposition in water areas.

4.1.3 **Wetland Inventory** Wetland Status
======================================================================
Wetland Status is a product generated by proxy dataset (NDVI), it is achieved through the reclassification fo the 
NDVI value to achieve a specified output. The specified output is termed as the Water and Wetness Probability Index (WWPI).
display the dry, wet or water covered areas. The wet areas show places with high soil moisture content, while the dry areas are places susceptible to drought and may have little or no vegetation cover. The water areas are the open known wetlands and open surface water areas such as lakes.


