# Physical-Design-of-Decision-Tree-Algorithm

## Introduction
- This project demonstrates the ASIC implementation of a Decision Tree model for hardware acceleration. It involves:

a) Design entry using Verilog.

 
b) Synthesis of the RTL design using Cadence Genus.

 
c) Physical implementation (floorplanning, placement, and routing) using Cadence Innovus.



## Synthesis Using Genus Tool

### 1. Schematic of generated netlist:

![image](https://github.com/user-attachments/assets/efafbf5a-3908-4465-bd8d-975663cf026c)


### 2. Cell Count and Area:

![image](https://github.com/user-attachments/assets/6ba2a84e-c1b6-49d5-8308-4fb2216b4edb)


### 3. Power Analysis:

![image](https://github.com/user-attachments/assets/35d7c52f-e87d-4f86-9c38-94fba76de747)


### 4. Timing Information:

![image](https://github.com/user-attachments/assets/606c06f8-645c-4bbf-9402-b378d75c49a0)


## Physical Design Using Innovus


### 1. Floorplan and Power Planning


#### Die Area Planning:
![image](https://github.com/user-attachments/assets/0a1d3ba2-1ed7-404d-9cc9-f1499988d9b3)

#### Power Ring Formation:

![image](https://github.com/user-attachments/assets/25964a34-72ac-4a55-bc4a-692551ab0d75)


#### Power Stripe Formation:

![image](https://github.com/user-attachments/assets/fac757c2-eb49-4145-b46a-07f9cb197d6e)


### 2. Placement

#### End Cap Insertion:

![image](https://github.com/user-attachments/assets/6df760af-d08e-4fc6-b04f-d98c08b6a3bb)

#### Well Tap Insertion:

![image](https://github.com/user-attachments/assets/1f8fea10-4361-4b4f-9642-323d7cffa507)

#### Standard Cell Placement:

![image](https://github.com/user-attachments/assets/4a01f6e3-b9f1-45f5-a4b3-e4535b2e1004)

### 3. Routing

![image](https://github.com/user-attachments/assets/b22708a3-e083-44f0-a3f2-721a9eb70f9f)


## Conclusion
- Decision tree implementation with four input features (featureA, featureB, featureC, featureD) and a 3-bit output class predictor.
- Fully synthesized and implemented in a 90nm technology node.
- Floorplanning, placement, and routing steps performed to achieve a complete physical layout.














