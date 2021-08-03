# Behavioural_Economics

Code is in Mathematica, meaning in order to run the code, it must be copied out of my repository onto a local machine running Mathematica. 

Behavioural Economics model of present bias (specifically quasi-hyperbolic discounted utility or QHDU) applied to the problem of Christmas shopping being delayed until the last moment. 

We looked at varying the present bias parameter (beta) and how the QHDU model predicted the set of agents would end up doing their shopping. 

The decision rule is simple: At each time step, every agent considers each future (as well as the present) time step's utility from going to the shop. Going to the shop incurs a fixed cost, namely alpha. This is the same at every time period. There is another cost, stress, which is the product between gamma (which parameterises each agent's unique attitude to stress- how chilled out they are) and 1 / (25-t), where t is the day in December. As a result, stress increases exponentially as christmas day approaches, with an asymptote at Christmas day (ensuring every agent does end up purchasing). Agents assess the present value of each future time step's cost, and if the present value of going shopping in the present time period is highest (i.e. the cost is the lowest) then they shop today. 

We find that QHDU presents a good explaination of the collective behaviour of delaying of Christmas shopping.  

For the full project report, please note the relevant PDF in this repository. 
