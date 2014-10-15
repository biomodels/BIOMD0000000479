# BIOMD0000000479: MODEL1305280000

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000479.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000479.git@20140916`


# Model Notes


Croft2013 - GPCR-RGS interaction that compartmentalizes RGS activity

Through modelling studies, the classic quaternary complex (ligand-GPCR-G-RGS)
has been extended to include an additional layer of regulation through GPCR-
RGS interactions, which facilitate the compartmentalization of RGS activity
into the plasma membrane and non-plasma compartments.

This model is described in the article:

[A physiologically required G protein-coupled receptor (GPCR)-regulator of G
protein signaling (RGS) interaction that compartmentalizes RGS
activity.](http://identifiers.org/pubmed/23900842)

Croft W, Hill C, McCann E, Bond M, Esparza-Franco M, Bennett J, Rand D, Davey
J, Ladds G.

J Biol Chem. 2013 Sep 20;288(38):27327-42.

Abstract:

G protein-coupled receptors (GPCRs) can interact with regulator of G protein
signaling (RGS) proteins. However, the effects of such interactions on signal
transduction and their physiological relevance have been largely undetermined.
Ligand-bound GPCRs initiate by promoting exchange of GDP for GTP on the Gα
subunit of heterotrimeric G proteins. Signaling is terminated by hydrolysis of
GTP to GDP through intrinsic GTPase activity of the Gα subunit, a reaction
catalyzed by RGS proteins. Using yeast as a tool to study GPCR signaling in
isolation, we define an interaction between the cognate GPCR (Mam2) and RGS
(Rgs1), mapping the interaction domains. This reaction tethers Rgs1 at the
plasma membrane and is essential for physiological signaling response. In vivo
quantitative data inform the development of a kinetic model of the GTPase
cycle, which extends previous attempts by including GPCR-RGS interactions. In
vivo and in silico data confirm that GPCR-RGS interactions can impose an
additional layer of regulation through mediating RGS subcellular localization
to compartmentalize RGS activity within a cell, thus highlighting their
importance as potential targets to modulate GPCR signaling pathways.

**Author's comment on reproducing the plots:**   
To reproduce dose-response plots in the publication, the model is simulated
with 12 different ligand concentrations (see parameter Ligand_conc).  
For each ligand concentration, a single value corresponding to total amount of
output must be obtained, by calculating the area under the curve of the
trajectory of species z3, from time=0 to time=30.  
These total output values are then used to build a dose-response plot (authors
used GraphPad Prism).  
Mutant strains are simulated with alternative parameter values or initial
conditions specified in the Supplementary Material.

This model is hosted on [BioModels Database](http://www.ebi.ac.uk/biomodels/)
and identified by:
[BIOMD0000000479](http://identifiers.org/biomodels.db/BIOMD0000000479) .

To cite BioModels Database, please use: [BioModels Database: An enhanced,
curated and annotated resource for published quantitative kinetic
models](http://identifiers.org/pubmed/20587024) .

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.


