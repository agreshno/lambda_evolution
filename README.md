# Evolution of CI lambda protein

**Bacteriophages** are viruses who infect bacterial cells and utilize their machinery for reproduction. 

These viruses can exist in two modes: 
- **Prophage mode** - a viral genome is inserted in a bacterial chromosome, this is an inactive mode. Expression of all genes (like capsid proteins) beside one is repressed; the only active gene is a repressor.
- **Lytic mode** - when viral genes are active. A virus generates multiple copies of its genome and makes a bacterial cell synthesize a number of capsid proteins. Finally, a bunch of new viral particles leaves the host cell (by killing the cell) and infect other cells.

![life cycle](https://github.com/agreshno/lambda_evolution/blob/master/figures/1.2.jpg)

**Figure 1.** Life cycle of bacteriophages

The central regulator of this process is **the repressor**, which controls the expression of other bacterial genes. It regulates it by binding with a special regulatory region - **an operator**, which usually is a part of **a promoter** (or several promoters). Through binding to an operator, it prevents recruiting of RNA polymerase and thus downregulates gene expression [1]. 

![reg region](https://github.com/agreshno/lambda_evolution/blob/master/figures/1.4.jpg)

**Figure 2.** Structure of a regulatory region in pahge lambda.

![CI lambda](https://github.com/agreshno/lambda_evolution/blob/master/figures/1.6.jpg)

**Figure 3.** Structure of CI lambda regulatory protein.

![CI regulation](https://github.com/agreshno/lambda_evolution/blob/master/figures/1.19.jpg)

**Figure 4.** Regulation with CI lambda

In my work, I would like to investigate the evolution of the repressor protein (CI protein) which plays a crucial role in regulating the life cycle of a phage. I would like to start with CI protein of phage lambda and then answer the following questions:

- What are viruses who have homologs of CI proteins in their genomes? 
- How do these CI proteins are different and relate to each other?
- Can we relate these proteins to their operators?

The plan is to:
- BLAST CI lambda sequence against viral genomes
- Build a phylogenetic tree based on sequences of CI homologs
- Find operator regions for these homologs in accessible viral genomes
- Build a phylogenetic tree based on operator regions of CI homologs

**References:**

[1] - A Genetic Switch, Third Edition, Phage Lambda Revisited. M. Ptashne. Cold Spring Harbor Laboratory Press. 2004. 154 pages. ISBN 0-87969-716-4.
