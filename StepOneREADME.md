# PBfB_Personal_Project - Step one
*Written by Lina Leuttgert and Sorsha Passmore*

Please read this file before using the scripts.

## Description:
Climate change has long been associated with changes in chlorophyll levels in oceans, seas and other water bodies. Much of the data gathered for these variables is available on the NOAA (where we collected our data from) however some of the databases are difficult to read, interpret or analyse. Our goal was to make it easier for scientists to interpret data such as this, whilst improving their bioinformatics skills through the use of our step by step guide on how the codes, scripts and functions were created and their purpose. 

After we downloaded the data we needed from NOAA, we saved the file in a seperate directory especially for this project. 

We then extracted the data file (in this case named: 'Oregon2_ocldb1517224912.11308.CTD.csv') into jEdit to begin writing our python codes. **Importantly**, before you can begin writing your codes, scripts, functions and so on, the access permission must be changed so that you can edit the data file.

To do this, we had to open Terminal and run the following command:
```
chmod u+x Oregon2_ocldb1517224912.11308.CTD.csv
```
*Where chmod stands for 'change mode', 'u' stands for user (can replace with 'o' for other or 'g' for group) and +x stands for execute. This command enables the user to be able to execute the file name written directly after the command.*

If you want to clone this repository then please enter the following command in your command line in terminal: 
```
git clone https://github.com/sorshapassmore/PBfB_Personal_Project.git
```

Once the access permissions have been edited, we were able to create a script in python.
