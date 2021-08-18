# Argument Extraction by Generation (Edited)

Code for paper "Document-Level Argument Extraction by Conditional Generation". NAACL 21'

NOTE: The code did not work for me with the dependencies below. The code in this fork has been edited to work with pytorch-lightning==1.4.2 and installing the requirements file should be enough to get training started on google colab with a GPU.

## Dependencies
- pytorch=1.6
- transformers=3.1.0
- pytorch-lightning=1.0.6
- spacy=3.0 # conflicts with transformers
- pytorch-struct=0.4

## Datasets
- RAMS (Download at [https://nlp.jhu.edu/rams/])
- ACE05 (Access from LDC[https://catalog.ldc.upenn.edu/LDC2006T06] and preprocessing following OneIE[http://blender.cs.illinois.edu/software/oneie/])
- WikiEvents (included in this repo)
