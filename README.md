# Splunk_ML_Toolkit_Algorithms
Additional MLTK Algorithms

First algorithm added is the OPTICS clustering algorithm.

This is an improvement in some ways on the DBSCAN algorithm for specific use cases. 

The scikit-learn implementation (https://scikit-learn.org/stable/modules/generated/sklearn.cluster.OPTICS.html) uses the default settings, with min_pts=5 and using euclidean distance for measurement. Additionally, max_eps is a usable feature to decrease computation time.


Need to check if you've registered your algorithm properly? Run this:

|  rest /servicesNS/nobody/-/configs/conf-algos
|  table title
|  search title="OPTICS"

