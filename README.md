# Supply_Chain_Analysis


# Business Problem
The company operates in multiple regions and manages the complete order delivery process, from shipping to final delivery. However, it is currently facing challenges in maintaining consistent delivery performance. In many cases, the actual shipping time does not match the planned schedule, which leads to delays in delivering orders to customers.

These delays can negatively affect customer satisfaction, as customers expect their orders to arrive on time. When deliveries are late, it can reduce trust in the company and impact customer loyalty. In addition to this, inconsistent delivery timing also creates problems in managing costs, which directly affects the profitability of each order.

Overall, the company needs to identify the reasons behind these delays and improve its logistics and delivery process to ensure timely deliveries, better customer experience, and more stable profitability.

# Goal
The goal is to analyze delivery operations, identify bottlenecks to reduce delays, optimize shipping decisions, and improve overall profitability and effeciency.

# Key Insights

1. Profitability distribution :
   order-level profitability was classified into three tiers based on order profit per order. While 80.7% of orders are profitable, the 18.7% loss-making share represents a meaningful      drag    that is disproportionately concentrated among delayed shipments.

2. Delay Distribution & Profit vs. Delay Days
   The delay distribution shows that 31.0% of all orders arrive exactly 1 day late the single largest cohort. Combined, orders delayed by 1-4 days account for 54.7% of all order volume,    directly mapping to the overall late delivery rate.

  A critical observation is that while mean profit per order remains relatively stable for small delays, it declines as delay duration increases (especially beyond 2–3 days).

  This indicates that:

  Minor delays are operational inefficiencies
  Larger delays directly impact profitability
 
3. Delivery Performance Gap
  The analysis shows that only 45.3% of deliveries are on time, while 54.7% are delayed, highlighting a major gap in delivery performance.
  Additionally, the 90th percentile delay is ~3 days, meaning a significant portion of customers experience noticeable delivery delays.

4. Financial Impact of Delays
   Delayed deliveries contribute to approximately $2.1M in losses, which is a substantial portion of total profit.

   This demonstrates that:

   Delays are not just a logistics issue
   They are a direct financial risk to the business
   
5. Shipping Mode as a Key Bottleneck
   The majority of orders are shipped via Standard Class, which also shows higher delay rates compared to faster shipping modes.

   This suggests:

   Over-reliance on cost-efficient shipping
   Lack of optimization between cost vs speed trade-off
   
6. Customer Segment Impact
   The Consumer segment accounts for the highest order volume and also experiences the highest delay percentage.

   This indicates:

   High-demand segments are placing pressure on logistics
   Operational capacity is not scaling with demand
   
7. Order Status & Process Inefficiency
   Orders in statuses such as Processing and Pending show higher delay rates.
   
   This highlights:
   
   Internal workflow inefficiencies
   Delays are not only shipping-related but also processing-related
   
8. Time-Based Delay Patterns
   Three temporal dimensions were analysed: month of year , day of week, and hour of day. While delay rates are relatively stable across all dimensions (53%-57%), specific peaks
   highlight opportunities for targeted capacity planning.

   • Peak Delay Months: August & September (55.4%) and December (55.2%)
     August and September are the highest months at 55.4%, with December close fulfilment capacity. July represents a notable low-point (~53.75%), confirming seasonal variation is            plannable.

   • Day-of-Week: Variance is Minimal
     Monday (55.5%) and Sunday (55.2%) are the peak days, but the spread across the week is less than 1 percentage point. Day-of-week is not a meaningful lever for operational                intervention.

   • Intra-Day Peaks: Hour 21 (57.1%), Hour 11 (56.7%), Hour 12 (56.0%)
     Late-evening orders (hour 21) have the highest delay rate at 57.1%, likely reflecting processing cutoff windows. Midday peaks suggest bottlenecks during peak-volume hours.

9 Strategic Recommendations

  → Immediately audit first class & second class shippingcapacity
    First Class shipping has a 100% delay rate and second class 79.8%. these modes operate in complete contradiction to their brand promise. Conduct an immediate carrier SLA audit.          Until resolved, consider suspending First Class or repricing to reflect actual performance.

 → Resolve Payment processing Bottlenects
   Orders in PAYMENT_REVIEW (55.3% overall; 80.0% in Central Africa) and PENDING_PAYMENT (55.0%) have significantly elevated delay rates. Introduce automated escalation for stalled         payment reviews exceeding 2 hours.

→ Develop Seasonal Surge Capacity Plans
  August , October (55.4%), and December (55.2%) are peak delay months. Build pre-season capacity plans including temporary logistics partnerships, inventory pre-positioning, and          adjusted delivery promise windows.

→ Investigate High-Delay Deparments in Africa
  Outdoors (61.3%) and Golf(60.8%) in Central Africa show significantly elevated delay rates. Conduct a warehouse-level audit of stock availability, pick-and-pack times, and assignment    for these product categories.

→ Reduce Loss-Making Order Share (18.7%)
  The 18.7% loss-making order share warrants a seperate pricing and discount review. Combine with delay analysis to identify whether discounted orders are disproportionately late,         creating a compounded margin problem.
  
  
