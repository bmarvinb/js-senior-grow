**Topics**
* What is Software Architecture?
* Software elements (modules);
* Relations among them (connections and communication protocols);
* Properties of both elements and relations (quality attributes);
* Constraints.
* Steps to define Architecture?
* Identify Stakeholders (to communicate with);
* Understand the Problem, Functional Requirements (solve a valid business problem or have a recognizable return on investment (ROI));
* Identify Design Elements and their Relationships (boundaries and context of the system);
* Evaluate the Architecture Design (Non-Functional Requirements, quality attributes, constraints);
* Prioritize quality attributes (trade-off analysis, suffer ones for others);
* Transform the Architecture Design (quality attributes oriented - optimization of solutions using various patterns);
* Document the results (to facilitate communication between stakeholders).
* Good Architecture principles?
* SOLID;
* Separation of concerns (SoC): separate your application into different sections, and each section will address a separate concern;
* System Service Components should be business focused. Security, communications, or system services like logging, profiling, and configuration should be abstracted in the separate components;
* Single Responsibility principle: Every module for a single functionality;
* Principle of Least Knowledge (Or Law of Demeter): An object should have limited knowledge about other objects;
* DRY;
* KISS;
* Minimize upfront design: Only design what is necessary. YAGNI ("You ain’t gonna need it"). think Return for Investment (ROI);
* Composition over Inheritance while Reusing the Functionality;
* Identify Components and Group them in Logical Layers;
* Define the Communication Protocol, Data Format between Layers;
* Design Exceptions and Exception Handling Mechanism;
* Naming Convention.