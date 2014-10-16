# MODEL8683876463: Priebe1998_VentricularArrhythmias

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL8683876463.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL8683876463.git@20140916`

## Usage

Importing the model package.

`import MODEL8683876463 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
**Simulation study of cellular electric properties in heart failure**   
Priebe L, Beuckelmann DJ. _Circ Res._ 1998; 82(11):1206-23
[9633920](http://www.ncbi.nlm.nih.gov/pubmed/9633920) ,  
**Abstract:**   
Patients with severe heart failure are at high risk of sudden cardiac death.
In the majority of these patients, sudden cardiac death is thought to be due
to ventricular tachyarrhythmias. Alterations of the electric properties of
single myocytes in heart failure may favor the occurrence of ventricular
arrhythmias in these patients by inducing early or delayed
afterdepolarizations. Mathematical models of the cellular action potential and
its underlying ionic currents could help to elucidate possible arrhythmogenic
mechanisms on a cellular level. In the present study, selected ionic currents
based on human data are incorporated into a model of the ventricular action
potential for the purpose of studying the cellular electrophysiological
consequences of heart failure. Ionic currents that are not yet sufficiently
characterized in human ventricular myocytes are adopted from the action
potential model developed by Luo and Rudy (LR model). The main results
obtained from this model are as follows: The action potential in ventricular
myocytes from failing hearts is longer than in nonfailing control hearts. The
major underlying mechanisms for this prolongation are the enhanced activity of
the Na+-Ca2+ exchanger, the slowed diastolic decay of the [Ca2+]i transient,
and the reduction of the inwardly rectifying K+ current and the Na+-K+ pump
current in myocytes of failing hearts. Furthermore, the fast and slow
components of the delayed rectifier K+ current (I(Kr) and I(Ks), respectively)
are of utmost importance in determining repolarization of the human
ventricular action potential. In contrast, the influence of the transient
outward K+ current on APD is only small in both cell groups. Inhibition of
I(Kr) promotes the development of early afterdepolarizations in failing, but
not nonfailing, myocytes. Furthermore, spontaneous Ca2+ release from the
sarcoplasmic reticulum triggers a premature action potential only in failing
myocytes. This model of the ventricular action potential and its alterations
in heart failure is intended to serve as a tool for investigating the effects
of therapeutic interventions on the electric excitability of the human
ventricular myocardium.

This model was taken from the [CellML
repository](http://www.cellml.org/models) and automatically converted to SBML.  
The original model was: [ **Priebe, Beuckelmann. (1998) - version02**
](http://www.cellml.org/models/priebe_beuckelmann_1998_version02)  
The original CellML model was created by:  
**Lloyd, Catherine, May**   
c.lloyd@auckland.ac.nz  
The University of Auckland  
Auckland Bioengineering Institute  

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not..  
  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


