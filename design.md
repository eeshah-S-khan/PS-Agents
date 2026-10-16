ICS 3202 Practical Exercise 3: Designing a Searching Agent

 Group Members
 Eeshah Sabir Khan  192089 
 Abdulle Abdullahi Faduma  191648 

Question 1: PEAS Framework and Environment Properties
### Agent description
The agent is a self-driving trailer that carries cargo along Kenya's highway network, for example from Nairobi to Kisumu, without a human driver.

### PEAS

| Component | Description |
|-----------|-------------|
| **Performance measure** | Reaching the destination with the cargo undamaged. Taking the shortest distance. Avoiding collisions. Obeying traffic rules and speed limits. Using fuel efficiently. Delivering on time. |
| **Environment** | Kenyan highways and the towns along them. Other vehicles such as cars, matatus and trucks. Pedestrians and animals on the road. Road signs, junctions and roundabouts. Weather (rain, fog). Road conditions like potholes and roadworks. Traffic police. |
| **Actuators** | Steering, accelerator, brakes, gear system, indicators, headlights, horn, windscreen wipers. |
| **Sensors** | Cameras, GPS, radar/lidar, ultrasonic sensors, speedometer, odometer, fuel gauge, rain sensor, cargo weight sensor. |

### Environment properties

| Property | Classification | Justification |
|----------|----------------|---------------|
| Observability | Partially observable | Information about the environment is not fully available to the trailer. Its sensors have limited range and can be noisy, so it cannot see around bends, hidden potholes or what other drivers will do. It must make informed guesses about the road ahead. |
| Determinism | Stochastic | The next state does not depend only on the current state and the trailer's action. Other drivers, weather, animals crossing and breakdowns are beyond the agent's control. |
| Episodic vs sequential | Sequential | The choice of action depends on previous actions. Earlier decisions on route, speed and fuel use affect what the trailer can do later in the trip. |
| Static vs dynamic | Dynamic | The environment keeps changing while the trailer is selecting an action, because other vehicles, pedestrians and traffic conditions are always moving. |
| Single vs multi-agent | Multi-agent | The trailer operates with other agents in the environment: other drivers, matatus, trucks, pedestrians and traffic police. |

Question 2: Directed Graph and Search Tree


Question 3: Optimal Path from Nairobi to Kisumu


 Teamwork Evidence
