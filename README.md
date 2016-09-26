# Saliency-Detection-for-Unconstrained-Videos-Using-Superpixel-level-Graph-and-Spatiotemporal-Propagat


Usage
call "demo.m" to run the demo and for more description of the arguments you 
will see in the deom.m files.

1, set your videos path, in the demo.m,
   such as :  datasetPath = fullfile(foldername, 'video_sequences', 'SegTrackv2');
   
2, the saliency map will save in the folder: 
   saliencyMap_Spatialrefined = =['Results/','saliencyMap/',videofolder,'/'];

3，downloads the ground-truth of SegTrackV2 from https://yunpan.cn/ckX9Up4XH54Uu  and the password is  e3e4

This software was developed under 32-bit/64-bit Windows 
with Matlab R2013b.

If you use this software for academic research, please cite the following paper:
[1] Z. Liu, J. Li, L. Ye, G. Sun, and L. Shen, “Saliency detection for unconstrained videos using superpixel-level graph and spatiotemporal propagation,” IEEE Transactions on Circuits and Systems for Video Technology, doi.: 10.1109/TCSVT.2016.2595324, Jul. 2016. 


