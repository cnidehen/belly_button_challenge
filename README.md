# belly_button_challenge
Module 14 Challenge

Background
In this assignment, you will build an interactive dashboard to explore the Belly Button Biodiversity datasetLinks to an external site., which catalogues the microbes that colonise human navels.

The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

Instructions
Complete the following steps:

Use the D3 library to read in samples.json from the URL https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json.

Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.

Use sample_values as the values for the bar chart.

Use otu_ids as the labels for the bar chart.

Use otu_labels as the hovertext for the chart.

![Otu_labels](https://github.com/cnidehen/belly_button_challenge/assets/128870405/d8587824-1fa1-424d-99a4-e72ecc608d4a)

Create a bubble chart that displays each sample.
Use otu_ids for the x values.

Use sample_values for the y values.

Use sample_values for the marker size.

Use otu_ids for the marker colors.

Use otu_labels for the text values.

![Bubble_chart](https://github.com/cnidehen/belly_button_challenge/assets/128870405/4315b4d0-4740-45f3-80aa-2e3b8da50997)

Display the sample metadata, i.e., an individual's demographic information.

Display each key-value pair from the metadata JSON object somewhere on the page.

![Guage_chart](https://github.com/cnidehen/belly_button_challenge/assets/128870405/92dd0004-23ad-485c-9641-6fe363d4c35b)

Update all the plots when a new sample is selected. Additionally, you are welcome to create any layout that you would like for your dashboard. An example dashboard is shown as follows:

![Dashboard](https://github.com/cnidehen/belly_button_challenge/assets/128870405/9ca521f2-493a-4d57-8ee0-1e732aabbca3)

The following task is advanced and therefore optional.

Adapt the Gauge Chart from https://plot.ly/javascript/gauge-charts/Links to an external site. to plot the weekly washing frequency of the individual.

You will need to modify the example gauge code to account for values ranging from 0 through 9.

Update the chart whenever a new sample is selected.

![Guage_chart](https://github.com/cnidehen/belly_button_challenge/assets/128870405/191a2846-85d2-4e0e-a56d-99f29e2e045e)





