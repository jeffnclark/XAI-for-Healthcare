# XAI-for-Healthcare

Potential structure
* Import model and data
* Run explanations
    * Counterfactuals
    * Surrogate tree explainers
    * LIME - (needs work)
    * Partial dependence (model-wide)
    * Tree interpreter (needs work)
* Return explainations
    * Tailor to user?
    * Other functionaility as in Quantus https://github.com/understandable-machine-intelligence-lab/Quantus?
    * Uncertainty quantification?

Optionals
* Check "skill/knowledge" with user
* Check with user that the explaination is suitable?

Potential things to resolve:
* Split into model-level and case-level explainations
* Provide back explainations for differnet organ systems
* Get LIME working
* Unscaled partial dependence - ideally extract values then have control over plotting
* Unscaled surrogate tree explainer - ideally extract values then have control over plotting
* Tailor explanations to user