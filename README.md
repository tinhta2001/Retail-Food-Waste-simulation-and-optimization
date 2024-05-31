# Retail-Food-Waste-simulation-and-optimization

Grocery retailers are selling fresh foods and constantly face uncertainty regarding the freshness of their supply. In developed countries more than 2/3 of food waste is generated at the retail and consumption stages of the supply chain. Recently, there have been technological solutions based on Blockchain to reduce food waste, such as the Food Trust by IBM. In essence, blockchain offers more precise information sharing regarding freshness of supply across the whole supply chain and allows the retailers to optimise their inventories better.

# Problems:

a) Consider first a retailer that is not using blockchain. Their consumer demand is stochastic and freshness-dependent: D=λ+βX+ϵ , where λ is a baseline level of demand, β
 is sensitivity of demand to freshness, and X and ϵ are independent normally distributed random variables, such that X∼N(0,σ2X) and ϵ∼N(0,σ2). The variable ϵ describes an idiosyncratic demand shock and the variable X  describes uncertain freshness of supply. For simplicity the variable X is mean-centred at zero.

 ssume that the baseline level of demand is λ=357.46 kg, sensitivity is β=82.38 kg/day, and σ=44.72 and σX=0.6509. Assume also that the retailer buys its stock with wholesale price 1 eur/kg and sells it with retail price 3 eur/kg. There is no salvage value with the stock that is unsold. The retailer is risk-neutral and maximises profit. Use the model to answer the following questions: what is the optimal level of fresh food to stock, and what is the associated expected profit with that level?

b) Now consider a Blockchain retailer who receives freshness information, i.e. knows the realisation  X=x before ordering. Note that even in this case the supply order may not match demand because of the component ϵ whose realisation is not observed before decision making. Use the model to answer the following questions: What is the improvement in expected profit with a retailer that is using Blockchain? How much less food waste is produced?

# Final deliveries:

* An excel file using both Excel solver and Open solver for uncertainties.
* An Python file using open source optimization libraries for result comparison.
