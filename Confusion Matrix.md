# 1. confusion matrix

  If a classification system has been trained to distinguish between cats, dogs and rabbits, 
  a confusion matrix will summarize the results of testing the algorithm for further inspection. 

Assuming a sample of 27 animals — 8 cats, 6 dogs, and 13 rabbits, the resulting confusion matrix could look like the table below: <br />
![images](/images/confusion_matrix.png "confusion_matrix")

# 2. table of confusion

  It is a table with two rows and columns that reports the number of false positives, false negatives, true positives and true negatives.
  This allows more detailed analysis than mere proportion of correct guesses(accurcy). <br />
  ![images](/images/table_of_confusion.png "table_of_confusion") <br /><br />


# 3. Terminology and derivations from a confusion matrix

  ## condition positive (P)
     The number of real positive cases in the data 
  ## condition negative (N)
     the number of real negative cases in the data
  
  ## true positve (TP)
     eqv. with hit
  ## true negative (TN)
     eqv. with correct rejection
  ## false positive (FP)
     eqv. with false alarm, Type I error
  ## false negative (FN)
     eqv. with miss, Type II error
     
  ## sensitivity, recall, hit rate, or true positive rate (TPR)
     TPR = TP / P = TP / (TP + FN)

  ## specificity or true negative rate(TNR)
     TNR = TN / N = TN / (TN + FP)
     
  ## precision or positive predictive value (PPV)
     PPV = TP / (TP + FP)
     
  ## negative predictive value (NPV)
     NPV = TN / (TN + FN)
     
  ## miss rate or false negative rate (FNR)
     FNR = FN / P = FN / (FN + TP) = 1 - TPR
     
  ## fall-out or false negative rate (FPR)
     FPR = FP / N = FP / (FP + TN) = 1 - TNR
     
  ## false discovery rate (FDR)
     FDR = FP / (FP + TP) = 1 - PPV
  
  ## false omission rate (FOR)
     FOR = FN / (FN + TN) = 1 - NPV
     
  ## accuracy (ACC)
     ACC = (TP + TN) / (P + N) = (TP + TN) / (TP + TN + FP + FN)
     
  ## F1-sorce : is the harmonic mean of precision and sensitivity
     F1 = 2 * PPV * TPR / (PPV + TPR) = 2 * TP / (2*TP + FP + FN)
  
 <br />
sources: https://en.wikipedia.org/wiki/Confusion-matrix

