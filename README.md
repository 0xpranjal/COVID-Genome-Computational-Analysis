# Computational Anaylysis of COVID-19 genome

<p  align="center"><img height="300" src = "https://raw.githubusercontent.com/Bhard27/COVID-Genome-Computational-Analysis/master/images_copy/wiki.png"></p>

This is a project based on the complete genome analysis of the COVID-19 (Sars-cov2) virus, taken from the Wuhan-Hu-1 isolate sample. I cleaned the genome sample to obtain an RNA sequence and I verified the number of base-pairs in the virus. Using the concept of Kolmogorov complexity, I was able to find the lower bound size of a compressed version of the COVID-19 virus. I was able to compress it into an 8.412 kb file using the "LZMA" algorithm. Then I converted the RNA sequence into a DNA string for applying the concepts of "Codons". This helped me to find the essential 20 different types of proteins that can be used to express the genome into the Protein sequence. Further, I made a decoder to make the genome into the Reading-Frame sequence. With the help of this reading frame sequence, I was able to extract the polypeptides and long-chain polypeptides in the virus. Then, I analyzed the Open Reading Frame(ORF) for the Sars-Cov-2 virus which has 10 different proteins that are responsible for the synthesis and catalytic process of COVID-19 in a human body. At last, I was able to verify the length of all the 10 proteins(ORF1a, ORF1b, Spike Glycoprotein, Membrane, ORF6, ORF7a, ORF8, ORF10) thus this project has the proof of all the scientific foundlings using Data science concepts.

## Kolmogorov complexity

Kolmogorov complexity of an object or algorithm is the length of its optimal specification. In some sense, it could be thought of as algorithmic entropy, in the sense that it is the amount of information contained in the object.

Kolmogorov complexity K of a string, relative to a Turing machine f of a string x, is Kf(x)=min{∣p∣:f(p)=x}.
It appears that the complexity depends both on f as well as x. This is, to some extent, unavoidable in the sense that the description really depends on the description language.
However, if the Turing machine is universal, the differences between the complexity of the string across such a Turing machine would be varying by constants.
This is known as the invariance theorem. The proof follows from the idea of encoding a Turing machine and then the program in that Turing machine. The first part (i.e. the encoded Turing machine) would not depend upon the string and is hence a constant.

x is incompressible if and only if K(x) ≥ x.

This project also opened the opportunity for me to explore and inspect if this virus was specially designed in a Laboratory or not. I did basic Data science operations on both samples of SARS and SARS-2 virus. Upon research, I found that the "Spike Glycoprotein" protein is present in both which acts as a catalyst for the virus while the genome was completely different and no evidence of modifications can be found.

Severe acute respiratory syndrome coronavirus 2 (SARS-CoV-2) is the strain of coronavirus that causes coronavirus disease 2019 (COVID-19), a respiratory illness. Colloquially known as the coronavirus, it was previously referred to by its provisional name, 2019 novel coronavirus (2019-nCoV). As described by the National Institutes of Health, it is the successor to SARS-CoV-1. SARS-CoV-2 is a positive-sense single-stranded RNA virus. It is contagious in humans, and the World Health Organization (WHO) has designated the ongoing pandemic of COVID-19 a Public Health Emergency of International Concern.

# Technologies Used
* ZLIB
* LZMA

Kaggle Submission : https://www.kaggle.com/pranjalb27/computational-predictions-of-protein-in-covid-19/data

## License

[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)
