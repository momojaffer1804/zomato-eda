# zomato-eda
# Zomato Restaurants: An Exploratory Data Analysis



### Project Overview

This project performs an in-depth exploratory data analysis (EDA) on the Zomato Restaurants dataset. The goal is to uncover insights into global restaurant distribution, popular cuisines, rating trends, and the availability of online services, providing a clear snapshot of the restaurant landscape as represented in this dataset.


---

### Key Questions & Insights

This analysis answers several key questions about the restaurant industry based on the Zomato data:

1.  **Where are most Zomato restaurants located?**
    * The data is heavily concentrated in **India**, with the **New Delhi NCR region** being the primary market.

2.  **What are the most popular food choices?**
    * **North Indian and Chinese** cuisines are the clear favorites, often served in combination.

3.  **What does the rating landscape look like?**
    * A large number of restaurants, especially in India, are **unrated**. Most rated establishments fall into an "Average" to "Good" bracket (2.6 - 3.7).

4.  **How common is online delivery?**
    * Online delivery services are not yet widespread and are primarily offered in **India and the UAE**.

5.  **Which cities are the top players?**
    * The top 5 cities with the most restaurants are all part of the greater **New Delhi region**, highlighting its market density.

---

### Key Visualizations

Here are a few sample visualizations from the analysis:

**1. Initial Data Overview (`pd.info()`):** A summary of the dataset showing column data types and non-null counts.
![Dataset Info Summary](blob:https://github.com/269105bb-3eff-419f-9439-c7640a75804a)

**2. Top Countries by Restaurant Count:** A pie chart showing the overwhelming market share of restaurants based in India.
![Top Countries Pie Chart](blob:https://github.com/9e63feaf-37ab-49fe-b34e-08191f246976)

**3. Rating Distribution:** A bar plot illustrating the frequency of different aggregate ratings.
![Ratings Distribution Bar Plot](blob:https://github.com/38a10e56-d9ff-48c1-b186-301ba8b32bc4)

---

### Technologies Used

* **Python:** Core language for analysis.
* **Pandas:** For data manipulation, cleaning, and merging.
* **Matplotlib & Seaborn:** For creating static and interactive visualizations.
* **Jupyter Notebook:** As the environment for the analysis.

---

### Setup and Installation

To replicate this analysis, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YourUsername/zomato-eda-project.git](https://github.com/YourUsername/zomato-eda-project.git)
    cd zomato-eda-project
    ```

2.  **Create and activate a virtual environment:**
    ```bash
    # For macOS/Linux
    python3 -m venv .venv
    source .venv/bin/activate

    # For Windows
    python -m venv .venv
    .\.venv\Scripts\activate
    ```

3.  **Install the required libraries:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Run the Jupyter Notebook:**
    ```bash
    jupyter notebook notebooks/zomato_analysis.ipynb
    ```

    ### Contact

Feel free to reach out with any questions or for collaborations!

* **Email:** [mohammad.jaffer.hussin@gmail.com]
* **LinkedIn:** [www.linkedin.com/in/mohammad-jaffer-hussin-614674315]
