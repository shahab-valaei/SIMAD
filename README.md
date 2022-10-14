# SIMDisasteR
## About SIMDisasteR
SIMDisasteR is a hybrid Simulation Modelling framework for operation and coordination of Agencies Involved Disaster response and recovery. The model uses Agent-Based Modeling (ABM) and System Dynamics (SD) modeling techniques to facilitate modeling the post-disaster response and recovery of the community and the involved entities, including the primary Emergency Support Functions (ESFs)[^1] be delivered to the population, the leading agencies involved in providing those ESFs, and the consequent macro level effects such as the state of health, housing, and security in the aftermath of a disaster.

The model is implemented in Python Programming Language. BPTK-Py[^2] is used as a platform for model implementation, which facilitates haybrid modeling using Agent-based Modeling and System Dynamics in Python. 


[^1]: Emergency Support Functions (ESFs) are defined as the primary coordinating structures used by governments to respond to the incidents and natural hazards.
[^2]: Grasl, O. (2022). Business Prototyping Toolkit for Python (BPTK-Py). _Transentis Labs_. https://pypi.org/project/BPTK-Py/

## Model Structure
SIMDisasteR comprises three main blocks. A high-level schematic view of blocks, their characteristics, and their relationships are shown in Figure 1, below. The first block, the simulation environment, provides a shared interactive setting for the operation and collaboration of organizations and includes the community infrastructure systems and lifelines at a coarse resolution. The second block, the Agent-Based Modeling (ABM) sub-model, simulates the intra- and inter-agency interactions among the entities responsible for disaster response and recovery. The third block, the System Dynamics (SD) sub-model, simulates the dynamics of the events in the aftermath of an earthquake, including provision of essentials, infectious diseases outbreak, and crime outbreak and prevention. These blocks work harmoniously to characterize the post-disaster state of the community and the progress of operations aimed to restore it to the pre-disaster level. The proposed model considers the performance of agencies and the coordination among them in delivering ESFs to characterize the status of various ESFs as a function of time.

![Figure1](https://user-images.githubusercontent.com/61154430/195952634-d729e330-ba3d-4314-8787-942f109cbaaa.png)

Figure 1: The structure of SIMDisasteR and the relationships between model components.

## A Sample Application of the Model
To showcase the capabilities of SIMDisasteR, its application on a virtual testbed, a community called INSURER City, is presented. INSURER is a virtual community that serves as a testbed for the research studies conducted at the Center for Infrastructure Sustainability and Resilience Research (INSURER)[^3], Sharif University of Technology. Figure 2 shows a schematic view of the community and its infrastructure systems.

![Figure2](https://user-images.githubusercontent.com/61154430/195952654-1dab83a4-cc24-4efa-8a5f-dd284e64c97c.jpg)

Figure 2: Schematic view of the INSURER city.

The represented ESFs in this example include search and rescue, public health services, temporary housing, debris removal, security, patient transfer, food and water supply, hospital restoration, infrastructures inspection, and infrastructures restoration. These ESFs and the agencies responsible for performing each of them are shown in Figure 3. Note that each agency can be responsible for one or multiple ESFs. For instance, Urban Development Organization is only responsible for issuing construction permits needed to commence with the repair and reconstruction activities. On the other hand, the Search and Rescue Organization is responsible for search and rescue operations, health services, and temporary housing.

![Figure3](https://user-images.githubusercontent.com/61154430/195952667-b51d86d9-65c4-45e3-869e-d468d9c12e13.png)

Figure 3: Emergency Support Functions in post-disaster response and recovery of the community and the agencies responsible for each function.

The model is capable of generating a wide range of outputs corresponding to various emergency support functions and dynamic phenomena. 
As an example of model outputs, the following sub-sections present the progress of multiple ESFs (search and rescue, damage inspection and restoration of infrastructure systems) under different simulation scenarios. The base scenario corresponds to the situation where all of the identified agencies cooperate. In each of the other scenarios, one or multiple of the agencies are incapacitated, meaning that its operational crews are not present in the region, and its manager is not functional to cooperate with other manager agents.

### Search and Rescue
Figure 4 shows the progress of the search and rescue operation as a function of time. It shows the percentage of operation that is completed at a given time.

![sar1](https://user-images.githubusercontent.com/61154430/195953802-4db4ccf3-c7bb-4d64-b8bb-a2f220c8ee58.png)

Figure 4: Status of search and rescue operations when a key agency is incapacitated.

### Damage Inspection of Infrastructure Systems

Figure 5 shows the overall progress of damage inspection operations across all community infrastructure systems and lifelines under various scenarios.

![ins7](https://user-images.githubusercontent.com/61154430/195953818-45357061-9a2c-43b2-8fdb-04d338904434.png)

Figure 5: Overall status of damage inspection of community infrastructure systems and lifelines.

### Restoration of Infrastructure Systems
The overall restoration curve for the community infrastructure systems in various simulation scenarios is provided in Figure 6.

![res7](https://user-images.githubusercontent.com/61154430/195953786-513861cc-5d7d-4a37-9afd-4f7afce2bcdd.png)

Figure 6. Overall status of restoration of community infrastructure systems and lifelines.

[^3]: https://insurer.sharif.edu/

## Disclaimer
It should be noted that the aim of SIMDisasteR is not to provide an accurate forecast of the post-earthquake state of the community under these scenarios. Simulation models often cannot accurately predict the complete interaction and cooperation of responsible agencies in the post-disaster response and recovery of the community because it is impossible to accurately model the behaviors of various system components in such large and complex systems. SIMDisasteR can provide a valuable analysis tool for policymakers and disaster management authorities to evaluate various coordination mechanisms and characterize the impacts of neglecting organizational duties.


