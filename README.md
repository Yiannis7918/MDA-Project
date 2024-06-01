# AED (Automated External Defibrillator): Aid Ends Death

## Group Members
- Camille Cu
- Linwei He
- Wendy Dewit
- Yiannis Dikaioulias

## Introduction

This is the project for the Modern Data Analysis in KU Leuven. Our group is dedicated to exploring the intricate relationship between the placement of AEDs and the occurrence of emergency incidents,to enhance public health and safety.

## Table of Contents
├── App<br>
│   ├── App Datasets<br>
│   │   ├── AED_DENS_POPUL_WITHIN_PROVINCES.geojson<br>
│   │   ├── AED_DENS_WITHIN_PROVINCES.geojson<br>
│   │   ├── AED_GEO.geojson<br>
│   │   ├── AED_WITHIN_PROVINCES.geojson<br>
│   │   ├── AED_per_municipality_antwerpen.csv<br>
│   │   ├── AED_per_municipality_brabant wallon.csv<br>
│   │   ├── AED_per_municipality_bruxelles-brussel.csv<br>
│   │   ├── AED_per_municipality_hainaut.csv<br>
│   │   ├── AED_per_municipality_liège.csv<br>
│   │   ├── AED_per_municipality_limburg.csv<br>
│   │   ├── AED_per_municipality_luxembourg.csv<br>
│   │   ├── AED_per_municipality_namur.csv<br>
│   │   ├── AED_per_municipality_oost-vlaanderen.csv<br>
│   │   ├── AED_per_municipality_vlaams-brabant.csv<br>
│   │   ├── AED_per_municipality_west-vlaanderen.csv<br>
│   │   ├── AREA_PROVINCES_NEW.geojson<br>
│   │   ├── BE_SHAPE.geojson<br>
│   │   ├── CARDIAC_per_municipality_antwerpen.csv<br>
│   │   ├── CARDIAC_per_municipality_brabant_wall.csv<br>
│   │   ├── CARDIAC_per_municipality_brussels.csv<br>
│   │   ├── CARDIAC_per_municipality_hainaut.csv<br>
│   │   ├── CARDIAC_per_municipality_liege.csv<br>
│   │   ├── CARDIAC_per_municipality_limburg.csv<br>
│   │   ├── CARDIAC_per_municipality_luxem.csv<br>
│   │   ├── CARDIAC_per_municipality_namur.csv<br>
│   │   ├── CARDIAC_per_municipality_oost_vlaand.csv<br>
│   │   ├── CARDIAC_per_municipality_vlaams_brabant.csv<br>
│   │   ├── CARDIAC_per_municipality_west_vlaand.csv<br>
│   │   ├── Cardiac_location.geojson<br>
│   │   ├── Cholorpleth_Cardiac_Arrests_Municipalities.html<br>
│   │   ├── Cholorpleth_Counts_Municipalities.html<br>
│   │   ├── Interventions_risky_probability.csv<br>
│   │   ├── Vecotrs.geojson<br>
│   │   ├── cardiac.csv<br>
│   │   └── cholorpleth_provinces.html<br>
│   ├── Procfile<br>
│   ├── app.py<br>
│   ├── pages<br>
│   │   ├── Page_1.py<br>
│   │   ├── Page_2.py<br>
│   │   ├── Page_3.py<br>
│   │   ├── Page_4.py<br>
│   │   ├── Page_5.py<br>
│   │   ├── Page_6.py<br>
│   │   ├── Page_7.py<br>
│   ├── requirements.txt<br>
│   └── runtime.txt<br>
├── Clustering<br>
│   ├── Cardiac_location.geojson<br>
│   ├── Cholorpleth_Cardiac_Arrests_Municipalities.html<br>
│   ├── Cholorpleth_Counts_Municipalities.html<br>
│   ├── Vecotrs.geojson<br>
│   ├── Vectors.ipynb<br>
│   ├── cardiac.csv<br>
│   ├── chorepleth_density.ipynb<br>
│   ├── choropleth_muni_vectors.ipynb<br>
│   ├── georef-belgium-submunicipality@public<br>
│   │   ├── georef-belgium-submunicipality-millesime.cpg<br>
│   │   ├── georef-belgium-submunicipality-millesime.dbf<br>
│   │   ├── georef-belgium-submunicipality-millesime.prj<br>
│   │   ├── georef-belgium-submunicipality-millesime.shp<br>
│   │   └── georef-belgium-submunicipality-millesime.shx<br>
│   ├── intervention.ipynb<br>
│   ├── lineplot.ipynb<br>
│   ├── mapboxheat.ipynb<br>
│   ├── vector_shape<br>
│   │   ├── amb.cpg<br>
│   │   ├── amb.dbf<br>
│   │   ├── amb.prj<br>
│   │   ├── amb.shp<br>
│   │   ├── amb.shx<br>
│   │   ├── be.cpg<br>
│   │   ├── be.dbf<br>
│   │   ├── be.prj<br>
│   │   ├── be.shp<br>
│   │   ├── be.shx<br>
│   │   ├── mug.cpg<br>
│   │   ├── mug.dbf<br>
│   │   ├── mug.prj<br>
│   │   ├── mug.shp<br>
│   │   ├── mug.shx<br>
│   │   ├── pit.cpg<br>
│   │   ├── pit.dbf<br>
│   │   ├── pit.prj<br>
│   │   ├── pit.shp<br>
│   │   └── pit.shx<br>
│   └── view_data.ipynb<br>
├── GeoJSON and CSV files from online sources<br>
│   ├── BE.json<br>
│   ├── BELGIUM_-_Provinces.geojson<br>
│   └── Belgique_-_Nombre_d_habitants_par_commune_en_2011.csv<br>
├── Modelling<br>
│   ├── Interventions_combined_pre_preprocessing.csv<br>
│   ├── Interventions_risky_probability.csv<br>
│   └── Modelling.ipynb<br>
├── README.md<br>
├── Raw Datasets from Toledo<br>
│   ├── LICENSE<br>
│   ├── aed_locations.parquet.gzip<br>
│   ├── ambulance_locations.parquet.gzip<br>
│   ├── cad9.parquet.gzip<br>
│   ├── interventions1.parquet.gzip<br>
│   ├── interventions2.parquet.gzip<br>
│   ├── interventions3.parquet.gzip<br>
│   ├── interventions_bxl.parquet.gzip<br>
│   ├── interventions_bxl2.parquet.gzip<br>
│   ├── mug_locations.parquet.gzip<br>
│   ├── pit_locations.parquet.gzip<br>
│   ├── protocole_112_nl_0.pdf<br>
│   ├── protocoles_112_fr_0.pdf<br>
│   └── variables_ambureg.xlsx<br>
├── Visualization<br>
│   ├── AED - Cardiac Bubble Plots - HTML<br>
│   │   ├── bubble_plot_Belgium.html<br>
│   │   ├── bubble_plot_antwerp.html<br>
│   │   ├── bubble_plot_antwerpen.html<br>
│   │   ├── bubble_plot_bruxelles-brussel.html<br>
│   │   ├── bubble_plot_hainaut.html<br>
│   │   ├── bubble_plot_liège.html<br>
│   │   ├── bubble_plot_limburg.html<br>
│   │   ├── bubble_plot_luxembourg.html<br>
│   │   ├── bubble_plot_namur.html<br>
│   │   ├── bubble_plot_oost-vlaanderen.html<br>
│   │   ├── bubble_plot_vlaams-brabant.html<br>
│   │   └── bubble_plot_west-vlaanderen.html<br>
│   ├── AED Cholorpleth Plots (Folium) - HTML<br>
│   │   └── cholorpleth_provinces.html<br>
│   ├── AED Location Plots - HTML<br>
│   │   ├── aed_locations_across_provinces.html<br>
│   │   ├── aed_locations_antwerpen.html<br>
│   │   ├── aed_locations_brabant wallon.html<br>
│   │   ├── aed_locations_bruxelles-brussel.html<br>
│   │   ├── aed_locations_hainaut.html<br>
│   │   ├── aed_locations_liège.html<br>
│   │   ├── aed_locations_limburg.html<br>
│   │   ├── aed_locations_luxembourg.html<br>
│   │   ├── aed_locations_namur.html<br>
│   │   ├── aed_locations_oost-vlaanderen.html<br>
│   │   ├── aed_locations_vlaams-brabant.html<br>
│   │   └── aed_locations_west-vlaanderen.html<br>
│   ├── Created CSV Files<br>
│   │   ├── AED per Municipality<br>
│   │   │   ├── AED_per_municipality_antwerpen.csv<br>
│   │   │   ├── AED_per_municipality_brabant wallon.csv<br>
│   │   │   ├── AED_per_municipality_bruxelles-brussel.csv<br>
│   │   │   ├── AED_per_municipality_hainaut.csv<br>
│   │   │   ├── AED_per_municipality_liège.csv<br>
│   │   │   ├── AED_per_municipality_limburg.csv<br>
│   │   │   ├── AED_per_municipality_luxembourg.csv<br>
│   │   │   ├── AED_per_municipality_namur.csv<br>
│   │   │   ├── AED_per_municipality_oost-vlaanderen.csv<br>
│   │   │   ├── AED_per_municipality_vlaams-brabant.csv<br>
│   │   │   └── AED_per_municipality_west-vlaanderen.csv<br>
│   │   ├── AED_GEO.csv<br>
│   │   ├── AED_coordinates_NEWEST_2.csv<br>
│   │   ├── AED_within_provinces.csv<br>
│   │   ├── AREA_PROVINCES.csv<br>
│   │   ├── Cardiac Arrest per Municipality<br>
│   │   │   ├── CARDIAC_per_municipality_antwerpen.csv<br>
│   │   │   ├── CARDIAC_per_municipality_brabant_wall.csv<br>
│   │   │   ├── CARDIAC_per_municipality_brussels.csv<br>
│   │   │   ├── CARDIAC_per_municipality_hainaut.csv<br>
│   │   │   ├── CARDIAC_per_municipality_liege.csv<br>
│   │   │   ├── CARDIAC_per_municipality_limburg.csv<br>
│   │   │   ├── CARDIAC_per_municipality_luxem.csv<br>
│   │   │   ├── CARDIAC_per_municipality_namur.csv<br>
│   │   │   ├── CARDIAC_per_municipality_oost_vlaand.csv<br>
│   │   │   ├── CARDIAC_per_municipality_vlaams_brabant.csv<br>
│   │   │   └── CARDIAC_per_municipality_west_vlaand.csv<br>
│   │   ├── MUG_coordinates_new.csv<br>
│   │   └── PIT_coordinates_new.csv<br>
│   ├── Created GeoJSON Files<br>
│   │   ├── AED_DENS_POPUL_WITHIN_PROVINCES.geojson<br>
│   │   ├── AED_DENS_WITHIN_PROVINCES.geojson<br>
│   │   ├── AED_GEO.geojson<br>
│   │   ├── AED_WITHIN_PROVINCES.geojson<br>
│   │   ├── AREA_PROVINCES_NEW.geojson<br>
│   │   └── BE_SHAPE.geojson<br>
│   └── Yiannis - Notebooks - Visualizations<br>
│       ├── All_Visualizations.ipynb<br>
│       ├── Bubble_plots_object.ipynb<br>
│       ├── Coordinates.ipynb<br>
│       ├── Plots_Provinces_AED.ipynb<br>
│       ├── Polygons.ipynb<br>
│       ├── municipality_AED.ipynb<br>
│       └── plot_municipalities_AED.ipynb<br>
└── preprocess_intervention<br>
    ├── cad9_clean.parquet<br>
    ├── cad9_cluster.ipynb<br>
    ├── cad9_preprocess.ipynb<br>
    ├── data_preprocess.ipynb<br>
    ├── intvn1_bxl1_clean.parquet<br>
    ├── intvn_clean.parquet<br>
    └── intvn_preprocess.ipynb<br>


## Installation
### Set up the Project?
Clone the project repository: 
```
git clone https://github.com/camilleecu/MDA.git
```

### Try our app? 
```
Please click the link: [https://mda-c5992f1a540f.herokuapp.com/](https://mda-c5992f1a540f.herokuapp.com/)  
(Chrome Recommended)

```

### Run the app locally?
```
For Windows Users: Download our App folder, then run the app.py document <br>
For Mac OS Users/Linux: [https://github.com/lynweih/MDA_app/](https://github.com/lynweih/MDA_app/)
```






