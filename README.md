# E-Commerce Order Status Dashboard (Excel)

An Excel data analysis project that tracks 200 e-commerce orders from order placement to delivery, cancellation, or return, and turns the data into a dashboard with business insights.

## Business Problem
Without a structured tracking sheet, an operations team cannot easily see which orders are delayed, cancelled, or returned, and management cannot measure delivery performance or sales trends. This project builds one reliable order status sheet and dashboard to answer those questions.

## Objectives
- Design a structured order status sheet covering the full order lifecycle
- Clean, organize, and validate the order data
- Analyze sales, delivery, cancellations, and returns
- Build Pivot Tables and an interactive Excel dashboard
- Turn the analysis into insights and recommendations

## Tools Used
- Microsoft Excel
- Excel formulas
- Data Validation (drop-down lists)
- Pivot Tables and Pivot Charts
- Slicers and Excel Dashboard

## Dataset
200 sample orders with these fields: Order ID, Order Date, Customer ID, Customer Name, City, Product ID, Product Name, Category, Quantity, Unit Price, Total Amount, Payment Method, Payment Status, Order Status, Expected Delivery Date, Actual Delivery Date, Delivery Partner, Return Reason, Cancellation Reason.

Order lifecycle: Placed → Confirmed → Shipped → Out for Delivery → Delivered (or Cancelled / Returned).

## Workbook Structure
| Sheet | Purpose |
| --- | --- |
| Raw_Data | Original order data |
| Cleaned_Data | Cleaned data with added columns: Delivery Delay Days, Delivery Performance, Order Month |
| Pivot sheets (7) | Category sales, city-wise orders, payment analysis, delivery analysis, order status, reasons, monthly revenue |
| Analysis | KPI summary: total orders, revenue, cancellation rate, return rate, on-time delivery % |
| Dashboard | Interactive dashboard with 6 charts and slicers |

## Data Cleaning and Validation
- Standardized inconsistent text entries and handled blank values
- Added Data Validation drop-downs for Order Status, Payment Status, and Payment Method
- Created formula-based columns for delivery delay and delivery performance

## Key Insights
1. **Top category:** Electronics has the highest sales (₹2,54,750); Stationery has the lowest (₹25,970).
2. **Monthly sales:** September is the highest month (₹2,46,990); August is the lowest (₹1,66,000).
3. **Delivery partner:** Blue Dart has the highest average delivery delay (0.9 days).
4. **Cancellations:** 15 orders were cancelled; delivery delay is the main reason.
5. **Returns:** 12 orders were returned; "Product not as expected" is the main reason, and Fashion has the most returns (5).

## Recommendations
- Give more orders to better-performing delivery partners to reduce delays
- Add clear images, size details, and descriptions for Fashion products to reduce returns
- Offer discounts and combo deals on Stationery to increase sales
- Follow up quickly on delayed orders to reduce delivery-related cancellations

## Files in This Repository
- `E_Commerce_Order_Status_Project.xlsx`: the full workbook
- `docs/Project_requirement.docx`: requirement document
- `docs/Project_insights.docx`: insights and recommendations
- `screenshots/`: dashboard screenshots

## Author
**Haseena Banu M**
[LinkedIn](https://linkedin.com/in/haseena-banu96) | skystars2208@gmail.com
