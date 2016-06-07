---
layout: post
title:  "Generally Useful Terms"
date:   2015-03-25 00:14:00
categories: CyVerse terms
---

Depending on your specialty coming into the lab, you may not need _all_ of the terms on this page. You may not need any! Either way feel free to skip to the 
relevant section for whatever information you may be lacking: Biology Terms, Statistics Terms, Computer Science Terms, next page.

#Biology Terms

* Genotype: The set of genes an organism possesses.
* Phenotype: The physical characteristic of an organism. Though normally biologists refer to a collection of physical characteristics in defining phenotype, our typical studies limit the phenotype definition strictly to quantitative 
traits such as height or weight. Most tools only use one of these quantitative characteristics for analysis for the sake of consistency and for statistical accuracy, though other options for phenotype are entirely possible 
(e.g. binary options like disease/no disease).      
* GWAS: Stands for _G_enome _W_ide _A_ssociation _S_tudies. Genome wide association studies examine variations in gene structure (genotypes) to see if these variations can be associated with certain physical traits or phenotypes. Because these studies
involve entire genetic sequences, large sample sizes with a high number of individuals are required for success. The Stapleton Lab is focused largely on this area of research.   
* SNP: Stands for _S_ingle _N_ucleotide _P_olymorphism. 
* QTL: Stands for _Q_uantitative _T_rait _L_oci analysis. 
* GxE: Stands for _G_enotype _E_nvironment interaction. 

#Statistics Terms

* _Variable:_ As the name implies, a variable varies from object to object. To be specific, a variable is a symbol representing potentially any characteristic or object that can be either measured or counted. 
Some basic examples of variables (when dealing with people) might include eye color, height, or the number of pets one owns. 
* _Quantitative vs. Qualitative:_ A quantitative variable is a value that can be *quantified*, or measured and represented numerically. Height or weight are good examples of quantitative traits. Quantitative variables can
be either discrete-only taking on a set number of values-or continuous-able to take on any value within a certain numerical range.  
* _Distribution:_ The description of the underlying observed or theoretical frequency of certain values occurring for a given variable. These frequencies, like the variables they describe, may be
either discrete or continuous. Some well known discrete distributions include binomial and geometric. Continuous distributions include the normal distribution (AKA the "bell curve") and
the gamma distribution.
* _Hypothesis Testing:_ A statistical method for testing the probability of a given hypothesis being true. A hypothesis test deals with both a *null hypothesis* (the hypothesis being tested, generally says that findings are
produced by chance) and an *alternative hypothesis*(a possible trend or hypothesis explaining the data formation, typically says that findings are the results of some difference or trend in data). The five steps of a hypothesis test are:
	1) State hypotheses
	2) Determine significance level to compare p-value against (usually 0.05)
	3) Calculate test statistic (standardized value of your sample's attribute assuming the null hypothesis is true)
	4) Calculate p-value
	5) State the conclusion
* _P-value:_ The value one refers to when making a final conclusion on certain statistical tests, particularly hypothesis tests. To be specific, a p-value is the probability of obtaining a certain sample (i.e. the sample
chosen for the test) under the assumption that the null hypothesis is true. Since a p-value is a probability, it will always lie between 0 and 1. If a p-value is small, the probability of your findings being produced under the null hypothesis is small, meaning that the null hypothesis probably isn't true.
Thus, if a p-value is below a specified significance level, the null hypothesis of your test may be rejected.
* _Statistical Significance:_ Typically used when describing a hypothesis test for differences in samples,  
* _Correlation:_ The measurement of the strength and direction of a linear relationship between two quantitative variables. Correlation is typically indicated by the correlation coefficient statistic *r*, and this statistic can take any
value from -1 to 1. A positive correlation (*r* value between 0 and 1) indicates that as one variable increases, the other tends to increase also. In contrast, a negative correlation (between -1 and 0) indicates that
as one variable increases, the other tends to decrease. Note the keyword "tends" in the previous explanations. Correlations guarantee nothing with respect to increase or decrease of variable values. Furthermore, and
this is an important point, *correlation does not equal causation!* Meaning that just because two variables are related does not mean that one necessarily causes another to increase or decrease.

#Computer Science Terms
* _Quality Control:_ The process of making sure software is working correctly. Quality Control typically includes a series of tests to measure software performance and/or ease of use. Developers and tester may have 
a certain set of standards that the tester may want the software to adhere to, or a list of criteria that the program must satisfy. 
* _Documentation:_ The necessary documents explaining how to use the software. Typically, documentation includes instructions for using each of the functions included and perhaps a tutorial for going through
some of the main features of a given program. 
* _Version:_ An iterative release of a computer program. Newer versions of computer software may include more features, be easier to use, or be less prone to errors than their predecessors. 
* _API:_ Stands for _A_pplication _P_rogramming _I_nterface. A set of tools, resources, or routines which make developing applications on a given system easier. For example, iPlant's Agave API allows for easier development
of scientific apps on the Stampede supercomputer.
* _Permissions_: The authorization to read, write, or execute a program. Certain programs or files may not require access by everyone, so developers may set up permissions on their code such that only a certain group of people may use it freely.
While certain permission barriers may be bypassed (e.g. through the "sudo" command on Linux or "Run as administrator" on Windows), permissions are usually set up for a reason, so it's best to just contact the developer if you need access to something
blocked off. 
* _Github:_ A version-control website frequently used for collaboration on software design. Github allows for both public and private access to project repositories and keeps a history
of different updates that users make to their programs. Anyone can make contributions to a public repository on Github. It also allows for you to set up webpages based on a project or organization and allows transfer of software permissions to other users or organizations.

Now that you have a basic grasp some on the lingo, we can move on to the main iPlant information.

Click here to move on to the Data Store tutorial!