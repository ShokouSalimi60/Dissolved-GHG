Charlotte Grasset-05/06/2024

Open with R studio the file Òscript-charlotte_list_of peaksÓ
R will ask you to load the GHG file, e.g. gga_er_2018-01-23_f0000.txt
R will then ask you to load the file with the injection times of the discrete samples, e.g. injectiontimesf000.txt
Check visually each peak in R studio and adjust the time in the file called with the injection times if needed (e.g. if the peak is cut)
R will create a file called Òareas_peaks.csvÓ with the area of the discrete samples you injected. 
You will need to do a calibration curve (inject standards of similar volume than your injected samples, and with different gas concentrations) to convert the area of the peaks into a number of moles (conversion done in the file Òarea_to_ppmÓ)

