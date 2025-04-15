# 💼 LinkedIn Profile Analysis | Power BI Dashboard
This project presents a comprehensive **Power BI dashboard** that analyzes a LinkedIn user's profile metrics to uncover patterns and engagement trends. The goal is to transform raw LinkedIn data into actionable insights through dynamic visuals and interactive filters.

## 🔗 Live Interactive Dashboard
👉 [Click here to explore the live Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYTAyZjYxMDktYmJhZi00ZmUxLTgyZmUtYmJlODdjNGY1N2U1IiwidCI6IjQ2ODQ3YjcwLWZlZDYtNDE2My04MjhkLTBjNmQ3ODhmOWRhZCIsImMiOjl9)
> ⚠️ *Dashboard is hosted on Power BI Service and is public through "Publish to Web".

The dashboard is divided into **two main pages**:
1. `Overview` – for summary-level KPIs and demographics
2. `Insights` – for detailed messaging, endorsements, and growth tracking

## 📸 Dashboard Previews

### 🧭 **Overview Page**

![Overview Page](https://github.com/user-attachments/assets/07ebd7f2-deae-4a5a-bdb2-4afdb4ae7c91)

---

### 📊 **Insights Page**

![Insights Page](https://github.com/user-attachments/assets/8331a318-ba49-45f1-b471-a9f19b43ab03)

## 🗺 Overview Page – Full Breakdown

### 🔢 **Top Summary Cards (KPIs)**

| KPI | Value | Meaning |
|-----|-------|---------|
| **Connections** | 4,089 | Total number of LinkedIn connections accumulated over time |
| **Companies** | 2,028 | Unique organizations your network is associated with |
| **Messages Sent** | 1,477 | Total messages you’ve sent |
| **Messages Received** | 1,282 | Total messages received |
| **Invitations Sent** | 1,216 | Number of connection requests you’ve sent |
| **Invitations Received** | 618 | Connection requests you’ve received from others |
| **Endorsements Given** | 38 | Skills you endorsed on other people’s profiles |
| **Endorsements Received** | 3 | Skills you were endorsed for |

> 📌 *These KPIs provide a direct reflection of profile activity and networking behavior.*

---

### 📈 **Total Connections by Month**

- **Chart Type:** Line + Area Chart
- **Insight:** This shows how my LinkedIn connections have grown month over month.
- **Observation:** The biggest spikes are in **March (406)**, **September (465)**, **October (529)**, and **December (520)**.
---

### 🏢 **Top 7 Companies by Connections**

- **Chart Type:** Horizontal Bar Chart
- **Insight:** Reveals the organizations where I have the most connections.
- **Top Companies:**
  1. Innovation and Digital Development Agency – 204
  2. Kapital Bank – 113
  3. ABB – 101
  4. Azerbaijani Railways – 55
  5. Pasha Bank OJSC – 48
  6. SOCAR – 44
  7. Unibank – 36

> 🧠 *Highlights my strong network in digital development, banking, and engineering sectors.*

---

### ⚧️ **Gender Count & Connection Ratio**

- **Visuals:**
  - Icon-based **gender count** chart
  - Donut chart showing **gender percentage**
- **Insight:**
  - 2,451 Male (59.9%)
  - 1,638 Female (40.1%)

> 📌 *Understanding gender diversity can help tailor content, outreach, or recruitment efforts.*

---

### 👔 **Top 7 Positions by Connections**

- **Chart Type:** Vertical Bar Chart
- **Insight:** Identifies the most common job titles among my connections.
- **Top Roles:**
  - Human Resources Specialist – 117
  - Data Analyst – 88
  - Founder – 47
  - Business Analyst – 45
  - Senior HR Specialist, HR Manager, and HR Manager – all between 32–34

> 🧩 *This data tells us my network is rich in HR and analytics professionals — a valuable insight for targeting content or services.*

---

## 📬 Insights Page – Full Breakdown

### 📈 **Messages Sent / Received by Month**

- **Chart Type:** Line Charts
- **Insight:** Patterns in communication over time
  - **Peak messages sent:** May (406)
  - **Peak messages received:** May (390), April (182), March (113)
  - Significant dips in June/July

> 🔍 *This may reflect seasonal activity or career phases.*

---

### 🧑‍🤝‍🧑 **Top Message Senders**

- **Chart Type:** Bar Chart
- **Insight:** Identifies my most frequent message interactions.
- **Top Contacts:**
  1. Jalal Ahmadov – 226
  2. Ramila Faracova – 136
  3. Nigar Azimzade – 107
  4. Ayaz Hasanli, Gunel Aliyeva, Shahriyar Aghamammadov, Eldar Ahmadzada

> 💡 *These are my closest contacts. Great for maintaining engagement or referrals.*

---

### 🧠 **Top Skills by Endorsement Given**

- **Skills Endorsed Most:**
  - Microsoft Excel – 3
  - Microsoft Power BI – 3
  - Analytical Skills – 2
  - Problem Solving – 2

> 🛠 *Even though the number is small, this insight shows what skills others value in my profile.*

---

### 📤📥 **Message & Invitation Breakdown**

- **Donut Charts**
- **Message Split:** 54% sent, 46% received
- **Invitation Split:** 66% sent, 34% received

> 📈 *I'm a proactive networker — sending out more messages and invitations than I receive.*

---

### 🏁 **Road to 5,000 Connections**

- **Gauge Chart:** Shows I'm currently at **4,089** connections out of a target of **5,000**.
- **Completion Rate:** **81.8%**

> 🎯 *Tracking progress toward a common LinkedIn milestone for super-connectors.*

---

### 🎛 Year Filter (Slicer)

- **Feature:** Interactive year filter from 2018 to 2025.
- **Located in:** Left sidebar on both dashboard pages.
- **Usage:** Allows users to dynamically filter all dashboard visuals (charts, KPIs, tables) by one or more selected years.
- **Business Value:** Enables focused analysis for a specific time period. For instance, you can compare activity during 2020 vs. 2022 to observe how your networking behavior evolved.

> 🔁 *Multi-select supported: hold CTRL (Windows) or CMD (Mac) to select multiple years.*

---

### 🔄 Clear All Filters Button

- **Function:** Resets all filters (like selected years) to show the full data again.
- **Location:** Found below the Year Filter panel on the left side.
- **Purpose:** Enhances user experience by providing a quick way to return to the default dashboard state.
- **Ideal for:** Viewers who explore multiple years and want to instantly reset their view.

> 🧼 *A must-have usability feature in any interactive BI dashboard!*

## 🛠 Tools & Technologies Used

- **Power BI Desktop** – For building the dashboard
- **Power Query (M Language)** – For data transformation and cleaning
- **DAX (Data Analysis Expressions)** – For calculating custom KPIs and metrics
- **LinkedIn Data Export (CSV)** – Data source downloaded from [LinkedIn Settings > Download Data](https://www.linkedin.com/settings/data-export-page)

---

## 🔍 Use Cases

- 📈 Personal branding insights
- 👥 Targeted networking strategy
- 💬 Communication pattern analysis
- 🧑‍💼 Market segmentation of your professional community
- 🎯 Goal tracking and profile optimization

---

## 👤 Author

**Elmaddin Hasanli**  
📍 Baku, Azerbaijan 
📫 [Connect with me on LinkedIn](https://www.linkedin.com/in/elmaddin-hasanli-aa1880156?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app)

---

> ⭐ *Feel free to fork this project, contribute, or use the structure for your own LinkedIn analysis dashboard.*
