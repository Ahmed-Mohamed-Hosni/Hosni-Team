# Quality Diversity Audit – GCHA Project

## Section 1: The Failure

The “Silent Bug” is a hidden quality failure in the GCHA AI engine where the system performs well for general patients but gives less accurate or delayed predictions for elderly patients and patients from regional hospitals. Using ISO/IEC 25010 terms, this is a Reliability failure because the system cannot consistently provide safe predictions for all patient groups. It is also a Functional Suitability failure because the system does not fully meet the medical requirement of supporting all intended users equally.

This failure is dangerous because GCHA is a high-reliability healthcare system. If the AI underperforms for elderly or regional patients, doctors may receive incorrect heart-failure warnings, which creates clinical, ethical, and reputational risk for GlobalCare.

## Section 2: The Decision

The London PMO has decided to HALT the rollout immediately.

This decision is based on the ACM/IEEE PUBLIC Principle, because the safety and welfare of patients must come before schedule pressure or business launch targets. Continuing the rollout while knowing the AI has a demographic bias would increase public risk and would violate professional responsibility. The project will only continue after the Berlin AI model passes a new diversity and reliability quality gate.

## Section 3: The Correction

The PMO will add the following Prevention Costs to the quality budget:

1. Diverse Dataset Purchase  
   Buy additional validated medical datasets covering elderly patients, rural hospitals, and regional legacy systems.

2. Regional Bias Training  
   Retrain the Berlin AI model using balanced data from London, Cairo, Berlin, Bangalore, and regional hospitals to reduce demographic bias.

3. Independent Fairness and Reliability Audit  
   Hire an external medical AI audit team to test model accuracy, false positives, false negatives, and reliability across different patient groups before rollout.

4. Additional Quality Gate in Jira  
   Add a mandatory “Diversity Data Audit Passed” checklist item before any AI-related Jira task can move to Done.

## Commit Message

Added Quality Diversity Audit and ethical rollout halt decision
