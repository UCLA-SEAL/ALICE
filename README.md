# ALICE
Active Inductive Logic Programming for Code Search (ICSE 2019)

## Summary of ALICE 
Modern search techniques either cannot efficiently incorporate human feedback to refine search results or cannot express structural or semantic properties of desired code. The key insight of our interactive code search technique ALICE is that user feedback can be actively incorporated to allow users to easily express and refine search queries. We design a query language to model the structure and semantics of code as logic facts. Given a code example with user annotations, ALICE automatically extracts a logic query from code features that are tagged as important. Users can refine the search query by labeling one or more examples as desired (positive) or irrelevant (negative). ALICE then infers a new logic query that separates positive examples from negative examples via active inductive logic programming. Our comprehensive simulation experiment shows that ALICE removes a large number of false positives quickly by actively incorporating user feedback. Its search algorithm is also robust to user labeling mistakes. Our choice of leveraging both positive and negative examples and using nested program structure as an inductive bias is effective in refining search queries. Compared with an existing interactive code search technique, ALICE does not require a user to manually construct a search pattern and yet achieves comparable precision and recall with much fewer search iterations. A case study with real developers shows that ALICE is easy to use and helps express complex code patterns.

## Team 
This project is developed by Professor [Miryung Kim](http://web.cs.ucla.edu/~miryung/)'s Software Engineering and Analysis Laboratory at UCLA. 
If you encounter any problems, please open an issue or feel free to contact us:

[Aishwarya Sivaraman](https://scholar.google.com/citations?user=PXKLONAAAAAJ&hl=en): PhD student; dcssiva@cs.ucla.edu

[Tianyi Zhang](https://https://tianyi-zhang.github.io): PhD student and now an assistant professor at Purdue; tianyi@purdue.edu


## How to cite 
Please refer to our ICSE'19 paper, [Active Inductive Logic Programming for Code Search
](http://web.cs.ucla.edu/~miryung/Publications/icse2019-alice.pdf) for more details. 
### Bibtex  

@INPROCEEDINGS{8812091,
  author={Sivaraman, Aishwarya and Zhang, Tianyi and Van den Broeck, Guy and Kim, Miryung},
  booktitle={2019 IEEE/ACM 41st International Conference on Software Engineering (ICSE)}, 
  title={Active Inductive Logic Programming for Code Search}, 
  year={2019},
  volume={},
  number={},
  pages={292-303},
  doi={10.1109/ICSE.2019.00044}}

[DOI Link](https://ieeexplore.ieee.org/document/8812091)

## Slides
You can watch an FSE'21 presentation video [here](http://web.cs.ucla.edu/~miryung/Publications/icse2019-alice-slides.pdf)

## Link
Plesae see the original project link at https://github.com/AishwaryaSivaraman/ALICE-ILP-for-Code-Search. 
This repository contains the latest version of ALICE code. 

If you want to try our eclipse plugin, use the VM available [here](https://ucla.box.com/s/yp952moxbcyd7mxollsnlkdfqm6weajd)

## Installation
ALICE requires ubuntu 14.04 with yap 6.3.3 and Eclipse LUNA.

### ALICE Artifact Evaluation and Tutorial 

The experiments we ran for the paper along with a walkthrough tutorial can be be found [here](https://ucla.box.com/s/hiqhjq3qdocnkqme7bo0fqrckkupfp2h)
