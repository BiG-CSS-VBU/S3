# S^3
Algorithm STR Seed Selection(S^3): 

Short Tandem Repeats(STR) are the repeatition of short DNA motif ranging in 1 to 6 nt 
in tandem over the genomes of complex organisms. STRs are well studied for their wide-
-ranging significance in various applications. Identification of STR loci in long DNA
sequences are vital for the applications in the area of genetic linkage analysis, DNA
profiling for cancer diagonis, kinsap analysis etc.
In this repository we have uploaded two files:
1. README.md (this file)
2. S^3(the executable code of the algorithm)
*************************************************************************************
The following section will describe how to use the executable code S^3 to extract STR loci from
DNA sequences.
The executable S^3 is compiled on a computer having Intel(R) Core(TM) i5-5200U CPU @ 2.22GHz 
and 4 GB RAM runing Ubuntu 16.2 using gcc compiler. The executable can run on Linux 
environmnet at this moment.

The syntex of running S^3

$./S3 seq.txt > output.txt

Here seq.txt is the input file that contains the DNA sequence from which we want to extract STRs 
and the output.txt will contain the output of S^3. Specifically, the start location, number of repeats, motif length and the motif itself of each of the STRs mined. 


Current implementation of the algorithm S^3 supports the following options

-l : it is used to input the cutoff value, that is the minimum length of STR

      (default value: 12)

-n : it is used to input the minimum motif length

      (default value: 1)

-m : it is used to input maximum motif length (current implemetation support maximum value of m =6)

      (default value: 6)


-p : it is used to specify whether the results include the partial motif(value 1) or exclude partial motif(value 0)

      (default value: 0)


