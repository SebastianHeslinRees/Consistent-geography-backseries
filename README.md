# Consistent-Geography-Backseries

---

This repository contains utilities for generating a consistent backseries between the 2011 and 2021 ONS population estimates. The provided functions facilitate the creation of a unified geography with areas that have been split or merged from 2011 to 2021, as well as handling more complex geography changes between 2011 and 2021. The functions are designed to accept varied geographic inputs, such as MSOA or LSOA.

## Contents

- **consistent_geography_backseries_functions**: This notebook contains the finalised functions for generating the consistent population backseries. It includes functions for creating a consistent geography such as handling split or merged areas, mapping geographic boundaries and the geographic differences between 2011 and 2021, providing a visual representation for analysis, and finally merging the necessary populations.

- **consistent_backseries_geo_dev_script**: This is a development script notebook to records the process of how the functions were generated. It serves as a development log documenting the evolution of the functions and their implementation. This will be deleted at a later date but is still required for development.

## Usage

To use the functions provided in the finalised functions notebook, simply import them into your Python environment and provide the necessary inputs, such as the ONS population data for 2011 and 2021, as well as the relevant area codes and boundary shapefiles which can typically be found [here](https://geoportal.statistics.gov.uk/). The functions are designed to be flexible and accommodate various geographic inputs.

## Note

These utilities are intended to assist in generating consistent backseries for population estimates. They are provided as-is and may require adaptation to suit specific use cases or data formats. Contributions and feedback are welcome.

Feel free to adapt this README as needed for your repository.
