# Cycling x Wind Resistance
	
Every cyclist who has ever pedaled into a stiff headwind knows about wind resistance. It's exhausting! In order to move forward, the cyclist must push through the mass of air in front of him/her. And this takes energy.

The idea of this project is to show visually how the wind resistance can impact the cycling activity.


## Team:

* Débora Karoline Silva de Azevedo ( deboraazevedoo@gmail.com )
* Eliseu Jayro de Souza Medeiros ( eliseujayro@gmail.com )
* Francisco de Paiva Marques Netto ( pvnetto1@gmail.com )
* Igor Augusto Brandão ( igorabrandao@gmail.com )



## The dataset:
The dataset consists in a workout history (CSV file which includes the coordinates of the routes of the physical activities done in the given period of time) and a Jupyter Notebook with all the instructions and libraries needed to perform the data analysis.

### How to use ###

1. Download the *py-exercise-dashboard.ipynb*, *dataSource.xlsx* files and put it in the same folder. 
2. After that, use Jupyter notebook tool and access the directory with the files. Enjoy yourself! :)

### Important ###

To run the heat map, it's necessary to run the following command:

```
jupyter notebook --NotebookApp.iopub_data_rate_limit=10000000
```

This command avoid aborting the heatmap processing, which can happen due to the huge amount of coordenates needed to create the maps.

## Activities definition ##

* Work on the WindyAPI (consume data from the web API and relate it to the Folium maps with the location and coordenates given): Francisco de Paiva and Igor Brandão
* Ideation and maps creation (think of ways to relate the data into significant aspects and use the data from the dataset, together with Folium, to create the maps): Débora Azevedo and Igor Brandão
* Desing of the images, writing and text review (create a context, a story that has a relation to the problematic brought in  this work and review writing): Eliseu Jayro and Débora Azevedo
