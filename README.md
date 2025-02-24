# PredictingCollisions

For this project the team analyzed traffic collision data to enhance road safety and EMS response times in Toronto. We merged datasets from the City of Toronto, Environment Canada, and other traffic sources—comprising over 180,000 records with 23 features—to explore the factors contributing to collisions and to identify high-risk areas.

We employed a multi-model approach:
- **Kernel Density Estimation (KDE):** Mapped spatial collision hotspots.
- **Logistic Regression (LR) & Random Forest Classifier (RFC):** Predicted collision risk by incorporating both spatial and non-spatial factors (e.g., time-of-day, weather conditions).
  
The predicted risk scores were then integrated into an optimization model—solved using Gurobipy—to determine the best locations for additional ambulance stations. Our findings indicated that strategically placing 5 additional ambulances could reduce the overall response distance by nearly 3,500 km, highlighting the potential impact of data-driven EMS optimization.

This project demonstrates how combining predictive analytics with optimization techniques can inform policy decisions and improve emergency response strategies. Future work aims to refine these models with more granular traffic data and road network information to further enhance response accuracy.

![RecSites](https://github.com/user-attachments/assets/bdc0f7db-6a6d-40cf-9f97-50b0570a0555)
