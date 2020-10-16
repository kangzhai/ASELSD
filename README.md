# ASELSD
The related data and scoure codes of adaptive selective ensemble learning based on sample correlation and dynamic/semi-dynamic mechanism (ASELSD) privided by Q. Kang.

The latest version is updated on 2020.10.16.

# Introduction
ASELSD is a novel selective ensemble learning protocol that first speculates the performances of different base models for various test samples based on sample correlations, and then adaptively selects the base models for ensemble. This protocol is applied to plant miRNA-lncRNA interaction prediction and shows improvement performance over the previous work and strong competitiveness compared with existing methods. It also has strong adaptability and expansibility for more research fields.

# Dependency
Windows operating system

Python 3.6.5

Kreas 2.2.4

# Data


# Usage
Open the console or powershell in the local folder and copy the following command to run ASELSD. It is also feasible to run the code using python IDE (such as pyCharm).

command: python ASELSD.py

Explanation: The input of the protocol is "fasta" data file of miRNA and lncRNA, the data format is such as:

">Ath-miR4245"

"AAUUGUCAGUAUAAAUCUUUGAUC"

The output of the protocol is the predicted miRNA-lncRNA interaction, and we will add more predicted information in future versions.

Users can open ASELSD.py using python IDE. Users can also open ASELSD.py as .txt or .fasta files. Then users can manually adjust the path of miRNA and lncRNA, or manually choose to use dynamic or semi-dynamic methods.

# Reference
Please waiting for update
