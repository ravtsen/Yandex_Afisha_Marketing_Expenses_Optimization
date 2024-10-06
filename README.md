# Yandex_Afisha_Marketing_Expenses_Optimization
TripleTen Sprint 9 Project - Business Analytics

This project aimed to help optimize marketing expenses in the analytical department at Yandex.Afisha. 

**Below dataset analysed in the project:**<br/>
Visits - Server logs with data on Yandex.Afisha visits from June 2017 through May 2018<br/>
Orders - Dump file with all orders for the period<br/>
Costs - Marketing expenses statistics<br/>

**Project questions:**
- How people use the product?
- When they start to buy?
- How much money each customer brings?
- When they pay off

**Product analitics include several questionss:**
- How many people use it every day, week, and month?
- How many sessions are there per day? (One user might have more than one session.)
- What is the length of each session?
- What's the user retention rate?

**Sales analitics questions:**
- When do people start buying?
- How many orders do they make during a given period of time?
- What is the average purchase size?
- How much money do they bring? (LTV)

**Marketing analitics questions:**
- How much money was spent? Overall, per source and over time.
- How much did customer acquisition from each of the sources cost?
- How worthwhile where the investments? (ROI)

**Description of the data:**

- The visits table (server logs with data on website visits):<br/>
Uid — user's unique identifier<br/>
Device — user's device<br/>
Start Ts — session start date and time<br/>
End Ts — session end date and time<br/>
Source Id — identifier of the ad source the user came from<br/>
All dates in this table are in YYYY-MM-DD format.<br/>

- The orders table (data on orders):<br/>
Uid — unique identifier of the user making an order<br/>
Buy Ts — order date and time<br/>
Revenue — Yandex.Afisha's revenue from the order<br/>

- The costs table (data on marketing expenses):<br/>
source_id — ad source identifier<br/>
dt — date<br/>
costs — expenses on this ad source on this day<br/>
