# 📱 App User Segmentation Using Python

This project replicates the tutorial from [The Clever Programmer](https://thecleverprogrammer.com/2023/01/30/app-user-segmentation-using-python/) to perform **user segmentation** based on in-app activity and spending behavior.
By clustering users, we aim to derive actionable business insights like identifying frequent visitors, high spenders, and users at risk of churn.

---

## 📊 Objective

* **Segment app users** based on:

  * Their last visited session time (minutes)
  * Average spending in the app (INR)
* **Visualize segments** to easily identify user behavior patterns.
* Enable **targeted marketing** and product personalization using these clusters.

---

## 🚀 Features

* 🔄 Clean and preprocess user activity data
* 🤖 Apply **KMeans Clustering** to group users
* 📊 Visualize segments using an **interactive scatter plot** (Plotly)
* 🎯 Identify distinct profiles like:

  * High Spenders
  * Frequent Visitors
  * Occasional Users
  * Low Activity / At-Risk Users

---

## 🛠️ Tech Stack

* **Python 3**
* **Pandas** — data manipulation
* **Scikit-learn** — clustering (KMeans)
* **Plotly** — interactive plots
* **Matplotlib** / **Seaborn** — additional visualizations (optional)

---

## 📂 Project Structure

```
├── application_user_segmentation.ipynb  # Jupyter Notebook (full code + outputs)
├── userbehaviour.csv                #  Sample user data
└── README.md                    # This file
```

---

## 📈 Key Visualization: User Segmentation Scatter Plot

The final output is an **interactive scatter plot** showing clustered user segments:

* **X-axis:** Last Visited Minutes
* **Y-axis:** Average Spent on App (INR)
* **Each color:** Represents a user segment (cluster)

Hovering over each point displays:

* Exact visit time
* Exact spend amount

This chart helps quickly spot:

* 💸 **High Spenders** (long sessions, high spend)
* 📲 **Frequent Visitors** (frequent visits, modest spend)
* 💤 **Occasional Users** (low visit, low spend)
* ⚠️ **Low Activity Users** (very inactive, possible churners)


---

## 📚 Reference

* **Original Tutorial**:
  [App User Segmentation Using Python (The Clever Programmer, 2023)](https://thecleverprogrammer.com/2023/01/30/app-user-segmentation-using-python/)

---

## 🙌 Acknowledgements

* Inspired by *The Clever Programmer*’s data science tutorials.
* Dataset structure based on sample user behavioral data.

