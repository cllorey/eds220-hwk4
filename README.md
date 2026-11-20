# Visualizing Fire Scars from the 2025 Eaton and Palisades Fires

![AP Photo/Etienne Laurent](/Users/courtneylorey/Desktop/GitHub/eds220/eds220-hwk4/data/ap25007862800451p.jpg)

Water is dropped by helicopter on the advancing Palisades Fire in the Pacific Palisades neighborhood of Los Angeles, Tuesday, Jan. 7, 2025.
[AP Photo/Etienne Laurent](https://www.capradio.org/articles/2025/01/08/wildfires-latest-hundreds-of-thousands-without-power-as-wildfires-tear-across-california/)

## About
This repository contains a notebook hwk4-task2-false-color-LOREY.ipynb visualizing the January 2025 Eaton and Palisades fire scars. 

After examining landsat and fire perimeter datasets, we create a false color image showing the extent, vegetation health, and burn severity of the scars.

## Repository Structure

```
eds220-hwk4
├── README.md
├── hwk4-task2-false-color-LOREY.ipynb
└── .gitignore
```

## Data
The data for this analysis is not housed in this repository. Landsat data was downloaded from the Microsoft Planetary Computer and clipped to an area surrounding the fire perimeters by the EDS 220 teaching team before being used locally. The specific file used in this exercise can be downloaded using [this link](https://drive.google.com/drive/folders/1USqhiMLyN8GE05B8WJmHabviJGnmAsLP?usp=sharing).

Data files:
* `landsat8-2025-02-23-palisades-eaton.nc`

Fire perimeter data was retrieved from the [official LA County site](https://data.lacounty.gov/maps/ad51845ea5fb4eb483bc2a7c38b2370c/about) and used locally. 

Data files:
* `Eaton_Perimeter_20250121.shp`
* `Palisades_Perimieter_20250121.shp`

## Authors
[Courtney Lorey](https://github.com/cllorey/cll214final), Bren School of Environmental Science & Management, University of California, Santa Barbara

## References

County of Los Angeles. (2025). *Palisades and Eaton Dissolved Fire Perimeters* [Data set]. LA County Open Data. Retrieved November 19, 2026, from [https://data.lacounty.gov/maps/ad51845ea5fb4eb483bc2a7c38b2370c/about](https://data.lacounty.gov/maps/ad51845ea5fb4eb483bc2a7c38b2370c/about)

County of Los Angeles. (n.d.). *Data and recovery tools* [dataset]. LA County Recovers. Retrieved November 19, 2026, from [https://recovery.lacounty.gov/data-recovery-tools/](https://recovery.lacounty.gov/data-recovery-tools/)

Microsoft Planetary Computer. (n.d.). *Landsat Collection 2 Level-2 atmospherically corrected surface reflectance data* [dataset]. Landsat Collection 2 Level-2. Retrieved November 19, 2026, from [https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2](https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2))
