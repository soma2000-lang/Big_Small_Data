# Big_Small_Data

MinHash	estimate Jaccard similarity and cardinality
Weighted MinHash	estimate weighted Jaccard similarity
HyperLogLog	estimate cardinality
HyperLogLog++	estimate cardinality



The following indexes for data sketches are provided to support sub-linear query time:

MinHash LSH	MinHash, Weighted MinHash	Jaccard Threshold
MinHash LSH Forest	MinHash, Weighted MinHash	Jaccard Top-K
MinHash LSH Ensemble	MinHash	Containment Threshold
HNSW	Any	Custom Metric Top-K
