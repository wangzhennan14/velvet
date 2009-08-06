contrib/ guide:

In this directory you will find software developed by various programmers which could be useful to Velvet users:

>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
- afg_handling by Simon Gladman (Simon.Gladman@csiro.au)

These two scripts allow you to examine the (generally) large .afg files which can be produced by Velvet

	asmbly_splitter allows you to choose a specific scaffold from the assembly and produce a self-standing .afg file for that scaffold.

	snp_view produces an ASCII pileup display of the reads above a given locus


>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
- layout by Paul Harrison (pfh@logarithmic.net)

This script converts a (Last)Graph file into a .dot file, which can then be converted into an image by GraphViz (www.graphviz.org). This allows you to directly observe the topology of a graph. 

>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
- VelvetOptimiser by Simon Gladman (Simon.Gladman@csiro.au)

This script automatically finds the optimal parameter settings for Velvet. 

>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
- estimate-exp_cov by Torsten Seeman (torsten.seemann@infotech.monash.edu.au)

This script automatically determines the expected coverage value as described in the manual, and displays an ASCII histogram, thus obviating the need to start R for each Velvet run.