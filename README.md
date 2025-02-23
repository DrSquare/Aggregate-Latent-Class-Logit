#################################################################################################
## Aggregate-Latent-Segment-Logit: Demand Model (i.e., Aggregate Latent Class Logit)
## Python and R code for the estimation of latent class logit model with aggregate POS data
## By Minha Hwang (minha@alum.mit.edu)
#################################################################################################


#### There are 3 Python / R codes and 1 supporting synthetic data set. 
1. lc-agglogit-main-availablity.R: Main R code - Note that this code accomodates varying choice sets (i.e. # of products are allowed to change over time/market.) 

## 2. ll_adclc_ava.R: Log-Likelihood function for maximization
##
## 3. fake-data-gen-with-availability.R: Synthetic data generation code (for code validation)
##
## 4. lcl_agg_fake_data-with-availability.csv: Synthetic data generated from the code above (aggregated data). The code can generate individual-level data as well.

#### Reference: 1. A Segment-Level Model of Category Volume and Brand Choice
####            William R. Dillon and Sunil Gupta 
####            Marketing Science, Vol. 15, No. 1 (1996), pp 38-59
####     
####            2. The Recoverability of Segmentation Structure from Store-level Aggregate Data
####            Anand V. Bodapati, and Sachin Gupta     
####            Journal of Marketing Research, August (2004)

#### Related package)
#### pyBLP support the estimation of random coefficient logit with aggregate data (under BLP demand model structure). However, pyBLP does not support latent segment 
#### (i.e. latent class) with aggregate data yet.

#### In case of quesitons, please reach out to minha@alum.mit.edu

