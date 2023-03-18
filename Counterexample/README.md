# Object-Role-Modeling-And-Ambiguity

The following ORM Diagram exposes a syntactic flaw in the graphical component of Obect-Role Modeling.

![Alt text](../Images/JoinSubsetConstraint-Counterexample.png?raw=true "Counterexample")

1. It seems to lack one of the required 2 links indicating the first and second arguments of the first sequence of the topmost Join Subset Constraint (only one is visible, emanating from the bottom right of the diagram in the fact type, “Round the World Ticket visits Country”); and

2. We don’t know whether the Join Subset Constraint reads:

![Alt text](../Images/CounterexampleVerbalisation1.png?raw=true "Counterexample Verbalisation Possibility One")

...or...

![Alt text](../Images/CounterexampleVerbalisation2.png?raw=true "Counterexample Verbalisation Possibility Two")

NB The Join Subset Constraint is actually drawn correctly, but the first argument of the first sequence is hidden below the first argument of the second sequence, which has the arrow. The syntax of Object-Role Modeling does not have the ability to disambiguate/resolve the problem, leaving the interpreter with the notion that the diagram is possibly drawn incorrectly. An independed interpreter (under model theory) is able to assign whatever meaning they like to the three-spoke otherwise-Join Subset Constraint, including:
1. The interpretation that the model is drawn incorrectly;
2. Some other meaning/interpretation conjured by the interpreter, which may be valid/consistent etc

I.e. The limitations of the graphical ORM notation leads to ambiguity.
