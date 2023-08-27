![](https://news.mit.edu/sites/default/files/styles/news_article__image_gallery/public/images/201603/MIT-Program-Bacteria_0.jpg?itok=ZvXyMZ6T)
# Belly Button Biodiversity
1111111111111111
 
## This project aims to create an interactive dashboard to explore the Belly Button Biodiversity dataset, links to an [external site](https://mahsabakhtiari.github.io/Belly_Button_Biodiversity/), and catalogs the microbes that colonize human navels. 

The dashboard has two plots, a bar plot and a bubble plot, and a metadata display that generates for every chosen id sample. The barplot displays the top 10 OTUs found in that individual. a bubble plot that, for every sample ID, displays OTUs and their sample values.

There are two main parts to this project:
* Data processing
* Data visualization and interactive plotting

### Data processing
The study's dataset is stored as a  JSON object in [URL](https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json) that was ingested and processed with D3 library. 

### Data visualization and interactive plotting
For interactive visualization, preloaded plots and metadata display were created with Plotly, and a on-change event handler was added to update the plots and the metadata display interactively.

### Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvement, please submit a pull  request or open an issue on the GitHub repository.

### Resources

- http://robdunnlab.com/projects/belly-button-biodiversity/
- https://plotly.com/chart-studio-help/json-chart-schema/



