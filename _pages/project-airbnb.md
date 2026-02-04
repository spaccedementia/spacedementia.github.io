---
title: "Airbnb Price Prediction"
permalink: /project-airbnb/
---

### One-line summary  
Predicted Airbnb listing prices using structured features and location signals, with emphasis on interpretability and generalization.

---

### Problem  
Accurately pricing short-term rentals is critical for revenue optimization and market positioning. The goal was to model listing prices while identifying key drivers such as location, amenities, and seasonality.

### Data  
- Public Airbnb listings  
- Features: location, room type, amenities, availability  
- Observations: thousands of listings (city-level)

### Approach  
- Feature engineering  
- Regularized regression and tree-based models  
- Cross-validation and error diagnostics  
- Model comparison against baseline benchmarks

### Validation  
- Train / validation splits  
- RMSE and MAE  
- Stability across neighborhoods

### Results  
- Improved prediction accuracy over baseline models  
- Identified strong location and amenity effects  
- Produced interpretable feature importance summaries

### What I would do next  
- Incorporate temporal demand signals  
- Explore hierarchical / spatial models  
- Test transferability across cities

### Artifacts  
- GitHub repository  
- Report PDF / slides
