<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Project Title

Leveraging RTA data and Street View imagery to validate and improve road safety.


## Summary

World Health Organisation data indicates that approximately 3,200 people die in Road Traffic Accidents globally every day.  The vast majority of these deaths occur in low- and middle-income countries, and it has been estimated that at least 100 million people have died on the roads since the era of the motor car began.  An enormous amount of research has been undertaken into the underlying causation and the optimal remedial action needed to address this issue, and in many instances this work has fallen into the three areas of education, engineering and enforcement.
I believe Artificial Intelligence offers a phenomenal opportunity to leverage data regarding accident frequency and location against "street view" imagery of the global road network to sift and intelligently categorise the many relevant physical variables.  If AI could be utilised to review accident sites in detail, intelligently, and at far greater speed than informed humans could, I believe it would firstly inform our current understanding and assumptions regarding RTA causation, and secondly, contribute to an overall reduction in road deaths worldwide.
Addressing the huge human toll of RTAs and its disproportionate impact on less affluent nations would also serve to demonstrate the immense potential AI offers to improve life.


## Background

Whilst significant data exists regarding prevalent variables in RTA occurrence (weather, visibility, road layout, signage), direct comparisons of sites globally in order to identify and quantify real-world common factors has to my knowledge not been undertaken hitherto.  Overall safety evaluations of national road networks have been undertaken (see, for example, https://s3-eu-west-1.amazonaws.com/roadsafetyfoundation.org/2008-05-20_IRE_RRM/2008-05-20_IRE_RRM_01_report.pdf), but this has been limited to an assigned safety score, rather than an assessment of specific circumstantial variables.  Visual imagery such as Google Street View and Apple Maps Look Around could, however,  be utilised by suitably trained AI to assess the physical characteristics of identified RTA sites to infer causal factors.  In the ten years since its inception in 2007, for example, Google Street View mapped 10 milion miles across 42 per cent of the world's countries, and the imagery obtained has already been used extensively for research purposes, e.g., quantifying greenery, health studies, and assessing cycling conditions


## How is it used?

I envisage the responsible national agencies as the primary users of this facility, and the local and regional departments (local authorities, emergency services) through which they responsiblity is enacted.
The output of the analysis could be used in a number of ways:
* in its simplest terms identification of the most signifcant variables in RTA frequency could be used to inform government policy on road safety (for example, to adjust the relative emphasis given to speed limit compliance and education regarding signage)
* poorer nations could utilise the data to identify the most cost effective measures that could be taken to improve the safety of their roads, and to validate proposals regarding new layouts
* specific recommendations regarding current approaches to road design could be made, with data made available on a compartive basis (so that, for example, a new road layout could be actively compared with similar examples globally)
* longitudinal analysis could be taken in the longer term, to validate or refute measures targeted at safety improvement.


## Data sources and AI methods
I envisage two fundamental sources of data for this project: satellite imaging and street view data, such as Google maps, and international road traffic accident statistics.  No dedicated data collection should be required.

Whilst there are significant variations in the quality and comparability of data captured nationally on RTAs, global organisations such as the European Commission and the International Traffic Safety Data and Analysis Group (IRTAD) at the OECD’s International Transport Forum, compile data from various countries to provide a comprehensive overview of road safety performance.

## Challenges

Some initial effort will be required to collate site-specific road data and allow cross-reference to available mapping.  Should this prove to be prohibitive, an initial proof of concept phase could be initiated in which road scores are mapped in order to review common variables.

## What next?

Once the initial analysis is completed, ongoing updates would provide a longitudinal study which would provide better information regarding  seasonal variations, time of day variation, as well as confirming or rejecting the anticipated road safety improvements arising from ongoing engineering updates and improvements.  In addition, the facility could be utilised to prototype proposed changes to road layouts, signage, speed limits, et cetera, in order to becnhmark them against similar contexts elsewhere in the world, and therefore predict likely impacts, before they are deployed.


## Acknowledgments

*Ito, K.; Biljecki, F. (2021). "Assessing bikeability with street view imagery and computer vision". Transportation Research Part C: Emerging Technologies. 132: 103371.
*Biljecki, F.; Ito, K. (2021). "Street view imagery in urban analytics and GIS: A review". Landscape and Urban Planning. 215: 104217.
*Ackerman, Dan (May 30, 2017). "Google Maps Street View celebrates its 10th birthday". CNET.
*https://etsc.eu/euroadsafetydata/
*https://www.itf-oecd.org/road-safety-annual-report-2024
*https://irap.org/rap-tools/crash-data/crash-risk-mapping/


