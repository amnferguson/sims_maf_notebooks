This repository contains a set of sims_maf ipython notebooks, demonstrating various uses and capabilities of MAF. 

Most of these notebooks assume you have installed and setup the LSST simulations package.  For instructions on installing and setting up MAF see here:
https://confluence.lsstcorp.org/display/SIM/MAF+Installation+and+Initial+Examples

These notebooks require the OpSim sqlite database enigma_1189_sqlite.db, it can be downloaded from here:
http://ops2.tuc.noao.edu/runs/enigma_1189/data/enigma_1189_sqlite.db.gz


# Notebook Summaries

### Introductory Notebooks
* [IntroductionNotebook.v3.ipynb](https://github.com/lsst-sims/sims_maf_notebooks/blob/master/notebooks/IntroductionNotebook.v3.ipynb):  Our introductory notebook, including installation instructions.
* [Slicers.v3.ipynb](https://github.com/lsst-sims/sims_maf_notebooks/blob/master/notebooks/Slicers.v3.ipynb):  Shows how the same metric can be run with three different slicers to produce different outputs.
* [TestNotebook.v3.ipynb](https://github.com/lsst-sims/sims_maf_notebooks/blob/master/notebooks/TestNotebook.v3.ipynb):  Test that ipython is working and you can load the MAF modules.

### Advanced Capabilities
* [Stackers.v3.ipynb](https://github.com/lsst-sims/sims_maf_notebooks/blob/master/notebooks/Stackers.v3.ipynb):  Example of calculating and adding a new column to the OpSim output "on-the-fly" with MAF.  Here, we calculate the hour angle of each pointing and then look at the distribution.
* [WritingNewMetric.v3.ipynb](https://github.com/lsst-sims/sims_maf_notebooks/blob/master/notebooks/WritingNewMetric.v3.ipynb):  A guide on how you can write and add your own algorithm into MAF by sub-classing an existing metric.
* [UsingMetricBundleData.v3.ipynb](https://github.com/lsst-sims/sims_maf_notebooks/blob/master/notebooks/UsingMetricBundleData.v3.ipynb):  Example of saving/restoring analysis and then adjusting and combining plots.

### Static Science Notebooks
* [DepthGoodSeeing.v3.ipynb](https://github.com/lsst-sims/sims_maf_notebooks/blob/master/notebooks/DepthGoodSeeing.v3.ipynb):  Using SQL constraints to compare coadded depth and coadded depth of only visits taken under good seeing conditions.
* [DepthPerYear.v3.ipynb](https://github.com/lsst-sims/sims_maf_notebooks/blob/master/notebooks/DepthPerYear.v3.ipynb):  An example of using SQL constraints to see the evolution of the coadded depth through the survey.
* [Dithers.v3.ipynb](https://github.com/lsst-sims/sims_maf_notebooks/blob/master/notebooks/Dithers.v3.ipynb):  MAF includes several potential dithering schemes.  This notebook demonstrates those dither patterns and compares their effect on the resulting power spectrum.
* [NVisitsCoadd_AllFilters_DitherComparison.v3.ipynb](https://github.com/lsst-sims/sims_maf_notebooks/blob/master/notebooks/NVisitsCoadd_AllFilters_DitherComparison.v3.ipynb):  Examines the number of visits in each filter as well as comparing dithered and undithered surveys.


### Solar System and Astrometry Notebooks
* [AstrometryMetrics.v3.ipynb](https://github.com/lsst-sims/sims_maf_notebooks/blob/master/notebooks/AstrometryMetrics.v3.ipynb):  Example of running our proper motion and parallax metrics.  

### Transient Notebooks
* [TransientMetric.v3.ipynb](https://github.com/lsst-sims/sims_maf_notebooks/blob/master/notebooks/TransientMetric.v3.ipynb):  Example of our transient metric where you can set a simple transient light-curve shape and set a variety of detection criteria to measure the fraction of such transients LSST can recover.

### Variable Notebooks
* Our variable metrics are in the [sims_maf_contrib](https://github.com/LSST-nonproject/sims_maf_contrib) repo. A notebook example of them can be found [here](https://github.com/LSST-nonproject/sims_maf_contrib/blob/master/other/Variability%20Metrics.ipynb).

### etc
* [Completeness_complexMetric.v3.ipynb](https://github.com/lsst-sims/sims_maf_notebooks/blob/master/notebooks/Completeness_complexMetric.v3.ipynb):  An example of the completeness metric which measures how many observations a field received compared to how many were requested.

