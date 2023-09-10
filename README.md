# US Homicide Data Science Project

Data science project investigating the murders of the last 50 years across the entire US. Extensive exploratory data analysis and visualization revealing important insights. Implementation of a supervised machine learning model using KNIME, which predicts the homicide clearance rate based on various parameters.

The data is provided by the [Murder Accountability Project](http://www.murderdata.org/) which tracks America's unsolved homicides. Here is the [link](https://www.dropbox.com/s/vul9mcu25q9usm1/SHR.zip?dl=1) to the dataset.

## Data Understanding

Unbalanced data set with 70% solved and 30% unsolved murder cases. Overall decline in murders per capita over the last 45 years, but rising again since 2014 with a sharp increase in 2020. Steady murder clearance rate of around 70% since 1990. Vast majority of murders carried out using handguns, followed by knifes and other types of firearms. For most murders the relationship of victim and offender could not be determined. The most common known relationship however is acquaintance. During the months of July and August there have been the most murders although the winter months of December, September and October follow closely behind.


Most of the victims were around 20 years old. Distribution decays exponentially with growing age. The overwhelming majority of murders only have one victim. Around 78% of victims where male and 22% were female. The share of black vs. white victims was almost 50/50 over the last 45 years. Due to the way the data was generated by the source, no reliable insights about the offenders could be derived.

Texas seems to have (compared to states with similar number of murders) a relatively high murder clearance rate while New York has a clearance rate of only about 50%. District of Columbia has an even worse clearance rate of only about 25% over the last 45 years. Looking at the distribution of sex of victims on a state-by-state basis reveals no obvious cases where disproportionately many women or men have been murdered. In almost all states the proportion of male vs. female victims is roughly 80/20. 


<p align="center"><img src="https://github.com/glarkstoat/DDS-Project/assets/74681570/329676f7-a519-492f-9551-b803a77c91c0" width="90%"/></p>
<p align="center"><img src="https://github.com/glarkstoat/DDS-Project/assets/74681570/d75fa689-2e69-49f9-8cd5-b5278f5dbdb7" width="90%"/></p>
<p align="center"><img src="https://github.com/glarkstoat/DDS-Project/assets/74681570/6162677e-5d66-4651-a593-66e1dedea622" width="50%"/></p>
<p align="center"><img src="https://github.com/glarkstoat/DDS-Project/assets/74681570/62454448-65bc-4e2a-986d-6113b08309e5" width="90%"/></p>
<p align="center"><img src="https://github.com/glarkstoat/DDS-Project/assets/74681570/6bd72bca-1c49-404a-b13a-f4f61b416146" width="90%"/></p>
