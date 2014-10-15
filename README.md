# MODEL1011010000: Bruck2008_Glycolysis

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1011010000.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1011010000.git@20140916`


# Model Notes


**Exploring the effect of variable enzyme concentrations in a kinetic model of yeast glycolysis**   
Jozsef Bruck, Wolfram Liebermeister, Edda Klipp, Genome Inform 2008 20:1-14

**Abstract:**   
Metabolism is one of the best studied fields of biochemistry, but its
regulation involves processes on many different levels, some of which are
still not understood well enough to allow for quantitative modeling and
prediction. Glycolysis in yeast is a good example: although high-quality
quantitative data are available, well-established mathematical models
typically only cover direct regulation of the involved enzymes by metabolite
binding. The effect of various metabolites on the enzyme kinetics is
summarized in carefully developed mathematical formulae. However, this
approach implicitly assumes that the enzyme concentrations themselves are
constant, thus neglecting other regulatory levels - e.g. transcriptional and
translational regulation--involved in the regulation of enzyme activities. It
is believed, however, that different experimental conditions result in
different enzyme activities regulated by the above mechanisms. Detailed
modeling of all regulatory levels is still out of reach since some of the
necessary data - e.g. quantitative large scale enzyme concentration data sets
- are lacking or rare. Nevertheless, a viable approach is to include the
regulation of enzyme concentrations into an established model and to
investigate whether this improves the predictive capabilities. Proteome data
are usually hard to obtain, but levels of mRNA transcripts may be used instead
as clues for changes in enzyme concentrations. Here we investigate whether
including mRNA data into an established model of yeast glycolysis allows to
predict the steady state metabolic concentrations for different experimental
conditions. To this end, we modified an established ODE model for the
glycolytic pathway of yeast to include changes of enzyme concentrations.
Presumable changes were inferred from mRNA transcript level measurement data.
We investigate how this approach can be used to predict metabolite
concentrations for steady-state yeast cultures at five different oxygen levels
ranging from anaerobic to fully aerobic conditions. We were partly able to
reproduce the experimental data and present a number of changes that were
necessary to improve the modeling result.

Further modifications to this model and improved data fit will be presented
soon.

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
or not. .  
  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


