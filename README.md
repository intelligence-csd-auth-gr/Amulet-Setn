# Zero-shot Classification using sentence-based bioBERT embeddings

This repository contains the code for our [SETN 2020](http://www.eetn.gr/index.php/setn-2020-home) paper with title: *Zero-Shot Classification of Biomedical Articles with EmergingMeSH Descriptors*

In brief, we develop a Zero-shot learning (ZSL) mechanism that tries to perform on-the-fly classification examining text-raw data that stem from PubMed abstracts searching for emerging MeSH terms that appear each upcoming year. Therefore, bioBERT embeddings are exploited comouted on sentence-level so as to exploit better the semantic relationships that occur into the corresponding abstracts, avoiding misclassification that may occur in case of word-guided approaches. Later, we use the same mechanism for providing weak labels into gathered data from previous years, and then apply two different Weakly supervised learning (WSL) approaches for examining their performance on the same tasks. Three different MeSH terms were investigated here, under single-label mode. An expansion of our work towards multi-label classification tasks covering more complex cases and larger number of labels is the next step in the context of a larger project, called AMULET (more info on Additional resources section).

If you find the code useful for your research, please cite our paper:


        @inproceedings{,
              title={Zero-Shot Classification of Biomedical Articles with EmergingMeSH Descriptors},
              booktitle={Proceedings of the 11th Hellenic Conference on Artificial Intelligence,
               {SETN} 2020, Athens, Greece, September 02-04, 2020)},
              author={N. Mylonas, S. Karlos and G. Tsoumakas},
              pages={},
              year={2020}
        }
        

## Requirements

Our code has been tested on Windows10 using python 3.7.6. The mentioned time responses correspond to a working station embedded with Intel Core i7-9700 (3GHz) processor and 32 GB RAM.


        
# #Developed by: 

|    Name     | e-mail          |
| ------------- |:-------------:|
| Νικόλαος Μυλωνάς     | myloniko@csd.auth.gr |
| Σταμάτης Κάρλος      | stkarlos@csd.auth.gr |
| Γρηγόριος Τσουμάκας  | greg@csd.auth.gr     |

## Funded by

The research work was supported by the Hellenic Foundation forResearch and Innovation (H.F.R.I.) under the “First Call for H.F.R.I.Research Projects to support Faculty members and Researchers andthe procurement of high-cost research equipment grant” (ProjectNumber: 514).

## Additional resources

- [AMULET project](https://www.linkedin.com/showcase/amulet-project/about/)
- [Academic Team's page] (https://intelligence.csd.auth.gr/#)
