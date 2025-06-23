# 🚗 USA Car Sales Analysis - Power BI Dashboard

## 📌 Objective
To analyze car sales performance across the USA and identify key factors influencing:
- Customer behavior  
- Regional demand  
- Brand performance  
- Vehicle features  

> Goal: Support **data-driven sales & inventory decisions**.

---

## 📂 Data Source
- **car sales.csv**

---

## 📊 Key Metrics (DAX Measures)

```DAX
Average_Annual_Income = AVERAGE('Car Sales'[Annual Income])
Average_Car_Price = AVERAGE('Car Sales'[Price])
Total_Sales = SUM('Car Sales'[Total Sales])
Total_Cars_Sold = COUNT('Car Sales'[Model])
Unique_Companies = DISTINCTCOUNT('Car Sales'[Company])
```

---

## 📈 Dashboard Visuals

### ✅ KPI Cards
- Average Annual Income  
- Average Car Price  
- Total Sales  
- Total Cars Sold  
- Unique Companies  

---

### 📊 Bar Chart – Sales by Body Style
- **Axis**: Body Style  
- **Values**: Total Sales  
- **Insight**: SUVs and Hatchbacks are the top-selling styles.

---

### 📊 Stacked Column Chart – Sales by Color
- **Axis**: Color  
- **Values**: Total Sales  
- **Insight**: Pale White is most preferred; Red is least.

---

### 🏭 Bar Chart – Sales by Company
- **Axis**: Company  
- **Values**: Total Sales, Average Price  
- **Insight**: Chevrolet, Ford, and Dodge lead in both sales and pricing.

---

### 🗺️ Map / Column Chart – Sales by Dealer Region
- **Axis**: Dealer Region  
- **Values**: Total Sales  
- **Insight**: Austin and Janesville generate the highest revenues.

---

### 🥧 Donut / Pie Charts – Sales by:
- Gender  
- Engine Type  
- Transmission  

**Insight**:
- Predominantly male buyers  
- Strong preference for automatic cars  
- Nearly equal engine distribution  

---

### 🌳 Tree Map – Sales by Model
- **Group**: Model  
- **Values**: Total Sales  
- **Insight**: LS400, Jetta, and Silhouette dominate the market.

---

## 🔎 Filters / Slicers Used
- Dealer Region  
- Gender  
- Transmission  
- Body Style  

---

## 💡 Business Insights
1. Push loyalty offers & upsells for top-performing models.  
2. Stock high-demand body styles (SUV, Hatchback) and top color (Pale White).  
3. Target gender-specific ads and highlight automatic variants.  
4. Boost presence in top-performing regions (Austin, Janesville).  
5. Collaborate with high-sales companies like Chevrolet & Ford.

---

## ✅ Conclusion
This interactive Power BI dashboard enables **sales, marketing, and inventory teams** to derive meaningful insights, make informed decisions, and strategically grow the USA car sales market.  
Interactive filters allow for deep-dive analysis at multiple levels.
