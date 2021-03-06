# BIOMD0000000233: Wilhelm2009_BistableReaction

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000233.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000233.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000233 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
**The smallest chemical reaction system with bistability**   
Thomas Wilhelm _BMC Systems Biology_ 2009;Sep 8;3:90.
[19737387](http://www.ncbi.nlm.nih.gov/pubmed/19737387) ,  
**Abstract:**   
Background  
Bistability underlies basic biological phenomena, such as cell division,
differentiation, cancer onset, and apoptosis. So far biologists identified two
necessary conditions for bistability: positive feedback and ultrasensitivity.  
Results  
Biological systems are based upon elementary mono- and bimolecular chemical
reactions. In order to definitely clarify all necessary conditions for
bistability we here present the corresponding minimal system. According to our
definition, it contains the minimal number of (i) reactants, (ii) reactions,
and (iii) terms in the corresponding ordinary differential equations
(decreasing importance from i-iii). The minimal bistable system contains two
reactants and four irreversible reactions (three bimolecular, one
monomolecular). We discuss the roles of the reactions with respect to the
necessary conditions for bistability: two reactions comprise the positive
feedback loop, a third reaction filters out small stimuli thus enabling a
stable 'off' state, and the fourth reaction prevents explosions. We argue that
prevention of explosion is a third general necessary condition for
bistability, which is so far lacking discussion in the literature. Moreover,
in addition to proving that in two-component systems three steady states are
necessary for bistability (five for tristability, etc.), we also present a
simple general method to design such systems: one just needs one production
and three different degradation mechanisms (one production, five degradations
for tristability, etc.). This helps modelling multistable systems and it is
important for corresponding synthetic biology projects.  
Conclusion  
The presented minimal bistable system finally clarifies the often discussed
question for the necessary conditions for bistability. The three necessary
conditions are: positive feedback, a mechanism to filter out small stimuli and
a mechanism to prevent explosions. This is important for modelling bistability
with simple systems and for synthetically designing new bistable systems. Our
simple model system is also well suited for corresponding teaching purposes.

  

This is a Systems Biology Markup Language (SBML) file, generated by MathSBML
2.9.0 [8-Oct-2008] 30-Jun-2009 17:26:58(GMT+00:59). SBML is a form of XML, and
most XML files will not display properly in an internet browser. To view the
contents of an XML file use the "Page Source" or equivalent button on you
browser.

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2012 The BioModels.net Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html) .  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


