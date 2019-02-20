# IEEESoftware-BankConciliation
This repository contains the complete data of the evaluation reported in (a submitted) IEEE Software paper entitled "A Multi-platform Architectural Conformance Solution for the Microservice Architecture" 

The Architectural Specification file presents the architectural specification in DCL+ of the evaluted application. In this file are defined each microservice definition with its communication constraints and structural design.  

The Extracted Communications folder contains the communications extracted from the Node-Middleware system with their graphical representation.

The Violated Communications folder contains the final report of the violated communications returned by DCL+check tool and its graphical representation, that illustrates the specific modules that occurred communication violations and their respective identification represented in a table. 

The Structural Design Violations folder is composed by three main files. The Architectural Specification file describes all the specification of strutural design from eleven microservices evaluated. The Violations file presents the final report of structural design violations returned by DCL+check from each microservice. Finally, the DSM file shows the Design Structural Matrix from the defined modules on each microservice, that shows the relationship between specific modules with the results of detected violations. In the matrix, the red cells represent absence of dependency between modules and orange cell divergence.
