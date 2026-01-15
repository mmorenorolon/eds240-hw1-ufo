# Interpreting `{ggplot2}` code: Insights into UFO sightings

## Overview
This repository contains code and supporting files used to recreate and annotate a multi-panel infographic summarizing over 88,000 reported UFO sightings across the United States. The project focuses on understanding how complex visualizations are constructed in ggplot2, including layering, faceting, inset elements, and custom theming.

The work was completed as part of a data visualization assignment and emphasizes both code interpretation and design reasoning rather than original data analysis. The full assignment description can be found on the [course website](https://eds-240-data-viz.github.io/course-materials/assignments/HW1.html).

## Repository Contents

This repository is organized as follows:

```
eds240-hw1-ufo
├───fonts
├───HW1_files
├───HW1.html
├───HW1.qmd
├───images
├───outputs
└───README.md
```

- `images/`
Includes external image assets used in the visualization (e.g., the UFO graphic).

- `outputs/`
Stores the final rendered infographic exported using `ggsave()`.

## Data Access

This project uses publicly available data from TidyTuesday.
The datasets are not stored locally in the repository and are accessed directly via URLs within the R script.

UFO sightings data and location metadata are loaded using `readr::read_csv()` from the TidyTuesday GitHub repository.

No authentication or API keys are required.

An active internet connection is necessary to run the script successfully. 

## Authors & Contributors

Melannie Moreno Rolón
Graduate Student, Environmental Data Science
[GitHub Profile](https://github.com/mmorenorolon)

This repository represents individual coursework and is not a collaborative project.

## References & Acknowledgements

Oehm, D. — Original visualization concept

Shanny-Csik, S. — Course materials and updated visualization structure (EDS 240)

TidyTuesday Project — Public data source for UFO sightings
https://github.com/rfordatascience/tidytuesday

Additional R packages used include:
`tidyverse`, `ggplot2`, `geofacet`, `ggtext`, `patchwork`, `magick`, and `sysfonts`.

## Contributing

This repository was created for a course assignment and is not actively maintained. While formal contributions are not expected, feedback or suggestions are welcome. If you notice an issue or have a suggestion, feel free to open an issue describing the problem or idea.

## License

1. **Code**  
All code in this repository is licensed under the MIT License, which permits reuse, modification, and distribution with attribution.

2. **Content & Visualizations**

Non-code content, such as the infographic output and written materials, is licensed under Creative Commons Attribution 4.0 (CC BY 4.0) unless otherwise noted.

3. **Data**

This repository does not redistribute original datasets. All data used in this project are publicly available and accessed directly from the TidyTuesday project. Users should refer to the original data providers for any applicable data licenses.
