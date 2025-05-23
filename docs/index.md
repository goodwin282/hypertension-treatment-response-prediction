<!-- Toolbar @TODO: Fix this if i want to add it in--> 
<!-- <div style="background: #f8f8f8; padding: 10px 0; text-align: right; border-bottom: 1px solid #e0e0e0; margin-bottom: 24px;">
  <a href="/hypertension-project-site/about/" style="margin-right: 20px; font-weight: bold; color: #0366d6; text-decoration: none;">About</a>
</div> -->

# Hypertension Treatment Response Prediction Project

## Problem Statement

**Clinical Challenge**: Hypertension affects 45% of US adults, but selecting the most effective first-line medication for individual patients remains largely trial-and-error. Current clinical guidelines provide general recommendations, but don't account for patient-specific factors that influence treatment response.

**Analytics Opportunity**: Electronic health records contain rich patient data that could enable personalized treatment selection, potentially improving patient outcomes while reducing time to blood pressure control and healthcare costs.

## Project Objective

Develop a predictive model that can recommend the most effective antihypertensive medication class for newly diagnosed hypertension patients based on their clinical characteristics, with the goal of maximizing the probability of achieving target blood pressure control within 3-6 months.

## Analytical Approach

### Data Source
- Synthetic EHR data generated using Synthea
- Focus on patients with newly diagnosed hypertension
- Extract treatment patterns and outcomes over 6-12 month periods

### Methodology
1. **Cohort Definition**: Identify patients starting first-line antihypertensive therapy
2. **Outcome Measurement**: Define treatment success as achieving target BP (<140/90 or <130/80) within specified timeframe
3. **Feature Engineering**: Extract baseline patient characteristics, comorbidities, lab values, and demographics
4. **Treatment Comparison**: Compare effectiveness across four main medication classes (ACE inhibitors, ARBs, calcium channel blockers, thiazide diuretics)
5. **Predictive Modeling**: Build machine learning models to predict treatment response probability for each medication class
6. **Clinical Decision Support**: Create recommendation system ranking treatments by predicted success probability

### Key Analytics Components
- Propensity score matching to address treatment selection bias
- Time-to-event analysis for treatment response timing
- Feature importance analysis to identify key predictors
- Model validation using clinically relevant metrics

## Desired Outcomes

### Technical Deliverables
- Clean, documented codebase demonstrating healthcare analytics skills
- Validated predictive models with interpretable results
- Interactive dashboard for exploring treatment recommendations
- Comprehensive analysis report with clinical context

### Professional Impact
- Demonstrate understanding of healthcare data complexities
- Show ability to translate clinical questions into analytical solutions
- Display knowledge of healthcare-specific validation approaches
- Create portfolio piece relevant to healthcare analytics roles

### Clinical Value Proposition
- Reduce time to effective blood pressure control
- Minimize adverse medication effects through better initial selection
- Support evidence-based clinical decision making
- Potentially improve patient adherence through more effective initial therapy

## Success Metrics
- Model performance: AUC >0.70 for treatment response prediction
- Clinical relevance: Identify actionable patient subgroups with different response patterns
- Interpretability: Clear feature importance rankings that align with clinical knowledge
- Portfolio impact: Demonstrate healthcare domain expertise to potential employers