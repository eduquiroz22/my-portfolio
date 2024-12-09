# My Portfolio

Hello! I’m Eduardo Quiroz, a physics student at "Universidad Mayor de San Simón" from Cochabamba, Bolivia. Here are some of the projects I've worked on during my studies:

## Projects

### **[Analysis of Particle Detection Data from UMSA](https://drive.google.com/file/d/1NIEeTrc9Gf192jm7z399cdxxGTFpp8Hl/view?usp=sharing)**  

- **Objective**:  
  Analyze particle detection data provided by UMSA ("Universidad Mayor de San Andrés" from La Paz, Bolivia), which involved working with large datasets from scintillators and Cherenkov detectors.

- **Achievements**:  
  Developed algorithms to structure large volumes of data and detect peaks in signals. Applied the Skewed Voigt model for peak fitting, which facilitated accurate analysis of particle detection events.

- **Tools Used**:  
  Python, LMFIT, multiprocessing package, data analysis techniques.
  
- **Results**:  
  A sample of the first 100 signals from each set can be found in the following link:  
  [Cota Cota Analysis](https://eduquiroz22.github.io/Cota-Cota/).  
  This document showcases the structured data and some of the visualizations produced from the analysis. Due to file upload limits, only the first 100 signals from each set are available for viewing.

---

### **[Development of a Crossmatch Algorithm for Star and Radio Source Catalogs (Part of Thesis Work)](https://github.com/eduquiroz22/crossmatching_algorithm)**  

- **Objective**:  
  Develop an efficient algorithm to crossmatch star and radio source catalogs by optimizing the angular separation calculation and implementing a binary search approach to enhance performance.

- **Achievements**:  
  Successfully developed an optimized algorithm for fast and accurate crossmatching between star catalogs and radio source databases, significantly improving the efficiency of the matching process. Additionally, the process was parallelized to utilize multiple processors, further enhancing performance and reducing computation time.

- **Tools Used**:  
  Python, Pandas, NumPy, multiprocessing package, custom binary search implementation.

For a detailed description of the work and methodology, please refer to the [documentation here](https://drive.google.com/file/d/1-OngqpRTozFUxsD3A8Z5mg3TsVMJS712/view?usp=sharing).

---

### **[Search for Radio Stars Using the "Image Method" by Adjusting Star Positions to Observation Epochs (Part of Thesis Work)](https://github.com/eduquiroz22/search_radio_stars_using_images)**    

- **Objective**:  
  Develop a method for identifying radio-emitting stars by adjusting star positions to the precise observation epochs. This method, called the **"Image Method"**, generates observational data for each star based on its position at a given epoch, without relying on an existing catalog of radio sources.

- **Achievements**:  
  Created the **"Image Method"**, which goes beyond traditional crossmatch catalog searches by enabling the identification of radio-emitting stars whose sources do not meet the criteria to be cataloged. This method significantly broadens the scope of the search, allowing for the discovery of stars that would otherwise be missed.

- **Tools Used**:  
  Python, Pandas, Numpy, PyAstrometry (for adjusting star positions made by Laurent Loinard), Astropy, Web Scraping techniques (Selenium and WebDrive) for gathering observational data.
  
For a detailed description of the work and methodology, please refer to the [documentation here](https://drive.google.com/file/d/1hHid_4rCvBlYHPT8f4aXWMlTASEUOMN0/view?usp=sharing).


---

### **[False Positive Estimation for Crossmatch Between Catalogs Using HPC (Part of Thesis Work)](https://github.com/eduquiroz22/simulation_method_catalogs)**  

- **Objective**:  
  Estimate the number of false positives in the crossmatching process by simulating random star and radio source positions for different distance ranges. The simulation was done progressively for distances from 10 to 250 pc, generating synthetic catalogs of stars and radio sources with random positions, and leveraging High-Performance Computing (HPC) for efficient processing.

- **Achievements**:  
  Conducted 1000 simulations for each distance considered, using HPC to process large-scale simulations efficiently. This approach enabled the generation of millions of synthetic observations, improving the estimation of the number of false positives and evaluating the crossmatching algorithm for large datasets.

- **Tools Used**:  
  Python, Pandas, NumPy, Astropy, High-Performance Computing (HPC), multiprocessing package, custom binary search implementation.
  
For a detailed description of the work and methodology, please refer to the [documentation here](https://drive.google.com/file/d/17RDFwJezf33d-4lM3-IKvSbjLMT-K5Kn/view?usp=sharing).

---

### **[Simulation of False Positives for Image-Based Method (Part of Thesis Work)](https://github.com/eduquiroz22/simulation_images_method)**  

- **Objective**:  
  Simulate the likelihood of false positives in an image-based search method by randomizing star positions within irregular observation areas.

- **Achievements**:  
  Performed simulations with randomized star positions to generate over 1.5 million observations and identifying potential false positives. This contributed to a more reliable and robust detection method for radio-emitting stars in image-based searches.

- **Tools Used**:  
  Python, Pandas, Numpy, Web scraping.

For a detailed description of the work and methodology, please refer to the [documentation here](https://drive.google.com/file/d/1ZBf8rpt7E_zgrULgnjOXPIV9ho6RutmN/view?usp=sharing).


---

### **[Generation of Radio Observation Images (Part of Thesis Work)](https://github.com/eduquiroz22/gen_observation_radio_images)**  

- **Objective**:  
  Generate images of radio observations showing star positions and their trajectories, in order to analyze proper motions visible in radio frequency observations.

- **Achievements**:  
  Created radio observation images using Python’s Kapteyn package, which enabled the visualization of proper motions for stars and radio sources, providing valuable insights into their movement across the sky.

- **Tools Used**:  
  Python, Pandas, Numpy, PyAstrometry, Kapteyn package, Astropy, data visualization techniques.

---

### **[Analysis of Temporal Variability Index (TVI) in Radio Sources (Part of Thesis Work)](https://github.com/eduquiroz22/temporal_variability_index)**  

- **Objective**:  
  Analyze the temporal variability of radio sources using a custom metric called the **"Temporal Variability Index (TVI)"**. This analysis helped to distinguish between radio stars and extragalactic sources.

- **Achievements**:  
  Developed the **TVI**, which successfully identified a significant difference in variability between radio stars and extragalactic sources. This led to the confirmation of two new radio stars based on variability characteristics.

- **Tools Used**:  
  Python, Pandas, Gaia, SDSS SkyServer, Legacy survey, DESI survey, Statistical insight, CASA (for Gaussian fitting of sources using automated scripts).

---

### **[X-Ray Generation Simulation from Electron Irradiation on Tungsten](https://drive.google.com/file/d/1nEiFpYSwptF2RWQgoYWAkO6UT2t87ZfX/view?usp=sharing)**  

- **Objective**:  
  Simulate the X-ray spectrum generated when a tungsten sample is irradiated with electrons, in order to analyze the characteristics of the X-rays produced.

- **Achievements**:  
  Successfully used GEANT4 to simulate electron irradiation and observed the X-ray spectrum. Results were analyzed using ROOT, providing insights into X-ray production in a tungsten sample.

- **Tools Used**:  
  GEANT4, ROOT, C++.

---

### **[Analysis of Data from Gaia Test Irradiation on CCDs (First Data Analysis Project)](https://drive.google.com/file/d/190OmD3ItyQDtJ395TAA0YSEOcr51YPDT/view?usp=sharing)**  

- **Objective**:  
  Analyze astrometric and photometric data from the Gaia mission’s test irradiation on CCDs, to assess the mission’s performance before its actual launch.

- **Achievements**:  
  Performed data analysis on the CCN10 test provided by the ESA, contributing to the validation of Gaia's sensor performance through astrometric and photometric testing.

- **Tools Used**:  
  Python, Pandas, Numpy, LMFIT package, data analysis techniques.

---

### **[Climate Simulation Model with RegCM](https://drive.google.com/file/d/1Fc73HmIouvwkJ4tBst8ZklB0hYblbIZ0/view?usp=sharing)**  

- **Objective**:  
  Simulate climate patterns for Bolivia by downscaling global data and performing nested simulations to increase resolution for the Cochabamba region.

- **Achievements**:  
  Developed custom GrADS scripts to automate the analysis and visualization of climate simulation results, improving the workflow for handling large datasets from RegCM simulations.

- **Tools Used**:  
  RegCM, GrADS, R, data visualization tools.

---

### **[Study of Star Clusters in Cochabamba’s Sky](https://drive.google.com/file/d/1CxozYqH5NObI-HO-1z8NpG70-v3FORoH/view?usp=sharing)**  

- **Objective**:  
  Conduct an astrometric and photometric study of star clusters visible in the sky of Cochabamba, using Gaia data to explore open and globular clusters.

- **Achievements**:  
  Successfully analyzed and compared star clusters using Gaia Release 3 and 2MASS catalogs. Observed key differences between open and globular clusters and their proper motions.

- **Tools Used**:  
  TOPCAT, Astropy, Gaia DR3, 2MASS.


---

Visit my [GitHub](link_to_your_profile) to see all my projects!
