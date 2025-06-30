# Study-of-data-on-the-Russian-film-distribution

# Project Description
The client for this research is the Ministry of Culture of the Russian Federation.
You need to study the Russian film distribution market and identify current trends. Pay special attention to films that have received government support. Try to answer the question of how interesting these films are to the audience.
You will work with data published on the Open Data Portal of the Ministry of Culture. The dataset contains information about distribution certificates, box office revenues, and government support for films, as well as data from the KinoPoisk website.

**Data Description**
The table **mkrf\_movies** contains information from the registry of distribution certificates. A single film can have multiple distribution certificates.

* **title** — film title;
* **puNumber** — distribution certificate number;
* **show\_start\_date** — film premiere date;
* **type** — film type;
* **film\_studio** — production studio;
* **production\_country** — production country;
* **director** — director;
* **producer** — producer;
* **age\_restriction** — age rating;
* **refundable\_support** — amount of refundable government support funds;
* **nonrefundable\_support** — amount of non-refundable government support funds;
* **financing\_source** — source of government financing;
* **budget** — total film budget;
* **ratings** — film rating on KinoPoisk;
* **genres** — film genre.

Note that the **budget** column already includes the full amount of government support. Data in this column is provided only for films that received government support.

The table **mkrf\_shows** contains information about film screenings in Russian cinemas.

* **puNumber** — distribution certificate number;
* **box\_office** — box office revenue in rubles.

  
