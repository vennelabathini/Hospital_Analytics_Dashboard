# Hospital_Analytics_Dashboard

🏥 Hospital Analytics Dashboard

Power BI · Multi-Page Operations Report

A full-scale, five-page Power BI application that brings an entire hospital's operations into a single connected report. It spans the whole picture — a top-level overview, deep-dive profiles for individual patients and doctors, clinical records, and complete financials — all linked by on-canvas navigation buttons and drill-through. Together the pages showcase data modeling, interactive what-if analysis, and end-to-end report design.

🧭 Dashboard Walkthrough

The report opens on a landing page that acts as its home screen, routing users to each of the five sections — Overview, Patient, Doctor, Hospital, and Finance. Every button jumps to a page built to answer one specific operational question, so the whole report reads as a single guided journey rather than a set of disconnected views.

<img width="624" height="361" alt="Picture2" src="https://github.com/user-attachments/assets/d8f60143-85ee-4911-8edd-982e74377406" />


Each page below answers a distinct operational question.

📋 Overview Dashboard

<img width="624" height="361" alt="Picture3" src="https://github.com/user-attachments/assets/42dc955d-41b7-4baf-bdfd-babbebda2a40" />

The executive summary of the hospital. Top-line cards report 30 patients (average age 46), 15 doctors, and 20 staff, alongside a 73% discharge rate. A discharge-by-date trend tracks patient flow month over month, a month-and-day heatmap monitors medicine movement, and a billing-charges breakdown shows Surgery as the dominant cost line at roughly 0.43M. Live appointment and feedback panels round out a real-time pulse of the facility.


🧑‍⚕️ Patient Dashboard (drill-through)

A single-patient drill-through profile — here, Deepak Menon (Discharged). It pulls together personal details (gender, weight, contact, address), the treating doctor (Dr. Amit Khanna), diagnosis and department (Nephrology), and blood group (AB+). Financials and clinical activity sit side by side: a 47.36K total bill, 124 units of medicine, admission/discharge dates, payment and surgery status, a billing-category split, and a medicine-tracking heatmap.



<img width="624" height="361" alt="Picture4" src="https://github.com/user-attachments/assets/a3455970-e471-489b-8447-57381bc1694f" />


👨‍⚕️ Doctor Dashboard (with commission what-if calculator)

A profile-and-planning view for an individual doctor — Dr. Kavita Menon (Ophthalmology, Available, 120K salary). Headline cards surface an estimated commission of 9.20K and patient expenditure of 18.12K at a 10% commission rate. The centerpiece is an interactive Commission Calculator: adjust the commission-rate and patient-spend parameters and the gauge recalculates in real time, turning the report into a compensation-modeling tool. An appointments list and a completed-bills table complete the page.

<img width="624" height="361" alt="Picture5" src="https://github.com/user-attachments/assets/e4bcc027-d165-434b-a3fd-fa423f76de82" />

🏨 Hospital Information Dashboard

The clinical operations layer. A patient-tests table logs results and physician notes — flagging findings such as "Tumor detected in left lung" and "Brain lesion detected" — while patients-by-age-category charts and a General-vs-Private bed-availability split give a read on demand and capacity. Scheduled surgeries and a doctors'-appointments-by-reason table show what's on the clinical calendar.

<img width="624" height="361" alt="Picture6" src="https://github.com/user-attachments/assets/b0db1d64-dee2-47d9-af93-b7be8c2ad8fc" />

💰 Finance Dashboard

The money view. Alongside a 714K total bill amount, cards track doctor salary (4M) and commission (71K), staff salary, and medicine-sale volume (3,928 units). A medicine stock-status panel compares units in stock against units sold to expose stock-out risk, a monthly med-sales trend peaks in June at 839, and a supplier-performance panel benchmarks vendors — tying revenue, payroll, and inventory into one financial picture.


<img width="624" height="361" alt="Picture7" src="https://github.com/user-attachments/assets/9472c518-4eee-4f4e-a6d5-d6076262b20c" />


💡 Key Insights


Surgery is the hospital's top revenue engine, leading the billing mix on every page that shows it.
The 73% discharge rate paired with the General-vs-Private bed split hands administrators an at-a-glance capacity check.
The doctor Commission Calculator converts a static report into a live tool for testing pay scenarios.
Stock-versus-sold and supplier tracking flag medicine stock-out risk, and the monthly sales curve exposes clear seasonality (a June high).
Button navigation and drill-through weave patient, doctor, clinical, and financial data into one continuous operations narrative.


🗂️ Dataset

Simulated hospital operations data spanning patients, doctors, staff, clinical tests, billing, and pharmacy inventory. Source: [dataset link].

🎯 Project Purpose

The application gives hospital leadership a single connected view of operations, clinical activity, and finance — enabling capacity planning, compensation modeling, and inventory oversight without switching between disconnected reports.

👥 Stakeholders


Hospital Administrators: Monitor discharge rates, bed capacity, and revenue drivers in real time.
Finance Teams: Track salaries, commissions, and pharmacy margins.
Department Heads: Use drill-through to review individual patient and doctor activity.
Data / BI Teams: Adapt the multi-page navigation and what-if patterns for other operational reports.


🛠️ Tools Used

Power BI — multi-page report with button navigation, drill-through, what-if parameters, DAX measures, KPI cards, heatmaps, donut and bar visuals, and a custom UI theme.

✅ Conclusion

A full hospital-in-a-report build that demonstrates data modeling, drill-through, and what-if interactivity — a st
