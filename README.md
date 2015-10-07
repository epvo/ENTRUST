ENTRUST
=======
ENTRUST (ENgineering of TRUstworthy Self-adaptive sofTware) is the first tool-supported methodology for the engineering of high-integrity self-adaptive software systems and the dynamic generation of their assurance cases. 

ENTRUST includes methods for the development of verifiable controllers for self-adaptive systems, for the generation of design-time and runtime assurance evidence, and for the runtime instantiation of an assurance argument pattern devised specifically for these systems.

ENTRUST is a joint work carried out by the departments of Computer Science, University of York, UK and Linnaeus University, SWE.

Further information about ENTRUST, can be found [here] (http://www-users.cs.york.ac.uk/~simos/ENTRUST).


###Prerequisites
ENTRUST self-adaptive systems use verifiable controller and stochastic models, and formal assurance cases. The current version of ENTRUST is realised using the following technologies:

1. **Controller models** are specified as a network of interacting timed automata and are assessed at design-time for their correctness using [UPPAAL] (http://www.uppaal.org). At runtime, these models are executed by a [reusable virtual machine] (http://homepage.lnu.se/staff/daweaa/ActivFORMS/ActivFORMS.htm).

2. **Stochastic models** are parametric stochastic Markovian models and are specified in the [PRISM language] (http://www.prismmodelchecker.org/manual/ThePRISMLanguage/Introduction). At runtime, these models are verified using the probabilistic model checker [PRISM](http://www.prismmodelchecker.org).

3. **Assurance cases** are developed using the [Goal Structuring Notation](http://www.goalstructuringnotation.info), a community standard widely used in industry for developing assurance cases. 

**Installation instructions**

Simulator

ActivForms

Prism
