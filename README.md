Overview

This code is written in MATLAB and contains two main experimental components, packaged separately in Nonsampling.zip and Sampling.zip, representing implementations without and with sampling schemes respectively.

Non-sampling Implementation

For the non-sampling version, extract Nonsampling.zip and run Main_execution_nosampling.m. The program will generate output files named in the format of Nonsampling_volume_w10.mat, where the filename indicates the data type and window size. Note that in this setting, the query size equals the window size. The results contain two variables: mean_result and distribution_result. Both variables are presented in 6x6 matrices, where each column corresponds to results for different epsilon values (ranging from 0.5 to 3) using the same method. The six methods, represented by rows, are SW-direct, IPP, APP, CAPP, BA-SW, and ToPL.

Sampling Implementation

For the sampling version, extract Sampling.zip and run Main_execution_sampling.m. The program will generate output files named in the format of Crowd_volume_w20_q20.mat, where the filename indicates the data type, window size, and query size. Similar to the non-sampling version, the results contain mean_result and distribution_result variables in 6x6 matrices. Each column represents results for different epsilon values (0.5 to 3) using the same method. The six methods, represented by rows, are SW-direct, APP, CAPP, Sampling, APP-S and CAPP-S.
