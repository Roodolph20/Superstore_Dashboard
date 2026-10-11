Superstore Sales Dashboard (Power BI)
Data: Sample - Superstore (9,994 order lines, US retail, 2014–2017).
Model: star schema built in Power Query - fact table + Product, Customer, Location dimensions
and a DAX date table; composite keys fixed non-unique Product IDs and postal codes.
DAX: YTD, same period last year, YoY % (with VAR), RANKX Top 10, SWITCH(TRUE()) discount bands.
Pages: Overview (KPIs, monthly trend vs. prior year), Products (Top 10, discount vs. margin),
Customer detail (drill-through), Conclusions.
Key insight: order lines with discounts above 20% generated a $135K loss (16% of sales).