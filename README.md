# HuScore
One line explanation: HuScore is an R package that analyzes HuProt .gpr files to calculate z-scores of the fluorescent mean intensities of IgA and IgG wavelengths. 

Goal: to develop an R package that allows us to select candidate autoantibodies from HuProt microarray data for further analysis. 

Abstract: The HuProt microarray contains over 21,000 human proteins and is a powerful tool for analyzing protein-protein interactions, protein specificity, and finding candidate autoantibodies. While HuProt is a powerful tool for screening candidate autoantibodies, the resulting data requires filtering and screening. A variety of tools can be utilized for further filtering and screening; however, we found our previous methods to be time-consuming, error-prone, and less intuitive when teaching than other methods could be. To address this, we developed HuScore, a package of R functions that reads in .gpr files, filters out blacklisted protein IDs, analyses the IgA and the IgG channels, calculates Z-Scores, and reads out the resulting data in the form of a .csv file. In contrast to the Excel method, the R functions limit manual analysis and only require the user to manually read in their .gpr file or folder containing .gpr files. 
