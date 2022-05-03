# R analysis of FCS files

FCS acquisition was made with a Cytoflex LX Cytometer and preprocessing was made in CytExpert2.0 to remove debris and doublets events. LiveCD45+ cells from each sample were gated and exported as FCS files.

Pre-processed and compensated FCS files were loaded and analyzed into R Studio with the packages flowCore, flowVix, flowSOM and CATALYST23. tSNE is based on the arcsinh-transformed expression of Live CD45+ cells stained with the LLA lineage markers: CD38, CD19, CD10, CD34, CXCR4, and GRP78.

This analysis is part of the following article:
https://www.nature.com/articles/s41598-022-05857-w