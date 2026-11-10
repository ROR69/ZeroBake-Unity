# ZeroBake-Unity
ZeroBake Brand 
==================================================
ZERO-BAKE REACTIVE NAVIGATION SYSTEM
==================================================
Author: ZeroBake / Independent Developer
Unity Version Required: 2022.3 LTS or higher.

OVERVIEW:
ZeroBake Reactive Navigation is a lightweight, zero-bake, heuristic-driven navigation framework. It allows agents to navigate dynamic environments, avoid obstacles via localized raycast sensors, and execute fluid movement without the need for pre-calculated NavMeshes.

QUICK START IN 3 STEPS:
1. Prepare your Agent GameObject:
   - Ensure it has a CharacterController component attached.
   - Attach the 'AgentPerception', 'AgentMover', 'ReactiveSteeringBrain', and 'ReactiveAgent' components.
   - Configure the 'Obstacle Layer' mask in the AgentPerception component to match your environment walls.

2. Set up your Environment:
   - Assign your walls and physical barriers to the obstacle layer you chose in step 1.
   - Place a Target transform in your scene.

3. Assign and Play:
   - Drag your Target object into the 'Target' slot of the ReactiveAgent component.
   - Hit Play!

COMPONENTS INCLUDED:
- IAgentBrain: Modular interface for custom logic brains.
- AgentPerception: Multi-raycast proximity sensor.
- ReactiveSteeringBrain: Default heuristic steering controller with orthogonal evasion and anti-stuck supervisor.
- AgentMover: Kinematic movement controller powered by CharacterController.
- ReactiveAgent: Main orchestrator component.

SUPPORT:
If you encounter any issues or have feature requests, please reach out via the support email listed on our publisher page. Thank you for your support!
