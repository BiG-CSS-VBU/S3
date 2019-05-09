# S3
STR Seed Selection Algorithm
Short Tandem Repeats(STR) are the repeatition of short DNA motif ranging in 1 to 6 nt 
in tandem over the genomes of complex organisms. STRs are well studied for their wide-
-ranging significance in various applications. Identification of STR loci in long DNA
sequences are vital for the applications in the area of genetic linkage analysis, DNA
profiling for cancer diagonis, kinsap analysis etc.
In this repository we have uploaded two files(including this).
1. README.md (this file)
2. s3( the executable)
*************************************************************************************
The following section will describe how to use the executable to extract STR loci from
DNA sequences.
The executable s3 is compiled on a computer having Intel(R) Core(TM) i5-5200U CPU @ 2.22GHz 
and 4 GB RAM runing Ubuntu 16.2 using gcc compiler. The executable can run on Linux environ
-mnet at this moment.
The syntex of running S3

$./S3 seq.txt 

Current implementation of the algorithm S3 supports the following options

-l : it is used to input the cutoff value, that is the minimum length of STR

-n : it is used to input the minimum motif length (1)

-m : it is used to input maximum motif length (current implemetation support maximum value of m =6)

-a : it use to specify whether atomic(1) or non-atomic(0) motifs are to be considered

-p : it is used to specify whether the result include the partial motif(1) or exclude(0)


