# pulsar-star-classification

A pulsar is a highly magnetized rotating compact star that emits beams of electromagnetic radiation out of
its magnetic poles. This radiation can be observed only when a beam of emission is pointing toward Earth (similar to the
way a lighthouse can be seen only when the light is pointed in the direction of an observer).

## Dataset

HTRU2 is a data set which describes a sample of pulsar candidates collected during the High Time Resolution Universe
Survey (South). The data set shared here contains 16,259 spurious examples caused by RFI/noise, and 1,639 real pulsar
examples. Each candidate is described by 8 continuous variables, and a single class variable.

## Clasification

Implemented different classification algorithms like Gaussian Discriminant Analysis algorithm, which acted as our baseline for the supervised
learning methods. This algorithm was provided with the entire dataset. We then applied Random Forest, using Python’s
Scikit-learn library.

## Clustering

After implementing supervised learning methods, we applied unsupervised learning methods to further categorize the true
pulsar stars in our dataset. First, we implemented K-means clustering, which acted as our baseline for unsupervised learning. We
then applied Agglomerative Clustering.
