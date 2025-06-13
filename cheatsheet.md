### **Power BI Dashboard Cheat Sheet: NYC Airbnb Analysis**  

#### **📌 Data Overview**  
- **Dataset:** NYC Airbnb listings (16 columns)  
  - Key fields: `neighborhood_group`, `room_type`, `price`, `reviews_per_month`, `last_review`, `host_id`, `host_name`.  
- **Source:** CSV file (link in video description).  

---

### **🚀 Step-by-Step Dashboard Creation**  

#### **1️⃣ Set Up the Canvas**  
- **Background:**  
  - `Canvas background` → Hex: `#FF5A60`, Transparency: `0%`.  
- **Filters (Slicers):**  
  - Add **two slicers**:  
    1. `neighborhood_group` (dropdown)  
    2. `room_type` (checkbox: "Entire home", "Private room", "Shared room").  
  - **Formatting:**  
    - Background: White  
    - Border: White, 20% transparency.  

#### **2️⃣ Create Cards (KPIs)**  
- **Cards to Add:**  
  1. **Avg. reviews/month** → `reviews_per_month` (Average).  
  2. **Total reviews** → `number_of_reviews` (Sum).  
  3. **# Neighborhoods** → `neighbourhood` (Count Distinct).  
  4. **Total hosts** → `host_id` (Count Distinct).  
- **Formatting:**  
  - Text: White  
  - Background: Match dashboard theme.  

#### **3️⃣ Vertical Bar Charts**  
1. **Total Last Reviews by Year**  
   - X-axis: `last_review` (Year).  
   - Y-axis: `last_review` (Count).  
   - Title: "Total Last Reviews by Year".  

2. **Total Reviews by Month**  
   - X-axis: `last_review` (Month).  
   - Y-axis: `reviews_per_month` (Sum).  
   - Title: "Total Reviews by Month".  


