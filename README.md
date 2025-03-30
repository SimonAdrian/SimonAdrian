### What I do

I am a researcher in **IT Security**, currently finalizing my PhD on **automated architectural security analysis techniques** for microservice applications. 
My work involves the creation of tools that can support developers and analysts in security-related software engineering tasks.

This profile holds all code, data, and replication packages for the roughly dozen publications that I (co-)authored.
The publications are listed on my [Google Scholar](https://scholar.google.com/citations?user=5kAe62IAAAAJ&hl=en).

### Main projects
The following repositories are the most important outcomes of my PhD:

- [**Code2DFD**](https://github.com/tuhh-softsec/code2DFD) - automatically extracts security-enriched dataflow diagrams (DFDs) from the source code of java microservice applications. 
The DFDs improve the persormance of manual security analysis tasks (as shown in [this publication](https://arxiv.org/pdf/2401.04446)) and are the input to the MicroCertiSec tool described below. We have compared Code2DFD to similar tools in [this publiation](https://arxiv.org/abs/2412.08352) and found, that it outperforms all comparable tools.

- [**MicroCertiSec**](https://github.com/tuhh-softsec/microCertiSec) - automatically checks architectural security rules of microservice applications via the DFDs extracted with Code2DFD or other architecture recovery tools. 
Rules can be expressed with a dedicated rule specification language I created for this purpose.
The tool produces a binary rule verdict as well as explainability for its analysis, i.e., evidence for the decision process that led to the verdict.

- [**microSecEnD**](https://tuhh-softsec.github.io/microSecEnD/) - is a dataset of manually created DFDs of microservice applications. 
Creating the models is an important preliminary for research in the domain of model-based security analysis.
Me and other researchers rely on this data to test our newly created tools.


### Contact
Feel free to contact me if you have questions, suggestions, collaborations, or anything else:

Mail: s\***n.sch\***der@tuhh.de (fill in my name) \
LinkedIn: [Simon Schneider](https://www.linkedin.com/in/simon-s-6765261b8/)

