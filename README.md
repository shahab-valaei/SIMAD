# SIMDisasteR
## About SIMDisasteR
SIMDisasteR is a hybrid Simulation Modelling framework for operation and coordination of Agencies Involved Disaster response and recovery. The model uses Agent-Based Modeling (ABM) and System Dynamics (SD) modeling techniques to facilitate modeling the post-disaster response and recovery of the community and the involved entities, including the primary Emergency Support Functions (ESFs)[^1] be delivered to the population, the leading agencies involved in providing those ESFs, and the consequent macro level effects such as the state of health, housing, and security in the aftermath of a disaster.

The model is implemented in Python Programming Language. BPTK-Py[^2] is used as a platform for model implementation, which facilitates haybrid modeling using Agent-based Modeling and System Dynamics in Python. 


[^1]: Emergency Support Functions (ESFs) are defined as the primary coordinating structures used by governments to respond to the incidents and natural hazards.
[^2]: Grasl, O. (2022). Business Prototyping Toolkit for Python (BPTK-Py). _Transentis Labs_. https://pypi.org/project/BPTK-Py/

## Model Structure
SIMDisasteR comprises three main blocks. A high-level schematic view of blocks, their characteristics, and their relationships are shown in Figure 1, below. The first block, the simulation environment, provides a shared interactive setting for the operation and collaboration of organizations and includes the community infrastructure systems and lifelines at a coarse resolution. The second block, called the System Dynamics (SD) sub-model, simulates the dynamics of the events in the aftermath of an earthquake. The third block, called the Agent-Based Modeling (ABM) sub-model, simulates the intra- and inter-agency interactions among the entities responsible for disaster response and recovery. These blocks work harmoniously to characterize the post-disaster state of the community and the progress of operations aimed to restore it to the pre-disaster level. The proposed model considers the performance of agencies and the coordination among them in delivering ESFs to characterize the status of various ESFs as a function of time.



## A Sample Application of the Model
To showcase the capabilities of SIMDisasteR, its application on a virtual testbed, a community called INSURER City, is presented. INSURER is a virtual community that serves as a testbed for the research studies conducted at the Center for Infrastructure Sustainability and Resilience Research (INSURER)[^3], Sharif University of Technology. Figure 2 shows a schematic view of the community and its infrastructure systems.





It should be noted that the aim of this framework is not to provide an accurate forecast of the post-earthquake state of the community under these scenarios. Simulation models often cannot accurately predict the complete interaction and cooperation of responsible agencies in the post-disaster response and recovery of the community because it is impossible to accurately model the behaviors of various system components in such large and complex systems. This simulation framework can provide a valuable analysis tool for policymakers and disaster management authorities to evaluate various coordination mechanisms and characterize the impacts of neglecting organizational duties.

[^3]: https://insurer.sharif.edu/
