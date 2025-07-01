doubts:

1
1. define: Apache Spark's distributed computing


2
1. how does spark automatically parallelizes data operations across available cores and nodes
2. Difference between rdd and df

3
1. 'Traditional Python executes most operations sequentially, unless you manually implement multiprocessing or multithreading, which still doesn’t scale well beyond one machine.'
Why?
2. What is lineage information? How does PySpark (via Spark) maintain lineage information for all transformations?
3. If a node fails during execution, how does Spark recompute lost partitions using lineage, without restarting the entire job? What would happen if all nodes fail?

