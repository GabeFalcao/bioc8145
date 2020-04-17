## Assignment 5: ATAC-seq

Due: Friday 04/24/02

Total points: 100

1. Read [From reads to insight: a hitchhiker’s guide to ATAC-seq data analysis](https://doi.org/10.1186/s13059-020-1929-3) (10pts)

2. Read [Chromatin accessibility and the regulatory epigenome](https://doi.org/10.1038/s41576-018-0089-8) (10pts)

3. Go through the [First Steps vignette](first_steps_tutorial.md) in this repository, and answer the following questions:

3-1. Use the `tail` command to find the last sequences in the R1 example file. What is the sequence of the final read in the file? (10pts)

3-2. Try using `time zcat {FILE} | head` to get the command runtime. Is the `tail` command faster, slower, or the same speed as the `head` command? Why might this be the case? (Hint: use `man zcat` to learn about what `zcat` is doing). (10pts)

3-3. How many of the reads in the tutorial aligned to chromosome 1? (10pts)

3-4. Which chromosome had the highest number of called peaks? (10pts)

4. Go through the [R Analysis vignette](R_analysis_tutorial.md) in this repository, and answer the following questions:

4-1. How many peaks are there in this BED file? (10pts)

4-2. What is the minimum, median, and maximum width of peaks in this file? (10pts)

4-3. Are these differentially accessible regions tissue-specific? Explain your answer. (10pts)

4-4. Run this bed file through [LOLAweb](http://lolaweb.databio.org), [coloc-stats](https://hyperbrowser.uio.no/coloc-stats/), or [GREAT](http://great.stanford.edu). List a result you find interesting. (10pts)


5. Bonus: Paste a list of all available remote assets hosted by the refgenie server for the 'mm10' genome (Hint, you can use `refgenie --help` `refgenie listr --help` to see how the command works). (10pts)