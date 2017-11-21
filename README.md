# Replication Package for "Analyzing a Decade of Linux System Calls"

Mojtaba Bagherzadeh, Nafiseh Kahani, Cor-Paul Bezemer, Ahmed E. Hassan, Juergen Dingel and James R. Cordy  
[Empirical Software Engineering journal, 2017](https://doi.org/10.1007/s10664-017-9551-z)

Abstract: Over the past 25 years, thousands of developers have contributed more than 18 million lines of code (LOC) to the Linux kernel. As the Linux kernel forms the central part of various operating systems that are used by millions of users, the kernel must be continuously adapted to the changing demands and expectations of these users. The Linux kernel provides its services to an application through system calls. The combined set of all system calls forms the essential Application Programming Interface (API) through which an application interacts with the kernel. In this paper, we conduct an empirical study of 8,770 changes that were made to Linux system calls during the last decade (i.e., from April 2005 to December 2014). In particular, we study the size of the changes, and we manually identify the type of changes and bug fixes that were made. Our analysis provides an overview of the evolution of the Linux system calls over the last decade. We find that there was a considerable amount of technical debt in the kernel, that was addressed by adding a number of sibling calls (i.e., 26% of all system calls). In addition, we find that by far, the ptrace() and signal handling system calls are the most challenging to maintain. Our study can be used by developers who want to improve the design and ensure the successful evolution of their own kernel APIs.

## Bibtex

```bibtex
@Article{Bagherzadeh2017,
author="Bagherzadeh, Mojtaba
and Kahani, Nafiseh
and Bezemer, Cor-Paul
and Hassan, Ahmed E.
and Dingel, Juergen
and Cordy, James R.",
title="Analyzing a decade of Linux system calls",
journal="Empirical Software Engineering",
year="2017",
month="Oct",
day="13",
issn="1573-7616",
doi="10.1007/s10664-017-9551-z",
url="https://doi.org/10.1007/s10664-017-9551-z"
}
```

## Data

- [A manual classification of a decade of system call-related commits.](https://github.com/SAILResearch/replication-linux_systemcalls/releases/download/v1.0/systemcalls_evolution.tar.gz) This dataset contains the following:
  - A manual classification of a decade of system call-related commits
  - A manual categorization of system calls
  - The entropy of each system call
  - The heuristics that we used to filter out data
  - Several useful queries for analyzing the data
- [Full race graph](http://sailhome.cs.queensu.ca/replication/systemcalls_evolution/full_race_graph.pdf)
