# IBM Data Science Capstone Project - SpaceX
## Introduction

In the realm of space exploration, SpaceX stands as a pioneering force with a commitment to democratizing space travel. Renowned for its achievements such as deploying spacecraft to the international space station, establishing a satellite constellation for global internet access, and conducting manned space missions, SpaceX distinguishes itself by achieving cost-effectiveness in rocket launches. The company's innovative approach involves the reutilization of the first stage of the Falcon 9 rocket, resulting in a launch cost of $62 million, a significant contrast to other providers whose expenses soar to over $165 million per launch without the capability to reuse the first stage. This research endeavors to ascertain the predictability of first-stage landing success by harnessing public data and machine learning models, thereby shedding light on the dynamics that influence launch outcomes.

## Explore

This study delves into the interplay of variables such as payload mass, launch site, number of flights, and orbits to discern their impact on the success of first-stage landings. Additionally, it examines the temporal evolution of successful landings, striving to identify patterns over time. The primary objective is to develop a robust predictive model for determining the likelihood of a successful first-stage landing, framing the investigation within the realm of binary classification.

## Executive Summary

The research methodology comprises several key steps. Initial data acquisition involved leveraging the SpaceX REST API and employing web scraping techniques to compile relevant information. Subsequent data wrangling facilitated the creation of an outcome variable distinguishing between successful and unsuccessful landings. Exploratory data analysis encompassed visualization techniques, utilizing factors such as payload, launch site, flight number, and yearly trends. Statistical analyses, employing SQL, provided insights into total payload, payload range for successful launches, and overall success and failure rates. The investigation extended to launch site success rates and their proximity to geographical markers, with visualizations highlighting successful launch sites and their payload ranges. The research also encompassed the construction and evaluation of predictive models, employing logistic regression, support vector machine (SVM), decision tree, and K-nearest neighbor (KNN) algorithms.

## Results

The exploratory data analysis revealed an overall improvement in launch success over time, with specific launch sites, such as KSC LC-39A, demonstrating notably high success rates. Certain orbits, including ES-L1, GEO, HEO, and SSO, achieved a 100% success rate. Visualization and analytics underscored the proximity of launch sites to the equator and coastlines. Predictive analytics showcased similar performance across models, with the decision tree model slightly outperforming others based on evaluation metrics.
Conclusion:
The research concludes with key insights into the factors influencing rocket landing success. Noteworthy observations include the positive trend in launch success over time, the influence of launch site selection on success rates, and the impact of payload mass on the likelihood of a successful landing. The study recommends further exploration with a larger dataset to enhance predictive analytics and suggests considering feature analysis or principal component analysis for improved accuracy. Additionally, the untapped potential of models like XGBoost poses an intriguing avenue for future investigation.

