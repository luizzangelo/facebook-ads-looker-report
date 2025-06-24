# Interactive Facebook Ads Report with Looker Studio
---

## 📖 Context & Objective

At LA Mídias, we leverage Looker Studio to convert raw Facebook Ads data into actionable insights. This report covers the period from **Jan 1, 2025** to **Jun 24, 2025**, enabling us to:

* Evaluate creative effectiveness and CTAs.
* Understand the audience journey through a custom engagement funnel.
* Identify the age groups with the highest return on ad spend.
* Track follower growth to validate ad performance.

This README tells the data story and showcases my skills in designing, configuring, and analyzing interactive dashboards.

---

## 🧩 Key Metrics Overview

| Metric                       | Value     | Note                                                        |
| ---------------------------- | --------- | ----------------------------------------------------------- |
| **Impressions**              | 1,286,817 | Total ad exposures                                          |
| **Reach**                    | 1,176,757 | Unique users reached                                        |
| **All Clicks**               | 35,715    | Total engagements                                           |
| **Link Clicks**              | 34,085    | Traffic-driving clicks (quality and bounce rate to analyze) |
| **CTR (Overall)**            | 2.78%     | Global click-through efficiency                             |
| **CTR (Link)**               | 2.65%     | Click-through rate on primary CTA                           |
| **Cost per Click (CPC)**     | R\$ 0.15  | Average cost per click                                      |
| **CPM**                      | R\$ 3.93  | Cost per thousand impressions                               |
| **Cost per Follower**        | R\$ 0.33  | Cost to acquire a new follower                              |
| **Net Followers (6 months)** | +2,097    | Validates conversion funnel                                 |

---

## 🔍 Engagement Funnel

We built a custom funnel in Looker Studio to track each stage:

1. **Attract**: Impressions (1,286,817)
2. **Convert**: Reach (1,176,757)
3. **Engage**: All Clicks (35,715)
4. **Drive Traffic**: Link Clicks (34,085)
5. **Acquire**: Messages Sent (845)


![Engagement Funnel](https://github.com/luizzangelo/facebook-ads-looker-report/blob/main/engagement-funnel.png?raw=true)


> **Insight:** Drop‑off is minimal between “Convert” and “Engage,” but there’s room to improve conversion from “Drive Traffic” to “Acquire.” Testing CTA and creative variations at the final stage could boost results.

---

## 👥 Budget Allocation by Age Group

We compared spend vs. clicks by age group to optimize budget distribution:

| Age Group | Spend        | Clicks | CPC      | % of Total Clicks |
| --------- | ------------ | ------ | -------- | ----------------- |
| 18–24     | R\$ 209.04   | 1,979  | R\$ 0.11 | 5.5%              |
| 25–34     | R\$ 2,363.37 | 15,298 | R\$ 0.15 | 42.8%             |
| 35–44     | R\$ 1,755.14 | 12,550 | R\$ 0.14 | 35.1%             |
| 45–54     | R\$ 500.21   | 3,805  | R\$ 0.13 | 10.7%             |
| 55–64     | R\$ 162.88   | 1,484  | R\$ 0.11 | 4.2%              |
| 65+       | R\$ 68.09    | 599    | R\$ 0.11 | 1.7%              |


> ![Spend vs. Clicks by Age](https://github.com/luizzangelo/facebook-ads-looker-report/blob/main/spend-clicks-age.png?raw=true)


> **Recommendation:** The **25–34** segment drives the highest volume. Consider shifting 10% of the budget from the **35–44** and **45–54** cohorts (where CPC remains competitive) to **25–34** to maximize click volume.

---

## 📈 Daily Follower Growth

We monitor daily Instagram follower increases to assess ad appeal:


> ![Daily Follower Growth](https://github.com/luizzangelo/facebook-ads-looker-report/blob/main/daily-followers.png?raw=true)

* From June 10–18: average of **160 followers/day**, well above the target of 80.
* June 22: spike to **520 new followers**, indicating a top-performing creative.

> **Action:** Identify the highest-performing ad elements (creative, copy, targeting) and replicate them in upcoming campaigns to sustain growth.

---

## 🏁 Conclusion & Next Steps

1. **Optimize final CTAs:** A/B test creative variations to reduce drop-off.
2. **Reallocate budget** towards the 25–34 segment for higher volume.
3. **Replicate the spike creative** to maintain follower growth.
4. **Expand analysis:** Integrate off-Facebook conversion data (e.g., sales) to complete the ROI loop.

This project highlights my expertise in:

* Building interactive dashboards in Looker Studio.
* Data storytelling: turning metrics into strategic decisions.
* Paid media planning driven by data insights.

> Enjoyed this report? Check out the full [dashboard on Looker Studio]([https://lookerstudio.google.com/reporting/YOUR_REPORT_ID](https://lookerstudio.google.com/reporting/0a2eb02a-5d76-4d9d-8a86-627618107799)) and let’s collaborate!

---

**Author:** Luiz Angelo  |  **LinkedIn:** [la-midias](https://www.linkedin.com/in/luiz-analista-de-dados)

> "Data-driven decisions start with clear insights."
