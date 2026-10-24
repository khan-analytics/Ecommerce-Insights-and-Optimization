# Ecommerce Insights and Optimization

**Business Requirements Document**

| | |
|---|---|
| **Project Type** | Data analytics portfolio project |
| **Tools** | SQL, Python, BI dashboard |
| **Status** | Draft v1.0 |

> Metric definitions will be finalized after checking the source data.

---

## 1. Business Problem

The ecommerce company wants to improve its sales performance and work more efficiently. Its product, order, shipping, and sales data has not been properly analyzed yet. Because of this, the company does not know:

- Which products and categories earn the most revenue
- How much shipping costs affect sales
- How sales change over time

## 2. Business Objectives

1. Check how products and categories perform in sales.
2. Understand how much the company spends on shipping.
3. Study how sales change over time.
4. Find ideas to improve the business, based on evidence.

## 3. Stakeholders

| Stakeholder | What They Need from the Analysis |
|---|---|
| Senior Management | Overall performance and help with big decisions |
| Product and Category Management | Best and weakest products and categories |
| Marketing | Demand patterns and the best timing for campaigns |
| Inventory and Supply Chain | Demand trends to plan stock |
| Logistics and Shipping | Shipping costs and unusual charges |
| Data Analytics | Data quality, clear methods, and repeatable work |

## 4. Scope

### 4.1 In Scope

**A. Product and Category Performance**
- Revenue by category and product
- Units sold by category
- Share of total revenue (revenue contribution)
- Sales concentration (how much revenue comes from a few products)
- Average selling price

**B. Shipping Cost Analysis**
- Total and average shipping cost
- Shipping cost per unit
- Shipping-to-sales ratio
- Link between product weight and shipping cost
- Check for unusual shipping costs

**C. Sales Trend Analysis**
- Monthly revenue
- Monthly order count
- Month-over-month change
- Monthly patterns by category

### 4.2 Out of Scope

- Profit and margin analysis, because reliable cost data is not available
- Customer-level analysis, unless the data supports it

## 5. Key Business Metrics

| Metric | Meaning |
|---|---|
| Revenue | Total value of sales |
| Units Sold | Total number of items sold |
| Unique Orders | Number of different orders |
| Average Order Value (AOV) | Revenue ÷ unique orders |
| Total Shipping Cost | Sum of all shipping charges |
| Shipping-to-Sales Ratio | Shipping cost ÷ revenue |
| Revenue Contribution % | Revenue of a category or product ÷ total revenue |

## 6. Success Criteria

- [ ] A complete data dictionary
- [ ] A documented data quality check
- [ ] Confirmed relationships between datasets
- [ ] SQL and Python analysis that can be repeated
- [ ] Clear visualizations focused on business needs
- [ ] At least five insights backed by evidence
- [ ] At least five practical recommendations
- [ ] A final dashboard and business report
- [ ] Clear notes on assumptions and limitations

## 7. Risks and Limitations

| Risk or Limitation | Possible Impact | Planned Action |
|---|---|---|
| Price and shipping cost definitions are not verified | Metrics may be calculated wrongly | Confirm definitions while inspecting the data |
| Data quality problems | Results may be unreliable | Run and document a data quality check |
| Wrong joins between tables | Revenue and order counts may be inflated | Check join keys and match totals |
| Not enough cost and margin data | Profit cannot be calculated reliably | Keep profit analysis out of scope |
| Short date range or missing data | Seasonal conclusions may be misleading | State the date range and avoid strong seasonal claims |

## 8. Assumptions

- The dataset represents the company's overall sales.
- Revenue and shipping fields can be found and checked in the data.
- All assumptions made during the analysis will be written in the final report.

## 9. Expected Outcome

A repeatable analytics solution that turns ecommerce data into verified findings, useful insights, and measurable recommendations. It will be delivered as a final dashboard and a business report.