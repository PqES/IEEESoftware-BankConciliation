# IEEESoftware-BankConciliation
This repository contains the complete data of the evaluation reported in (a submitted) IEEE Software paper entitled "Applying a Multi-plataform Architectural Conformance Solution in a Real-world Microservice-based System" 

The Architectural Specification file presents the architectural specification in DCL+ of the evaluted application. In this file, we defined each microservice with its communication constraints and structural design.

[Visit architecturalSpecification.txt](architecturalSpecification.txt)


The Extracted Communications folder contains the communications extracted from the Node-Middleware system with their graphical representation.

[Visit folder](Extracted%20Communications)


The Violated Communications folder contains the final report of the violated communications returned by DCL+check tool and its graphical representation, that illustrates the specific modules that occurred communication violations and their respective identification represented in a table. 

[Visit folder](Violated%20Communications)


The Structural Design Violations folder is composed by three main files. The Architectural Specification file describes all the specification of strutural design from eleven microservices evaluated. The Violations file presents the final report of structural design violations returned by DCL+check from each microservice. Finally, the DSM file shows the Design Structural Matrix from the defined modules on each microservice, that shows the relationship between specific modules with the results of detected violations. In the matrix, the red cells represent absence of dependency between modules and orange cell divergence.

[Visit folder](Structural%20Design%20Violations)
