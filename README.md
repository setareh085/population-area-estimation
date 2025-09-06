# 🌍 Population-Area Estimation

This project collects country data from [scrapethissite](https://scrapethissite.com) and stores it in a MySQL database.  
The goal of the project is to estimate the area of a country based on its population.

---

## 📂 Project Structure
population-area-estimation/
├── data/
│ └── countries.sql # Database backup
├── src/
│ └── web.py # Python analysis code
└── README.md # Project documentation


---

## ⚙️ Requirements
- Python 3.10+
- MySQL 8.0+
- Install dependencies:
  ```bash
  pip install -r requirements.txt
  ```
  ## 🗄️ Database Setup
1. Log in to MySQL and create a new database:
   ```bash
   CREATE DATABASE countries;
   ```
2. Import the database dump:
   ```bash
   mysql -u root -p countries < data/countries.sql
   ```
   ## 🚀 Run the Project
To run the Python script:
```bash
python src/web.py
```
The program will ask you for a population value and then try to estimate the country’s area.

## 📝 Notes
The SQL dump is provided in the data/ folder.
Results are approximate and meant for educational purposes.
This repository is published on GitHub as a portfolio project.

## 📄 License

This project is licensed under the MIT License - see the LICENSE
 file for details.
## 👩‍💻 Author
Setareh

Project created for practicing web scraping, database handling, and data analysis.
