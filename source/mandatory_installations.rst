3. Mandatory Software Installation
==================================

In order to conduct the workflow properly, all of the following software need to be successfully downloaded and installed to your local machine.

3.1 Installing the ArcGIS Pro extensions
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
    
3.2 Create an ArcGIS Online account
-----------------------------------

    1. Open `ArcGIS online <https://www.arcgis.com/index.html>`_ in your browser.
    2. Click **sign in** and then **create an account** or **sign in** if you already have an account.

    Once you've created an account and singend in successfully, you can manage your data within the **content** tab in the **menu bar** at the top of the page. 

3.3 Installing the text editor Notepad++
----------------------------------------

    1. Open `Notepad++ <https://notepad-plus-plus.org/downloads/>`_ in your browser.
    2. Download the latest installer package 
    3. Open the downloaded installer package and follow the instructions of the installation wizard.


3.4 Installing the 3dcitydb software
------------------------------------

    1. Open `3dcitydb <https://www.3dcitydb.org/3dcitydb/downloads/>`_ in your browser.
    2. Download the latest installer package. 
    3. Open the downloaded installer package and follow the instructions of the installation wizard.

    .. note:: 

        Make sure Java version 11 or higher (e.g. `Oracle JDK <https://www.oracle.com/java/technologies/downloads/#java11?er=221886>`_ or `Open JDK <https://adoptopenjdk.net/releases.html>`_) is installed on your system. To check your current Java version type **cmd** in your windows search bar and enter the command **java - -version** and press enter.

    Like this:

    .. code-block:: console

        java --version

    You should see something like this:

    .. code-block:: console

        openjdk 
        OpenJDK Runtime Environment 
        OpenJDK 64-Bit Server VM 

    .. note:: 

        If you don't see anything, you need to install Java first. 
        

3.5 Installing the pgAdmin software
-----------------------------------

    1. Open `pgAdmin <https://www.pgadmin.org/download/>`_ in your browser.
    2. Choose your operating system and download the corresponding installation package.
    3. Open the downloaded installer package and follow the instructions of the insallation wizard.

3.6 Downloading the LiDAR processing toolbox LAStools
-----------------------------------------------------

    1. Open `LAStools <https://rapidlasso.de/downloads/>`_ in your browser.
    2. Extract the downloaded folder **LAStools.zip** and copy it to a directory of your choice.
    3. In this tutorial only the file **laszip64.exe** is used. You can find it here: **LAStools --> bin --> laszip64**.



    .. note:: 

        After successfully downloading and installing all the above mentioned Software and tools the next step is downloading the data for the map. Klick **Next** to continue.
