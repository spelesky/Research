This is a code repository for a search for long-duration local Universe transients and FRB persistent radio source counterparts in the LoTSS DR1 field. Below I include a description of the files included and a summary of the sources being analyzed. 

# Files

SDSSgalaxies.fits: This file contains the SDSS DR16 galaxy data for the galaxies that are within the LoTSS DR1 field that are local under a photometric redshift constraint and with an absolute brightness -16 AB or brighter. 

asu.fit: This file contains LoTSS DR1 radio sources that have an integrated flux $\geq$ 0.8 mJy. 


Note - There is a file containing the LoTSS DR2 radio sources that are in the DR1 field and have an integrated flux $\geq$ 0.8 mJy however the file is too large to add yet so I will have to figure that out. This file and the previous are needed to calculate the chance association probability only.


plot.ipynb: This is a jupyter notebook that contains the analysis of these final sources being analyzed as well as other calculations done including spectral index, chance association probability, and projected offset. The plots/analysis includes BPT diagrams, WHAN plot, L-SFR plot, sSFR-Mass plot, WISE color-color plot, offset distribution plot with chance association fit, redshift distribution plot, and galaxy contour images. 


Research Sources (2).xlsx: This is an excel sheet that contains all of the data used in the analysis that is not directly from SDSS DR16 or LoTSS DR1/DR2. 

Research Sources - Sheet1.csv: This is a cvs file of the excel file to access all of the data in plots.ipynb.

# Summary of Sources:

The current list of candidates includes 11 sources. These 11 sources are radio sources that are compact in both DR1 and DR2 of LoTSS with an anverage integrated flux of 2.14 mJy and have been associated with a galaxy from the SDSS galaxy sample with these galaxies having an average redshift of 0.0327. Of these 11 sources, two of them have offsets larger than 2" (11.7" and 11.9") from their host galaxy and the remaining 9 have offsets less than 1". Using the emission line data from SDSS DR12, these sources were plotted on BPT diagrams and fall under the star-forming region (not being ruled out as AGN). One source does fall in the composit region of the second BPT diagram which warrants further investigation of classification in other surveys. More emission line data was used to plot these sources on a WHAN diagram where all 11 fall under the star-forming region. These 11 sources also are plotted on a luminosity vs. star-formation rate to show their luminosities are large compared to their SFR and therefore could be a result of something other than SFR. All 11 sources are above the one-sigma line for L-SFR relation which correlates luminosity due to star-formation. Lastly, these 11 sources are plotted on a mass vs. specific star-formation rate and all lie within the star-formation classfication.

So far, all 11 sources are classified as star-forming under these previous analyses. 

Note - There was one source that did not have emission line data for Halpha resulting in it not appearing on the BPT, WHAN, and L-SFR plots. I will look for emission line data in another survey (there was one sent to me however there also was no Haplha data).
