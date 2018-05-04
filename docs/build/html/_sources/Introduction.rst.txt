Introduction
===============
The purpose of this document is to identify differentially expressed genes by comparing different expressions of samples and processed samples, that is, ¡°Oh My Genes¡±.

Purpose
-----------
Through our scientists uploading the gene expression file, identifying differentially expressed genes given a gene expression file containing two cell samples, quickly obtaining the differentially expressed genes and feedback the results to the scientists, so that scientists can better understand the mystery of gene expression.

Overview
--------
The web application has a simple interface with a single button [Upload and GO]. Our scientists upload a plain text file containing gene expression levels from two samples, representing two experimental conditions. Accepting the file, the software will return a table of differentially expressed genes and a scatter plot of these genes whose X-axis is control and Y-axis is treatment. If an invalid gene expression is given, the web application returns a page informing the user to provide the correct format.

User characteristics
--------------------
end-users: Scientist who studies gene expression.
web site maintainers: Programer

Conventions, acronyms, abbreviations, terminology, glossary
-----------------------------------------------------------
The purpose of this section is to introduce conventions, acronyms, abbreviations, terminology, glossary, it can help you get a better understanding of the project.

Conventions
-----------
Scientists must abide by the confidentiality agreement, not to be allowed to publicize the differential genes without permission, not to sell the research results illegally, and not to use the results of the research for illegal use, that is, to destroy human harmony and destroy social stability.

Acronyms & Abbreviations
------------------------
OMG - Oh My Genes, that is, the peroject name.
logFC - log fold change of gene expression. log_2 [T/C], where T is the gene expression level from a treatment sample, while C is the gene expression level from a control sample.

Terminology & Glossary
----------------------
Control sample - a cell sample prepared in its normal condition.
Treatment sample - a cell sample treated by special chemicals, or in which some genes are altered.
Differentially expressed genes - the genes which have significantly different expression levels between two samples.
Up-regulation - a gene is said to be up-regulated if it has higher expression in treatment than in control.