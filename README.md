# Machine Learning for Social Sciences

## Instructor

[Reto Wüest](http://retowuest.net/) [<reto.wuest@unige.ch>]<br />
University of Geneva

## Course Description

With ever more data available in electronic form, automated methods of data analysis become increasingly important also in the social sciences. Machine learning refers to a set of methods that can automatically detect patterns in data, or "learn" from data. The uncovered patterns can then be used by the analyst to make accurate predictions and decisions under uncertainty.

This course will introduce participants to the fundamentals of machine learning. Students will leave the course with a thorough understanding of the core issues in machine learning (prediction and inference, supervised and unsupervised learning, overfitting, bias-variance trade-off), knowledge of some of the most widely used machine learning methods, and the ability to apply these methods in their own research. All course materials are available at <http://retowuest.net/recsm-2018/>.

## Software

The course will use the open-source software R, which is freely available for download at <https://www.r-project.org/>. We will interact with R through the user interface RStudio, which can be downloaded at <https://www.rstudio.com/products/rstudio/download/>.

## Prerequisites

Participants are expected to have a solid understanding of linear and binary regression models. The course will also assume at least a basic familiarity with the R statistical programming language.

## Schedule

A PDF of the syllabus is available [here](syllabus/syllabus-recsm-ml-2019.pdf).

### Session 1: Introduction to Machine Learning

#### July 8, 2019, 9:00-13:00

The first session will provide an introduction to machine learning. We will discuss the goals of machine learning (prediction, inference, or both), the difference between supervised and unsupervised machine learning, the problem of overfitting, and the bias-variance trade-off. We will then get to know a first class of important supervised learning methods, namely shrinkage methods (ridge regression and the lasso).

#### Class Schedule

| Time        | Topic                | Materials                                     |
|:----------- |:-------------------- |:--------------------------------------------- |
| 09:00-09:30 | Introductions and course overview | [Slides](slides/session-1/slides-recsm-ml-2019-s11.pdf) |
| 09:30-10:00 | Introduction to machine learning | Slides |
| 10:00-10:45 | Supervised learning and model accuracy | Slides |
| 10:45-11:15 | Break | |
| 11:15-11:45 | Shrinkage methods I: ridge regression | Slides |
| 11:45-12:15 | Shrinkage methods II: the lasso | Slides |
| 12:15-13:00 | Applications of ridge regression and the lasso | Lab Exercise &#124; Lab Solution |

#### Main Readings

- James et al., [*An Introduction to Statistical Learning*](http://www-bcf.usc.edu/~gareth/ISL/), chs. 2 (pp. 15-42) and 6 (pp. 214-228)

#### Recommended Readings

- James et al., [*An Introduction to Statistical Learning*](http://www-bcf.usc.edu/~gareth/ISL/), ch. 5 (pp. 175-186)
- Hastie et al., [*The Elements of Statistical Learning*](https://web.stanford.edu/~hastie/ElemStatLearn/), chs. 2, 3, and 7
- Shalev-Shwartz and Ben-David, [*Understanding Machine Learning*](http://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/), chs. 2, 5, and 13
- Bishop, *Pattern Recognition and Machine Learning*, ch. 12
- Provost and Fawcett, *Data Science for Business*, chs. 2 and 5

### Session 2: Classification and Regression Trees (CART)

#### July 9, 2019, 9:00-13:00

The second session will deal with tree-based methods, which are another important and highly flexible class of supervised learning methods. After an introduction to the basics of decision trees and a general discussion of the advantages and disadvantages of tree-based models, we will look at three specific widely-used tree-based methods: bagging, random forests, and boosting.

#### Class Schedule

| Time        | Topic                | Materials                              |
|:----------- |:-------------------- |:-------------------------------------- |
| 09:00-09:30 | Introduction to classification and regression trees | Slides |
| 09:30-10:00 | Advantages and disadvantages of trees | Slides |
| 10:00-10:45 | Bagging, random forests | Slides |
| 10:45-11:15 | Break | |
| 11:15-12:00 | Boosting | Slides |
| 12:00-12:30 | Application 1: classification and regression trees | Lab |
| 12:30-13:00 | Application 2: bagging, random forests, boosting | Lab |

#### Main Readings

- James et al., [*An Introduction to Statistical Learning*](http://www-bcf.usc.edu/~gareth/ISL/), ch. 8

#### Recommended Readings

- Hastie et al., [*The Elements of Statistical Learning*](https://web.stanford.edu/~hastie/ElemStatLearn/), chs. 9, 10, and 15
- Shalev-Shwartz and Ben-David, [*Understanding Machine Learning*](http://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/), ch. 18
- Lantz, *Machine Learning with R*, chs. 5 and 11
- Provost and Fawcett, *Data Science for Business*, ch. 3

### Session 3: Unsupervised Learning

#### July 10, 2019, 9:00-13:00

In the third session, we will move to unsupervised machine learning methods. We will cover two important unsupervised learning techniques: principal components analysis (PCA) and clustering analysis (*K*-means clustering and hierarchical clustering).

#### Class Schedule

| Time        | Topic                | Materials                              |
|:----------- |:-------------------- |:-------------------------------------- |
| 09:00-09:30 | Introduction to unsupervised learning | Slides |
| 09:30-10:15 | Principal components analysis (PCA) | Slides |
| 10:15-10:45 | *K*-means clustering | Slides |
| 10:45-11:15 | Break | |
| 11:15-12:00 | Hierarchical clustering | Slides |
| 12:00-12:30 | Application 1: PCA | Lab |
| 12:30-13:00 | Application 2: clustering methods | Lab |

#### Main Readings

- James et al., [*An Introduction to Statistical Learning*](http://www-bcf.usc.edu/~gareth/ISL/), ch. 10

#### Recommended Readings

- Hastie et al., [*The Elements of Statistical Learning*](https://web.stanford.edu/~hastie/ElemStatLearn/), ch. 14
- Shalev-Shwartz and Ben-David, [*Understanding Machine Learning*](http://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/), chs. 22 and 23
- Bishop, *Pattern Recognition and Machine Learning*, ch. 12
- Barber, [*Bayesian Reasoning and Machine Learning*](http://web4.cs.ucl.ac.uk/staff/D.Barber/pmwiki/pmwiki.php?n=Brml.HomePage), ch. 15
- Lantz, *Machine Learning with R*, ch. 9
- Provost and Fawcett, *Data Science for Business*, ch. 6
