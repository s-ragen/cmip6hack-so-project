# CMIP6 Hackathon Project: SO Overturning and Sea Ice

### Scientific Motivation:

The circulation in the Southern Ocean is important for global climate, meridional overturning circulation, and stratification. Its capacity for heat uptake and its influence on global overturning make it an important driver for heat and carbon redistribution in the global ocean system. Climate models often poorly simulate bottom water formation in the Southern Ocean (see figure below), creating bottom water with densities that differ from climatology or getting the right amount of bottom water with the right properties for the wrong reasons. In the CMIP5 models, no models produced deep Antarctic water on the shelf and allowing it to spill over and convect, rather, models generate deep water through open ocean deep convection. Also, those models with strong sea ice seasonality have spurious deep convection (Huezé et al, 2013). Diagnosing the deep convection process and the bottom water formation in CMIP6 models is an important step in identifying models that can accurately simulate future Southern Ocean properties as well as future global climate changes.

![Image of Heuze Fig 2](https://github.com/s-ragen/cmip6hack-so-project/blob/master/hueze2013.jpg)

The first goal of this project is to determine whether CMIP6 models form bottom water around Antarctica with properties and in quantities similar to observations as well as if they do it in the right way. The second goal is to determine whether deep convection impacts sea ice variability across models or vice versa and if there is an easily identifiable physical mechanism.

### Research Questions
We hope to diagnose the Southern Ocean bottom water formation in CMIP6 models and the impact this formation has on overturning and transport in the region. We also hope to see whether there are links between bottom water formation and sea ice concentration and whether there are any mechanisms that link the two, perhaps through overturning or transport. The following proposed can serve as a guideline as to what we hope to build.

- Determine the water mass properties in the abyssal ocean around Antarctica
- Look at mixed layer depths in the Southern Ocean
    - Calculate MLD like Huezé et al? https://agupubs.onlinelibrary.wiley.com/doi/full/10.1002/grl.50287
- Calculate residual mean overturning streamfunction in the Southern Ocean
- Look at ACC transport in the Southern Ocean
- Plot seasonal sea ice concentration

### What's included?

1. `catalogs`: data catalogs that can be used by Intake-ESM.
1. `environments`: Conda environment files for the NCAR/Google Cloud deployments.
1. `notebooks`: a place for storing Jupyter Notebooks.
1. `README.md`: short project description
1. `LICENSE`: a default (MIT) license file.


Once the initial setup is done, everyone will want to clone the repository onto the compute system they plan to use for the hackathon.

1. Open a JupyterLab session on the system you plan to use.
1. Open a terminal in the JupyterLab environment.
1. Clone your project: `git clone https://github.com/username/cmip6hack-myproject.git`
1. Get to work!


### How to make your project citable

[Zenodo](https://about.zenodo.org/) is a data archiving tool that can help make your project citable by assigning a DOI to the project's GitHub repository.

Follow the guidelines here https://guides.github.com/activities/citable-code
