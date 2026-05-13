# Comp-Final-Description

## Scientific Question 
How do the two generations of GCM (CMIP6 & CMIP5) compare to the RCM Cordex-Africa in representing annual max temperatures (TX) in near term (2021-2040), high emissions scenarios (SSP5-8.5), specifically over IPCC bounds for South-Eastern Africa (SE-AF)?

## Hypothesis
GCMs CMIP6 and CMIP5 will have a coarser and warmer projected annual maximum temperature (TX) bias over SE-Africa compared to RCM CORDEX-Africa. CMIP6 shows improvement over CMIP5 due to model advancements, while CORDEX Africa will capture even finer spatial variability in TX due to its high regional resolution.  

## Dataset

Data for [CMIP6](https://interactive-atlas.ipcc.ch/regional-information#eyJ0eXBlIjoiQVRMQVMiLCJjb21tb25zIjp7ImxhdCI6LTY4NTQyNiwibG5nIjo4NzYzNCwiem9vbSI6MywicHJvaiI6IkVQU0c6NTQwMzAiLCJtb2RlIjoiY29tcGxldGVfYXRsYXMifSwicHJpbWFyeSI6eyJzY2VuYXJpbyI6InNzcDU4NSIsInBlcmlvZCI6Im5lYXIiLCJzZWFzb24iOiJ5ZWFyIiwiZGF0YXNldCI6IkNNSVA2IiwidmFyaWFibGUiOiJ0YXNtYXgiLCJ2YWx1ZVR5cGUiOiJWQUxVRSIsImhhdGNoaW5nIjoiU0lNUExFIiwicmVnaW9uU2V0IjoiYXI2IiwiYmFzZWxpbmUiOiJBUjUiLCJyZWdpb25zU2VsZWN0ZWQiOltdfSwicGxvdCI6eyJhY3RpdmVUYWIiOiJwbHVtZSIsIm1hc2siOiJub25lIiwic2NhdHRlcllNYWciOm51bGwsInNjYXR0ZXJZVmFyIjpudWxsLCJzaG93aW5nIjpmYWxzZX19), [CMIP5](https://interactive-atlas.ipcc.ch/regional-information#eyJ0eXBlIjoiQVRMQVMiLCJjb21tb25zIjp7ImxhdCI6LTY4NTQyNiwibG5nIjo4NzYzNCwiem9vbSI6MywicHJvaiI6IkVQU0c6NTQwMzAiLCJtb2RlIjoiY29tcGxldGVfYXRsYXMifSwicHJpbWFyeSI6eyJzY2VuYXJpbyI6InJjcDg1IiwicGVyaW9kIjoibmVhciIsInNlYXNvbiI6InllYXIiLCJkYXRhc2V0IjoiQ01JUDUiLCJ2YXJpYWJsZSI6InRhc21heCIsInZhbHVlVHlwZSI6IlZBTFVFIiwiaGF0Y2hpbmciOiJTSU1QTEUiLCJyZWdpb25TZXQiOiJhcjYiLCJiYXNlbGluZSI6IkFSNSIsInJlZ2lvbnNTZWxlY3RlZCI6W119LCJwbG90Ijp7ImFjdGl2ZVRhYiI6InBsdW1lIiwibWFzayI6Im5vbmUiLCJzY2F0dGVyWU1hZyI6bnVsbCwic2NhdHRlcllWYXIiOm51bGwsInNob3dpbmciOmZhbHNlfX0=), [CORDEX-Africa](https://interactive-atlas.ipcc.ch/regional-information#eyJ0eXBlIjoiQVRMQVMiLCJjb21tb25zIjp7ImxhdCI6LTY4NTQyNiwibG5nIjo4NzYzNCwiem9vbSI6MywicHJvaiI6IkVQU0c6NTQwMzAiLCJtb2RlIjoiY29tcGxldGVfYXRsYXMifSwicHJpbWFyeSI6eyJzY2VuYXJpbyI6InJjcDg1IiwicGVyaW9kIjoibmVhciIsInNlYXNvbiI6InllYXIiLCJkYXRhc2V0IjoiQUZSLTIyIiwidmFyaWFibGUiOiJ0YXNtYXgiLCJ2YWx1ZVR5cGUiOiJWQUxVRSIsImhhdGNoaW5nIjoiU0lNUExFIiwicmVnaW9uU2V0IjoiYXI2IiwiYmFzZWxpbmUiOiJBUjUiLCJyZWdpb25zU2VsZWN0ZWQiOltdfSwicGxvdCI6eyJhY3RpdmVUYWIiOiJwbHVtZSIsIm1hc2siOiJub25lIiwic2NhdHRlcllNYWciOm51bGwsInNjYXR0ZXJZVmFyIjpudWxsLCJzaG93aW5nIjpmYWxzZX19) are sourced from **IPCC WGI Interactive Atlas** as NetCDF files

## Potential graphs of generation
+ Fig 1 - Cartopy Map; Array of Models over Africa 
+ Fig 2 - 3 Array Panel Cartopy; mean TX spatial by model family over SE-AF
+ Fig 3 - 2 Array Panel Cartpoy; CMIP6 minus CMIP5, CMIP6 minus CORDEX-Africa over SE-AF
+ Fig 4 - Time Series; Regional Mean TX 2021-2041 over SE-AF
+ Fig 5 - Zonal Mean; Latitude vs Longitude profile of TX
+ Fig 6 - Histogram; Distribution of Values over SE-AF (CMIP6 v CMIP5 v CORDEX)  
+ Fig 7 - Grouped bar Chart; Annual TX ANomally relative to Baseline


