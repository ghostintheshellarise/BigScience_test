<b>Task: Interaction Extraction between two biomedical entities</b>

My primary focus is trying to extract a relationship tuple and to present the relation along a structure similar to Predicate logic. 

For example, </br>
a predicate logic composite like, activate(X, Y)

Specific example: </br>
NS5A activate PI3K = <b>activate</b>(NSSA, PI3K)

With this construction, I am trying to build a GNN using PyNeuraLogic (or other libraries that provide similar functions) that enables logical deduction from facts.

The Jupyter notebook would outline how I handle the extraction of interaction.

The closest scheme which is similar to what I intende to do is the one used in bc5cdr.  However, there is a slight difference and I don't know if I should use that or create something different.

Advice is needed on what I should do next.  Any help is highly apprecaited.  Thanks.

(P.S.: Currently, I have a corpus that is composed of around 10K such sentences.  I am only half way through the clean-up.)
