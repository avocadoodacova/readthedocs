2. Getting Started
==================

2.1 Recommended installation of ArcGIS Pro and extensions
---------------------------------------------------------
    1. ArcGIS Pro Version: 3.3.2 or higher.
    2. ArcGIS Pro extensions: 3D Analyst, Data Interoperability, Data Reviewer, Geostatistical Analyst, Image Analyst, Publisher, Spatial Analyst.
    3. ArcGIS Online Account: `ArcGIS online <https://www.arcgis.com/index.html>`_

2.2 Recommended Installation of open-source software
----------------------------------------------------

    1. Text editor: `Notepad++ <https://notepad-plus-plus.org/downloads/>`_
    2. Python IDE: `Spyder <https://www.spyder-ide.org/>`_
    3. Processing 3D building data: `3dcitydb <https://www.3dcitydb.org/3dcitydb/>`_ and `pgAdmin <https://www.pgadmin.org/>`_
    4. Processing LiDAR data:  `LAStools <https://rapidlasso.de/downloads/>`_ 

2.3 Required Data
-----------------

    1. 3D building data: `Geoportal NRW <https://www.geoportal.nrw/?activetab=map&openDownloadclient=true>`_ 
    2. LiDAR data: `Geoportal NRW <https://www.geoportal.nrw/?activetab=map&openDownloadclient=true>`_
    3. Tree cadastre: `Open-data Dortmund <https://open-data.dortmund.de/explore/dataset/baumkataster/export/?disjunctive.ubz&disjunctive.statbezibe&disjunctive.stadtbezbe&disjunctive.sozialrbe&disjunctive.aktionsrbz&disjunctive.aktionsrnr&disjunctive.sozialrnr&disjunctive.stadtbeznr&disjunctive.statbeznr&disjunctive.ubznr&disjunctive.art_botani&disjunctive.art_deutsc&disjunctive.pflanzjahr&disjunctive.standalter&disjunctive.stammdurch&disjunctive.stammumfan&disjunctive.kronendurc>`_

    .. note::
        Download and install all requirements to proceed. The installation and setup of ArcGIS Pro and its extensions is not part of this documentation. Everything else is covered in the following steps. 

2.4 Installing the ArcGIS Pro extensions
----------------------------------------

    1. Open ArcGIS Pro
    2. In the left pane navigate to --> Licensing
    3. Klick "Manage your data licensing"
    4. In the context menu "ArcGIS Pro Extensions" select the following extensions

        - `3D Analyst <https://pro.arcgis.com/en/pro-app/3.3/help/analysis/3d-analyst/what-is-the-3d-analyst-extension-.htm>`_ --> Provides tools for 3D feature and surface analysis.
        - `Data Interoperability <https://pro.arcgis.com/en/pro-app/3.3/help/data/data-interoperability/what-is-the-data-interoperability-extension.htm>`_ --> Is an integrated spatial toolset (ETL, extract, transform and load) that runs within the groprocessing framework using Safe Software's FME technology. It enables you to integrate data from multiple sources and formats, use that data with geoprocessing tools, and publish it. Important for the integration of the 3D building dataset.
        - `Data Reviewer <https://pro.arcgis.com/en/pro-app/latest/help/data/validating-data/get-started-with-data-reviewer.htm>`_ --> Provides a variety of tools to help perfom and manage QA/QC of spatial data.
        - `Publisher <https://pro.arcgis.com/en/pro-app/latest/help/sharing/overview/what-is-publisher.htm>`_ --> Enables the sharing of data throughout the ArcGIS Platform. Important for sharing your data in the ArcGIS online account.
        - `Spatial Analyst <https://pro.arcgis.com/en/pro-app/latest/help/analysis/spatial-analyst/basics/get-started-with-spatial-analyst-in-arcgis-pro.htm>`_ --> Provides advanced spatial modeling and analysis tools for raster data. Important for the analysis of raster layers.
    
