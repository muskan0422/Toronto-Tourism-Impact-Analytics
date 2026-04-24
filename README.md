# Toronto Tourism Impact Analytics: FIFA 2026 Predictive Impact Framework

A predictive analytics framework forecasting tourism's impact on Toronto's infrastructure for the FIFA World Cup 2026.

## Project Overview
This project analyzes how tourism in the City of Toronto impacts four key urban indicators: **Tourist Demand**, **Accommodation Pressure**, **Transportation Strain**, and **Resident Sentiment**. Using a decade of historical data (2014–2024), the project provides a predictive framework to forecast city-wide needs for the **FIFA World Cup 2026**.

## Key Performance Indicators (KPIs) & Forecasts (2025-2026)
* **Tourist Demand**: Predicted **16.15M** base visitors for the 2025-2026 period.
* **Accommodation Pressure**: Average hotel occupancy rate forecasted at **0.71 (71%)**.
* **Transportation Strain**: Projected **753M** total TTC boardings.
* **Resident Sentiment Index (RSI)**: Anticipated **821K** municipal service requests (311) related to city operations.

## "What-If" Scenario: FIFA 2026 Uplift
A central feature of the framework is a stress-test multiplier to simulate the impact of a global influx during match months:
* **International Visitor Arrivals**: +15% increase.
* **Hotel Occupancy Rate**: +10% increase.
* **TTC Ridership**: +5% increase.
* **Resident Complaints (RSI)**: +40% increase.

## Methodology & Predictive Modeling
* **Decision Tree Regressor**: Employed for **Tourist Demand** to identify non-linear seasonal splits and holiday effects.
* **Random Forest Regressor**: Used for **Transportation Strain** to handle complex relationships between ridership, events, and capacity.
* **Linear Regression**: Applied to **Accommodation** and **Resident Sentiment** to model proportional trends between visitor volume and city feedback.

## Technical Stack
* **Modeling**: Python (Pandas, Scikit-learn).
* **Data Preparation**: SQL, Power Query.
* **Visualization**: Power BI.
