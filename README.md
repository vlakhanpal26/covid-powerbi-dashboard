# Epidemic Flashbacks: Learning From History
**Predictive COVID-19 Dashboard for Assessing Future Country Preparedness**

I built this Power BI dashboard as part of my undergraduate coursework to explore how historical pandemic data can inform future readiness. The report brings together public datasets (WHO and Kaggle) and tracks the COVID-19 story across countries cases, recoveries, deaths, vaccination progress, and pressure on hospital capacity. Beyond the core epidemiology views, I also analyze secondary signals like age/sex distributions, stress/behavioral patterns, and cancer-care disruptions during the pandemic to understand broader system impacts.

The dashboard is organized as a set of focused pages:
- **Country COVID-19 Overview** – high-level KPIs (confirmed, active, deaths, recovered) with a country selector and time-based breakdowns.
- **Global Variants** – geographic distribution of major variants with interactive filtering.
- **Impact & Lifestyle Insights** – mortality vs vaccination, GDP context, and behavior trends (screen time / sleep) during the pandemic.
- **Cancer: Cases & Treatments** – pre-pandemic vs pandemic comparisons for stage, age groups, tumor size, and treatment patterns.
- **Hospital & ICU Capacity** – projected demand vs available beds and indicative utilization.

**What I focused on:**
- Data cleaning/joins, calculated measures, and slicer design for clear interaction.
- Consistent visual language (colors, typography, spacing) to keep the narrative readable.
- Practical trade-offs between visual richness and performance in the Service.
- Transparent limitations (public-data coverage, map permissions/Azure Maps toggles, and non-causal relationships).

My goal with this project is to demonstrate how a well-structured BI report can help non-technical stakeholders move from “what happened?” to “where are we under-resourced and why?”. Feedback is welcome—especially on metrics to add, better normalizations (e.g., per-capita views), and ideas for scenario modeling.

 **PDF Dashboard:** [Download here](covid19-preparedness-dashboard.pdf)  

---

##  Data Sources
- World Health Organization (WHO)  
- Kaggle datasets  

---

## Notes
- Built in **Power BI**, exported as **PDF** for portability.  
- Some visuals (e.g., Azure Maps) may require tenant admin settings to display in Power BI Service.  
