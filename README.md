<img width="1459" alt="testtesttest" src="https://github.com/user-attachments/assets/992293e0-8e33-498e-ae08-f016236d2edc" />


# RCA_ADS2    -    Earth Engines

October 2025 
<br>


Earth Engines is a workshop that experiments with remote sensing as both method and medium, using Google Earth Engine to explore the atmospheric and spectral layers of the Earth. Through coding and cloud-based data processing, it reframes satellite imagery as temporal and moving surfaces to interpret and translate environmental change.


<p align="center">
  <img width="488" height="386" alt="Screenshot 2025-10-22 at 8 21 47 PM" src="https://github.com/user-attachments/assets/af7c05d6-12ab-4bdb-9a80-7e3ab3462083" />
</p>


## CLOUD COMPUTING 💻

<img width="1459" alt="Screenshot 2025-02-18 at 2 01 30 AM" src="https://github.com/user-attachments/assets/1736e108-9530-48f6-ae5f-32a578e28f48" />

[Google Earth Engine requires all users to sign-up for an account](https://code.earthengine.google.com/register). This account is linked with Google Cloud and users must create a Google Cloud Project to use the service. 
- On the Product Registration Page, select Register a Noncommercial or Commercial Cloud project.
- Next, you need to choose How do you want to use Earth Engine?. Choose the Unpaid usage, click Next. Since we are in Academia provider, we have chosen Unpaid usage → Research & Academia.
- In the next dialog, choose Create a new Google Cloud Project. Select No organization for Organization and enter a Project-ID. This id needs to be unique. A standard practice is to use the project-ID in the form of ee-<yourusername>. Click CONTINUE TO SUMMARY. If you have never used Google Cloud before, an error message will be displayed with a note You must accept the Cloud Terms of Service before a Cloud Project can be created.
- Choose your Country and review the Google Cloud Platform Terms of Service and the terms of service of any applicable services and APIs. After reviewing, click AGREE AND CONTINUE.
- You will be presented with a summary in the Confirm your Cloud project information dialog. Review and click CONFIRM.
- The project will be registered and you will be redirected to the Code Editor. If you are not redirected automatically, visit the Earth Engine Code Editor.


Database links:
<br>
[Earth Engine Data Catalog](https://developers.google.com/earth-engine/datasets/catalog/landsat) <br>
[GEE Community Catalogue](https://gee-community-catalog.org/)<br>
[Spectral Indexes](https://awesome-ee-spectral-indices.readthedocs.io/en/latest/index.html)





## CODE SNIPPETS :globe_with_meridians: 

The following code snippets are designed as **interactive examples** to be used during the lecture. In the **second part of the workshop**, we will **break down and explain each section of the code**


### 00.Satellites

- **Pixels** – Understanding how satellite images are composed of discrete units of information.  
- **Orbits and Frequency** – Exploring how satellites capture imagery at different time intervals and resolutions.

<img width="1573" height="1047" alt="Screenshot 2025-10-22 at 9 07 37 PM" src="https://github.com/user-attachments/assets/04986569-fc38-4621-a18f-10b83041fbac" />


. [00RCA_Satellite](https://code.earthengine.google.com/05e54fa76944c926339cee4f09cfe588)

### 01.Elevation 

- **Height** – Map the vertical dimension of the Earth's surface.

<img width="1573" height="1047" alt="Screenshot 2025-10-22 at 9 22 01 PM" src="https://github.com/user-attachments/assets/88d889e4-79ef-48ae-8bfb-944b6844c7a1" />

. [01RCA_DEM](https://code.earthengine.google.com/5f6656bd7cdb5e7c5ade88a4dc2df1fc)


### 02.Spectrum and Indexes

- **Light** – When light strikes an object, it can be absorbed, transmitted, or reflected. How this interaction happens and how it depends on the material properties of the surface?  
- **Bands** – Combining bands - specific segments of the electromagnetic spectrum.
<p align="center">
<img width="478" height="475" alt="Screenshot 2025-10-22 at 9 56 22 PM" src="https://github.com/user-attachments/assets/a832263c-6eb1-4eb9-b8c9-baf2ca848618" />
</p>

. [02RCA_Spectrum Indexes01](https://code.earthengine.google.com/2cf269fbc6c0e8f4d630b04d0d154434) 
   <br>
   
<img width="1615" height="1002" alt="Screenshot 2025-10-22 at 10 04 59 PM" src="https://github.com/user-attachments/assets/8026bea7-7844-439b-91d4-74583c3fe9f1" />


. [02RCA_Spectrum Indexes02](https://code.earthengine.google.com/ff302159375cbe90f5e51e0aaceb0044) 


### 03.Time Machine

- **Time** – The continuous Landsat archive enables temporal analysis of Earth’s surface, providing multi-decadal observations for change detection.
- **Memory** –  Each spectral band preserves radiometric information that allows reconstruction of past environmental and land surface conditions.

  <img width="1615" height="1002" alt="Screenshot 2025-10-22 at 10 03 36 PM" src="https://github.com/user-attachments/assets/7690dfb4-8bb6-44d9-801a-8a66a0e6491a" />

. [03RCA_Time Machine](https://code.earthengine.google.com/bc2bf69666d3cb0680074a9984da3d00) 


  <br>
    <br>
      <br>
        <br>
        

## INDEXES 🛰️ 

Each of the following terms describes how energy interacts with Earth’s surface and atmosphere, and connects to three core satellites driving Earth sensing: Landsat, Sentinel, and GOES.

### REFLECTANCE
<img width="1615" height="1002" alt="Screenshot 2025-10-22 at 10 28 42 PM" src="https://github.com/user-attachments/assets/f4dbf17d-3f8b-47bc-b3e6-5c41b435ae76" />
(https://code.earthengine.google.com/0565361e27d68a6ecccb38f2c32f094b)


### RADIANCE
<img width="1615" height="1002" alt="Screenshot 2025-10-22 at 10 31 45 PM" src="https://github.com/user-attachments/assets/c1702116-a443-4e73-8b4d-07abb0f8e626" />
(https://code.earthengine.google.com/6e4777d972ea284b73ebc54aeab5e137)

### TRANSIMMTANCE
<img width="1615" height="1002" alt="Screenshot 2025-10-22 at 10 32 49 PM" src="https://github.com/user-attachments/assets/c5b0cc9c-f613-48e2-bcaa-77fc6298349d" />
(https://code.earthengine.google.com/c64c60abe61486d4600dd664b3fe8b15)



