# NativePTMannotation
Automatically annotate native spectra

Native mass spectra could provide more comprehensive information in the intact protein level. However, the annotation of native spectra acquires many mannually work, especially for glycoproteins which have multiple sites and multiple glycoforms at each site. 
We developed an algorithm integrating native mass data and peptide-centric data which allowed the automatically annotation of native spectra. 

The data are required in this algorithm including:
1. Native mass spectra: raw peak list and peak intensities/deconvoluted peak list by any deconvolution software is also applicable. The example of raw peak list and peak intensities can be found in the file "S1.txt".
2. General information of the protein: sequence, number of disulfide bridges, fixed modifications, possible modifications
3. Detailed information of possible modifications: ideally, sites, sites-specific modifications (modification forms and occupancy); however, partially information of possible modifications is also applicable with some changes in the script. The example of ideal site-specific information from peptide-centric data can be found in the file "PTM.xlsx".
