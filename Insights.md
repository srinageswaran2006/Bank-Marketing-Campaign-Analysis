# Bank Marketing Campaign Analysis — Business Insights

## 1. Executive Summary

The bank marketing campaign achieved an overall subscription rate of **47.4%**, with **5,289 out of 11,162 customers** subscribing to the offered product.

Campaign performance varied significantly across customer segments, previous marketing history, and current campaign behaviour. Previous campaign success, call duration, loan status, customer age/job segments, and contact frequency showed notable associations with subscription.

The analysis suggests that campaign efficiency could be improved by prioritizing high-response customer segments, using previous campaign outcomes for targeting, focusing on quality customer conversations, and reviewing periods and groups with weaker performance.

---

# 2. Overall Campaign Performance

| Metric | Value |
|---|---:|
| Total Customers | 11,162 |
| Subscribed Customers | 5,289 |
| Non-Subscribed Customers | 5,873 |
| Subscription Rate | 47.4% |
| Average Call Duration | 372 sec |

### Key Finding

The campaign achieved a **47.4% subscription rate**, with results relatively balanced between subscribers and non-subscribers.

### Business Implication

There is significant scope to improve campaign efficiency through better customer targeting and contact strategies.

---

# 3. Customer Profile Insights

## 3.1 Job

- **Students** had the highest subscription rate at **74.7%**.
- **Retired customers** followed at **66.3%**.
- **Blue-collar customers** had the lowest rate at **36.4%**.

### Business Implication

Customer response differs considerably by occupation. Higher-performing segments could be prioritized while weaker segments may require different messaging or targeting strategies.

---

## 3.2 Age

- Customers aged **60+** had the highest subscription rate at **82.2%**.
- Customers aged **40–49** had the lowest rate at **40.8%**.
- The **30–39** group was the largest segment with **4,188 customers**.

### Business Implication

Age can help identify customer groups with stronger campaign response, particularly older customers and younger customers.

---

## 3.3 Marital Status

- **Single customers:** 54.4%
- **Divorced customers:** 48.1%
- **Married customers:** 43.4%

Single customers showed the strongest subscription rate.

---

## 3.4 Education

- **Tertiary:** 54.1%
- **Unknown:** 50.7%
- **Secondary:** 44.7%
- **Primary:** 39.4%

Tertiary-educated customers showed the highest subscription rate.

---

## 3.5 Loan Status

Customers without loans generally showed stronger campaign response:

| Customer Group | Subscription Rate |
|---|---:|
| No Housing Loan | 57.0% |
| Housing Loan | 36.6% |
| No Personal Loan | 49.5% |
| Personal Loan | 33.2% |

### Business Implication

Loan status may be useful as a segmentation variable when designing campaign targeting and messaging.

---

# 4. Previous Marketing History

## 4.1 Previous Campaign Outcome

| Previous Outcome | Subscription Rate |
|---|---:|
| Success | 91.3% |
| Other | 57.2% |
| Failure | 50.3% |
| Unknown | 40.7% |

Customers with a previous successful campaign outcome showed a **91.3% subscription rate**, substantially higher than the overall campaign rate.

### Business Implication

Previous campaign outcomes are a strong signal for identifying customers who may be more receptive to future offers.

---

## 4.2 Previous Contact History

Customers with previous contact history generally had higher subscription rates than customers who had **no previous contacts**.

- No previous contacts: **40.7%**
- Previous contacts: generally higher response rates

The subscription rate generally increased through around **5 previous contacts**, although higher contact counts had very small sample sizes.

### Business Implication

Existing customer engagement history can be incorporated into campaign targeting rather than treating all customers equally.

---

## 4.3 Days Since Previous Contact

Customers previously contacted **31–90 days earlier** had the highest subscription rate at **81.7%**.

Customers who had never been contacted previously had the lowest rate at **40.7%**.

### Business Implication

The timing of previous customer interactions may be useful when planning follow-up campaigns.

---

# 5. Current Campaign Behaviour

## 5.1 Number of Campaign Contacts

Customers contacted fewer times generally showed better subscription rates.

- 1 contact: **53.4%**
- 2 contacts: **46.3%**
- 5 contacts: **36.8%**
- 10 contacts: **26.9%**

Higher contact counts had very small sample sizes and showed fluctuations.

### Business Implication

Repeatedly contacting customers does not necessarily improve conversion. Campaigns should focus on **targeting quality rather than simply increasing contact frequency**.

> Note: This is an association, not proof that repeated calls cause lower conversion.

---

## 5.2 Call Duration

Call duration showed one of the strongest differences between subscribers and non-subscribers.

| Outcome | Median Call Duration |
|---|---:|
| Subscribed | 426 sec |
| Not Subscribed | 163 sec |

Subscribers had substantially longer calls than non-subscribers.

### Business Implication

The finding suggests that **quality and depth of customer conversations** may be more important than simply increasing the number of calls.

> Note: Longer calls are associated with subscription; this does not prove that longer calls directly cause conversion.

---

## 5.3 Contact Method

| Contact Method | Subscription Rate |
|---|---:|
| Cellular | 54.3% |
| Telephone | 50.4% |
| Unknown | 22.6% |

Cellular was the strongest known contact method and also represented the largest customer group.

### Business Implication

The large performance gap for customers with an unknown contact method should be investigated, particularly from a data-quality and campaign-tracking perspective.

---

# 6. Campaign Timing

Subscription rates varied considerably by month.

### Strongest Months

- December: **90.9%**
- March: **89.9%**
- September: **84.3%**
- October: **82.4%**

### Weakest Months

- May: **32.8%**
- January: **41.3%**
- July: **41.4%**
- November: **42.7%**

May was also the largest customer group, with **2,824 customers**.

### Business Implication

The weaker performance during May–August should be investigated further to understand whether campaign timing, customer mix, messaging, or other factors contributed to the lower response.

Some high-performing months had relatively small customer volumes, so their rates should be interpreted carefully.

---

# 7. Deeper Customer Segmentation

## 7.1 Age + Job

Strong-performing segments included:

| Segment | Subscription Rate |
|---|---:|
| 60+ Retired | 81.3% |
| Under 30 Students | 77.0% |
| Under 30 Management | 60.6% |

Lower-performing segments included:

| Segment | Subscription Rate |
|---|---:|
| 50–59 Blue-collar | 33.3% |
| 30–39 Blue-collar | 34.2% |
| 40–49 Blue-collar | 34.3% |

### Business Implication

Combining customer characteristics provides more useful targeting information than looking at individual demographic variables alone.

---

## 7.2 Education + Housing

The strongest segment was:

**Tertiary education + No housing loan → 61.6%**

The weakest was:

**Primary education + Housing loan → 30.3%**

Across every education level, customers without housing loans had higher subscription rates.

---

## 7.3 Marital Status + Personal Loan

The strongest segment was:

**Single + No personal loan → 55.6%**

The weakest was:

**Married + Personal loan → 29.6%**

Customers without personal loans consistently showed higher subscription rates across all marital-status groups.

---

# 8. Key Findings → Business Action

| Finding | Evidence | Recommended Action |
|---|---|---|
| Previous campaign success strongly relates to subscription | 91.3% subscription rate | Prioritize customers with previous successful outcomes |
| Some customer segments respond better | 60+ Retired: 81.3%; Under 30 Students: 77.0% | Prioritize high-performing segments |
| Longer calls are associated with subscription | Median: 426 sec vs 163 sec | Focus on quality conversations rather than call volume |
| Repeated contacts generally show weaker response | 1 contact: 53.4% | Avoid excessive repeated calling and improve targeting |
| Customers without loans respond better | Housing loan: 36.6% vs no loan: 57.0% | Consider loan status in customer segmentation |
| May–August generally underperformed | May: 32.8% | Investigate campaign timing and messaging |
| Unknown contact/history groups perform poorly | Unknown contact: 22.6% | Improve data quality and customer history tracking |
| Previous contact history is associated with higher response | No previous contact: 40.7% | Use customer engagement history in targeting |

---

# 9. Priority Customer Segments

Based on the analysis, the following groups showed particularly strong subscription rates:

1. **60+ Retired customers — 81.3%**
2. **Under 30 Students — 77.0%**
3. **Customers with previous campaign success — 91.3%**
4. **Under 30 Management — 60.6%**
5. **Tertiary-educated customers without housing loans — 61.6%**
6. **Single customers without personal loans — 55.6%**

These segments can be considered for higher-priority targeting, while ensuring that customer volume and campaign costs are also considered.

---

# 10. Recommendations

### 1. Prioritize High-Response Customers

Use previous campaign outcomes and customer characteristics to identify customers with higher likelihood of subscription.

### 2. Reduce Unnecessary Repeated Contacts

The analysis suggests that repeatedly contacting the same customer is associated with weaker response rates. Improve targeting before increasing contact frequency.

### 3. Focus on Conversation Quality

Subscribers had substantially longer calls. Training and improving the quality of customer conversations may be more useful than simply increasing the number of calls.

### 4. Investigate Weak Campaign Periods

May–August showed relatively weaker performance. Review campaign strategy, customer mix, and messaging during these periods.

### 5. Improve Customer Data Tracking

Large numbers of customers had unknown previous campaign outcomes or unknown contact methods. Improving tracking could support better segmentation and targeting.

---

# 11. Final Business Conclusion

The bank marketing campaign achieved a **47.4% subscription rate**, but campaign performance varied considerably across customer segments and campaign characteristics.

The strongest associations were observed for **previous campaign success, call duration, customer segment, loan status, and previous contact history**.

The analysis indicates that the bank could improve campaign efficiency by moving from broad customer outreach toward **data-driven customer targeting**, prioritizing high-response segments and customers with positive previous interactions while reducing unnecessary repeated contacts.

These findings represent **associations observed in the dataset and should not be interpreted as proof of causation**. Further testing through controlled campaigns would be required to determine which strategies directly improve subscription rates.
