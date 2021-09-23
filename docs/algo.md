# Algorithm

####Overview

Arya XAI uses significance propagation as the base algorithm. This propagation is different for each network component as they follow different mathematical functions.

Arya XAI currently has two modes of operation. 

1. Network Analysis: In this mode, the significance is always positive and propagated according to the contribution of each unit. This can be used to prune the under-utilized parts of the network and modify the saturated ones. The is also helpful in reducing or modifying the input features. 
2. Decision Analysis: In this mode, the significance can be negative or positive depending on the relative contribution of any unit to the decision. The is helpful in providing explanations based on which input features are positively/ negatively affecting the decision.
