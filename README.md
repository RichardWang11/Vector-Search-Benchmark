# Vector-Search-Benchmark&Datasets
   a benchmark contains all vecor searchs (include dense vector, sparse vector, filter vector search...)
# Benchmarks
## Billion-scale BigANN benchmarks
### Results of the Big ANN: NeurIPS’23 competition(https://arxiv.org/pdf/2409.17424)
*Track 1: *Filtered Search Track*
*Track 2: *Out-Of-Distribution(OOD) Track*
       The query vectors and vectors in database have different distributions in the share vector space.
   ![image](https://github.com/RichardWang11/Vector-Search-Benchmark/blob/main/OODtrack.png)
*Track 3: *Sparse Track*
      Given a sparse query vector, the index should return the top-k results according to the maximal inner product between the vectors.
*Track 4: *Streaming Track*
      While in practice such indices must support concurrent operations, we allow the index to batch process one class of operations at a time for simplicity. The index startswith zero points and must implement a “runbook” – a sequence of batches of insertion operations, deletion operations, and search commands in a ratio of roughly 4:4:1.

### CANDY (https://arxiv.org/pdf/2406.19651)
   A Benchmark for Continuous Approximate Nearest Neighbor Search with Dynamic Data Ingestion
   Evaluating vector search performance to adapt to changing data pattern, integrating new optimizations (e.g. ML-driven inference) to replace traditional heuristic scans, and improved distance computation methods.
### Datasets
Reference this paper, we category the datasets into 5 types (https://ieeexplore.ieee.org/abstract/document/8681160):

Name | n*(10^3) | d | RC | LID | Type
---- | ---- | ----
Nus* |269 |500| 1.67| 24.5| Image



SIFT1M,SIFT100M; Deep1M; GIST1M;Msong;Audio;UQ-V;Crawl;GloVe;Enron
    
