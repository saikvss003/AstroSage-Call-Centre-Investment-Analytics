# 📈 AstroSage Call Centre Dashboard - EXCEL

Allocating a ₹1 Crore investment across operational efficiency, customer satisfaction, and profitability - using Excel PivotTables, formulas, and an interactive dashboard.

Built as part of the Data Analytics, Engineering & Science program at Newton School.

---

# 🧩 Problem Statement :-

> AstroSage has received a ₹1 crore investment to transform its call centre operations. Should the money go toward hiring more agents, improving training programs, or upgrading call centre technology - and how should it be split?

- Answers 24 business questions (14 objective + 10 subjective)
- Covers call volume trends, operational cost, revenue mix, customer satisfaction, guru (agent) performance, and workload balance
- Translates findings into a justified ₹1 crore allocation across 5 strategic initiatives

---

# 🗄️ Dataset :-

- 28,027 consultation records (Dec 1, 2023 - Jan 3, 2024), cleaned down from 35 to 29 attributes
- Removed system/ID columns (`_id`, `user`, `guru`, `isWhiteListUser`, `queue`, `statementEntryId`) and duplicate records

| Metric | Value |
|---|---|
| Consultation records | 28,027 |
| Voice calls tracked (unique CallSid) | 8,365 |
| Gurus (astrologers) | 131 |
| Unique callers | 3,628 |
| Days of operations data | 34 |
| Categorical columns | 15 |
| Attributes after cleaning | 29 |

---

# 🛠️ Tools & Techniques :-

**Tool**
- Google Spreadsheet

**Techniques**
- PivotTables & PivotCharts
- `COUNTIF` / `SUMIF` / `COUNTA` / `AVERAGE` / `COLUMNS` / `CORREL`
- Data cleaning & deduplication
- Slicers (Date, Website, Consultation Type)
- Interactive KPI dashboard

---

# 🔍 Analysis Covered :-

- **Data Cleaning** - removed system columns and duplicates, standardized timestamps, validated statuses
- **Call Volume Analysis** - daily and monthly call trends, day-by-day change, peak vs. off-peak hours
- **Operational Cost** - monthly astrologer earnings and total operational cost
- **Revenue Analysis** - net revenue by consultation type (Call, Chat, Public Live, Complementary)
- **Customer Satisfaction** - average rating overall, by month, and by guru; correlation between call duration and rating
- **Repeat Caller & Loyalty Analysis** - repeat caller count and their share of total calls
- **Guru (Agent) Performance** - average rating and call duration per guru, workload balance
- **Call & Chat Status Analysis** - completed, failed, incomplete, busy, no-answer outcomes by channel
- **Interactive Dashboard** - KPI cards, charts, and slicers for dynamic exploration

---

# 💡 Key Insights :-

| # | Insight |
|---|---|
| 1 | **Calls drive the business** - 78.7% of net revenue (₹1,68,442 of ₹2,13,987) comes from voice calls; chat contributes 21.3%, complementary and public live are near 0% |
| 2 | **Customer satisfaction is critically low** - average rating is 2.93/10, and it slipped further from 2.95 (Dec) to 2.68 (Jan); ~49% of all consultations are rated 2 or below |
| 3 | **Call duration and satisfaction are positively correlated (+0.481)** - longer, unhurried consultations genuinely satisfy customers more; rushed calls hurt ratings |
| 4 | **Loyalty exists despite low satisfaction** - 56.6% of all calls come from repeat callers (1,275 of 3,628 unique callers, ~35.1%), each phoning in nearly 5 times on average |
| 5 | **Chat is the broken growth channel** - 71% of chats end in failure or incomplete status, versus ~35% of calls hitting no-answer/busy; this is a fixable technology problem, not a demand problem |
| 6 | **Guru performance is highly uneven** - top gurus (Tarot Mystical, Astro Pujaa Rai) average 7.5/10, while several gurus sit near 0, creating both a training gap and an over-reliance risk on top performers |

---

# 📈 ₹1 Crore Investment Allocation :-

| Initiative | Allocation | Rationale |
|---|---|---|
| **Call Operations Optimisation** | ₹45 L | AI-based call routing, skill-based allocation, and workforce tools to protect the 78.7% revenue channel |
| **Chat Experience Enhancement** | ₹25 L | AI chatbots, structured scripts, faster SLAs, and agent QA to fix the 71% chat failure rate |
| **Call Technology Upgrade** | ₹15 L | CRM integration, speech/sentiment analytics, and cloud call-centre infrastructure |
| **Customer Satisfaction Programs** | ₹15 L | Loyalty programs, repeat-user incentives, and personalised recommendations to lift ratings from 2.9 toward 5+ |
| **Complementary Services** | ₹5 L | Promotional live sessions and onboarding consultations to build trust and convert free users to paid |

---

# 📊 Dashboard :-

An interactive Excel dashboard with KPI cards (Astrologer Earnings, No of Gurus, net revenue across consultations, average calls / Day) and Pivot 
Chart visuals for call volume trends, revenue mix, satisfaction distribution, and top/bottom guru performance - filterable via Date, Website, and Consultation Type slicers.

---

## 📎 Project Files :-

| File | Description |
|---|---|
| [Astrosage Analysis Google Sheet](https://docs.google.com/spreadsheets/d/1yH5LyU-wibVko9ggRr-_bcIgRvQDphZXT1r3dkAWcgs/edit?gid=726910250#gid=726910250) | Cleaned data, 17 analysis sheets (PivotTables/charts per question), and the interactive dashboard |
| [spreadsheet project presentation](https://github.com/saikvss003/AstroSage-Call-Centre-Investment-Analytics/blob/main/183.pptx) | Full findings deck with charts and the ₹1 crore allocation plan |
| [spreadsheet project doc](https://github.com/saikvss003/AstroSage-Call-Centre-Investment-Analytics/blob/main/183.docx) | Full written analysis - question, approach, insights, and recommendations for all 24 questions |

# 🙌 Reflection :-

This project moved beyond single-formula answers into full PivotTable-driven analysis, correlation testing, and workload/performance diagnostics - then tied every finding back to a justified ₹1 crore allocation across five initiatives.
