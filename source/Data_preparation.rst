4. Data aquisition
==================

**3D Building data (CityGML)**
    
        - Open the `Geoportal NRW <https://www.geoportal.nrw/?activetab=map&openDownloadclient=true>`_.
        - In the menu on the right side, you can select the are of interest (AOI). 
        - Select **"Aus Gebietslisten auswählen"**.
        - In the menu bar on the top, select **"Kreise"** and then **"Dortmund"** --> The AOI is automatically drawn in the map. 
        - Click on **"Übernehmen"**.
        - Choose your desired products (3D building data) by clicking the **+** symbol.
        - In the searchbar type **CityGML** and tick the box at **"3D-Gebäudemodell LoD2 (CityGML) - Paketierung: Einzelkacheln"**.
        - Click on **"Übernehmen"**.
        - The estimated file size for the city of Dortmund should be around **4.35 GB**.
        - Click on **"Zum Download"** and then on **"Alle herunterladen"**.

    .. note::
            This will download a .zip Folder with 332 single tiles containing the 3D building data.

    It should look something like this: 

    .. image:: _static/citygml.jpg
        :width: 100%
        :align: center

    
**LiDAR Data (Laz)**

    To download the LiDAR data you can proceed the same way as before:
    
        - Open the `Geoportal NRW <https://www.geoportal.nrw/?activetab=map&openDownloadclient=true>`_.
        - In the menu on the right side, you can select the are of interest (AOI). 
        - Select **"Aus Gebietslisten auswählen"**.
        - In the menu bar on the top, select **"Kreise"** and then **"Dortmund"** --> The AOI is automatically drawn in the map. 
        - Click on **"Übernehmen"**.
        - Choose your desired products (LiDAR data) by clicking the **"+"** symbol.
        - In the searchbar type **"3dm"** and tick the box at **"3D-Messdaten Laserscanning (LAS) - Paketierung: Einzelkacheln"**.
        - Click on **"Übernehmen"**.
        - The estimated file size for the city of Dortmund should be around **42.6 GB**.
        - Click on **"Zum Download"** and then on **"Alle herunterladen"**.

    .. note::
            This will download a .zip Folder with 332 single tiles containing the LiDAR data.

    It should look something like this: 

    .. image:: _static/citygml.jpg
        :width: 100%
        :align: center

[change picture]

**Tree cadastre data (geojson)**

        - Open the `Geoportal of the city of Dortmund <https://dortmund.opendatasoft.com/explore/dataset/baumkataster/information/?disjunctive.ubz&disjunctive.statbezibe&disjunctive.stadtbezbe&disjunctive.sozialrbe&disjunctive.aktionsrbz&disjunctive.aktionsrnr&disjunctive.sozialrnr&disjunctive.stadtbeznr&disjunctive.statbeznr&disjunctive.ubznr&disjunctive.art_botani&disjunctive.art_deutsc&disjunctive.pflanzjahr&disjunctive.standalter&disjunctive.stammdurch&disjunctive.stammumfan&disjunctive.kronendurc&location=18,51.50979,7.47071&basemap=a8bade>`_.
        - Navigate to the tab **"Exporte"**
        - Download the **geojson file** (not the shapefile because it is not complete).

    .. note::
            As the shapfile dataset only contains a limited number of trees, it is recommended to download the geojson file, which contains all public trees in Dortmund. At a later stage of this tutorial, the geojson dataset is converted into a shapefile.