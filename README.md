# Diabetes Data Study from ITExperience
demo: https://youtu.be/uADWdKBi4gI?t=247 (my part starts at 4:07)
***
## Task
Create any project in Python with a group using libraries taught in the course (pandas, numpy, seaborn, matplotlib, etc...).
***
## Criteria
* Work with a team to create the project (ours had 3 people)
* Use Python and Jupyter Notebook or Google Collab
* Integrate Python libraries
* Document and present findings
***
## Summary
This was the final group project in a certification course for Python and Machine Learning. The project investigates information from a diabetes database by cleaning the data, training a model using sklearn, and creating a GUI. Each member worked focused on one of these areas (my part is the GUI).
***
## Functionality
Users can use the GUI interface near the bottom of the code to generate various graphs.The first section allows the user to compare variables with 1 or 2 fields. The color bar can be changed to reflect the color used on the graphs. The second section allows the user to view any number of the selected graphs that were previously cleaned.
***
## Design
This project is designed to take the user through each step of our data inv3estigation process. The first portion imports libraries and sets up graphs. The fiirst graphs display raw data, without cleaning or modeling. The next section removes stray data points (points that were entered with a value of null or impossible values). After this the machine learning works with the clean data sets to determine high corellation variables for diabetes. The final section is a graphical interface that allows users to see how data corresponds (high and low correlation of variables).
***
***
## Run Locally
* Open the file in Jupyter Notebook or Google Collab
* Compile all cell blocks
* note: it is important to compile them in order to ensure libraries are imported properly and graphs are genterated for GUI use
* Use the GUI section to generate desired graphs
