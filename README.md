# Data Science and Analysis Project

## Dataset Description: `utd_19`

**Dataset Name:** `utd_19`  
**Size:** 5,070,083 rows × 8 columns 
**City** : Madrid 

---

### Overview
The `utd_19` dataset contains traffic data collected from detector units across multiple cities.  
It records vehicle counts and road occupancy over specific time intervals, allowing detailed analysis of traffic flow patterns.  

---

### Columns
- **day** *(object)* → Day of observation (e.g., Monday, Tuesday, etc.).  
- **interval** *(int64)* → Time interval of data collection (e.g., per 5 minutes).  
- **detid** *(int64)* → Unique traffic detector ID.  
- **flow** *(float64)* → Number of vehicles passing the detector within one interval.  
- **occ** *(float64)* → Occupancy, percentage of time the lane was occupied by vehicles.  
- **error** *(float64)* → Error indicator (mostly NaN, dropped during preprocessing).  
- **city** *(object)* → City where the detector is located.  
- **speed** *(float64)* → Average vehicle speed (mostly NaN, dropped during preprocessing).  

---

### Use Cases
This dataset can be used for:
- Analyzing traffic patterns across days and time intervals.  
- Identifying congestion and high-traffic periods in different cities.  
- Machine learning experiments on traffic flow prediction.  
- Studying the relationship between vehicle flow and occupancy.  

---

## How to Clone this Project


### 1. Clone the repository
```bash
git clone https://github.com/username/utd_19.git
```

### 2. Change Directory
```bash
cd folder
```

### 3. Create Virtual Environment
```bash
python -m venv .venv
```

### 4. Activate Virtual Environment
```bash
.venv\Scripts\Activate
```

### 5. Install Dependencies
```bash
pip install -r requirements.txt
```

---

## Collaborator
1. Darrell Chesta Adabi
2. Anom Nur Maulid

---


⚡ This project is still under active development and will continue until the end of this year.