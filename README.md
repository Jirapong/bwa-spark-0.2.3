bwa-spark-0.2.3
===============
Development NOTE:
(1) Native execution support (using JNI) for some performance critical parts
(2) The order after sorting INFLUENCES the results. The result will be slightly different from the original C version.
    This occurs in MemChainToAlign(), MemSortAndDedup() and MemMarkPrimarySe().
(3) Tree ordering influences results... (B-tree: original C implementation  V.S. RB-tree: our implementation)
(4) The goal of 0.2.2 - pair end implementation (done)
