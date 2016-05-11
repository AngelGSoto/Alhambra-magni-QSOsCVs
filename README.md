# Alhambra-magni-QSOsCVs
## ALHAMBRA magnitudes of QSOs and CVs

Contains folders with the ALHAMBRA magnitudes of QSOs in several redshift range and the ALHAMBRA magnitudes of the CVs from SDSS.

## Description of the folders

-) The folders named "QSOs-??-spectros" contain the file.json with the ALHAMBRA magnitudes (there is a file.json for each source). These folders also contain the SED (magnitude vs filter) of each source.
Folders are classified according to the redshift range ie;

 * QSOs-010-spectros -> 0.01<z<1.0
 * QSOs-101-spectros -> 1.01<z<2.0
 * QSOs-201-spectros -> 2.01<z<3.0
 * QSOs-301-spectros -> 3.01<z<4.0
 * QSOs-401-spectros -> 4.01<z<5.0

-) The folder "CVs-spectros" contain the ALHAMBRA magnithed (file.json) and the plot (magnitude vs filter) of each CV.

## Description of file.json

-) There is a file.json for each source.

-) The file.json contains a dictionary, that have the magnitude of each filter of the ALHAMBRA photometric system. The file also has the "id" and the redshift "z" of the source.



