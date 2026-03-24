ENCODE RNA-seq pipeline
=================================================
[![CircleCI](https://circleci.com/gh/ENCODE-DCC/rna-seq-pipeline.svg?style=svg)](https://circleci.com/gh/ENCODE-DCC/rna-seq-pipeline)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

This is a fork of the ENCODE-DCC RNA-sequencing pipeline. Follow the link above for the original pipeline.
This fork runs STAR+WASP (https://pubmed.ncbi.nlm.nih.gov/38370773/) to remove reads with alignment bias. 
Some package versions also needed to be updated in order to run this newer version of STAR.
