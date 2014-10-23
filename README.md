Getting and Cleaning Data Course Project
====================

milindaj (October 23, 2014)
---------------------



**Key points related to creating tidy dataset**

1.  It is assumed that the zip file containing assignment datasets are extracted under ```UCI HAR Dataset``` folder. Also the ```run_analysis.R``` script is expected to reside under the folder one level above ```UCI HAR Dataset``` folder which we shall call as ```base``` folder
2.  Before running the script, set the working directory to the ```base``` folder
3.  The name of the tidy dataset expected in step 4 of assignment is ``` tidyData ``` wnich is a data.frame 
4.  The name of the output file is ```tidyAvgData.txt``` and it is stored under the ```UCI HAR Dataset``` folder once generated
5.  All the intermediate variables used in the script are removed after use and thus are not available post script execution
