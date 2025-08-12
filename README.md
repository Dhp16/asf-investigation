## Investigation into ASF and it's impact on herd sizes and pork prices

To run the code to generate any of the data refered to below, open `ASF_investigation.ipynb` in jupyter-notebook.

### Part 1: Investigating reported instances of ASF

**1. data source**: 

- Food and Agriculture Organisation of the United Nations: https://europe-west1-fao-empresi.cloudfunctions.net/getDiseaseEvents?disease_name=african_swine_fever&animal_type=all&diagnosis_status=confirmed&end_date=2025-08-07&start_date=2000-05-07

**2. findings**:

* Reported numbers from most regions appear unreliable, Europe and South East Asia are the exceptions. 

**3. Plots**:

![Cases in europe](plots/asf_instances_by_country.svg)

### Part 2: How useful can this data be in anticipating a Chinese ban on pork imports?

**1. Italy:**
China re-approved pork imports from Italy in . In this data we later find the earliest case reported to be the **5th of January 2022**.
With the Chinese ban being announced on January 26th 2022. It would have been possible to anticipate the ban.

**2. Germany:** 
The first reported case found in the dataset for Germany was **9th of September 2020** for a case observed **7th of September**,
China banned imports of pork from Germany on September 14th 2020. It would have been possible to anticipate such ban.

**3. Indonesia:**


**4. Further findings:** despite the findings suggesting that following the data at the Food and Agriculture Organisation of the United Nations would be enough to get ahead
of national import bans from China, there will always be a lag between the observed date and the reported date, but also between the reported date and the published date.
The place best measure to get the most up to date data on new observed instances of ASF is the [World Organisation for Animal Health](https://www.woah.org/en/home/), more specifically to sign up to 
their [distribution list](https://www.woah.org/en/what-we-do/animal-health-and-welfare/disease-data-collection/info-list/).

### Part 3: 