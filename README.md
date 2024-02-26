# COT-Study

This repository is a central node for all the projects that we come up to in the course **Code Transformation and Optimization** at *Politecnico di Milano* a.y. 2023/2024.

## Project structure 

All the projects presented in this repository will preferrably follow a "software engineering" structure.

Indeed each project must be presented with a document which indicates exactly the problem to solve, with in-detail description of the algorithms implemented and a visual schematic ( I personally suggest a UML representation using [LucidChart](https://www.lucidchart.com/pages/) ) of the classes implemented, with its attributes and methods.

It should also be clear how to compile and run both the program and its tests.

## Which aspects are to consider

In order to create an effective implementation of each project (with the final objective in mind to hopefully put all the components together in a compiler for a single language), the following characteristics are required:

* *readibility* : the code must be readable from a person external to the project, so it should contain meaningful names for the variables, extensive comments (ideally each component should be commented with its functionalities), and preferrably no spaghetti codification
* *robustness* : if the input is formatted wrongly it should be able to "gracefully terminate" and not throw a system error to the screen
* *modularity* : each component should implement one and only one functionality, with extensive explaination of its public interface
* *efficiency* : we should always ask ourselves if there is a faster way or a better data structure when writing our code

## Testing

This is delicate and requires its own section. The problem should be carried on in parallel to its own test developement (one could also use the so-called "test-driven developement" approach). 

The tests need to be extensive, with its own dedicated documentation, covering all possible branches of the code (even the non-correct ones), and should be easily modifiable if needed (e.g. adding a new test).
