# SABABA (Score-bug Annotations in BAsketBAll)
the SABABA dataset comprises of numerous score bugs from multiple basketball leagues. 
While some score bugs share comparable geometric dimensions, they differ in attributes such as background colors, font sizes, and text values. 
SABABA dataset consist of 1168 score bug images. We split the dataset into three subsets: train, validation and test. 
In train set we have 584 samples, in validation set we have 140 samples and in test set, 444 samples.
Needless to say, but test set was not part of the training phase, it was only for evaluate models performance. In order to generate ground truth annotations, we adopted a manual annotation process and hand-crafted score bug template matching
structure. We asked professionals annotators to draw a score bug template and its elements ( and their labels) and run template matching algorithm over many frames. For score
bug element classification task, each sample in SABABA dataset contains a relevant bounding box information and label.
