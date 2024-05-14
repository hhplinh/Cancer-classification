# An assessment of Meta-Polyp and DUCK-Net models for polyp segmentation
Aimed to evaluate the performance of two segmentation models, Meta-Polyp and
DUCK-Net, in accurately segmenting polyps.

The models’ performance was assessed using the
Dice coefficient and Intersection over Union, metrics that
measure the overlap between the models’ predictions and
the ground truth masks. 

Findings revealed that Meta-Polyp
exhibited excellent performance on its training test and
unseen datasets, with no zero-value results, while DUCK-Net also performed well, albeit with slightly lower results
on one dataset and superior performance on another,
with some zero-value results. Both models encountered
difficulties with unclear polyp borders, small polyps, large
tissue blocks, and multiple polyps, and struggled with edge
cases in the testing dataset, with DUCK-Net being more
affected by these factors than Meta-Polyp.
