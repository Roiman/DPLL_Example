# DPLL_Example
an example implementation of DPLL recursive algorithm for CS152 (AI) course at Minerva Schools at KGI.

The iPython notebook includes the required inputs (kb in the form of Conjunctive Normal Form (CNF).
It does not convert the KB to CNF, and the input kb has to be of the form:
{-A,B,E}, {-B, A}, {-E, A}, where "," between sets represent "and", and "or" within sets.

If the KB is satisfiable, returns True and the model found to satisfy it (other models are possible sometimes!)
If the KB is unsatisfiable, returns False and assignes "Free" to all literals in the model.
