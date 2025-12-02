Food Habits vs BMI — Data Analysis Project

This project explores how different eating habits and lifestyle factors relate to BMI (Body Mass Index).  

## Project Overview
**Objective:**  
To analyze whether habits like eating breakfast, exercise frequency, fruit/veggie intake, fries consumption, and eating-out frequency show any meaningful relationship with BMI.

**Dataset:**  
Survey-style data with coded responses for food habits and lifestyle patterns.

## Steps Performed
1. **Data Cleaning**
   - Removed non-numeric and unrealistic weights  
   - Cleaned height values  
   - Created BMI column  
   - Selected features that were important
   - Converted ordinal and categorical values to numeric

2. **Feature Selection**
   - breakfast  
   - eating_out  
   - exercise  
   - fries  
   - fruit_day  
   - veggies_day  
   - employment (activity level)

3. **EDA (Exploratory Data Analysis)**
   - BMI distribution  
   - Boxplots (BMI vs habits)  
   - Scatterplots for trends  
   - Correlation heatmap  
   - Group-wise BMI means

4. **Insights Summary**
   - **Exercise:** Strong inverse relationship — less exercise → higher BMI  
   - **Fruit intake:** Lowest fruit intake shows highest BMI; more fruit → lower BMI  
   - **Veggies:** Slight inverse pattern, similar to fruits  
   - **Fries:** More fries → higher BMI  
   - **Eating out:** Not very linear; highest level shows higher BMI  
   - **Breakfast:** No major difference observed  
   - **Employment:** Activity level shows noticeable BMI differences
