---
title: Education Modules
nav:
  order: 1
  tooltip: CITY-AI Curriculum & Training Modules
---

# {% include icon.html icon="fa-solid fa-graduation-cap" %} CITY-AI Education Modules

The **CITY-AI** curriculum aims to bridge the gap between urban science, cyberinfrastructure (CI), and artificial intelligence (AI) using the HPC resources including **I-GUIDE Platform** and **NSF Anvil Supercomputer**.

{% include section.html %}

## Curriculum Overview

All training materials are developed as **Open Educational Resources (OERs)** following **FAIR** (Findability, Accessibility, Interoperability, and Reusability) principles, packaged with interactive Jupyter Notebooks and containerized Docker environments.

<div class="themes-overview" style="display: flex; flex-direction: column; align-items: center; gap: 18px; margin: 25px 0;">
  <div style="background: var(--background-alt, #f8f9fa); border: 2px solid var(--primary, #007bff); border-radius: 12px; padding: 14px 28px; font-weight: 700; font-size: 1.1rem; text-align: center; box-shadow: var(--shadow); max-width: 600px; width: 100%;">
    CITY-AI Urban Informatics Curriculum Themes
  </div>
  <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(240px, 1fr)); gap: 18px; width: 100%;">
    <div style="background: var(--background-alt, #f8f9fa); border-top: 4px solid #17a2b8; border-radius: 10px; padding: 18px 20px; box-shadow: var(--shadow); text-align: center;">
      <h4 style="margin-top: 0; color: #17a2b8; font-weight: 700;">Theme 1: Core CI Skills</h4>
      <p style="margin: 0; font-size: 0.95rem; opacity: 0.85;">Linux, HPC, Python, Profiling & Scaling, NSF Anvil Supercomputer</p>
    </div>
    <div style="background: var(--background-alt, #f8f9fa); border-top: 4px solid #28a745; border-radius: 10px; padding: 18px 20px; box-shadow: var(--shadow); text-align: center;">
      <h4 style="margin-top: 0; color: #28a745; font-weight: 700;">Theme 2: Urban Analytics</h4>
      <p style="margin: 0; font-size: 0.95rem; opacity: 0.85;">Spatial Data, Big Data, Streaming IoT, Spatiotemporal Analysis</p>
    </div>
    <div style="background: var(--background-alt, #f8f9fa); border-top: 4px solid #fd7e14; border-radius: 10px; padding: 18px 20px; box-shadow: var(--shadow); text-align: center;">
      <h4 style="margin-top: 0; color: #fd7e14; font-weight: 700;">Theme 3: Urban Use-Cases</h4>
      <p style="margin: 0; font-size: 0.95rem; opacity: 0.85;">Air Quality, Urban Heat Islands, GeoAI, SVI & Computer Vision</p>
    </div>
  </div>
</div>

{% include section.html %}

## Theme 1: Core Cyberinfrastructure (CI) Skills

These modules lower technical barriers for urban planners and geographers by introducing high-performance computing (HPC) environments, terminal workflows, and distributed resources.

| Module Topic | Level | Key Learning Goals |
| :--- | :---: | :--- |
| **Intro to Linux** | *Beginner* | Terminal navigation, shell scripting, file management, I/O streams, and cluster environment basics. |
| **Intro to HPC** | *Beginner* | Accessing NSF ACCESS resources, NSF Anvil supercomputer, OpenOnDemand portal, and batch job scheduling (SLURM). |
| **Python & JupyterLab** | *Intermediate* | Python programming in JupyterLab; scientific libraries including NumPy, SciPy, Pandas, and Matplotlib. |
| **Profiling & Scaling** | *Advanced* | Computational complexity analysis, estimating resource requirements, parallelization, and software scaling strategies. |

{% include section.html %}

## Theme 2: Urban Data Analytics

Focused on building fundamental geospatial, spatiotemporal, and high-velocity streaming data processing skills.

| Module Topic | Level | Key Learning Goals |
| :--- | :---: | :--- |
| **Spatial Data** | *Beginner* | Core GIS concepts, spatial reference systems, vector/raster data structures, and interactive thematic mapping. |
| **Big Data** | *Intermediate* | Handling high-volume urban datasets, memory-efficient processing, spatial indexing, and distributed storage. |
| **Streaming Data** | *Intermediate* | Acquiring, cleaning, and ingesting real-time urban data streams from sensor networks and IoT gateways. |
| **Spatiotemporal (ST) Data** | *Advanced* | ST analysis techniques, clustering algorithms, spatiotemporal autocorrelation, and dynamic geovisualization. |

{% include section.html %}

## Theme 3: Urban Informatics Use-Cases

Hands-on case studies demonstrating how cutting-edge GeoAI and CI solve urgent smart city and environmental challenges.

| Module Topic | Level | Key Learning Goals |
| :--- | :---: | :--- |
| **Volunteered Geographic Info (VGI)** | *Intermediate* | Extracting, cleaning, and modeling crowdsourced geospatial data from OpenStreetMap (OSM) for urban infrastructure. |
| **Air Quality Monitoring** | *Intermediate* | Processing spatio-temporal streams from environmental sensors and predicting localized air pollution exposure. |
| **Urban Heat Island (UHI)** | *Advanced* | Integrating satellite thermal observations with in-situ urban sensor networks to model microclimate temperature anomalies. |
| **Geospatial AI (GeoAI)** | *Intermediate* | Formulating machine learning models that explicitly account for spatial heterogeneity and temporal dynamics. |
| **Transportation & Accessibility** | *Advanced* | Utilizing real-time GTFS feeds to analyze public transit delays and compute scalable spatial accessibility metrics. |
| **Computer Vision (CV)** | *Advanced* | Applying deep learning vision architectures (CNNs, Vision Transformers) to fine-tune image models on urban datasets. |
| **Street View Imagery (SVI)** | *Advanced* | Automated object detection and segmentation on street-level panoramas to identify urban physical retrofitting and greenery. |
| **Urban Remote Sensing** | *Advanced* | High-resolution satellite and LiDAR image processing for urban land use classification and 3D canopy extraction. |

{% include section.html %}

## Computing Environment

All training modules are hosted and executable directly through:

- **I-GUIDE Platform & JupyterHub:** Providing reproducible, containerized cloud environments with pre-installed GeoAI libraries.
- **NSF Anvil Supercomputer (ACCESS):** Accelerating intensive training with large-capacity GPU nodes (NVIDIA A100/H100) and Kubernetes-based composable services.
