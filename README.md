Module 15 Challenge
# leaflet_challenge
# USGS Earthquake Data Visualization
The United States Geological Survey (USGS) is seeking to develop a set of tools to visualize their earthquake data and provide meaningful information about the Earth and its processes. As a part of this challenge, you have been tasked with creating a visualization to display USGS earthquake data in an informative and interactive manner.

Before You Begin
Create a new repository for this project called "leaflet-challenge." Do not add this Challenge to an existing repository.

Clone the new repository to your computer.

Inside your local git repository, create two directories for the Leaflet challenge: "Leaflet-Part-1" and "Leaflet-Part-2." Use these folder names to correspond to the respective challenges.

Add all the necessary files, including HTML and JavaScript, to run the analysis. These will be the main files for the visualization.

Push the changes to GitHub.

# Instructions
The instructions for this activity are divided into two parts:

Part 1: Create the Earthquake Visualization
Get your dataset:

Visit the USGS GeoJSON Feed page Link to USGS GeoJSON Feed.

Choose a dataset to visualize. For example, you can select "All Earthquakes from the Past 7 Days."

Click on the dataset to view the JSON representation of the earthquake data.

Import and visualize the data:

Use Leaflet to create a map that plots all the earthquakes from your chosen dataset based on their longitude and latitude.

Represent the magnitude of the earthquakes using the size of the data markers, and the depth of the earthquakes using different colors. Larger earthquakes should have larger markers, and earthquakes with greater depth should appear with darker colors.

The depth of each earthquake can be found as the third coordinate for each entry in the dataset.

Include popups that provide additional information about each earthquake when its associated marker is clicked.

Create a legend that provides context for the earthquake data on the map.

Your visualization should resemble the example map provided in the prompt.
