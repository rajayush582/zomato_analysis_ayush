# 🍽️ Zomato Analysis Dashboard

An interactive dashboard that explores restaurant data from Zomato, focusing on restaurant distribution, customer ratings, votes, cuisines, pricing, and online delivery.

## 📊 Dashboard Preview

![Zomato Analysis Dashboard](dashboard.png)

> **Note:** Add your dashboard screenshot to the repository and name it `dashboard.png`, or update the image path above to match your screenshot's filename.

## 🎯 Project Objective

The objective of this project is to turn restaurant data into clear visual insights. The dashboard helps users explore restaurant coverage across cities, understand rating patterns, compare price ranges, and examine the relationship between ratings and customer votes.

## 🔑 Key Performance Indicators (KPIs)

The dashboard displays six summary metrics:

| KPI | Displayed Value |
|---|---:|
| Total Restaurants | 10K |
| Average Rating | 2.67 |
| Average Cost for Two | 1.20K |
| Total Votes | 1M |
| Number of Cities | 147 |
| Total Cuisines | 1.831K |

*Values are shown as displayed in the dashboard and may be rounded or abbreviated.*

## 📈 Visualizations and What They Show

### 1. Count of Restaurants by City
A horizontal bar chart compares restaurant counts across cities. New Delhi has the largest count among the cities shown, followed by Gurgaon and Noida.

### 2. Restaurants by Online Delivery
A donut chart shows the split between restaurants with and without online delivery. The dashboard displays approximately **25.65% Yes** and **74.29% No**; the remaining small percentage may reflect rounding or a separate category.

### 3. Average Rating by City
An area/line chart compares average ratings across cities. It helps identify differences in the rating values for the cities included in the visualization.

### 4. Rating by Price Range
A horizontal bar chart compares restaurant counts across price/rating categories labelled 1 to 4. It helps users see how records are distributed across the displayed categories.

### 5. Restaurants by Rating Text
A donut chart groups restaurants by rating text, including Average, Good, Very Good, Poor, and Not rated. The largest displayed group is **Average (39.11%)**, followed by **Not rated (22.47%)** and **Good (21.9%)**.

### 6. Total Votes by Rating
An area chart shows how total votes are distributed across rating values. It helps explore which rating ranges receive more customer engagement.

## 💡 Initial Insights

Based on the values and charts visible in the dashboard:

- **New Delhi** has the highest restaurant count among the cities shown.
- Restaurants without online delivery make up the largest share in the delivery chart.
- **Average** is the most common rating-text category displayed.
- The total-votes chart shows higher voting activity around ratings in the upper-middle range, roughly 3.7–4.3.
- The dashboard summarizes a dataset covering **147 cities** and approximately **10K restaurants**.

These are descriptive observations from the dashboard, not proof of why a particular pattern occurs.

## 🛠️ Tools and Technologies

Update this section to match the tools you actually used. A typical setup for this type of project may include:

- **Power BI** — dashboard design and interactive visuals
- **Microsoft Excel / CSV** — data storage and initial inspection
- **Data cleaning and transformation** — preparing fields for analysis

## 🗂️ Repository Structure

A simple repository structure could look like this:

```text
zomato-analysis-dashboard/
├── README.md
├── dashboard.png
├── data/
│   └── zomato_data.csv
└── report/
    └── dashboard-file.pbix
```

Keep only the folders and files that are actually present in your repository. If your dataset or dashboard file cannot be shared, remove those entries or replace them with a note.

## 🚀 How to Explore the Project

1. Open the dashboard screenshot in this repository to review the visual layout.
2. If the Power BI `.pbix` file is included, download it and open it with Power BI Desktop.
3. If the dataset is included, review the data file and the fields used in the visuals.
4. Use the dashboard's available filters and interactions to explore the data, if supported by the published project file.

## 🔍 Possible Future Improvements

- Add filters for city, cuisine, rating, price range, and online delivery.
- Include a map to show restaurant distribution geographically.
- Compare average cost with ratings and customer votes.
- Add clearer labels, units, and definitions for each KPI.
- Document the data source, cleaning steps, and any assumptions.
- Add a section describing the business questions and conclusions drawn from the analysis.

## ⚠️ Notes and Limitations

- KPI values may be rounded or abbreviated in the dashboard.
- The interpretation of the “Rating by price range” chart depends on how the categories were defined in the underlying dataset.
- The dashboard screenshot alone does not establish the data source, date range, or cleaning methodology. Add those details when available.

## 👤 Author

**Your Name**  
BBA — Business Analytics

- GitHub: [Your GitHub Profile](https://github.com/your-username)
- LinkedIn: [Your LinkedIn Profile](https://www.linkedin.com/in/your-profile/)

---

If you found this project useful, feel free to ⭐ the repository or share suggestions for improvement.
