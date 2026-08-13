# Instructions

This project is a take-home test for the Senior Analytics Engineer role, follow the intructions below:

1. Remove the test model once you make sure it works

2. Dive deep into the Pipedrive CRM source data to gain a thorough understanding of all its details. (You may also research the Pipedrive CRM tool terms).

3. Define DBT sources and build the necessary layers organizing the data flow for optimal relevance and maintainability.

4. Build a reporting model (`rep_sales_funnel_monthly`) with monthly intervals, incorporating the following funnel steps (KPIs):
   - Step 1: Lead Generation
   - Step 2: Qualified Lead
   - Step 2.1: Sales Call 1
   - Step 3: Needs Assessment
   - Step 3.1: Sales Call 2
   - Step 4: Proposal/Quote Preparation
   - Step 5: Negotiation
   - Step 6: Closing
   - Step 7: Implementation/Onboarding
   - Step 8: Follow-up/Customer Success
   - Step 9: Renewal/Expansion

5. Column names of the reporting model: `month`, `kpi_name`, `funnel_step`, `deals_count`.
