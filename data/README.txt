Contact md.monitoring@noaa.gov with any questions about this dataset.

--------------------------------------------------
MDMAP_Export_20230827.csv
--------------------------------------------------

CSV file containing MDMAP survey data and debris counts from the water’s edge to the back barrier of the shoreline. Data were collected using multiple protocol versions. The protocol version is denoted in the survey_protocol column.
Protocol versions are:

MDMAP 2.0
Initiated spring 2021.
As described in Burgess, H.K., Herring C.E., Lippiatt S., Lowe S., & Uhrin A.V. (2021). NOAA Marine Debris Monitoring and Assessment Project Shoreline Survey Guide. National Oceanic and Atmospheric Administration Marine Debris Program.

MDMAP Standing Stock Protocol
MDMAP Accumulation Protocol
Discontinued fall 2021.
As described in Lippiatt, S., Opfer S., & Arthur, C. (2013). Marine Debris Monitoring and Assessment. National Oceanic and Atmospheric Administration Technical Memorandum NOS-OR&R-46.

Each row represents a survey of a transect from the water’s edge to the back barrier of the shoreline. 

The number and dimensions of the transects vary according to the protocol version. 

MDMAP 2.0. At least four transects are surveyed within a fixed site of dimensions beach width x site length for each survey date. Debris items 2.5cm and larger are counted in categories according to material and item type. Debris is removed or left in place, which is recorded.

Standing Stock - transect dimensions are the beach width x 5m. At least four transects were surveyed within a fixed site of dimensions beach width x site length for each survey date. Debris items 2.5cm and larger are counted according to material and item type. Debris was left in place.  

Accumulation - transect dimensions are the beach width x the site length, i.e equivalent to the site dimensions. The site was cleaned from the water’s edge to the back barrier, all debris items 2.5cm and larger were counted in categories according to material and item type. 

Debris count columns appear in order by standard material and item type (material:item) as described in 
NOAA Marine Debris Program. (2021). NOAA Marine Debris Monitoring and Assessment Project Marine Debris Item Categorization Guide. 

Custom items, which are subtypes of the standard material and item types that are tracked by only some data collectors, occupy columns to the right of the standard list (materia:item:custom type). Custom item cells may be blank if that custom item type was not considered for that site and survey. Cells will be zero or counts if the item was tracked for that site and survey.

Material:item counts include any custom type counts within that category. Total material counts (total:material) include all material:item counts within that material type. Total debris (total:debris) is a total of all debris 

Because transect dimensions vary, units are not common across sites and protocols. Raw counts from the different protocols and beach lengths should be converted into common units (items per area or length of shoreline) as appropriate for analysis.

Data were cleaned and formatted to be compatible in a common spreadsheet. Steps included normalization and standardization of custom item types and their relationships to standard material and item types, as well as correcting for variable methods of recording custom item counts prior to 2021. 

--------------------------------------------------
MDMAP_Export_20230827_backbarrier.csv
--------------------------------------------------

CSV file containing survey data and debris counts from the edge of the back barrier to two meters landward, following MDMAP 2.0

Initiated spring 2021.
As described in Burgess, H.K., Herring C.E., Lippiatt S., Lowe S., & Uhrin A.V. (2021). NOAA Marine Debris Monitoring and Assessment Project Shoreline Survey Guide. National Oceanic and Atmospheric Administration Marine Debris 