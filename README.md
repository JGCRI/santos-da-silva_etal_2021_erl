_your zenodo badge here_

# santos-da-silva_etal_2021_erl

**The implications of uncertain renewable resource potentials for global solar and wind electricity projections**

Silvia R. Santos da Silva<sup>1,2\*</sup>, Gokul Iyer<sup>2</sup>, Thomas B. Wild<sup>2,4,5</sup>, Mohamad I. Hejazi<sup>3</sup>, Chris R. Vernon<sup>2,6</sup>, Matthew Binsted<sup>2</sup>, Fernando Miralles-Wilhelm<sup>4,7</sup>

<sup>1 </sup> Department of Atmospheric and Oceanic Science, University of Maryland, College Park, Maryland, United States of America

<sup>2 </sup> Joint Global Change Research Institute, Pacific Northwest National Laboratory, College Park, Maryland, United States of America

<sup>3 </sup> King Abdullah Petroleum Studies and Research Center, Riyadh, Saudi Arabia

<sup>4 </sup> Earth System Science Interdisciplinary Center, College Park, Maryland, United States of America

<sup>5 </sup> Department of Civil and Environmental Engineering, University of Maryland, College Park, Maryland, United States of America

<sup>6 </sup> Pacific Northwest National Laboratory, Richland, Washington, United States of America

<sup>7 </sup> College of Science, George Mason University, Fairfax, Virginia, United States of America

\* corresponding author:  silviameteoro@gmail.com

## Abstract
Studies exploring long-term energy system transitions rely on resource cost-supply curves derived from estimates of renewable energy (RE) potentials to generate solar and wind power projections. However, estimates of RE potentials are characterized by large uncertainties stemming from methodological assumptions that vary across studies, including factors such as the suitability of land and the performance and configuration of technology. Based on a synthesis of modeling approaches and parameter values used in prior studies, we explore the implications of these uncertain assumptions for solar PV and onshore wind electricity generation projections globally using the Global Change Analysis Model (GCAM). We show that variability in parametric assumptions related to land use (e.g. land suitability) are responsible for the most substantial uncertainty in both wind and solar generation projections. Additionally, assumptions about the average turbine installation density and turbine technology are responsible for substantial uncertainty in wind generation projections. Under scenarios that account for climate impacts on solar and wind power, we find that these parametric uncertainties are far more significant than those emerging from differences in climate models and scenarios in a global assessment, but uncertainty surrounding climate impacts (across models and scenarios) have significant effects regionally, especially for wind. Our analysis suggests the need for studies focusing on long-term energy system transitions to account for this uncertainty.

## Journal reference
TBD

## Code reference
References for each minted software release for all code involved.  

These are generated by Zenodo automatically when conducting a release when Zenodo has been linked to your GitHub repository. The Zenodo references are built by setting the author order in order of contribution to the code using the author's GitHub user name.  This citation can, and likely should, be edited without altering the DOI.

If you have modified a codebase that is outside of a formal release, and the modifications are not planned on being merged back into a version, fork the parent repository and add a `.<shortname>` to the version number of the parent and construct your own name.  For example, `v1.2.5.hydro`.

Human, I.M. (2021, April 14). Project/repo:v0.1.0 (Version v0.1.0). Zenodo. http://doi.org/some-doi-number/zenodo.7777777

## Data reference

### Input data
Reference for each minted data source for your input data.  For example:

Human, I.M. (2021). My input dataset name [Data set]. DataHub. https://doi.org/some-doi-number

### Output data
Reference for each minted data source for your output data.  For example:

Human, I.M. (2021). My output dataset name [Data set]. DataHub. https://doi.org/some-doi-number

## Contributing modeling software
| Model | Version | Repository Link | DOI |
|-------|---------|-----------------|-----|
| model 1 | version | link to code repository | link to DOI dataset |
| model 2 | version | link to code repository | link to DOI dataset |
| component 1 | version | link to code repository | link to DOI dataset |

## Reproduce my experiment
Fill in detailed info here or link to other documentation that is a thorough walkthrough of how to use what is in this repository to reproduce your experiment.


1. Install the software components required to conduct the experiement from [Contributing modeling software](#contributing-modeling-software)
2. Download and install the supporting input data required to conduct the experiement from [Input data](#input-data)
3. Run the following scripts in the `workflow` directory to re-create this experiment:

| Script Name | Description | How to Run |
| --- | --- | --- |
| `step_one.py` | Script to run the first part of my experiment | `python3 step_one.py -f /path/to/inputdata/file_one.csv` |
| `step_two.py` | Script to run the last part of my experiment | `python3 step_two.py -o /path/to/my/outputdir` |

4. Download and unzip the output data from my experiment [Output data](#output-data)
5. Run the following scripts in the `workflow` directory to compare my outputs to those from the publication

| Script Name | Description | How to Run |
| --- | --- | --- |
| `compare.py` | Script to compare my outputs to the original | `python3 compare.py --orig /path/to/original/data.csv --new /path/to/new/data.csv` |

## Reproduce my figures
Use the scripts found in the `figures` directory to reproduce the figures used in this publication.

| Script Name | Description | How to Run |
| --- | --- | --- |
| `generate_figures.py` | Script to generate my figures | `python3 generate_figures.py -i /path/to/inputs -o /path/to/outuptdir` |
