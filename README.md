# Radioactive Decay Plot
 This repository features a radioactive decay plotter specifically designed for high school laboratory projects. It provides an interactive and educational tool to help students visualize and understand the principles of radioactive decay. It contains a csv file which can be opened with excel and saved as a csv file which will be later opened using pandas to fit an exponential curve by using scipy and finally plot the data by using a matplotlib plot with a design similar to a graph paper to help the student to measure the half time directly on a printed version of the plot for different radioactive samples. For this specific case a Cs-137 sample was used to measure the half-life of Ba-137m, which is around 153 seconds as to be found in http://nucleardata.nuclear.lu.se/toi/nuclide.asp?iZA=560437 
 
 The only that the students must do is to fill the prepared table on the csv file, save the changes and in the ipynb file run the first snippet to create the plot and save it at the same time in the figures folder. To check how the program should work an example file is available to test the functionality of the code.
ChatGPT
Radioactive Decay Plot
This repository features a radioactive decay plotter specifically designed for high school laboratory projects. It provides an interactive and educational tool to help students visualize and understand the principles of radioactive decay.

Features
CSV Input: Includes a prepared CSV file that students can open in Excel, fill in with their data, and save.
Data Processing: Utilizes pandas to read the CSV file and SciPy to fit an exponential curve to the data.
Graphical Output: Generates a plot using Matplotlib with a design similar to graph paper, allowing students to measure the half-life directly on a printed version of the plot.
Example Case: Demonstrates the decay of a Cs-137 sample to measure the half-life of Ba-137m, approximately 153 seconds, as documented here.
Instructions
Prepare the Data:

Open the provided CSV file in Excel.
Fill in the prepared table with your experimental data.
Save the changes to the CSV file.
Generate the Plot:

Open the provided Jupyter notebook (ipynb file).
Run the first code snippet to read the CSV file, fit the exponential curve, and generate the plot.
The plot will be saved automatically in the figures folder.
Example File:

An example CSV file is included to test the functionality of the code and understand how the program works.
This tool simplifies the process of analyzing radioactive decay data, making it easier for students to learn and experiment with real-life examples.
 
 ![plot](https://github.com/GegAll/radioactive-decay-plot/assets/170819708/4a5a8682-25a6-4a55-9139-16c47c34d0c6)
