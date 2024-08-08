## Overview

The notebooks are developed to analyze the difference in frequency behavior between SLITRK2&4, knock-out, and control mice. We extract certain frequency behaviors for both mouse types mainly gamma and theta behavior.

You can use both notebooks to analyze any .edf data files as long as they follow the rules mentioned for each notebook.

### Sizure_Data_Analysis Notebook

This notebook imports all the .edf files in the 'All_KA' folder and the time bins files in .xlsx format from the 'bins' folder and analyzes them. The results are stored in the 'final' folder as .csv files.
The code extracts the Theta mean, Gamma mean, Theta peak, and Gamma peak for ictal and interictal intervals on a trial basis and a mouse basis. You can easily differentiate the results by looking at the file’s name or checking the last block of the code.

To apply this code to other datasets just put the required time series files and time bin files in respective folders and run the code. 

The naming of the files in folders:

All_KA folder:
i_name_KO/Con.edf, 'i' is the number of the mouse. Make sure to state the KO or Con, the code uses it to separate the data.

bins folder:
i_name_KO/Con.xlsx, 'i' is the number of the mouse. Make sure to state the KO or Con, the code uses it to separate the data.

Finally, it is worth mentioning that the code has more emphasis on the files in the bins folder. If there is a file that is damaged or any data that you want to exclude from the analysis, just remove its time bin data from the bins folder and the code won't analyze it.
You can use the result tables stored in the 'final' folder to make graphs in the Prism application.

### Spontaneous_Data_Analysis Notebook

This notebook imports all the .edf files in the 'All_Spontaneous' folder and analyzes them. The results are stored in the same folder where the notebook is located.
The code extracts the mean and standard deviation of Theta mean, Gamma mean, Theta peak, and Gamma peak for 1-minute long intervals and averages them for the entire 24 hours. You can easily differentiate the results by looking at the file’s name or checking the last block of the code.

The naming of the files in folders:

All_Spontneous folder:
i_name_KO/Con.edf, 'i' is the number of the mouse. Make sure to state the KO or Con, the code uses it to separate the data.

You can use the final results to make graphs in the prism application.

## Contributors
Jaewon Ko        kojaewon0@gmail.com


Jiwon Um         jiwonum1@gmail.com


Hyeji Jung       gpwl4670@gmail.com


Pouya Farivar    pouyam.fr@gmail.com




