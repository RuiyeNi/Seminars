## Insurance
- State Regulation  
  - Pricing  
  - Reserving
- Life Insurance Pricing  
 - coverage
 - mortatily rate (life table)
- Underwriting income = Premium - Loss
- Investment income  

### Property & Casualty Insurance
- multiple lines of business
- Premium = Base Rate * Factor1 * Factor2 * ... * FactorN + expense

### Health Insurance
- Commercial  
  - Group  
  - Individual
- Medicare  
- Mediaid 
- Premium = P1*Disease1 Cost + P2*Disease2 Cost ... + Pn*DiseaseN cost
- DX Code
- Disability Income  
  - State Transition Diagram, markov chain
  
### Generalized Linear Model(GLM)
- Go-to model in insurance industry
- Goal  
  - Will this client renew the contract: Logistic regresssion, Bernouli distribution 
  - How frequent will car accidents happen: Poisson regression, Poisson distribution
  - How much will any car accident cost: Gamma regression, Gamma distribution
  - How much will the total loss be: Tweedie regression, Tweedie distribution
- Newton-Raphson method for estimation

### Tree-based Methods  
- Random forest, gradient boosting are relatively new in insurane industry  
- Interpretability is important
  - Global model interpretation  
    - What are the most important variables?  
    - How does change in one variable affect overall prediction
  - Local model interpretation  
    - Given a specific observation, what is the most important variables
    - How change one variable affect the specific observation   
      - Individual Conditional Expectation (ICE), too noisy if there is large numbre of samples
      - Partial Dependence Plot (PDP) average over all ICE's  
        - Two features at the same time, heatmap  
      - SHapley Additive exPlanations (SHAP), waterfall chart

