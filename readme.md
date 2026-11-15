<h1 align="center">🚨 HR SaaS Customer Analytics</h1>

<p align="center"><b>Can you tell which customers will leave before they do?</b><br>
In this dataset, yes: every at-risk account showed the same warning signs.<br>
Microsoft Excel · Pivot Tables · Dashboards</p>

> ### 👀 Want to see the dashboards?
> **Open the `.png` files in the `main` branch of this repository.** Each dashboard is listed by file name in the table below, and the full workbook `HR_SaaS_Customer_Analytics.xlsx` is there too.

---

## 🎯 At a glance

| 🏢 Accounts analysed | ⚠️ High churn risk | ❤️ Avg health score | 🚀 Upsell opportunities |
|:---:|:---:|:---:|:---:|
| **15** | **5 (33%)** | **66.6 / 100** | **10 accounts** |

---

## 🔑 Key findings

### 1. Every at-risk account is a small business on the Basic plan
All **5 High-risk accounts are SMB customers on the Basic plan**. No Enterprise or Premium account is High risk.

| Churn risk | Accounts | Avg health score |
|:---:|:---:|:---:|
| 🔴 High | 5 | **36.0** |
| 🟠 Medium | 4 | **69.5** |
| 🟢 Low | 6 | **90.2** |

### 2. Low logins are a clear early-warning sign
No account with **2 or fewer logins a week** was rated below High risk.

| Segment | Avg logins per week | Avg jobs posted per month |
|---|:---:|:---:|
| 🏢 Enterprise accounts (6) | **22.7** | **16.8** |
| 🏪 SMB accounts (9) | **2.8** | **1.6** |

Enterprise accounts log in about **8x** more and post about **10x** more jobs.

### 3. Support tickets pile up where the risk is
Of **24 open tickets**, the 5 High-risk accounts hold **17 (71%)**. SMB accounts hold 20 of 24 (83%).

| Account | Open tickets | Churn risk |
|---|:---:|:---:|
| Zenith Hospitality | 5 | 🔴 High |
| BlueSky Media Hub | 4 | 🔴 High |
| TechCorp India | 3 | 🔴 High |
| Metro Infra Solutions | 3 | 🔴 High |

### 4. The 5 accounts that need a rescue call

| Account | Logins/wk | Jobs/mo | Open tickets | Health score |
|---|:---:|:---:|:---:|:---:|
| Zenith Hospitality | 1 | 0 | 5 | **25** |
| Apex Retail Solutions | 1 | 0 | 2 | **30** |
| BlueSky Media Hub | 1 | 1 | 4 | **38** |
| Metro Infra Solutions | 2 | 0 | 3 | **42** |
| TechCorp India | 2 | 1 | 3 | **45** |

Three of them posted **zero jobs** in the month, so they pay for a platform they barely use.

### 5. Growth is concentrated in healthy accounts
**10 of 15 accounts** have an upsell opportunity: 5 Enterprise and 5 SMB.
- Healthy accounts have clear next steps, such as a multi-location license, an Enterprise suite or e-learning modules.
- Three High-risk accounts are also flagged for an upsell (TechCorp India, Apex Retail, Metro Infra). The data suggests fixing their adoption first, since selling more to an account that barely logs in is unlikely to work.

---

## 💡 What I would recommend

| Priority | Action | Why |
|:---:|---|---|
| 1 | Call the 5 High-risk SMB accounts this week | Health scores of 45 or below, and low platform use |
| 2 | Add an alert when an account drops to 2 or fewer logins a week | This was the clearest warning sign in the data |
| 3 | Clear the ticket backlog on High-risk accounts | They hold 71% of open tickets |
| 4 | Start upsell conversations with healthy Enterprise accounts | Low risk, high usage |
| 5 | Delay upsells to at-risk SMBs until they are active again | Adoption has to come first |

*These are recommendations drawn from a small sample, not proven rules.*

---

## 📌 Project overview

This project analyses engagement and account health for an HR SaaS platform serving recruitment-focused companies. It answers three questions: **who is at risk, why, and where can the business grow?**

## 🧾 Metrics analysed

| Metric | What it tells us |
|---|---|
| Account Type | SMB or Enterprise |
| Contract Plan | Basic, Premium or Enterprise |
| Logins per Week | How actively the platform is used |
| Jobs Posted per Month | How much recruiting runs through it |
| Open Tickets | Support load and likely frustration |
| Health Score | Overall account health out of 100 |
| Churn Risk | Low, Medium or High |
| Upsell Opportunity | The add-on or upgrade that fits |

## 🛠️ Tools and method

| Step | What happened |
|:---:|---|
| 1 | Built a 15-account customer dataset |
| 2 | Summarised it with Pivot Tables |
| 3 | Visualised each analysis as a dashboard chart |
| 4 | Combined engagement, health and support data to spot patterns |

**Tools:** Microsoft Excel · Pivot Tables · Pivot Charts

## ⚠️ Limitations

- This is a **sample of 15 accounts**, so the patterns are indicative, not statistically proven.
- The data is illustrative and does not come from a live company.
- Churn risk labels are given in the data, not predicted by a model.

---

## 📸 Dashboards: open these files in the `main` branch

| # | Open this file | What it shows | Question answered |
|:---:|---|---|---|
| 📋 | `data.png` | The customer account dataset | What data was analysed? |
| 1 | `open_tickets.png` | Open support tickets by account | Which accounts need extra support? |
| 2 | `login_companytype.png` | Logins by company type and plan | How does usage differ across plans? |
| 3 | `health_score.png` | Account health scores | How healthy is each account? |
| 4 | `jobs_posted.png` | Jobs posted per month | Which accounts use the platform most? |
| 5 | `churn_risk.png` | Churn risk by account type | How does health differ by risk level? |
| 6 | `upsell.png` | Upsell opportunities | Where can the business grow? |

📊 **Full workbook with data and pivot tables:** `HR_SaaS_Customer_Analytics.xlsx`

---

## 👤 Author
**M.S. Jhanavi** · MBA (HR & Marketing 
), KL University

## ⭐ Conclusion
In this sample, churn risk was easy to see in the data: low logins, little job posting, a backlog of tickets and a low health score all lined up on the same small accounts. The project shows how Excel and Pivot Tables can turn customer data into clear actions on who to rescue, who to support and who to grow.
