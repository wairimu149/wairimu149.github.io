---
title: "Exploring HR Insights through a Tableau Dashboard"
date: 2025-10-25
categories: [Projects, Tableau, HR Analytics]
tags: [Tableau, HR Analytics, Dashboard, Data Visualization]
description: >-
  From raw data to real results — blending analytics, curiosity, and strategy to fuel business growth and innovation.
---

## Project Overview
In this project I developed an interactive HR summary dashboard using Tableau to help HR teams and business leaders gain visibility into workforce trends, performance, and opportunities for improvement.

**Live dashboard:**  
👉 [View the live Tableau Dashboard](https://public.tableau.com/app/profile/grace.nganga/viz/CS-DA02-25074GraceNganga/HRSUMMARY?publish=yes)

---

## Objectives
- Provide a consolidated view of headcount, tenure, turnover, and hiring.  
- Highlight department-level patterns and performance metrics.  
- Enable stakeholders to explore HR data visually and make data-driven decisions.

---

## Tools & Techniques
- **Tableau Public** — interactive dashboard and visual storytelling.  
- **Excel / CSV** for preprocessing and cleaning.  
- KPIs used: turnover rate, average tenure, new hires, department headcount.  
- Applied visualization best practices (clear layout, readable labels, interactive filters).

---

## Key Insights
- Departments with higher turnover tended to have lower average tenure — a potential retention concern.  
- Hiring spikes in certain quarters suggest seasonal recruitment or project ramp-ups.  
- Role and tenure distributions reveal areas with high experience concentration vs. those needing development.  
- Interactive filters enable drilling down by department, role, or period for targeted insights.

---

## Reflection & Next Steps
Building this dashboard reinforced my ability to structure visual stories that stakeholders can navigate intuitively. For future improvements I would:
- Add predictive analytics (e.g., turnover forecasting) for forward-looking insights.  
- Integrate employee engagement and training data for fuller context.  
- Add scenario-based filters (e.g., “what if hiring increases by 20%”) to support planning.

---

## Embedded Dashboard (interactive)
Below is an embedded view of the Tableau dashboard so visitors can interact without leaving the page.

> **Note:** If your site sanitizes iframes or you prefer not to embed, keep the direct link above instead.

```html
<!-- Responsive container for embedded Tableau -->
<style>
.tableau-container {
  position: relative;
  width: 100%;
  padding-bottom: 56.25%; /* 16:9 aspect ratio — adjust if you want taller */
  height: 0;
  overflow: hidden;
}
.tableau-container iframe {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  border: 0;
}
</style>

<div class="tableau-container">
  <iframe src="https://public.tableau.com/views/CS-DA02-25074GraceNganga/HRSUMMARY?:showVizHome=no&:embed=true"
          allowfullscreen
          scrolling="no">
  </iframe>
</div>

