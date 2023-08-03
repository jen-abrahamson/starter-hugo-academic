---
title: IARPA SMART Research
summary: Research on developing methods to automate the broad-area search of multi-source satellite imagery to detect, monitor, and characterize the progression of anthropogenic or natural processes.
date: "2016-04-27T00:00:00Z"


image:
  caption: United Emirates
  focal_point: Smart


---
## **MUTATED: Modeling and Understanding using Temporal Analysis of Transient Earth Data**
&nbsp;

For my research assistantship, I am a member of the MUTATED team. The MUTATED team is part of IARPA's (Intelligence Advanced Research Projects Activity) [Space-Based Machine Automated Recognition Technique (SMART) Program]((https://www.iarpa.gov/research-programs/smart) working to automate broad-area search of multi-source satellite imagery to detect, monitor, and characterize the progression of anthropogenic or natural processes.

To address this goal, our team has been working extensively on developing a novel online change detection algorithm. This algorithm, termed roboBayes, was based on the established Bayesian Online Changepoint Detection Algorithm (BOCPD, Adams and MacKay 2007) but was created and implemented specifically for remote sensing change detection by team member Laura Wendelberger (Wendelberger et. al 2021). My work on this algorithm is outlined below:

**Outlier Detection** \
To help address the issue of outliers in our data, due to clouds or other sources of atmospheric interference, I implemented two different spike filter options in the pre-processing portion of the roboBayes pipeline. The first, is a lagging spike filter which uses a moving window of the previous values compared to the next data observation in order to flag a spike, or outlier, that is outside of a set standard deviation threshold. The second spike filter, is a traditional moving window spike filter where the moving window looks at the center data point of the window and flags a spike, or outlier, that is outside of a set standard deviation threshold.


**Heuristics-Based Filtering** \
To aid in eliminating false positives and classifying changes related to heavy construction, I developed a heuristics-based filter in the post-processing portion of the roboBayes pipeline. To determine what remote sensing signals and model coefficients were indicative of heavy construction, I performed unsupervised K-means clustering of all model coefficients across multiple regions for all signals that contained a change point. These coefficients included the model mean, amplitude, and variance for each signal. This helped me to target signals that were most important for heavy construction classification to create a parameter filter that improved our precision across regions while still maintaining high levels of recall.

**Machine Learning Change Characterization** \
To create a method more robust than the heuristic-based filters established previously, I developed a machine learning-based characterization module where I tested Random Forest and Extreme Gradient Boosting Methods with a variety of features for classifying changes as construction or not construction. These models were trained using detected changes from regions all across the globe and showed significant improvement in F1 scores for heavy construction change detection.

### Associated Articles 

* [Spotting Objects From Space Is Easy. This Challenge Is Harder](https://www.wired.com/story/spotting-objects-from-space-is-easy-this-challenge-is-harder/) 
* [New IARPA-Funded Research Will Improve Accuracy and Efficiency of Analyzing Geospatial Imagery Across Large Scales](https://cnr.ncsu.edu/geospatial/news/2021/02/08/new-research-will-improve-accuracy-efficiency-of-imagery-analysis/)

---
