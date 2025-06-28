# Autism-Diagnostic-Insights
# Beyond the Diagnosis: Modeling Autism Prevalence with Purpose
This project explores the evolving landscape of autism diagnosis across the United States—bridging clinical traits, demographic disparities, and temporal dynamics to uncover how diagnostic systems reflect and shape access to care.
“The autism diagnosis is more than a statistic. It is a reflection of systems that shape recognition, environments that foster understanding, and communities that demand equity.”
# Project Overview
This data-driven analysis integrates individual-level and national-level data to:
- Visualize patterns in autism prevalence over five decades
- Examine how behavioral traits influence diagnostic outcomes
- Detect disparities across geographic and demographic groups
- Identify “gray zone” diagnostic clusters through machine learning
- Evaluate temporal structure for forecasting with ARIMA models
The final product is a cohesive Tableau Storyboard that guides clinicians, policymakers, and researchers from observation to action.
# Tools Used
- Python: Data cleaning, clustering, temporal analysis (pandas, seaborn, statsmodels, scikit-learn)
- Tableau: Dashboard design and storytelling
- GeoPandas / GeoJSON: Spatial data integration
- PostgreSQL (optional): For structured querying and reproducibility
# Key Insights
- Trait clusters reveal diagnostic blind spots in underrepresented groups.
- Girls and minority children remain under-identified, despite trait presence.
- Temporal patterning suggests AR(1) dynamics, enabling future modeling.
- Post-2015 diagnostic slowdown may reflect systemic saturation or reporting shifts.
- Geo-demographic analysis highlights equity gaps across states and populations.
# Data Sources
This project draws from three key datasets:
- Individual-Level Diagnostic Data
Kaggle: Autism Trait Dataset
Used to analyze behavioral scores (e.g., Qchat-10, SRS, CARS) and perform clustering by diagnostic traits and demographics.
- National Prevalence and Policy Data
Hugging Face: Autism Prevalence Studies Dataset
Provides U.S. state-level prevalence rates across years, including population denominators and diagnostic policy context.
- U.S. Census State Population Estimates
U.S. Census Bureau – State Total Population Estimates
Used to calculate per-capita prevalence and normalize comparisons across geography and time.

# Tableau Storyboard
https://public.tableau.com/views/AutismProject/Story1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link








