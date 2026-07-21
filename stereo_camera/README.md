# Stereo Photogrammetry for River Water Level Monitoring

This repository contains the research presentation for "Stereo photogrammetry for river water level and cross-section update: classical and deep learning approaches" presented at the EGU General Assembly 2025.

## Abstract

Water level information is essential for monitoring and modelling river systems. Traditional water level monitoring is done using intrusive gauging methods, such as pressure gauges; however, these sensors might be lost during an intense flood. Furthermore, in extreme flood or drought events, measurements may become insufficient.

Camera gauges have gained attention over recent years as a low-cost and remote sensing approach for river monitoring. Common camera gauge setups use one camera requiring additional information, e.g., a 3D model of river reach and ground control points (GCPs). However, capturing 3D models can be challenging and is sometimes not possible. Further, due to cross-section change over time, there is a need to update the 3D model to ensure precise measurement.

In this research, we propose to change the camera gauge paradigm by using two cameras and applying stereo-photogrammetry. Using a traditional stereo-photogrammetry approach, points from two images can be projected into a 3D space without the need for a 3D model. The only required additional information besides the interior camera geometry is the distance between cameras (baseline).

## Key Features

- Classical stereo processing pipeline for water level measurement
- Deep learning approach for improved feature matching
- Comparison of Z-coordinates between models and reference points
- Practical application in water level and discharge measurement

## Repository Structure

```
river_stereo_twin/
├── images/         # Presentation slides and figures
├── .github/        # GitHub Actions workflows
└── index.html      # Project webpage
```

## Event Information

- **Event:** EGU General Assembly 2025
- **Location:** Vienna, Austria
- **Date:** 27 Apr–2 May 2025
- **Session:** [HS1.2.1](https://meetingorganizer.copernicus.org/EGU25/session/53961)
- **Abstract:** EGU25-9375
- **DOI:** [10.5194/egusphere-egu25-9375](https://doi.org/10.5194/egusphere-egu25-9375)

## Authors

- Pedro Alberto Pereira Zamboni
- Robert Krüger
- Anette Eltner

Institute of Photogrammetry and Remote Sensing, Dresden University of Technology, Dresden, Germany

## License

© 2025 Author(s). This work is distributed under the [Creative Commons Attribution 4.0 License](https://creativecommons.org/licenses/by/4.0/).

## Project Website

Visit our [project website](https://pedrozamboni.github.io/river_stereo_twin/) for more information and visual demonstrations.
