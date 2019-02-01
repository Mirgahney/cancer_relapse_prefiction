# cancer_relapse_prefiction
This project is part of Kernel methods course at AMMI, the task is predicting relapse in patients the data is gene expression levels for 4654 genes on 184 early-stage breast cancer samples.

## Suggested methods to use
### Preprocessing:
  1. Log Transform
  2. Replicated handling
  3. Missing values (we don't have)
  4. Flat pattern filtering.(need to look out)
  5. Normalization
  Filtering non-expressed genes:
  * Histogram of average logCPM for gene selection.
### Modeling
  We are going to use hirerchial modeling, staring with clustering and then with in each cluster we are going to run different kerenl model.
  Also second thing to try is to use soft clustering and the use the weights as a mixsuer values for the multi-models.
  Also Stack modeles.
### MI for gene selection + SVM
### [multi-kernel learning](https://github.com/mstrazar/mklaren) 
### double RBF-Kernel 
### featuers selection [scikit-rebate](https://github.com/EpistasisLab/scikit-rebate)

### Note:
 In multicellular organisms, complexity of gene expression is often summarized by two measures: first, how many transcripts are generated per locus (referred to as 'gene expression level') and second, how broadly each transcript is found in different tissues (referred to as 'gene expression breadth').
