# NonLinear Addditive Regression Absolute Loss

There are total four codes summarizing our method in the paper.

A) Journal_version_makegraph.R, B) Journal_version_NAM.R C) Journal_non_linear_RF.R D) Journal_version_make_mu_gamma.R

We describe the code following the illustrative figure of our method as in Figure 2 of the main text.

1) On obtaining the weighted adjacency matrix from  SMILES using the implementation in Journal_version_makegraph.R we obtain the graphical descriptors, and chemical descriptors are as obtained from AqSol-Db.

2) Step 1 and Step 2 using non-linear additive model is included in  Journal_version_NAM.R : sgd_int() is the function that show the step by step implmentation of the non-linear additive morel, particulary Step 2 in the Figure 2.

3) Random Forest implementation is in Journal_non_linear_RF.R

4)Journal_version_make_mu_gamma.R : In this code we implement initialization of the parameters following the procedure in Section S2 in the Supplementary Information.
