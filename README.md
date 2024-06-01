# AED (Automated External Defibrillator): Aid Ends Death

## Group Members
- Camille Cu
- Linwei He
- Wendy Dewit
- Yiannis Dikaioulias

## Introduction

This is the project for the Modern Data Analysis in KU Leuven. Our group is dedicated to exploring the intricate relationship between the placement of AEDs and the occurrence of emergency incidents,to enhance public health and safety.

## Table of Contents
├── App
│   ├── App Datasets
│   │   ├── AED_DENS_POPUL_WITHIN_PROVINCES.geojson
│   │   ├── AED_DENS_WITHIN_PROVINCES.geojson
│   │   ├── AED_GEO.geojson
│   │   ├── AED_WITHIN_PROVINCES.geojson
│   │   ├── AED_per_municipality_antwerpen.csv
│   │   ├── AED_per_municipality_brabant wallon.csv
│   │   ├── AED_per_municipality_bruxelles-brussel.csv
│   │   ├── AED_per_municipality_hainaut.csv
│   │   ├── AED_per_municipality_liège.csv
│   │   ├── AED_per_municipality_limburg.csv
│   │   ├── AED_per_municipality_luxembourg.csv
│   │   ├── AED_per_municipality_namur.csv
│   │   ├── AED_per_municipality_oost-vlaanderen.csv
│   │   ├── AED_per_municipality_vlaams-brabant.csv
│   │   ├── AED_per_municipality_west-vlaanderen.csv
│   │   ├── AREA_PROVINCES_NEW.geojson
│   │   ├── BE_SHAPE.geojson
│   │   ├── CARDIAC_per_municipality_antwerpen.csv
│   │   ├── CARDIAC_per_municipality_brabant_wall.csv
│   │   ├── CARDIAC_per_municipality_brussels.csv
│   │   ├── CARDIAC_per_municipality_hainaut.csv
│   │   ├── CARDIAC_per_municipality_liege.csv
│   │   ├── CARDIAC_per_municipality_limburg.csv
│   │   ├── CARDIAC_per_municipality_luxem.csv
│   │   ├── CARDIAC_per_municipality_namur.csv
│   │   ├── CARDIAC_per_municipality_oost_vlaand.csv
│   │   ├── CARDIAC_per_municipality_vlaams_brabant.csv
│   │   ├── CARDIAC_per_municipality_west_vlaand.csv
│   │   ├── Cardiac_location.geojson
│   │   ├── Cholorpleth_Cardiac_Arrests_Municipalities.html
│   │   ├── Cholorpleth_Counts_Municipalities.html
│   │   ├── Interventions_risky_probability.csv
│   │   ├── Vecotrs.geojson
│   │   ├── cardiac.csv
│   │   └── cholorpleth_provinces.html
│   ├── Procfile
│   ├── app.py
│   ├── pages
│   │   ├── Page_1.py
│   │   ├── Page_2.py
│   │   ├── Page_3.py
│   │   ├── Page_4.py
│   │   ├── Page_5.py
│   │   ├── Page_6.py
│   │   ├── Page_7.py
│   │   └── __pycache__
│   │       ├── AED_Locations.cpython-311.pyc
│   │       ├── Cardiac_Arrests_to_AED.cpython-311.pyc
│   │       ├── Closest_AED_Ambulance.cpython-311.pyc
│   │       ├── Clustering.cpython-311.pyc
│   │       ├── Clustering_Optimization.cpython-311.pyc
│   │       ├── Page_1.cpython-311.pyc
│   │       ├── Page_2.cpython-311.pyc
│   │       ├── Page_3.cpython-311.pyc
│   │       ├── Page_4.cpython-311.pyc
│   │       ├── Page_5.cpython-311.pyc
│   │       ├── Page_6.cpython-311.pyc
│   │       ├── Page_7.cpython-311.pyc
│   │       ├── Risk_Probability.cpython-311.pyc
│   │       ├── archive.cpython-311.pyc
│   │       └── home.cpython-311.pyc
│   ├── requirements.txt
│   └── runtime.txt
├── Clustering
│   ├── Cardiac_location.geojson
│   ├── Cholorpleth_Cardiac_Arrests_Municipalities.html
│   ├── Cholorpleth_Counts_Municipalities.html
│   ├── Vecotrs.geojson
│   ├── Vectors.ipynb
│   ├── cardiac.csv
│   ├── chorepleth_density.ipynb
│   ├── choropleth_muni_vectors.ipynb
│   ├── georef-belgium-submunicipality@public
│   │   ├── georef-belgium-submunicipality-millesime.cpg
│   │   ├── georef-belgium-submunicipality-millesime.dbf
│   │   ├── georef-belgium-submunicipality-millesime.prj
│   │   ├── georef-belgium-submunicipality-millesime.shp
│   │   └── georef-belgium-submunicipality-millesime.shx
│   ├── intervention.ipynb
│   ├── lineplot.ipynb
│   ├── mapboxheat.ipynb
│   ├── vector_shape
│   │   ├── amb.cpg
│   │   ├── amb.dbf
│   │   ├── amb.prj
│   │   ├── amb.shp
│   │   ├── amb.shx
│   │   ├── be.cpg
│   │   ├── be.dbf
│   │   ├── be.prj
│   │   ├── be.shp
│   │   ├── be.shx
│   │   ├── mug.cpg
│   │   ├── mug.dbf
│   │   ├── mug.prj
│   │   ├── mug.shp
│   │   ├── mug.shx
│   │   ├── pit.cpg
│   │   ├── pit.dbf
│   │   ├── pit.prj
│   │   ├── pit.shp
│   │   └── pit.shx
│   └── view_data.ipynb
├── GeoJSON and CSV files from online sources
│   ├── BE.json
│   ├── BELGIUM_-_Provinces.geojson
│   └── Belgique_-_Nombre_d_habitants_par_commune_en_2011.csv
├── Modelling
│   ├── Interventions_combined_pre_preprocessing.csv
│   ├── Interventions_risky_probability.csv
│   └── Modelling.ipynb
├── README.md
├── Raw Datasets from Toledo
│   ├── LICENSE
│   ├── aed_locations.parquet.gzip
│   ├── ambulance_locations.parquet.gzip
│   ├── cad9.parquet.gzip
│   ├── interventions1.parquet.gzip
│   ├── interventions2.parquet.gzip
│   ├── interventions3.parquet.gzip
│   ├── interventions_bxl.parquet.gzip
│   ├── interventions_bxl2.parquet.gzip
│   ├── mug_locations.parquet.gzip
│   ├── pit_locations.parquet.gzip
│   ├── protocole_112_nl_0.pdf
│   ├── protocoles_112_fr_0.pdf
│   └── variables_ambureg.xlsx
├── Visualization
│   ├── AED - Cardiac Bubble Plots - HTML
│   │   ├── bubble_plot_Belgium.html
│   │   ├── bubble_plot_antwerp.html
│   │   ├── bubble_plot_antwerpen.html
│   │   ├── bubble_plot_bruxelles-brussel.html
│   │   ├── bubble_plot_hainaut.html
│   │   ├── bubble_plot_liège.html
│   │   ├── bubble_plot_limburg.html
│   │   ├── bubble_plot_luxembourg.html
│   │   ├── bubble_plot_namur.html
│   │   ├── bubble_plot_oost-vlaanderen.html
│   │   ├── bubble_plot_vlaams-brabant.html
│   │   └── bubble_plot_west-vlaanderen.html
│   ├── AED Cholorpleth Plots (Folium) - HTML
│   │   └── cholorpleth_provinces.html
│   ├── AED Location Plots - HTML
│   │   ├── aed_locations_across_provinces.html
│   │   ├── aed_locations_antwerpen.html
│   │   ├── aed_locations_brabant wallon.html
│   │   ├── aed_locations_bruxelles-brussel.html
│   │   ├── aed_locations_hainaut.html
│   │   ├── aed_locations_liège.html
│   │   ├── aed_locations_limburg.html
│   │   ├── aed_locations_luxembourg.html
│   │   ├── aed_locations_namur.html
│   │   ├── aed_locations_oost-vlaanderen.html
│   │   ├── aed_locations_vlaams-brabant.html
│   │   └── aed_locations_west-vlaanderen.html
│   ├── Created CSV Files
│   │   ├── AED per Municipality
│   │   │   ├── AED_per_municipality_antwerpen.csv
│   │   │   ├── AED_per_municipality_brabant wallon.csv
│   │   │   ├── AED_per_municipality_bruxelles-brussel.csv
│   │   │   ├── AED_per_municipality_hainaut.csv
│   │   │   ├── AED_per_municipality_liège.csv
│   │   │   ├── AED_per_municipality_limburg.csv
│   │   │   ├── AED_per_municipality_luxembourg.csv
│   │   │   ├── AED_per_municipality_namur.csv
│   │   │   ├── AED_per_municipality_oost-vlaanderen.csv
│   │   │   ├── AED_per_municipality_vlaams-brabant.csv
│   │   │   └── AED_per_municipality_west-vlaanderen.csv
│   │   ├── AED_GEO.csv
│   │   ├── AED_coordinates_NEWEST_2.csv
│   │   ├── AED_within_provinces.csv
│   │   ├── AREA_PROVINCES.csv
│   │   ├── Cardiac Arrest per Municipality
│   │   │   ├── CARDIAC_per_municipality_antwerpen.csv
│   │   │   ├── CARDIAC_per_municipality_brabant_wall.csv
│   │   │   ├── CARDIAC_per_municipality_brussels.csv
│   │   │   ├── CARDIAC_per_municipality_hainaut.csv
│   │   │   ├── CARDIAC_per_municipality_liege.csv
│   │   │   ├── CARDIAC_per_municipality_limburg.csv
│   │   │   ├── CARDIAC_per_municipality_luxem.csv
│   │   │   ├── CARDIAC_per_municipality_namur.csv
│   │   │   ├── CARDIAC_per_municipality_oost_vlaand.csv
│   │   │   ├── CARDIAC_per_municipality_vlaams_brabant.csv
│   │   │   └── CARDIAC_per_municipality_west_vlaand.csv
│   │   ├── MUG_coordinates_new.csv
│   │   └── PIT_coordinates_new.csv
│   ├── Created GeoJSON Files
│   │   ├── AED_DENS_POPUL_WITHIN_PROVINCES.geojson
│   │   ├── AED_DENS_WITHIN_PROVINCES.geojson
│   │   ├── AED_GEO.geojson
│   │   ├── AED_WITHIN_PROVINCES.geojson
│   │   ├── AREA_PROVINCES_NEW.geojson
│   │   └── BE_SHAPE.geojson
│   └── Yiannis - Notebooks - Visualizations
│       ├── All_Visualizations.ipynb
│       ├── Bubble_plots_object.ipynb
│       ├── Coordinates.ipynb
│       ├── Plots_Provinces_AED.ipynb
│       ├── Polygons.ipynb
│       ├── municipality_AED.ipynb
│       └── plot_municipalities_AED.ipynb
└── preprocess_intervention
    ├── cad9_clean.parquet
    ├── cad9_cluster.ipynb
    ├── cad9_preprocess.ipynb
    ├── data_preprocess.ipynb
    ├── intvn1_bxl1_clean.parquet
    ├── intvn_clean.parquet
    └── intvn_preprocess.ipynb


## Installation
### Set up the Project?
Clone the project repository: 
```
git clone https://github.com/camilleecu/MDA.git
```

### Try our app? 
```
Please click the link: [https://mda-c5992f1a540f.herokuapp.com/](https://mda-c5992f1a540f.herokuapp.com/) (Chrome Recommended)<br>
```

### Run the app locally?
```
For Windows Users: Download our App folder, then run the app.py document <br>
For Mac OS Users/Linux: [https://github.com/lynweih/MDA_app](https://github.com/lynweih/MDA_app)
```






