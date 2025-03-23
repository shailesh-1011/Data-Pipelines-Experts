# 📊 Healthcare Trend Analysis

## 🏥 Project Overview
Healthcare is rapidly evolving with advancements in treatments, emerging diseases, and new technologies. This project analyzes healthcare trends by scraping medical research articles and news, providing insights for healthcare professionals, investors, and policymakers. 

## 🚀 Features
- **🔍 Data Scraping**: Extracts healthcare-related data from sources like WebMD, Healthline, Medical News Today, and PubMed.
- **🛠️ Data Cleaning & Processing**: Removes duplicates, formats data, and categorizes it into medical treatments, disease outbreaks, and healthcare innovations.
- **📊 Data Analysis**: Uses SQL to identify key trends in medical advancements and healthcare investments.
- **📈 Data Visualization**: Power BI dashboards for tracking trends, disease outbreaks, and investment patterns.

---

## 📂 Dataset Description
| Column Name       | Description |
|------------------|-------------|
| `age`            | Age of the reviewer |
| `condition`      | Medical condition being reviewed |
| `date`           | Date of the review |
| `drug`           | Name of the drug |
| `drugid`         | Unique ID assigned to the drug |
| `easeofuse`      | Rating for ease of use (1-5) |
| `effectiveness`  | Effectiveness rating (1-5) |
| `reviews`        | Text review provided by the user |
| `satisfaction`   | Overall satisfaction rating (1-5) |
| `sex`            | Gender of the reviewer |
| `sides`          | Side effects mentioned |
| `usefulcount`    | Number of people who found the review useful |

---

## ⚙️ Installation & Setup
1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/healthcare-trend-analysis.git
   cd healthcare-trend-analysis
   ```
2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```
3. **Run Data Processing Script**
   ```bash
   python cleaning.py
   ```
4. **Open Power BI for Visualization**
   - Load the processed dataset (`cleaned_data.csv`) into Power BI
   - Open the `.pbix` file to explore dashboards

---

## 🔮 Future Enhancements
- **🔄 Automate Data Scraping** using scheduled jobs.
- **📡 Integrate Real-Time Data Feeds** from health organizations.
- **🧠 Machine Learning Analysis** for predicting future healthcare trends.

---

## 📜 License
This project is licensed under the MIT License.

## 🙌 Contribution
Contributions are welcome! Feel free to open an issue or submit a pull request.

---

## 📝 Authors
- **Your Name** - [GitHub Profile]((https://github.com/shailesh-1011))
