%
% SGR: Sparse graph regularization DEMO.
%        Version: 1.0
%        Date   : Apr 2021
%
%    This demo shows the SGR methods for robust crop mapping using hyperspectral image classification with very few in-situ data.
%
%    fun_SGR.p ....... A function implementing the SGR model (compiled in Matlab R2022a)
%    sunsal.m ..........A function conducting SR using sunsal algorithm
%    calcError.m .......A function for computing confusion matrix
%    soft.m ............A soft thresholding function
%    CASI_SASI_SGR.m ..... A main code to run SGR on CASI/SASI Heihe data sets
%    /data ................ The folder contains the CASI/SASI Heihe data sets
%    /GCmex2.0 .............The folder contains the Graph cuts codes
%
%
%   --------------------------------------
%   Cite:
%   --------------------------------------
%
%   [1]Z. Xue, P. Du, J. Li, H. Su. Sparse graph regularization for robust crop mapping using hyperspectral remotely sensed imagery with very few in situ data[J]. ISPRS Journal of Photogrammetry Remote Sensing, 2017, 124: 1-15.
%   
%
%   --------------------------------------
%   Copyright & Disclaimer
%   --------------------------------------
%
%   The programs contained in this package are granted free of charge for
%   research and education purposes only. 
%
%   Copyright (c) 2021 by Zhaohui Xue
%   zhaohui.xue@hhu.edu.cn
%   --------------------------------------
%   For full package:
%   --------------------------------------
%   https://sites.google.com/site/zhaohuixuers/
