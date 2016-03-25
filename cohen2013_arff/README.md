We construct a attribute vector for each crater candidate using Haar-like attributes described by Papageorgiou 1998. These attributes are simple texture attributes which are calculated using Haar-like image masks that were used by Viola in 2004 for face detection consisting only black and white sectors. The value of a attribute is the
difference between the sum of gray pixel values located within the black sector and the white sector of an image mask. The figure below shows nine image masks used in our case study. The first five masks focus on capturing
diagonal texture gradient changes while the remaining four masks on horizontal or vertical textures.


This data has been put in the Weka arff format

http://www.cs.waikato.ac.nz/ml/weka/arff.html


==Citation==

Cohen, Joseph Paul, and Wei Ding. “Crater Detection via Genetic Search Methods to Reduce Image Features.” Advances in Space Research, 2013. doi:10.1016/j.asr.2013.05.010.

Cohen, Joseph Paul, Siyi Liu, and Wei Ding. “Genetically Enhanced Feature Selection of Discriminative Planetary Crater Image Features.” In Proceedings of the The 24th Australasian Joint Conference on Artificial Intelligence. Perth, Western Australia, 2011.
