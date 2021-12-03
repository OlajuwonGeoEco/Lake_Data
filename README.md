# Lake_Data
I worked on datasets from Oklahama and Texas lakes. The goal of this analysis was to find specific factors that influenced the nutrient (Nitrogen and Phosphorus) levels in these states 
and they were numerous variables. 

The factors were grouped into internal vs external factors.

I did the PCA to see important variables for internal, external, and the whole data.

For Internal: Maxdepth,Watershed:LV,  and Secchi Depth
For External: OpenWater, Slope, Mean Temp, Large and Intermediate Watershed, Herbaceous
Combined: Openwater, Latitude, Totallivestock_watershedarea, A-High-infiltration.

Finally, I ran a random forest

The random forest was classified by state. Classification had zero percent error.

The most important variables according to the random forest are Latitude > TN:TP > Barren > Mean_Temp> AvgTN> MaxDepth> Wetlands.
