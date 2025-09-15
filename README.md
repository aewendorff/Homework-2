
# Homework 2 


Objective: exploring open access objectives of contemporary literature. 

Authors: Aubrey Wendorff, Rebekkah LaBlue, and Victoria Salerno.

Due: September 15, 2025.


### --- Objective 1 --- ###

Aubrey: I am in the field of aquatic ecology or limnology. For this task, I used a variety of search terms: road salt, chloride, phosphorus, water, urban, Hilary Dugan, and Jacques Finlay. I discovered that 5 out of 10 of the articles I looked at used an open source software (RStudio and GIS), 5 out of 10 used a data repository (Github, Zenodo, FRDR, or EDI), and 5 out of 10 used a public repository for their code (Github, Zenodo, FRDR, or EDI). For the full list of the articles and their corresponding information, use this google sheets link: https://docs.google.com/spreadsheets/d/13p7qnb2ViAvDIRS3vLg7n-C-giYZ4bLPLhDFdLjBFjo/edit?usp=sharing. 

Rebekkah: For my literature revoew, I used the following search terms: birds, protected areas, species distribution models, and bird atlas data. Of my 10 sources, 9 were open access articles; all used at least one open source software for analysis (primarily R, some Grass GIS, QGIS, Python) (limited access software included MatLab, Google Earth Engine); half of the articles has data in public repositories (github, re3data, google drive(???)), and of those that did not create a project-specific repository for their data indicated that the data was available and could be accessed on a public platform (eBird, iNaturalist, WorldClim, etc.); finally, only four of the ten papers provided code scripts for their analyses. Overall, I found the accessibility of these contemporary papers to be mixed at best for my specific research themes. For a full picture of these paper, see this link: https://docs.google.com/spreadsheets/d/1bhr2VANGD5Tu8pTs90pX-6oEg-dOQ6fHYMIiRgvlr6U/edit?usp=sharing

Victoria: Victoria:
My research and interests fall within the fields of entomology and behavioral ecology largely (focused on solitary bees). I used search terms such as solitary bee, behavior, global change, osmia lignaria, and megachilie rotundata (species I work with). Out of the ten articles I looked at it was relatively difficult to find clear data repositories and access to github/r/etc. I am not sure why this is, as I work in a lab that uses these formats quite frequently. I found that in more recent papers there was more details about code/data, but still not as acessible as I thought. Link to my scholarly articles: https://docs.google.com/spreadsheets/d/1Qde-HRuiOEVs20UZEln4SkEkDqSFrs1ltxVjgdMpgOs/edit?usp=sharing

### --- Objective 2 --- ###

We cloned the repo from "Modeling the Feasibility of Reducing Chloride Concentrations in an Urban Lake due to Road Salt Runoff" (https://doi.org/10.1111/1752-1688.70041). We recreated figure #4 with the code, aka "RMSE relationship between observed and modeled chloride with a rolling chloride line". The only change that needed to be made was the location in which the final figure was saved. This was done by changing ggsave('Figures_new/ModelOutput.png', width = 6.5, height = 3, dpi = 500) to ggsave('C:/Users/aubsc/OneDrive/Documents/QuantMeth.png', width = 6.5, height = 3, dpi = 500). 
