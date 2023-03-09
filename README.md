# SABABA (Score-bug Annotations in BAsketBAll)
the SABABA dataset comprises of numerous score bugs from multiple basketball leagues. 
While some score bugs share comparable geometric dimensions, they differ in attributes such as background colors, font sizes, and text values. 
SABABA dataset consist of 1168 score bug images. We split the dataset into three subsets: train, validation and test. 
In train set we have 584 samples, in validation set we have 140 samples and in test set, 444 samples.
Needless to say, but test set was not part of the training phase, it was only for evaluate models performance. In order to generate ground truth annotations, we adopted a manual annotation process and hand-crafted score bug template matching
structure. We asked professionals annotators to draw a score bug template and its elements ( and their labels) and run template matching algorithm over many frames. For score
bug element classification task, each sample in SABABA dataset contains a relevant bounding box information and label.


![000BAD5B-30C2-4DB5-9DC1-7DA0A41C1567_1](https://user-images.githubusercontent.com/23358024/223979082-2b065e43-6e56-4c24-9816-8577bfbc2027.png)

![2F4A98EC-5C44-4170-B799-7E25125B79D6_1](https://user-images.githubusercontent.com/23358024/223979103-c522b1c9-dabf-408a-ba4e-e4ab9a1b6068.png)

![A6C23AC3-36A7-4D60-8C26-64AC05EC1104_1](https://user-images.githubusercontent.com/23358024/223979186-1b9ba98a-4744-4596-9b60-be103a697665.png)
