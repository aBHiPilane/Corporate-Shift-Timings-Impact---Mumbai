🧠 Productivity Analytics — Modeling Productivity as a System
This project is a productivity analytics case study that challenges the traditional belief that more working hours = more productivity.
Instead of focusing only on hours worked or task completion, this dashboard models productivity as a system influenced by:
Time loss
Commute stress
Energy levels
Weekend recovery cycles

It answers a key question:
Why do longer working hours not always result in higher productivity?

🎯 Problem Statement
Most productivity dashboards measure:
Total working hours
Output volume
Task completion

But real-world observation shows:
Commute stress drains energy before work even begins - Longer hours often lead to higher fatigue, not higher output - Weekends restore energy — but this effect is rarely measured.
This project quantifies these hidden drivers of productivity and presents them in an executive-friendly dashboard.

🏗️ Project Evolution
Phase 1 — Data Modeling
Designed a Star Schema
Separated:
fact_time_management → operational data
fact_time_insights → analytical metrics
Modeled:
Shifts
Commute modes
Stress levels
Energy carryover
Weekend indicators

Phase 2 — Analytics & Storytelling
Removed redundant visuals
Designed each chart to answer a clear “why” or “what decision”
Focused on insights, not decoration

🧩 Dashboard Structure
The dashboard is divided into four logical sections, each explaining a layer of the productivity system.

🟦 1. Overview — Executive KPIs
Purpose: 5-second snapshot of productivity health
KPIs
Average Time Lost per Day
Average Net Productive Hours
Average Energy Carryover
Average Time ROI
Productivity depends more on efficiency and recovery than increasing work hours.

🟦 2. Shift Comparison — Early vs Standard Shift
Purpose: Data-driven shift evaluation
Findings
Early Shift (7–4) → Lower time loss, better energy sustainability
Standard Shift (9–6) → Slightly higher output, higher fatigue
The best shift is not universal — it depends on balancing output with human sustainability.

🟦 3. Commute Impact — Root Cause Analysis
Purpose: Identify where time and energy are actually lost
Findings
Public/crowded transport → higher stress and time loss
Walking/low-friction commute → better energy preservation
Commute design is a productivity lever, not just a logistics issue.

🟦 4. Weekend Effect — Recovery Modeling
Purpose: Measure the impact of rest on productivity
Findings
Energy declines steadily during weekdays
Weekends restore nearly one full energy unit
Recovery is not idle time — it is an active input to productivity.

🧠 Key Design Principles
Minimal but meaningful DAX measures - Clean Star Schema for flexible slicing, No decorative visuals — every chart answers a question, Human-centric metrics intentionally included.

🏁 Final Conclusion
This project shows that:
Productivity is a system, not a single KPI
Performance is influenced by:
Time loss
Commute stress
Energy management
Recovery cycles

The dashboard supports decisions such as:
Flexible / hybrid shift policies
Commute-aware scheduling
Protecting recovery time for sustained performance

🛠️ Tools & Technologies
SQL — Data modeling & preprocessing
Power BI — DAX, visuals, storytelling
Star Schema Design

Analytical & product-oriented thinking
