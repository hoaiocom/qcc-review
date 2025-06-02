# Quantum Cloud Computing Review - Supplemental Data

This repository contains the systematic literature review search queries and results in each stage of the review protocol used in the manuscript:

> Hoa T. Nguyen, Prabhakar Krishnan, Dilip Krishnaswamy, Muhammad Usman, and Rajkumar Buyya, "Quantum Cloud Computing: A Review, Open Problems, and Future Directions", arXiv: 2404.11420

The following search queries were executed across multiple databases to identify relevant publications in the field of quantum cloud computing. All detailed analysis and further discussion of the review can be found in our manuscript.

## Web of Science (Scopus)

Search string:

```json
(TI=("quantum" and "cloud" and "computing") OR AB=("quantum" and "cloud" and "computing")) AND (DT==("ARTICLE" OR "PROCEEDINGS PAPER" OR "REVIEW" OR "BOOK CHAPTER") AND TASCA==("COMPUTER SCIENCE INFORMATION SYSTEMS" OR "COMPUTER SCIENCE THEORY METHODS" OR "QUANTUM SCIENCE TECHNOLOGY" OR "COMPUTER SCIENCE INTERDISCIPLINARY APPLICATIONS" OR "COMPUTER SCIENCE HARDWARE ARCHITECTURE" OR "COMPUTER SCIENCE SOFTWARE ENGINEERING" OR "COMPUTER SCIENCE CYBERNETICS" OR "COMPUTER SCIENCE ARTIFICIAL INTELLIGENCE"))
```

Publication Date limit to 2017-01-01 → 2024-09-01


## ACM Digital Library

Search string:
```json
[[Title: "quantum"] AND [Title: "cloud"] AND [Title: "computing"]] OR [[Abstract: "quantum"] AND [Abstract: "cloud"] AND [Abstract: "computing"]] AND [E-Publication Date: (01/01/2018 TO 30/09/2024)]
```


## Scopus
Search string:
```json
TITLE-ABS ( "quantum" AND "cloud" AND "computing" AND NOT "quantum-inspired" AND NOT "post-quantum" AND NOT "for cloud computing" ) AND PUBYEAR > 2016 AND PUBYEAR < 2025 AND ( LIMIT-TO ( SUBJAREA , "COMP" ) ) AND ( LIMIT-TO ( DOCTYPE , "ar" ) OR LIMIT-TO ( DOCTYPE , "cp" ) OR LIMIT-TO ( DOCTYPE , "ch" ) ) AND ( LIMIT-TO ( LANGUAGE , "English" ) ) AND ( LIMIT-TO ( EXACTKEYWORD , "Quantum Computing" ) OR LIMIT-TO ( EXACTKEYWORD , "Cloud Computing" ) OR LIMIT-TO ( EXACTKEYWORD , "Quantum Cloud Computing" ) OR LIMIT-TO ( EXACTKEYWORD , "Distributed Computer Systems" ) OR LIMIT-TO ( EXACTKEYWORD , "Cloud Platforms" ) OR LIMIT-TO ( EXACTKEYWORD , "Cloud Computing Environments" ) OR LIMIT-TO ( EXACTKEYWORD , "Resource Management" ) OR LIMIT-TO ( EXACTKEYWORD , "Computing Paradigm" ) OR LIMIT-TO ( EXACTKEYWORD , "Cloud Services" ) )
```

## IEEE Xplore
Search string:
```json
("Document Title":"quantum" and "cloud" and "computing") OR ("Abstract":"quantum" and "cloud" and "computing") NOT ("Document Title":"quantum-inspired" or "post-quantum") NOT ("Abstract":"quantum-inspired" or "post-quantum")
```

**Filters Applied:** Quantum Computing - Cloud Computing - Cloud Environment - Quantum System - 2017 - 2024



## DBLP
Search string
```json
quantum cloud computing
```
