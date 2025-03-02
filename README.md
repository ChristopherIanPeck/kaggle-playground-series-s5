# Kaggle Playground Series Season 5
Welcome to my repository for the Kaggle Playground Series Season 5!  
This repository will serve as a centralized hub for my work on the competitions hosted as part of this series.

## Overview

The Kaggle Playground Series is a monthly machine learning competition series aimed at providing interesting and approachable datasets for the Kaggle community to practice their skills and build experience with real-world problems. The competitions are open to beginners and experts alike, making them an excellent opportunity to learn, experiment, and grow.

## Current Competition:
## [Kaggle Playground Series - S5E3 Overview](https://www.kaggle.com/competitions/playground-series-s5e3/data)  
[My Work](binary-prediction-challenge.ipynb)

### Competition Details

**Description:**  
Predict rainfall for each day of the year.  

**Start Date:** March 1st 2025  
**End Date:** March 31st 2025

## Evaluation Metric: ROC curve

Submissions are evaluated on area under the ROC curve between the predicted probability and the observed target:

$$
\textrm{AUC} = \sum_{i=1}^{n} ( \textrm{FPR}_i - \textrm{FPR}_{i-1} ) \times \textrm{TPR}_i
$$  

---
## Past Competition:  
## [Kaggle Playground Series - S5E2 Overview](https://www.kaggle.com/competitions/playground-series-s5e2)  
[My Work](backpack-prediction-challenge.ipynb)

### Competition Details

**Description:**  
Predict the price of backpacks given various attributes.

**Start Date:** Febuary 1st 2025  
**End Date:** Febuary 28th 2025

## Evaluation Metric: Root Mean Squared Error (RMSE)

Submissions are scored on the root mean squared error. RMSE is defined as:

$$
\textrm{RMSE} =  \left( \frac{1}{N} \sum_{i=1}^{N} (y_i - \widehat{y}_i)^2 \right)^{\frac{1}{2}}
$$

where:  
$$\widehat{y}_i\$$ is the predicted value,  
$$y_i$$ is the original value for each instance $$i$$.  

---
## [Kaggle Playground Series - S5E1 Overview](https://www.kaggle.com/competitions/playground-series-s5e1)  
[My Work](forecasting-sticker-sales-s5e1.ipynb)

### Competition Details  
**Description:**  
The objective of this challenge is to forecast sticker sales in different countries.  

**Start Date:** January 1st 2025  
**End Date:** January 31st 2025  

## **Evaluation Metric:**  
Submissions are evaluated using the Mean Absolute Percentage Error (MAPE).  

$$
\textrm{MAPE} = \frac{1}{N} \sum_{i=1}^{N} \left| \frac{y_i - \widehat{y}_i}{y_i} \right| \times 100
$$

where:  
$$y_i \$$ is the actual value,  
$$\widehat{y}_i \$$ is the predicted value,  
$$N \$$ is the total number of observations.

### Future Competitions

This repository will be continuously updated with additional competitions in the series as they are announced.

---
## Acknowledgments

Thanks to the Kaggle team and the Kaggle community for providing these valuable learning opportunities. Special mention to the organizers of the Playground Series for their efforts in curating the datasets and tasks.

### Contact

If you have any questions, suggestions, or feedback, feel free to reach out:

GitHub: [ChristopherIanPeck](https://github.com/ChristopherIanPeck)  
Portfolio: [christopherianpeck.github.io](https://christopherianpeck.github.io/)

Happy modeling and good luck to everyone participating in the Kaggle Playground Series Season 5!

