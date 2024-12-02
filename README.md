# Healthcare Data Dashboard Project

## **Setup Instructions**

### **Prerequisites**
- Python 3.8 or higher
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`, `streamlit`

### **Steps to Reproduce**

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-repo/healthcare-dashboard.git
   cd healthcare-dashboard
   ```

2. **Install Required Libraries**
   Run the following command to install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. **Prepare the Dataset**
   - Download the Synthea dataset.
   - Place the following CSV files into the `data/` directory:
     - `patients.csv`
     - `conditions.csv`
     - `medications.csv`
     - `observations.csv`
     - `procedures.csv`

4. **Run the Dashboard**
   Launch the interactive dashboard using:
   ```bash
   streamlit run dashboard.py
   ```

5. **Access the Dashboard**
   - Once the dashboard is running, it will open automatically in your default browser.
   - If it doesn't, navigate to the displayed local URL (e.g., `http://localhost:8501`).

---

## **Directory Structure**
```
healthcare-dashboard/
├── data/
│   ├── patients.csv
│   ├── conditions.csv
│   ├── medications.csv
│   ├── observations.csv
│   ├── procedures.csv
├── dashboard.py          # Python script for generating the dashboard
├── requirements.txt      # List of required Python libraries
├── README.md             # Project documentation
```

---