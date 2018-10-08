# Rajesh-Task
Programming task



Please find the below execution steps:

Please execute below command from command prompt where App.jar is placed.
cmd> java -cp App.jar EBI01286.rajesh.App pdb_seqres.gz 5

Input	:	<no input parameters>
result	:	Please provide arguments (one or more gzip compressed Fasta files and number of worker threads)

Input	:	pdb_seqres.gz	
result	:	Please provide number of threads and in numeric.

Input	:	pdb_seqres.txt 3	
result	:	Please provide only .gz files.

Input	:	pdb_seqres.gz sd
result	:	Please provide number of threads and in numeric.

Input	:	pdb_seqres.gz 3 <If file is not at specified location)
result	:	Exception while performing Task: pdb_seqres.gz (The system cannot find the file specified).

Input	:	pdb_seqres.gz 5
result	:	REPORT.TXT, SEQUENCE.FASTA.GZ files will be generated with expected results.


please delete the files (if generated) before running new test cases.

Please find the files that I have ran positive test case and generated output files(REPORT.TXT, SEQUENCE.FASTA.GZ) based on input file pdb_seqres.gz(pdb_seqres1.fasta, pdb_seqres2.fasta).
