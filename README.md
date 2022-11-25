# IE643CourseProject
Face Manipulation Detection <br><br>
The following reference was used:<br>
N. Bonettini, E. D. Cannas, S. Mandelli, L. Bondi, P. Bestagini and S. Tubaro, "Video Face Manipulation Detection Through Ensemble of CNNs," 2020 25th International Conference on Pattern Recognition (ICPR), 2021, pp. 5012-5019, doi: 10.1109/ICPR48806.2021.9412711.<br>
The github repo: https://github.com/polimi-ispl/icpr2020dfdc#datasets 
<br><br>
Suitable changes have been made to run it on NVIDIA GEFORCE GTX 1660 TI GPU, intel core i7 processor. <br><br>
Install pytorch from official website in a conda environment<br>
Update the environment using environment.yml file commenting pytorch wherever given<br>
Original code uses python 3.6.9 but to utilize GPU in training python version 3.7.x has been used in this code<br><br>
Several depracated functions have been replaced with the new versions<br><br>
Tweak the learning rate and max_iter in .sh files for a faster training of the model<br>
If Cuda goes out of memory, try lowering down the batch size of training dataset<br><br>
The results obtained by testing the trained model [stored in weight directory] is stored in results directory. <br>
The bestval.pth in weights directory is the file with the minimum loss encountered during training procedure <br><br>
Pre trained models have also been preented as usable notebooks in notebook directory<br><br>
Nikhil Tiwari
<br>200010050<br>
In guidance of Prof P Balamurugan
