# Qronos-Benchmark
Qronos Benchmark results, images and report

The circuits in this folder correspond to the benchmark set introduced by Nam et al. [1], optimised for the IBM-Eagle gate set using our algorithm.

Circuit Optimisation Results by Qronos

|Circuit|Original|Qiskit|Tket|Quartz|Quarl|Qronos<sup>†</sup>|
|---|---|---|---|---|---|---|
|adder_8		                       |1744|1014|788|997|684|**365**|
|barenco_tof_10	                   |902|463|374|482|277|**161**|
|barenco_tof_3	                   |118|64|52|52|41|**23**|
|barenco_tof_4	                   |230|121|98|99|74|**41**|
|barenco_tof_5	                   |342|178|144|146|107|**61**|
|csla_mux_3	                       |330|199|143|181|164|**77**|
|csum_mux_9	                       |560|447|355|459|318|**151**|
|gf2⁴_mult                         |499|233|206|229|191|**93**|
|gf2⁵_mult                         |779|353|319|372|294|**153**|
|gf2⁶_mult                         |1121|497|454|528|421|**216**|
|gf2⁷_mult                         |1525|665|614|708|572|**281**|
|gf2⁸_mult                         |2005|864|806|923|820|**416**|
|mod5_4	                           |123|68|54|62|49|**14**|
|mod_mult_55		                   |231|135|97|114|99|**57**|
|mod_red_21	                       |542|285|226|292|203|**103**|
|qcla_adder_10                     |1029|542|430|586|411|**221**|
|qcla_com_7                        |869|444|361|470|303|**167**|
|qcla_mod_7                        |756|903|752|978|745|**358**|
|rc_adder_6                        |376|214|159|189|163|**93**|
|tof_10                            |527|290|222|217|202|**104**|
|tof_3                             |93|52|40|42|38|**18**|
|tof_4                             |155|86|66|67|61|**30**|
|tof_5                             |217|120|92|92|84|**42**|
|vbe_adder_3                       |290|139|121|124|81|**44**|


The original circuits are available in the [optimiser benchmark repository](https://github.com/njross/optimizer). 

*Note: The circuits should be transpiled to the IBM-Eagle gate set ({CX, SX, X, Rz}) using Qiskit before optimisation.*


### References
[1] Y. Nam, N.J. Ross, Y. Su, A.M. Childs, and D. Maslov. Automated optimization of large quantum circuits with continuous parameters. October 2017. Available from https://arxiv.org/abs/1710.07345.
