# k-means clustering algorithm in Haskell

kmeans-vector is a Haskell library to perform the k-means clustering algorithm. It is based on the very efficient 'vector' library.

Feel free to contribute, may it be features, performance improvements, etc.

Performances
------------

*kmeans-vector* is much faster than the existing [kmeans](http://hackage.haskell.org/package/kmeans) package. For example, the kmeans package performs k-means on 10000 2D points with k=5 in 21.099s while kmeans-vector does the same in 6.605s. For 50000 3D points, with k=5 still, kmeans-vector performs in 47.853s while I Ctrl+C'd the kmeans version after 6 minutes and a half.

Author
------

This library is written and maintained by Alp Mestanogullari,
<alpmestan@gmail.com>