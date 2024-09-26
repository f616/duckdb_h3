# Notebooks using DuckDB with the H3 Extension and Overture Maps Data

![kepler gl (1)](https://github.com/user-attachments/assets/5dcd6e47-ee66-48b4-a5a9-2f78e8a28ebahttps://github.com/kentstephen/duckdb_h3/blob/main/tlc_overture_lonboard.ipynb

## In [tlc_overture_lonboard.ipynb](https://github.com/kentstephen/duckdb_h3/blob/main/tlc_overture_lonboard.ipynb) and [tlc_overture_kepler.ipynb](https://github.com/kentstephen/duckdb_h3/blob/main/tlc_overture_kepler.ipynb) I demonstrate how you can generate H3 from taxi data and merge it with Overture Buildings with those respective mapping libraries.

## *The latest DuckDB 1.1.0 now reads geoparquet natively. So that means all of these queries with `ST_GeomFromWKB` will break*
I am going to update them soon but for now just take out `ST_GeomFromWKB()` Now all but [montpelier_water_buildings.ipynb](montpelier_water_buildings.ipynb) is updated.

### In [montpelier_water_buildings.ipynb](montpelier_water_buildings.ipynb), I visualize the volume of buildings near water.

### In [egypt_building_density.ipynb](egypt_building_density.ipynb) I look at building density.
