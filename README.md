

Chen2004 - Cell Cycle Regulation

This is a hypothetical model of cell cycle that describes the molecular
mechanism for regulating DNA synthesis, bud emergence, mitosis, and cell
division in budding yeast.

This model is described in the article:

[Integrative analysis of cell cycle control in budding
yeast.](http://identifiers.org/pubmed/15169868)

Chen KC, Calzone L, Csikasz-Nagy A, Cross FR, Novak B, Tyson JJ

Mol. Biol. Cell. [2004 Aug; Volume: 15 (Issue: 8 )] Page info: 3841-62

Abstract:

The adaptive responses of a living cell to internal and external signals are
controlled by networks of proteins whose interactions are so complex that the
functional integration of the network cannot be comprehended by intuitive
reasoning alone. Mathematical modeling, based on biochemical rate equations,
provides a rigorous and reliable tool for unraveling the complexities of
molecular regulatory networks. The budding yeast cell cycle is a challenging
test case for this approach, because the control system is known in exquisite
detail and its function is constrained by the phenotypic properties of >100
genetically engineered strains. We show that a mathematical model built on a
consensus picture of this control system is largely successful in explaining
the phenotypes of mutants described so far. A few inconsistencies between the
model and experiments indicate aspects of the mechanism that require revision.
In addition, the model allows one to frame and critique hypotheses about how
the division cycle is regulated in wild-type and mutant cells, to predict the
phenotypes of new mutant combinations, and to estimate the effective values of
biochemical rate constants that are difficult to measure directly in vivo.

The model reproduces the time profiles of the different species in Figure 2 of
the paper. The figure depicts the cycle of a daughter cell. Since the Mass
Doubling Time (MDT) is 90 minutes, time t=90 from the model simulation will
correspond to time t=0 in the paper. The model was successfully tested using
MathSBML and SBML odeSolver.

To create a valid SBML file, a local parameter k=1 was added in the reaction
'Inactivation_274_CDC20'. Also, in order to annotate the protein and to have
the interaction in the reaction graph to match figure 1 of the article, the
reaction rate constants k_{mad2}, k_{bub2} and k_{lte1} are considered as
species and renamed as MAD2, BUB2 and LTE1 in the model.

This model is hosted on [BioModels Database](http://www.ebi.ac.uk/biomodels/)
and identified by:
[BIOMD0000000056](http://identifiers.org/biomodels.db/BIOMD0000000056) .

To cite BioModels Database, please use: [BioModels Database: An enhanced,
curated and annotated resource for published quantitative kinetic
models](http://identifiers.org/pubmed/20587024) .

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

