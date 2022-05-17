# tree automaton determinization

forked from YNedderhoff

How to run program?

```
python <program-name>.py -s <startsymbols> -p <productions>
```

The startsymbols file lists the startsymbols per line. The grammar is stored in the productions file. It has to be a regular tree grammar (RTG). The productions file stores the productions in Tiburon format.

* n0 → A(n1,n2) : non-terminal n0 goes to the tree rooted in A with nonterminals n1 and n2
* n1 → a : non-terminal n1 goes to the leaf symbol a
* n2 → b : non-terminal n2 goes to the leaf symbol b

For details see the example files "startsymbols.txt" and "productions.txt"

As output you'll get the states and productions of the equivalent deterministic tree automaton.
