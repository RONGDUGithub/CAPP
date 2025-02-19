Code Description
This code is written in MATLAB. The experimental code is divided into two categories:

Without sampling scheme (in Nonsampling.zip)
With sampling scheme (in Sampling.zip)
Non-sampling Version
After extracting Nonsampling.zip, run Main_execution_nosampling.m. The results will be output to files like Nonsampling_volume_w10.mat, where the filename indicates the data type and window size. In this setting, query size equals window size.

The final results contain two variables:

mean_result
distribution_result
Each variable shows results in a 6x6 matrix:

Each column represents the same method with different epsilon values (0.5-3)
Each row represents different methods in the following order:
1.SW-direct
2.IPP
3.APP
4.CAPP
5.BA-SW
6.ToPL
Sampling Version
After extracting Sampling.zip, run Main_execution_sampling.m. The results will be output to files like Crowd_volume_w20_q20.mat, where the filename indicates the data type, window size, and query size.

The final results contain two variables:

mean_result
distribution_result
Each variable shows results in a 6x6 matrix:

Each column represents the same method with different epsilon values (0.5-3)
Each row represents different methods in the following order:
1.SW-direct
2.APP
3.CAPP
4.Sampling
5.APP-S
6.CAPP-S
