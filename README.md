# Time_Series_Prediction
Use Python to deal with Time Series.


## 1. Input
### (1) Determine Data Units
- **primary key**: `reg_day`, `city`
- **driver_cnt**: `reg`, `vip`, `N_rate`
- **others**: `ai_type`, `city_score`, `fix_rate`

### (2) Construct Data Features
- **N_rate_p**

## 2. Model
### (1) Select Prediction Model
- **Train Model**
- **Predict**

## 3. Output
### (1) Determine Output Format
- **Prediction Results**
- **Error**

### (2) Result Presentation
- **Retrieve Data**: `columns`, `rows`
- **Recompute**
- **Mapping**: `columns`, `content`

---

## Issues:
1. Predict for any month **m**, but for specific months in the next year, there is no data.
2. **Modularize the Model**
   - **Training** -> `DataFrame`
   - **Prediction** -> `list of number` (pd.Series)

