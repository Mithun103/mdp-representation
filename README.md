# MDP REPRESENTATION

## AIM:
the aim of this experiment is to create a Markov decision process (MDP) representation and implementing python to model the decision making process in a agriculture  automatic irrigation system

## PROBLEM STATEMENT:

### Problem Description
Agricultural irrigation in the past has been a common problem for inefficient water use, Which would result in crops having inadequate or excessive water resources, using up a lot more water, and even takes on a more expensive cost.
Therefore, an intelligent agricultural irrigation system must be developed in order to achieve agricultural water efficiency by minimizing the water waste. The system should provide the recommended water resources to the plants to maximize the plant's growth based on the current climate of the land, so that it could contribute to the sustainability of agriculture, food security, and agriculture. 

### State Space
- Moisture conditions in distinct zones of the field
- Current weather circumstances (such as temperature and humidity)
- Weather forecast information (such as anticipated precipitation or temperature)
- Type of crop growing in the field and the crop growth stage
- The time of the day

### Sample State
- Moisture levels: 30% in zones
- Current weather: Sunny, 28°C, 60% humidity
- Weather forecast: Rain expected in 6 hours
- Crop type and stage of growth: Corn, early stage of growth
- Time of day: 10:00 a.m


### Action Space
- Apply a certain water to zone 
- Skip watering some zones


### Sample Action
Action: Water Zone and skip watering Zone 

### Reward Function
The reward function is formulated to promote efficient water use practices and sustainable crop growth. 
- Positive reward for maintaining adequate soil moisture levels
- Negative reward for over-watering or under-watering (which could result in wasted water or crop stress)


### Graphical Representation
![image](https://github.com/user-attachments/assets/824842b7-ecf1-4024-8bd5-7964398236eb)


## PYTHON REPRESENTATION:
![image](https://github.com/user-attachments/assets/8c6edc28-e642-4102-9605-459854c5f64f)


## OUTPUT:
![image](https://github.com/user-attachments/assets/2172c6b1-2db4-4804-a505-122e20d7e178)


## RESULT:
Thus we successfully created Markov decision process (MDP) representation and implemented python to model the decision making process in a agriculture automatic irrigation system


