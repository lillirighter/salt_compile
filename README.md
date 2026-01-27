lillirighter 1/12/26

Code and resulting .cut files used to compile data spreadsheets for CLAN KidEval "Compare to Norms" function.

Original csvs are hand compiled from published norms data or exported from SALT data.

compile.RMd takes existing csvs and reformats them into spreadsheets that match the column structure of the KidEval output, aligns them into norms datasets, and creates CLAN-readable .cut files.

Each .cut file corresponds to one norming dataset and contains the minimum value, maximum value, mean, and standard deviation for each available transcript variable for each age bin in that dataset.
