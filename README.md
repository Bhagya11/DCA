# DCA
DCA implementaion
Inputs:
%       X       :   pxn matrix containing the first set of training feature vectors
%                   p:  dimensionality of the first feature set
%                   n:  number of training samples
% 
%       Y       :   qxn matrix containing the second set of training feature vectors
%                   q:  dimensionality of the second feature set
% 
%       label   :   1xn row vector of length n containing the class labels
%               
% Outputs:
%       Ax  :   Transformation matrix for the first data set (rxp)
%               r:  maximum dimensionality in the new subspace
%       Ay  :   Transformation matrix for the second data set (rxq)
%       Xs  :   First set of transformed feature vectors (rxn)
%       Xy  :   Second set of transformed feature vectors (rxn)
% 
