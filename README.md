# BIOMD0000000325: minfb

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000325.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000325.git@20140916`


# Model Notes


This is the model of the minmal 2 feedback switch described in the article:  
**Synthetic conversion of a graded receptor signal into a tunable, reversible switch.**   
Santhosh Palani and Casim A. Sarkar, 2011, Molecular Systems Biology 7:480;
doi: [10.1038/msb.2011.13](http://dx.doi.org/10.1038/msb.2011.13)

The ability to engineer an all-or-none cellular response to a given signaling
ligand is important in applications ranging from biosensing to tissue
engineering. However, synthetic gene network switches have been limited in
their applicability and tunability due to their reliance on specific
components to function. Here, we present a strategy for reversible switch
design that instead relies only on a robust, easily constructed network
topology with two positive feedback loops and we apply the method to create
highly ultrasensitive (nH420), bistable cellular responses to a synthetic
ligand/receptor complex. Independent modulation of the two feedback strengths
enables rational tuning and some decoupling of steady-state (ultrasensitivity,
signal amplitude, switching threshold, and bistability) and kinetic (rates of
system activation and deactivation) response properties. Our integrated
computational and synthetic biology approach elucidates design rules for
building cellular switches with desired properties, which may be of utility in
engineering signal-transduction pathways.

This model is parametrised for a transcription factor and receptor feedback
strength of 3, TFs = 3 and Rs = 3. To reproduce figure 1 E, the parameters TFs
and Rs have to be varied accordingly.

Nomenclature for the model:  
L : Ligand  
R : Receptor  
C : Ligand-Receptor Complex  
I : Inactive Transcription Factor  
X : C bound to I  
A : Active Transcription Factor

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html) .  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


