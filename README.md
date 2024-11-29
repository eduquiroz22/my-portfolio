# My Portfolio

Hello! I’m Eduardo Quiroz, a physics student at "Universidad Mayor de San Simón" from Cochabamba, Bolivia. Below are some of the key projects I've worked on during my studies. Click on the project titles to learn more about each project.

## Projects

### 1. **[Analysis of Data from Gaia Test Irradiation on CCDs](link_to_project1)**

**Objective**:  
This project involved performing astrometric and photometric analysis of test data (CCN10) provided by the European Space Agency (ESA). The data was gathered as part of the radiation test campaigns for the Gaia mission, which aims to map the stars of our galaxy. The goal was to analyze the impact of radiation on Gaia's CCD sensors in preparation for the mission.

**Key Achievements**:  
- Successfully processed and analyzed large datasets to assess the effects of irradiation on CCDs.
- Applied statistical methods to detect potential issues that could affect the mission's data quality.
- Contributed to the calibration of the Gaia mission’s instruments, which would later be used in the actual mission for star mapping.

**Tools Used**:  
- Python, Matplotlib, Astropy, FITS format, Gaia DR3

[More details here](project1.md)

---

### 2. **[X-Ray Generation Simulation from Electron Irradiation on Tungsten](link_to_project2)**

**Objective**:  
The goal of this project was to simulate the generation of X-rays caused by electron irradiation in a tungsten sample. Using the GEANT4 simulation framework (developed by CERN), I modeled the interaction of high-energy electrons with tungsten and analyzed the resulting X-ray spectrum using ROOT.

**Key Achievements**:  
- Developed simulations to accurately model the energy deposition in tungsten and the resultant X-ray emission.
- Analyzed spectral data to identify key X-ray peaks and their relevance for experimental physics.
- Gained expertise in GEANT4 and ROOT, which are widely used in high-energy physics simulations.

**Tools Used**:  
- GEANT4, ROOT, C++, CERN libraries

[More details here](project2.md)

---

### 3. **[Climate Simulation Model with RegCM](link_to_project3)**

**Objective**:  
This project involved running climate simulations for Bolivia using the Regional Climate Model (RegCM), with the aim of achieving higher resolution projections through downscaling. The goal was to simulate climate patterns with a focus on Cochabamba, using data from the EIN15 global climate model.

**Key Achievements**:  
- Performed downscaling of global climate data to obtain high-resolution simulations for Bolivia and Cochabamba.
- Automated the process of plotting and analyzing simulation results using GrADS scripting, allowing for the efficient handling of large datasets.
- Demonstrated the use of advanced climate modeling tools and data analysis techniques to assess the potential impact of climate change on the region.

**Tools Used**:  
- RegCM, GrADS, Python, Bash scripting

[More details here](project3.md)

---

### 4. **[Study of Star Clusters in Cochabamba’s Sky](link_to_project4)**

**Objective**:  
This project focused on the astrometric and photometric analysis of open and globular star clusters visible from Cochabamba, Bolivia. The goal was to provide amateur astronomers and enthusiasts with information on the star clusters that can be observed in the region's night sky.

**Key Achievements**:  
- Identified and analyzed six star clusters using data from Gaia DR3 and the 2MASS catalog.
- Applied techniques like Crossmatch and TOPCAT to analyze stellar properties, such as proper motion and distance.
- Presented findings on the evolutionary stages of open clusters and the dynamics of globular clusters.

**Tools Used**:  
- Gaia DR3, 2MASS, TOPCAT, Python

[More details here](project4.md)

---

### 5. **[Analysis of Particle Detection Data from UMSA](link_to_project5)**

**Objective**:  
This project involved analyzing particle detection data collected at the Universidad Mayor de San Simón (UMSA) in La Paz, Bolivia. The data was obtained from scintillators and Cherenkov detectors used to study particle interactions.

**Key Achievements**:  
- Developed a method to restructure and organize large volumes of raw data, making it easier to analyze.
- Created an algorithm to identify and fit particle detection peaks using the Skewed Voigt model.
- Analyzed particle interactions and identified key signals, contributing to a better understanding of cosmic and particle physics experiments.

**Tools Used**:  
- Python, Numpy, SciPy, ROOT, LMfit

[More details here](project5.md)

---

### 6. **[Development of a Crossmatch Algorithm for Star and Radio Source Catalogs](link_to_project6)**

**Objective**:  
To identify stars that emit in radio frequencies, I developed an efficient algorithm to search for matches between star catalogs (such as Gaia) and radio source catalogs. This involved optimizing the calculation of angular separation and using a binary search approach to speed up the matching process.

**Key Achievements**:  
- Successfully implemented an optimized crossmatch algorithm that significantly reduced the computational time for matching large catalogs.
- Validated the algorithm by running thousands of simulations with synthetic catalogs to estimate the likelihood of random matches (false positives).
- Provided a robust foundation for further analysis in my thesis work, where this algorithm was later used to identify potential radio stars.

**Tools Used**:  
- Python, Astropy, Numpy

[More details here](project6.md)

---

### 7. **[False Positive Estimation for Crossmatch Between Catalogs](link_to_project7)**

**Objective**:  
This project aimed to estimate the rate of false positives in the crossmatch between star and radio source catalogs. Using randomized positions within the observation area, I simulated random matches and calculated the probability of false positives.

**Key Achievements**:  
- Conducted extensive simulations to estimate the number of false positives for crossmatching star and radio catalogs.
- Used web scraping techniques to gather data for over 1.5 million simulated observations.
- Calculated the probability of false positives and incorporated this into a more accurate search for radio stars.

**Tools Used**:  
- Python, Web Scraping, Astropy, Numpy

[More details here](project7.md)

---

### 8. **[Search for Radio Stars by Adjusting Star Positions to Observation Epochs](link_to_project8)**

**Objective**:  
In this project, I developed a method to search for radio stars without relying on a catalog of radio sources. Instead, I adjusted star positions to the exact observation epochs and analyzed the resulting data to identify stars that might emit in radio frequencies.

**Key Achievements**:  
- Created an innovative method to search for radio-emitting stars using precise position adjustments.
- Implemented a web scraping tool to gather observational data for thousands of stars, making the method computationally feasible.
- Successfully identified new potential radio stars based on their motion and alignment with observation epochs.

**Tools Used**:  
- Python, Web Scraping, Astropy

[More details here](project8.md)

---

### 9. **[Simulation of False Positives for Image-Based Method](link_to_project9)**

**Objective**:  
To estimate false positives in an image-based search method for radio stars, I simulated the movement of stars within the observation area and randomized their positions to generate false matches.

**Key Achievements**:  
- Developed a robust method for simulating false positives in image-based searches for radio stars.
- Utilized the Kapteyn package in Python to create accurate simulations of star movement and generate synthetic radio star images.
- Analyzed the results to refine the criteria used for identifying real radio stars versus false positives.

**Tools Used**:  
- Python, Kapteyn, Astropy, Numpy

[More details here](project9.md)

---

### 10. **[Generation of Radio Observation Images](link_to_project10)**

**Objective**:  
This project involved generating images of radio observations that included the original positions of stars (from Gaia DR3) and their trajectories over time. The goal was to identify proper motion in radio sources, which could indicate the presence of radio-emitting stars.

**Key Achievements**:  
- Successfully generated time-series images of star positions, showing their movements and proper motions.
- Utilized the Kapteyn package to create high-quality visualizations of star movements within radio observations.
- Contributed to a better understanding of how star motion correlates with radio emission.

**Tools Used**:  
- Python, Kapteyn, Astropy, Matplotlib

[More details here](project10.md)

---

### 11. **[Analysis of Temporal Variability (IVT) in Radio Sources](link_to_project11)**

**Objective**:  
In this project, I analyzed the temporal variability in radio sources using a custom metric called the **Index of Temporal Variability (IVT)**. This analysis helped to distinguish between regular radio stars and extragalactic sources.

**Key Achievements**:  
- Developed a custom metric (IVT) to quantify the temporal variability of radio sources.
- Applied IVT to both confirmed radio stars and extragalactic radio sources, revealing significant differences.
- Used the IVT metric to identify two new radio stars based on their variability patterns.

**Tools Used**:
