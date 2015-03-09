# The Logic of AMR: Practical, Unified, Graph-Based Sentence Semantics for NLP

Tutorial at [NAACL-HLT 2015](http://naacl.org/naacl-hlt-2015/)

May 31, 2015 in Denver, Colorado

Nathan Schneider, Jeffrey Flanigan, and Tim O'Gorman

## Abstract

The [Abstract Meaning Representation](http://amr.isi.edu/) formalism is rapidly emerging as an important practical form of structured sentence semantics which, thanks to the availability of large-scale annotated corpora, has potential 
as a convergence point for NLP research. This tutorial unmasks the design philosophy, data creation process, and existing algorithms for AMR semantics. It is intended for anyone interested in working with AMR data, including parsing text into AMRs, generating text from AMRs, and applying AMRs to tasks such as machine translation and summarization.

The goals of this tutorial are twofold. First, it will describe the nature and design principles behind the representation, and demonstrate that it can be practical for annotation. In __Part I: The AMR Formalism__, participants will be coached in the basics of annotation so that, when working with AMR data in the future, they will appreciate the benefits and limitations of the process by which it was created. Second, the tutorial will survey the state of the art for computation with AMRs. __Part II: Algorithms and Applications__ will focus on the task of parsing English text into AMR graphs, which requires algorithms for alignment, for structured prediction, and for statistical learning. The tutorial will also address graph grammar formalisms that have been recently developed, and future applications such as AMR-based machine translation and summarization.

Participants with laptops are encouraged to bring them to the tutorial.

## Instructors

### Part I: The AMR Formalism

__[Nathan Schneider](http://nathan.cl)__ is an annotation schemer and computational modeler for natural language. He has been involved in the design of the AMR formalism since 2012, when he interned with Kevin Knight at ISI. 
His 2014 [dissertation](http://www.cs.cmu.edu/~nschneid/thesis/) introduced a coarse-grained representation for lexical semantics that facilitates rapid annotation and is practical for broad-coverage statistical NLP. He has also worked on [semantic parsing for the FrameNet representation](http://www.ark.cs.cmu.edu/SEMAFOR/) and other forms of [syntactic](http://www.ark.cs.cmu.edu/TweetNLP/)/[semantic](http://www.ark.cs.cmu.edu/ArabicNER/) annotation and processing for social media text. For most of these projects, he led the design of the annotation scheme, guidelines, and workflows, and the training and supervision of annotators.

__[Tim O'Gorman](https://timjogorman.wordpress.com/)__ is a third year Linguistics Ph.D. student at the University of Colorado – Boulder, working with Martha Palmer.  He manages CU-Boulder's AMR annotation team, and participated in the Fred Jelinek Memorial Workshop in Prague in 2014, working on mapping the Prague tectogrammatical layer to AMRs. His research areas include implicit arguments, semantic role projection, and linking sentence-level semantics to discourse.

### Part II: Algorithms and Applications

__[Jeffrey Flanigan](http://www.cs.cmu.edu/~jmflanig/)__ is a fifth year Ph.D. candidate at Carnegie Mellon University. He and his collaborators at CMU built the first broad-coverage [AMR parser](https://github.com/jflanigan/jamr/). He also participated in the Fred Jelinek Memorial Workshop in Prague in 2014, working on cross-lingual parsing and generation from AMR. His research areas include machine translation, generation, summarization, and semantic parsing.
