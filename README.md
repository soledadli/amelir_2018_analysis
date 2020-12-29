# Amelir 2018 Analysis
* Data Source: https://www.ameli.fr/l-assurance-maladie/statistiques-et-publications/donnees-statistiques/professionnels-de-sante-liberaux/honoraires/honoraires-totaux-et-moyens.php

# Design of the work

## 1. Clarification of the question:

The leading question should be answered by the analysis of different varaibles: density of the physicians; exceeding fees; departement, specialist
important concept: All paid-out services are taken as specialists, thus it includes sage-femmes, lab etc.

## 2. Prepare the data:
* the disordered data structures from the orignial datasets of Amelir.fr
  * the labels are misrepresented
  * the dimensions are mixed 
* combine all the sheets of the same excel and then merge them.(Be careful of non-match rows) 
* remove all unnecessary and duplicated data.
* "nc": missing values are replaced by 0 or mean depends on situation

## 3. Data demonstration:

Overview of basic information for important varaibles

## 4. Pre-Analysis:

* Take an overall look on the data and then narrow the scope
* Applyied standard deviation methods to command the overall distribution of data to narrow down cases

## 5. Analysis:

### Overall trending analysis of the correlation:

Following the pre-analysis, we picked: **nurse** as the case-study for physicians, and **paris** as the case-study for departments. 

### Extension look:

* We found the original data online and discovered another excel sheet concerning the same topic, but for regions(provinces) instead of department. 
* We apply similiar process with an aim to view the data on a more general geographic/administrative division.) 
  -- case-study: Paris 
  -- case-study: Nurse (In regional scale) 
  -- case-study: Dentist (In regional scale)
* Other ideas: -- use map to show data(suspended due to our limited knowledge of coding) 
