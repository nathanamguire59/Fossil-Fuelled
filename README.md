# Fossil Fuelled

Fossil Fuelled is a first-person shooter developed in Unreal Engine. 

## Technical Overview
* **Scalable Weapon Systems:** Structured the weapon logic in a base class, enabling rapid implementation of new guns without altering core systems.
* **Responsive Controls:** Focused on refining player controls to ensure actions such as reloading and weapon switching are consistent, responsive, and free of input conflicts.

## Reflection on Development
This project was a valuable learning experience in maintaining clean, scalable Blueprint logic while delivering a polished player experience.

Upon reviewing the state-checking logic I implemented, I identified an opportunity for improvement. Although the current system is effective for small projects, the nested Branch node structure becomes difficult to debug as additional states, such as vaulting or sliding, are introduced. In future iterations, I would implement a Finite State Machine (FSM) to manage player transitions more efficiently. This approach would reduce complexity and improve maintainability as the project scales.
