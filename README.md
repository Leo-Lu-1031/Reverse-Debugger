# Reverse-Debugger

## Helpful Links:
[Dissertation in Progress](https://www.overleaf.com/project/6ad4efe86120db704debf23d/share#adaa21c6b410250b5809110719e43e4c4e91581f2ea598d3)

## Work Log:
### Week 1: 
Finished project proposal

### Week 2: 
Work package 1 almost completed: Formalized Python grammar subset (paraphrased and modified from), formalized success criteria (rephrased from Akgul and Mooney, added control flow information into program state to capture ifs and whiles). DID NOT YET look at libraries for implementing AST parses and command line debuggers so will lump that into next work package <br>
Discoveries / Issues: <br>
A previously undiscovered side effect of this is that for loops are useless in this language since iterables are by nature heap objects. Therefore I've made the executive decision to exclude them from the simple version of the program. <br>
Sources: <br>
[Python Semantics](https://docs.python.org/3/reference/grammar.html) <br>

## Work Plans:
### Week 3:
Finish command line debugger (From my research it seems this work package is easier than it seems)
