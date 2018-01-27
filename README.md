# COWTS_ILP_Summary

Implementation of the paper 
Rudra et al., Extracting Situational Information from Microblogs during Disaster Events: A Classification-Summarization Approach, CIKM 2015.

Command - 
```
python ILP_Summary.py <num_of_sentences> <input> <output>
```

* requires [GLPK](https://www.gnu.org/software/glpk/) via [Optlang](https://github.com/biosustain/optlang) - other supported solvers can also be used.
* requires [CMU parts-of-speech tagger](https://github.com/brendano/ark-tweet-nlp), which has been stored in the present folder.
* Input and Output File in txt format
