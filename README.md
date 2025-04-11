
![Cyanobacteria-Research-in-Lake-Victorias-Winam-Gulf-1737785011-1](https://github.com/user-attachments/assets/bfc5c5d7-7801-4a25-bf3c-db96ee0925f3)


# <ins>Estimating Chloropyhll-a Concentrations in Lake Victoria</ins>

The project focuses on utilizing satellite imagery and remote sensing techniques to estimate **Chlorophyll-a (Chl-a)** levels in Lake Victoria, the largest lake in Africa. Chlorophyll-a is a key pigment in phytoplankton and is widely used as an indicator of water quality and ecosystem health, particularly for tracking eutrophication and algal blooms.

The study employs Google Earth Engine (GEE) and Landsat 8 satellite imagery to estimate Chl-a concentrations over Lake Victoria for the year 2023. Landsat 8 is chosen for its optimal spatial resolution (30m), free data availability, and suitable spectral bands for water quality analysis. The analysis begins with preprocessing steps such as cloud and shadow masking, scaling radiometric values, and extracting water surfaces using the _Modified Normalized Difference Water Index (MNDWI)_.

Once the water body is isolated, the _Normalized Difference Chlorophyll Index (NDCI)_ is computed using red and red-edge bands as a proxy for Chl-a distribution. The final estimation of Chl-a concentration is performed using a mathematical model derived from recent literature, applying an exponential formula based on the ratio of specific reflectance bands (Green/Blue). This allows for pixel-wise calculation of Chl-a levels across the lake.

This project not only provides a scalable method for monitoring Chl-a across time but also supports the management of Lake Victoria's ecosystem by helping detect ecological stressors, guiding fisheries, and informing transboundary environmental policies.




