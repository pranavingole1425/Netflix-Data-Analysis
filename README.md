# 🎬 Netflix Data Analysis

An Exploratory Data Analysis (EDA) project on Netflix movies dataset to uncover trends, genre preferences, popularity patterns, and more using Python and Plotly.

---

## 📌 Project Overview

This project performs a comprehensive analysis of a Netflix movies dataset containing **9,826 entries** and **9 features**. The goal is to extract meaningful insights about content trends, audience preferences, and movie performance metrics.

---

## 📂 Dataset

**File:** `NetflixData.csv`

| Column | Description |
|---|---|
| `Release_Date` | Date the movie was released |
| `Title` | Name of the movie |
| `Overview` | Brief description of the movie |
| `Popularity` | Popularity score |
| `Vote_Count` | Total number of votes received |
| `Vote_Average` | Average audience rating (0–10) |
| `Original_Language` | Language the movie was originally produced in |
| `Genre` | Genre(s) of the movie |
| `Poster_Url` | URL to the movie poster image |

---

## 🔍 Analysis Performed

- **Data Loading & Preview** – Loading the dataset and inspecting its structure
- **Dataset Structure** – Shape, columns, data types, and null value detection
- **Data Cleaning** – Handling missing values and formatting date columns
- **Genre Analysis** – Most frequent genres and average popularity by genre
- **Language Distribution** – Distribution of movies by original language
- **Release Year Trends** – Number of movies released per year over time
- **Popularity & Voting Analysis** – Distribution of popularity scores and vote counts
- **Rating Analysis** – Vote average distribution and category-wise breakdown

---

## 📊 Key Insights

- **Drama** is the most frequently occurring genre on Netflix.
- **Adventure** movies show the highest average popularity among all genres.
- **Action** and **Science Fiction** also attract high audience engagement.
- Movie releases increased significantly **after the year 2000**, reflecting the rapid growth of the film industry and streaming platforms.
- The popularity distribution is **highly skewed** — most movies are average, and only a few become blockbuster hits.

---

## 🛠️ Tech Stack

- **Python 3**
- **Pandas** – Data manipulation and analysis
- **Plotly Express** – Interactive visualizations
- **Google Colab** – Development environment

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/your-username/netflix-data-analysis.git
cd netflix-data-analysis
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Add the dataset
Place `NetflixData.csv` in the project root directory (or update the path in the notebook).

### 4. Run the notebook
```bash
jupyter notebook Netflix_Data_Analysis.ipynb
```

Or open it directly in [Google Colab](https://colab.research.google.com/).

---

## 📁 Project Structure

```
netflix-data-analysis/
│
├── Netflix_Data_Analysis.ipynb   # Main analysis notebook
├── NetflixData.csv               # Dataset (add manually)
├── requirements.txt              # Python dependencies
└── README.md                     # Project documentation
```

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
