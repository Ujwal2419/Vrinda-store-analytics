# Vrinda Store Analytics 📊

A comprehensive e-commerce sales data analysis project for Vrinda Store, featuring multi-channel sales tracking, customer demographics analysis, and business intelligence insights from 2022 operations.

## 🎯 Project Overview

This repository contains detailed sales and order analytics for Vrinda Store, an Indian e-commerce business operating across multiple platforms including Amazon, Flipkart, Myntra, Meesho, and others. The analysis covers over 31,000+ orders with complete customer demographics, product information, and fulfillment data.

## 📈 Key Insights

### Business Performance
- **Total Revenue**: ₹21.17M+ across all channels
- **Order Volume**: 31,047+ orders processed
- **Monthly Average**: ~₹1.8M revenue with ~2,650 orders/month
- **Delivery Success Rate**: 92% (28,641 delivered orders)

### Customer Demographics
- **Gender Split**: 
  - Women: 64% of revenue (₹13.56M)
  - Men: 36% of revenue (₹7.61M)
- **Age Groups**: Adult, Senior, and Teenager segments analyzed

### Geographic Reach
**Top 5 States by Revenue:**
1. Maharashtra - ₹2.99M
2. Karnataka - ₹2.65M
3. Uttar Pradesh - ₹2.10M
4. Telangana - ₹1.71M
5. Tamil Nadu - ₹1.68M

### Sales Channels
- **Amazon**: 35.5% of orders
- **Myntra**: 23.4% of orders
- **Flipkart**: 21.6% of orders
- **Others**: Ajio, Meesho, Nalli, and more

## 📁 Dataset Structure

### Main Data Sheet: `Vrinda Store`
Contains 31,047+ rows with the following columns:

| Column | Description |
|--------|-------------|
| Index | Unique row identifier |
| Order ID | Unique order reference |
| Cust ID | Customer identifier |
| Gender | Customer gender (Men/Women) |
| Age | Customer age |
| Age_Group | Categorized age groups |
| Date | Order date (2022) |
| Month | Month extracted from date |
| Status | Order status (Delivered/Cancelled/Returned/Refunded) |
| Channel | Sales platform (Amazon/Flipkart/Myntra/etc.) |
| SKU | Stock keeping unit identifier |
| Category | Product category (kurta, Set, Western Dress) |
| Size | Product size (S/M/L/XL/XXL) |
| Qty | Quantity ordered |
| Currency | INR (Indian Rupees) |
| Amount | Order value |
| ship-city | Shipping city |
| ship-state | Shipping state |
| ship-postal-code | Postal code |
| ship-country | Country (IN - India) |
| B2B | Business-to-Business flag |

### Analysis Sheets

1. **Sheet1**: Monthly sales trends (Amount & Order Count)
2. **Sheet4**: Gender-wise revenue distribution
3. **Order Status**: Order fulfillment analysis
4. **Sheet6**: State-wise revenue breakdown
5. **Age and Gender**: Customer segmentation matrix
6. **Sheet8**: Channel performance metrics
7. **Report**: Executive summary dashboard

## 🛠️ Technologies & Tools

- **Data Format**: Microsoft Excel (.xlsx)
- **Analysis Tools**: Excel Pivot Tables, Formulas
- **Visualization**: Charts and dashboards (embedded in Report sheet)

## 📊 Analysis Components

### 1. Time Series Analysis
- Monthly revenue and order trends
- Seasonal patterns identification
- Growth rate calculations

### 2. Customer Segmentation
- Gender-based purchasing patterns
- Age group analysis
- Geographic distribution

### 3. Channel Performance
- Multi-channel sales comparison
- Channel-wise conversion tracking
- Platform efficiency metrics

### 4. Order Fulfillment
- Delivery success rates
- Return and refund analysis
- Cancellation patterns

**Explore Pre-built Analysis**
   - Navigate through different sheets for specific insights
   - Check the 'Report' sheet for executive summary
   - Use filters and slicers for interactive exploration

## 📌 Business Questions Answered

- ✅ Which gender contributes more to revenue?
- ✅ What are the top-performing states?
- ✅ Which sales channel is most effective?
- ✅ What is the order fulfillment rate?
- ✅ How do different age groups shop?
- ✅ What are monthly sales trends?
- ✅ Which product categories are most popular?

## 🎨 Potential Enhancements

- [ ] Add year-over-year comparison analysis
- [ ] Implement customer lifetime value (CLV) calculations
- [ ] Create automated dashboards with Power BI/Tableau
- [ ] Build predictive models for demand forecasting
- [ ] Analyze product return patterns by category
- [ ] Develop customer retention metrics




