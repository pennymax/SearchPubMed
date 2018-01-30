#Search Pubmed
## Search Pubmed throu programming interface

The usage is very simple. 

Search by title:
```sh
python ./search_pubmed.py 'Changes in the calcium-parathyroid hormone-vitamin d axis and prognosis for critically ill patients: a prospective observational study'
```

or any pubmed compatible rules:  
```sh
python ./search_pubmed.py '24073265[uid] OR 24073266[uid]'
```

Passing one or more '-v's will give more detailed information.  
```sh

python ./search_pubmed.py -vvvvv '24073265[uid]'

```

Passing search query
```sh

python search_pubmed.py -l 5 -vvvvv '(escitalopram) AND Tachycardia'

```

```
PMID:      29222399
Title:     Pediatric Disorders of Orthostatic Intolerance.
Journal:   Pediatrics
Authors:   Stewart JM, Boris JR, Chelimsky G, Fischer PR, Fortunato JE, Grubb BP, Heyer GL, Jarjour IT, Medow MS, Numan MT, Pianosi PT, Singer W, Tarbell S, Chelimsky TC, Pediatric Writing Group of the American Autonomic Society.
PubDate:   2018 Jan
PubType:   Journal Article, Review
Volume:    141
Issue:     1
Pages:
ISSN:      0031-4005
ESSN:      1098-4275
Link:      https://doi.org/10.1542/peds.2017-1673
Abstract:
     Orthostatic intolerance (OI), having difficulty tolerating an upright posture because of symptoms or signs that abate when returned to supine, is common in pediatrics. For example, ∼40% of people faint during their lives, half of whom faint during adolescence, and the peak age for first faint is 15 years. Because of this, we describe the most common forms of OI in pediatrics and distinguish between chronic and acute OI. These common forms of OI include initial orthostatic hypotension (which is a frequently seen benign condition in youngsters), true orthostatic hypotension (both neurogenic and nonneurogenic), vasovagal syncope, and postural tachycardia syndrome. We also describe the influences of chronic bed rest and rapid weight loss as aggravating factors and causes of OI. Presenting signs and symptoms are discussed as well as patient evaluation and testing modalities. Putative causes of OI, such as gravitational and exercise deconditioning, immune-mediated disease, mast cell activation, and central hypovolemia, are described as well as frequent comorbidities, such as joint hypermobility, anxiety, and gastrointestinal issues. The medical management of OI is considered, which includes both nonpharmacologic and pharmacologic approaches. Finally, we discuss the prognosis and long-term implications of OI and indicate future directions for research and patient management.
```
