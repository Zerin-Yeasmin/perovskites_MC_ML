# Introuction




# Foundation of Theory

<!-- Discuss About the Theoretical Background -->



# Empirical Research

<!-- Relevant Research in the field -->



# Research Gap

<!-- Limitations of this Literature -->



# ML Methods

<!-- All the ML/DL Algorithms and their parameters and structure of them used in this literature -->

- Data Set Splitting
  - training data = 80%
  - test data = 20% 

ML methods:

- RF
  - n_estimators = 1400
  - criterion=‘entropy’
  - max depth=40, 
  - max features=‘auto’,
  - min samples leaf=1, 
  - min samples split=2. 

  For perovskite formability prediction the chosen parameters are:
   - n estimator=1500, 
   - min samples leaf=1, 
   - min samples split=5.

- XGBoost 
  - n estimators=100, 
  - gamma=0.1, 
  - learning rate=0.25, 
  - max depth=12,
  - objective=‘multi:softprob’. 
  
  For perovskite formability prediction we used the default parameters.

# Data Set

<!-- All the Data sets used in this literature and their summary [ `<pandas>.inf()` ] -->

Model 1
Features

• r(AXII) 12 site coordination of cation A
• r(AV I) 6 site coordination of cation A
• EN(A) Electronegativity of cation A
• EN(B) Electronegativity of cation B
• l(A − O) Length of covalent A-O bond
• l(B − O) Length of covalent B-O bond
• ∆ENR Difference electronegativity with radius
• tG Goldschmidt tolerance factor
• µ Octahedral factor

- Target
    
    Lowest Distortion 

Model 2
Features

• r(AXII) 12 site coordination of cation A
• r(AV I) 6 site coordination of cation A
• EN(A) Electronegativity of cation A
• EN(B) Electronegativity of cation B
• l(A − O) Length of covalent A-O bond
• l(B − O) Length of covalent B-O bond
• ∆ENR Difference electronegativity with radius
• µ Octahedral factor
Lowest Distortion 

- Target
    Perovskites
    


# Result

- RF
    - 0.7736742424242424  (Without SMOTE)
    - 0.7632575757575758   (With SMOTE)






# Conclusion

<!-- Summary of the review. Results and Comments on Future progression (maybe already done researches)-->