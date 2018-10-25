# S-matrix-KOR-ACL

An Excel file for E. coli flux balance analysis is contained in the file "S matrix.zip".

The Excel file named "FBA KOR ACL" contains the stoichiometric matrix (S) of E. coli core metabolism pathway with the metabolites and reactions that are included.
This S matrix is used for flux balance analysis and estimating E. coli growth.
The codes for objective function in MATLAB are present in the last two worksheets, named as "MATLAB code for KOR" and "MATLAB code for KOR ACL".



System requirements:

The codes are wrote for MATLAB linprog syntax and tested in MATLAB v9.3 and v9.4 without any problem.



Installation guide:

The linprog syntax already in MATLAB program after installation of MATLAB.



Demo:

Simplely copy all of the text in the "MATLAB code for KOR" or "MATLAB code for KOR ACL" worksheet in "FBA KOR ACL.xlsx" to MATLAB command window.
The program will run automatically to solve the objective function and show the flux rates of each reactions in order in less than 2 sec.



