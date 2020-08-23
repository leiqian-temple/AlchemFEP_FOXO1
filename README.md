## AlchemFEP_FOXO1

### These scripts are used to combine two types of Gromacs topology files:

#### 1. hybrid top file prepared by pmx. 
#### *** It contains State A and State B for Alchemical_FEP use. (e.g. "hybrid_3coa_L183P.top")

#### 2. mcpb top file prepared by mcpb.py. 
#### *** It contains new force constants for protein atoms forming coordination bonds to metal ion. (e.g. "3COA_dry_GMX.top")

#### 3. In update folder, the below command would generate the combined top file: top_comb.top
#### *** python3 job_Topol_Combine.py 3COA_dry_GMX.top hybrid_3coa_L183P.top

