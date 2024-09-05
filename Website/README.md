# Deep Fingerprinting

This repository contains a dataset for 95 websites, each with ~1000.

### Dataset Overview

Due to the limitations of GitHub's storage capacity, the dataset has been uploaded to OneDrive. You can access it [here](https://waynestateprod-my.sharepoint.com/:f:/g/personal/hi8289_wayne_edu/EjdxG7raovZAhEYoxA-9nvAB7aFg4vV--q0LGl0OCRnUUQ?e=ltf0oW).

### Dataset Contents

The dataset includes **~105k text files** representing **95 websites** with **~1000 traces**:

```
data/
├── 0  // traffic features for website 0
├── 0-1  // website 0
├── ...
├── 0-1111  // webiste 0
├── ...
├── ..
├── ..
└── 94-*  // website 94
```
* For each file, each row captures the features of a single packet in a two-column text format. The first column represents the timestamp, while the second column indicates the packet length, where +1 signifies outgoing packets and -1 denotes incoming packets.


### References

To explore more about the dataset and classification details, here are some useful links:
* [Deep Fingerprinting](https://dl.acm.org/doi/pdf/10.1145/3243734.3243768)




