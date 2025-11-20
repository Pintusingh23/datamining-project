📱 Smartphone Usage and App Trends
📊 Google Play Store Data Analysis (Phase 1 & Phase 2)

Smartphones have transformed how people communicate, work, learn, and entertain themselves. With millions of apps available on app stores, analyzing their structure and market patterns reveals meaningful insights about user preferences and the digital ecosystem.

This project explores the Google Play Store Apps Dataset to understand trends across categories, downloads, monetization strategies, and metadata patterns. Through systematic preprocessing and early exploratory analysis, we identify what shapes app visibility and potential popularity in the marketplace.

👩‍💻 Team Members

Pintu Singh (Team Lead)

Samyak Mittal

Suyash Parmar

📂 Project Structure
googleplaystore-analysis/
│
├── data/
│   ├── googleplaystore.csv
│   └── cleaned_googleplaystore.csv
│
├── notebooks/
│   ├── phase1_analysis.ipynb
│   ├── descriptive_analysis.ipynb
│   └── eda_plan.ipynb
│
├── reports/
│   └── data_summary.txt
│
├── README.md
├── requirements.txt
└── .gitignore

🎯 Project Overview

This project focuses on the Phase 1 and Phase 2 components of a larger data mining workflow.
The goal is to understand the structure of the dataset, perform data cleaning, and prepare it for deeper analysis in later phases.

We work with:

Google Play Store App Metadata
(App Name, Category, Rating, Reviews, Size, Installs, Price, Content Rating, Genres, etc.)

Our emphasis is on:

Data Understanding

Cleaning & Preprocessing

Early Insights through Descriptive Analysis

🧠 Phase 1 – Initial Setup & Exploratory Data Analysis
✔ Repository Setup

Created GitHub repository

Structured directories (data, notebooks, reports)

Assigned team roles

✔ Dataset Loading & Inspection

Loaded raw CSV file into Pandas

Checked dataset shape and metadata

Used info(), describe(), and statistical summaries

✔ Identified Data Characteristics

Found mix of numerical and categorical variables

Observed missing values and inconsistent formats

Checked for duplicate records

Saved initial observations in data_summary.txt

🔧 Phase 2 – Data Cleaning & Preprocessing

In Phase 2, the focus was on transforming raw data into clean and usable form.

✔ Handling Missing Values

Identified null entries in fields like Current Ver and Android Ver

Removed or handled missing values appropriately

✔ Cleaning Numerical Fields

Converted Installs (e.g., "1,000+" → 1000)

Cleaned Price (e.g., "$2.99" → 2.99)

Ensured fields like Reviews, Installs, and Price are numeric

✔ Standardizing Categorical Fields

Encoded features such as:

Category

Type

Content Rating

Genres

✔ Removing Unnecessary Columns

Columns like:

Size

Last Updated

Current Ver

Android Ver

were dropped due to inconsistent formatting or low analytical value in early stages.

✔ Saving Cleaned Dataset

Produced cleaned_googleplaystore.csv

Dataset is now ready for modeling & deeper EDA in future phases

📊 Key Early Observations (Phase 1–2)
⭐ 1. Most apps have high ratings

Average rating ≈ 4.18, showing strong user satisfaction.

⭐ 2. Certain categories dominate

FAMILY, GAME, and TOOLS categories appear most frequently.

⭐ 3. Install counts vary drastically

From 10+ installs to 1 billion+, showing massive diversity in app reach.

⭐ 4. Reviews and installs are strongly linked

Apps with higher installs typically receive more reviews.

⭐ 5. Many features have inconsistent formats

Price, Installs, and Size required intensive cleaning before use.

These insights help guide deeper analysis and modeling in later phases.

🌍 Societal Impact

Even at Phase 1–2, our project contributes positively by:

✔ Helping users

Understand which categories are popular and well-rated.

✔ Helping developers

Identify competitive app categories and common metadata patterns.

✔ Contributing to digital literacy

Showing how app data reflects user behavior and market trends.

✔ Providing a foundation for further analysis

Clean, organized datasets enable advanced exploration, predictive modeling, and sentiment analysis in future phases.

⚙️ Tools & Libraries Used

Python 3.x

Pandas, NumPy

Matplotlib, Seaborn

Jupyter Notebook

🏁 Final Conclusion (Phase 1–2)

We successfully cleaned, understood, and prepared the Google Play Store dataset for deeper analysis. Through data inspection, preprocessing, and descriptive observations, we established a solid foundation for more advanced modeling, trend analysis, and app behavior understanding in future phases.
