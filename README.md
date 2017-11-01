# ERA
Elastic Range (ERA) is a disk-based suffix tree construction method. ERA works efficiently with very long strings that are much larger than the available memory. ERA partitions the tree construction process horizontally and vertically and minimizes I/Os by dynamically adjusting the horizontal partitions independently for each vertical partition, based on the evolving shape of the tree and the available memory. Where appropriate, ERA also groups vertical partitions together to amortize the I/O cost. We developed a serial version; a parallel version for shared-memory and shared-disk multi-core systems; and a parallel version for shared-nothing architectures. 
Full paper at https://arxiv.org/abs/1109.6884
The code was written by Dr. Amin Allam (http://scholar.cu.edu.eg/aminallam/)
