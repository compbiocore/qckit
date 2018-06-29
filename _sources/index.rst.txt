
.. qckit index file, created by `ablog start` on Fri Jun 29 15:28:21 2018.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

qckit
========

Quality control toolkits for genomic sequencing data in RA.

About
------

This is the landing page for the Computational Biology Core's suite of quality control R packages for genomic sequencing data. At the moment we are working on:

	* qckitfastq - Quality control for FASTQ format data
	* qckitalign - Quality control for reference-aligned reads
	* qcdb - Database of quality control results from publically available experiments
	* qcviz - Visualization of quality control results.

Planned packages include qckitrnaseq, for RNA-seq specific data, and qckitsinglecell - for single-cell RNA-seq data.

Purpose
-------

Quality control is a vital but often neglected step in experiments involving genomic and transcriptomic sequencing data. While many researchers utilize the popular tool fastqc for quality control of the FASTQ formatted sequencing data, the end goal for this data usually involves many intermediary and computationally difficult steps. It is important to run quality control at these intermediary steps as well, yet tools to do so become sparse at that level. In addition, assessing quality at each of these steps is often dependent on the researcher's domain expertise and system familiarity.

The goal of the qckit project is to make running & assessing quality control on complicated bioinformatics pipelines easy and accessible. To do this we work towards three key objectives. First, we aim to provide quality control packages (in R) for all of the more common intermediary steps. Second, we aim to provide a public database of qc results against which a researcher can compare the quality control results of their experiments for similar systems. Finally, we aim to provide a visualization tool that interfaces with the qckit packages and qc database so that researchers can immediately assess results quality without needing extensive domain expertise.


.. `toctree` directive, below, contains list of non-post `.rst` files.
   This is how they appear in Navigation sidebar. Note that directive
   also contains `:hidden:` option so that it is not included inside the page.

   Posts are excluded from this directive so that they aren't double listed
   in the sidebar both under Navigation and Recent Posts.

.. toctree::
   :hidden:

