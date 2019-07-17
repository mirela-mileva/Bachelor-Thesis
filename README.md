# Minimizing Mealy Machines With Dependent Inputs


The following Bachelor Thesis Project introduces a pioneering algorithm for Minimizing Mealy Machines w.r.t. a disabling relation, a binary relation over some finite input alphabet. The project consists of a paper with theoretical foundations of the algorithm and its Java implementation.

#### About

Mealy Machines are Finite State Machines, whose transitions determine for each combination of a state and input, an output symbol. Besides classical algorithms for minimization of Mealy Machines which rely on trace equivalence and use partition refinement, the algorithm presented in the project establishes a more general approach that goes beyond state merging. The main idea is to use the disabling relation to perform optimal minimization while preserving the behavior of the initial Mealy Machine. 

A core component of the implementation is the usage of the AutomataLib library, which provides support for modelling graph-based structures, different automata theory algorithms, as well as serialization and visualisation via GraphViz.

### Build Instructions

For running and future developing of the algorithm presented in the paper, the following installations are required after simply cloning the **src** folder:

- JDK 8
- Apache Maven 3.6.1 or later 
- <a href="https://graphviz.gitlab.io/download/" target="_blank">GraphViz Library</a>
- <a href="http://www.alexander-merz.com/graphviz/" target="_blank">Java-based Parser for Graphviz Documents</a>
- AutomataLib (<a href="https://github.com/LearnLib/automatalib#build-instructions" target="_blank">Build Instructions</a>)

Because either the libraries are not in the Central Maven Repository or a SNAPSHOT version is used in the project, after download they must be installed in the local Maven-Cache with `$ mvn install`.

#### Documentation

- The project contains an extensive API documentation.
- <a href="http://learnlib.github.io/automatalib/maven-site/latest/apidocs/" target="_blank">AutomataLib documentation</a>.

### Mailing Lists

General question regarding the project can be sent to <mirela.mileva66@gmail.com>.

### Maintainers

- <a href="https://git.rwth-aachen.de/mirela.mileva66" target="_blank">Mirela Mileva</a>
