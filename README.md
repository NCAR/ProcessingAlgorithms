              RAF Technical Note: Processing Algorithms

[![DOI:10.26023/zc3gpm25](https://img.shields.io/badge/DOI-10.26023/zc3gpm25-brightgreen.svg)](<https://doi.org/10.26023/zc3gpm25>)

This repository contains the text files for the RAF Technical Note on
processing algorithms that are used for processing data collected
on the RAF research aircraft. The variables that appear in archived
data are defined here, and the algorithms used in their calculation
are described. This document does not describe the instrumentation
used, but there are many links to such descriptions. The goal of this
document is to describe both current and past algorithms, so it is
expected that this document will be modified often so that it can
remain current. 

When referencing this RAF Technical Note on processing algorithms, please use the identifier 10.26023/zc3gpm25 - for example as a citation:

> UCAR/NCAR - Earth Observing Laboratory (2022) RAF Technical Note: Processing Algorithms. UCAR/NCAR - Earth Observing Laboratory. https://doi.org/10.26023/zc3gpm25  V2022.0 Retrieved *enter date here*

### Notes to maintainers

The master branch of this repository is used to generate the content at https://ncar.github.io/aircraft_ProcessingAlgorithms/index.html

Changes to content should only be performed to the .Rmd files, which will be built to generate the HTML files. 

Once code changes have been committed and pushed to this repo, the GitHub Pages site will udpate to reflect the updated content. 

Each time this document is updated, the change log on the within the Preface should be updated with a description of the change. A static PDF should be generated to capture the previous version (before the change) so that citations can reference the version of the document that was used. 
