# Travel-Time-Data
Alternative Source of Highway and Transit Skims for Use in Transportation Models

Traditionally, mode choice models use travel times estimates from the regional travel demand model. This provides a zone to zone travel time by highway and transit modes. The walk and bike travel times are calculated by dividing the distance by approximate walk/bike speeds (Koppelman and Bhat, 2006). This modeled traveled time is a crude approximation compared to the actual travel time experienced by travelers. Moreover, since these modeled travel times are retrieved from travel demand models developed in the past, they do not always have the latest service information. This can be overcome by using Google Maps Distance Matrix/Directions API, which returns point to point travel time estimates for trips by different modes of travel.

This repository contains a notebook which can be used to retrieve travel time data by different modes of transport for any given origin-destination pair. The output will contain driving duration, driving distance, bike duration, bike distance, walk duration, walk distance for the automobile, bike and walk mode respectively. For the transit mode, information is gleaned from the response of the directions api such as total transit travel time, total distance, access duration, access distance, egress duration, egress distance and number of transfers.

# For more information

Noor, Albab. "Market Segmentation of Travel Mode Choice with An Alternative Source of Travel Time Data", MS Thesis, 2018, University of Connecticut

# Attribution

If this code is useful in your research or work, please cite this package by citing the thesis above.
