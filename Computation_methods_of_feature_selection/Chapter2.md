# 2.1 introduction #

**1. 为什么我们需要 feature selection in UNsupervised learning**

​	1) unlabeled 的数据多，维度大，feature selection有需求

​	2)  多余的feature维数会使得所需要的采样样本数增加（即密度小）

**2. unsupervised feature selection 定义**

**3.unsupervised feature selection trouble**

​          1) without any labeled information

​          2) need to define what "interesting" and "natural" mean in the form of criterion or objective function

# 2.2 Clustering#

**1.some hierarchical clustering algorithms are mention in reference**

**2. k-means**

​          1) two type of k-means that are different in when to update the cluster centroids

**3.Finite Mixture Clustering**

​          1) GMM is a typical FMC

# 2.3 Feature Selection#

​     feature selection has two main components 

**1.feature search**

​          这里提及的search方法也适用于supervised

​          1) branch and bound algorithm ( curse of dimensionality )

​          2) SBS and SFS

​          3) SBFS and SFFS

**2.feature subset evaluation **

​          1) key problem: deciding the evaluation criteria

​          2) what is irrelevant and redundant ( using two figures )

# 2.4 Feature Selection for Unlabeled Data#

​     The difference between wrapper and filter methods is that wrapper method evaluate subset by clustering algorithms

**1.Filter Methods**

​          1) three filter approaches to remove irrelevant features

​          2) feature cluster to remove redundancy

​          3) feature transformation ( PCA, <font color="#8b0000">Projection pursuit,  ICA</font> )

**2.Wrapper method**

​          There are two issues involved in wrapper method

​          1) Feature subspaceshave different underlying numbers of clusters

​          2) Feature evaluation criterion should not be biased with respect to dimensionality

​               # different criterion perfer different dimensions.

​               # clustering method deals with defining what "natural" means, and feature selectio criterion defines what "interestingness"means

​               # a cross-projection scheme is proposed

​               # alterative in finding the natural cluster or finding well-separated cluster

​                <font color="#8b0000"># Scatter separability is similar to the criterion function in discriminant analysis</font>

​              

# 2.5 Local Approaches#

​	<font color="#8b0000" >这一块都没咋看懂，Subspace Clustering可能就是以前上课讲过的密度聚类，但是后一种就不太懂了</font>

1. Subspace Clustering

​          

1. Co-Clistering/Bi-Clustering