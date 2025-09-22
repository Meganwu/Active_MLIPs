# Active_learning_MLIPs

# Install


# Step 1 randomly generate few initial dataset based on torsion angles and distance of molecules away from the surface
(example: ZnBr2Me4DPP majorly two flexible torsion angle)

## first 30 initial configs (optimized by DFT), choose configs at the interval of 5, 10, 15, 20.

# Step2  Train MLIPs (based on Mace here)
## from scratch
## refine from the foundation model


# Step3  Generate more configurations based on MLIPs
## a. BOSS
## b. MACE optimization
## C. MACE molecular dynamics
## d. randomly creat distorsions by changing bonds or angles from some inital configurations


# Step4 Evaluate these configurations
## Similarity
  ### RMSD (atomic positions n:3) 
  ### Similarity like SSIM and Cosine based on fingerprints (mace model node feature n: 640)
  ### QBC


# Step5 Construct new training dataset from step4



# Step6 Evaluate the performance of MLIPs
## STM images
## Optimization
## Diffusion energy







