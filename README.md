# SIMDisasteR
## About SIMDisasteR
SIMDisasteR is a hybrid Simulation Modelling framework for operation and coordination of Agencies Involved Disaster response and recovery. The model uses Agent-Based Modeling (ABM) and System Dynamics (SD) modeling techniques to facilitate modeling the post-disaster response and recovery of the community and the involved entities, including the primary Emergency Support Functions (ESFs)[^1] be delivered to the population, the leading agencies involved in providing those ESFs, and the consequent macro level effects such as the state of health, housing, and security in the aftermath of a disaster.

The model is implemented in Python Programming Language. BPTK-Py[^2] is used as a platform for model implementation, which facilitates haybrid modeling using Agent-based Modeling and System Dynamics in Python. 


[^1]: Emergency Support Functions (ESFs) are defined as the primary coordinating structures used by governments to respond to the incidents and natural hazards.
[^2]: Grasl, O. (2022). Business Prototyping Toolkit for Python (BPTK-Py). _Transentis Labs_. https://pypi.org/project/BPTK-Py/

## Model Structure
SIMDisasteR comprises three main blocks. A high-level schematic view of blocks, their characteristics, and their relationships are shown in Figure 1, below. The first block, the simulation environment, provides a shared interactive setting for the operation and collaboration of organizations and includes the community infrastructure systems and lifelines at a coarse resolution. The second block, the Agent-Based Modeling (ABM) sub-model, simulates the intra- and inter-agency interactions among the entities responsible for disaster response and recovery. The third block, the System Dynamics (SD) sub-model, simulates the dynamics of the events in the aftermath of an earthquake, including provision of essentials, infectious diseases outbreak, and crime outbreak and prevention. These blocks work harmoniously to characterize the post-disaster state of the community and the progress of operations aimed to restore it to the pre-disaster level. The proposed model considers the performance of agencies and the coordination among them in delivering ESFs to characterize the status of various ESFs as a function of time.
![Figure 1](https://drive.google.com/file/d/1jHygiW7X3p5xj15Hbib9MItM_zyliRl0/view?usp=sharing)
## A Sample Application of the Model
To showcase the capabilities of SIMDisasteR, its application on a virtual testbed, a community called INSURER City, is presented. INSURER is a virtual community that serves as a testbed for the research studies conducted at the Center for Infrastructure Sustainability and Resilience Research (INSURER)[^3], Sharif University of Technology. Figure 2 shows a schematic view of the community and its infrastructure systems.

Figure 2. 
The represented ESFs in this example include search and rescue, public health services, temporary housing, debris removal, security, patient transfer, food and water supply, hospital restoration, infrastructures inspection, and infrastructures restoration. These ESFs and the agencies responsible for performing each of them are shown in Figure 3. Note that each agency can be responsible for one or multiple ESFs. For instance, Urban Development Organization is only responsible for issuing construction permits needed to commence with the repair and reconstruction activities. On the other hand, the Search and Rescue Organization is responsible for search and rescue operations, health services, and temporary housing.

Figure 3. 
The model is capable of generating a wide range of outputs corresponding to various emergency support functions and dynamic phenomena. 
As an example of model outputs, the following sub-sections present the progress of multiple ESFs (search and rescue, damage inspection and restoration of infrastructure systems) under different simulation scenarios. The base scenario corresponds to the situation where all of the identified agencies cooperate. In each of the other scenarios, one or multiple of the agencies are incapacitated, meaning that its operational crews are not present in the region, and its manager is not functional to cooperate with other manager agents.

### Search and Rescue
Figure 4 shows the progress of the search and rescue operation as a function of time. It shows the percentage of operation that is completed at a given time.

Figure 4.

### Damage Inspection of Infrastructure Systems
Figure 5 shows the overall progress of damage inspection operations across all community infrastructure systems and lifelines under various scenarios.

Figure 5.

### Restoration of Infrastructure Systems
The overall restoration curve for the community infrastructure systems in various simulation scenarios is provided in Figure 6.

Figure 6.

[^3]: https://insurer.sharif.edu/

## Disclaimer
It should be noted that the aim of SIMDisasteR is not to provide an accurate forecast of the post-earthquake state of the community under these scenarios. Simulation models often cannot accurately predict the complete interaction and cooperation of responsible agencies in the post-disaster response and recovery of the community because it is impossible to accurately model the behaviors of various system components in such large and complex systems. SIMDisasteR can provide a valuable analysis tool for policymakers and disaster management authorities to evaluate various coordination mechanisms and characterize the impacts of neglecting organizational duties.


