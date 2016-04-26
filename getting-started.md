# Getting Started with the General Defect Classification
The General Defect Classification (GDC) is a classification scheme that treats code 1) defects, 2) changes ("fixes of the defects"), 3) warnings from automated static analyzer tools (ASATs), and 4) the rules that generate these warnings ("checkers") as first class citizens and allows their classification under one common topology.

## The GDC in a Nutshell
The GDC has two major categories, functional and maintainability defects. In total, these are split up into 16 sub-categories, depicted in `gdc-topology.pdf`. A more thorough description of the GDC with a view toward static analyzers and the rules they check for is given in `gdc-category-description-1.pdf`. We provide a mapping between the 2,385 rules from the nine supported ASATs (Checkstyle, ESLint, FindBugs, JSCS, JSHint, JSL, PMD, Pylint, and RuboCop) to their respective GDC categories in `asat-gdc-mapping.html`. A good description of the complimentary GDC categories toward the other views 1 and 2 accompanies this package as `gdc-category-description-2.pdf`, originally authored by [Mika Mäntylä and Casper Lassenius](https://dx.doi.org/10.6084/m9.figshare.689805) under a CC-BY license.

## How to Cite
If the GDC is helpful to you, please pay attribution by referencing this GDC usage package (*Moritz Beller, http://dx.doi.org/10.6084/m9.figshare.1603419, 2016*) and citing the paper in which we introduced it:

*Moritz Beller, Radjino Bholanath, Shane McIntosh, Andy Zaidman: Analyzing the State of Static Analysis: A Large-Scale Evaluation in Open Source Software in 23rd IEEE International Conference on Software Analysis, Evolution, and Reengineering (SANER), Osaka (Japan), 2016.*

## Genealogy
The GDC's line of ancestors reaches back to the Orthogonal Defect Classification (ODC) by IBM and the IEEE 1993 defect definition (IEEE Std 1044-1993). In particular, the GDC has a direct ancestor in the classification of code review fixes from Beller et al. [1]. This, in turn, is closely related to the classification of Mäntylä et al. [2]. Both classifications have been shown to have good to excellent interrater reliability. The ancestry tree of the GDC is presented in `gdc-genealogy.pdf`. 

[1] *Moritz Beller, Alberto Bacchelli, Andy Zaidman, Elmar Jürgens: Modern Code Reviews in Open-Source Projects: Which Problems Do They Fix? in 11th Working Conference on Mining Software Repositories (MSR), Hyderabad (India), 2014.*

[2] *Mika Mäntylä and Casper Lassenius. What Types of Defects Are Really Discovered in Code Reviews? IEEE Transactions Software Engineering, 35(3):430–448, 2009.*


## License
This work is licensed under the Creative Commons Attribution 4.0 International License. To view a copy of this license, visit [http://creativecommons.org/licenses/by/4.0/](http://creativecommons.org/licenses/by/4.0/) or send a letter to Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.

