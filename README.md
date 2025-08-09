#  Vijayawada Railway Data

> Analytical insights into train fares, schedules, and availability for services through **Vijayawada Junction**, using Python and Jupyter Notebooks.

---

##  Table of Contents

- [Overview](#overview)  
- [Features](#features)  
- [Dataset](#dataset)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Sample Visuals](#sample-visuals)  
- [Modeling & Results](#modeling--results)  
- [Contributing](#contributing)  
- [License](#license)  
- [Contact](#contact)

---

##  Overview

This project offers a synthetic yet realistic dataset featuring fare breakdowns, distance, duration, and seat availability for trains through Vijayawada (BZA). Leveraging Python and Jupyter Notebooks, it enables users to explore data, visualize insights, and even train machine learning models for fare prediction.

---

##  Features

- Clean, well-structured dataset of train fare components and availability  
- Interactive data exploration via Jupyter  
- Visualizations: fare distributions, distance vs. fare charts, class-wise analyses  
- Ready-to-train ML models: Linear Regression, Random Forest, Gradient Boosting

---

##  Dataset

| Column             | Description                                   |
|--------------------|-----------------------------------------------|
| `baseFare`         | Base fare for journey (INR)                    |
| `reservationCharge`| Reservation fee component (INR)               |
| `superfastCharge`  | Charge for superfast service (INR)             |
| `serviceTax`       | Applicable taxes (INR)                         |
| `cateringCharge`   | Catering/food fee (INR)                        |
| `dynamicFare`      | Fare adjustments due to demand (INR)           |
| `distance`         | Distance traveled (km)                         |
| `duration`         | Journey time (min or hours based on data)      |
| `availability`     | Seat availability statuses on given dates      |
| …other metadata…   | Train number, origin/destination codes, etc.   |

---

##  Installation

1. **Clone the repository**  
   ```bash
   git clone https://github.com/Krupakar-injeti/Vijayawada-Railway-Data.git
   cd Vijayawada-Railway-Data
Install dependencies

'''bash
Copy
Edit
pip install -r requirements.txt
Launch Jupyter Notebook

'''bash
Copy
Edit
jupyter notebook
Open and run the railway_fare_prediction.ipynb file for the full analysis.
