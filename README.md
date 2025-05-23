# Modern Methods of Applied Statistics (Spring 2024) STAT 34800
Instructor: Aaron Schein <br>
TAs: Jimmy Lederman, Sean O'Hagan, Jinwen Yang <br>

Term: Spring 2024 <br>
The University of Chicago

---

## Logistics:
- Time: Tuesday and Thursday, 3:30am-4:50pm
- Place: Eckhart room 133
- TA office hours: 
    - Jimmy: Mon 1:30-2:30pm (Jones 304)
    - Sean: Wed 3:00-4:00pm (Jones 304)
    - Jinwen: Fri 10:00-11:00am (Jones 304)
- Instructor office hours:
    - Aaron: Thurs 5:00-6:00pm (Searle 236)

## Assignments
- [Assignment 1: Bayesian linear regression](https://github.com/aschein/stat_348_2025/blob/main/assignments/hw1/hw1.ipynb). Due **Sunday April 6 at 11:59pm** on GradeScope. 
- [Assignment 2: Hierarchical models and Gibbs sampling](https://github.com/aschein/stat_348_2025/blob/main/assignments/hw2/hw2.ipynb). Due **Sunday April 13 at 11:59pm** on GradeScope.
- [Assignment 3: Mixture models and EM](https://github.com/aschein/stat_348_2025/blob/main/assignments/hw3/hw3.ipynb). Due **Sunday April 20 at 11:59pm** on GradeScope.
- [Assignment 4: HMMs and the sum-product algorithm](https://github.com/aschein/stat_348_2025/blob/main/assignments/hw4/hw4.ipynb). Due **Tuesday May 6 at 11:59pm** on GradeScope.
- [Assignment 5: Poisson matrix factorization and CAVI](https://github.com/aschein/stat_348_2025/blob/main/assignments/hw5/hw5.ipynb). Due **Wednesday May 14 at 11:59pm** on GradeScope.
- [Assignment 6: Neural networks and variational autoencoders (VAESs)](https://github.com/aschein/stat_348_2025/blob/main/assignments/hw6/hw6.ipynb). Due **Wednesday May 21 at 11:59pm** on GradeScope. 

## Schedule

### Lecture 1 (March 19): Review of decision theory & supervised learning
- Reading / resources:
    - Materials for L1-L3 of Matthew Stephens' course: [STAT 348 (Spring 2021)](https://dynalist.io/d/ehiGZbaDzYG4q9tJvuCrag3U#z=Hu-cB8VnWnu5IXOgZ-3MaF6C)
    - Chap 2 of [Elements of Statistical Learning](https://hastie.su.domains/ElemStatLearn/)
    - Chap 2 of [An Introduction to Statistical Learning with Applications in Python](https://www.statlearning.com/)
    - Chap 3 and 12 of [Advanced Data Analysis
from an Elementary Point of View](https://www.stat.cmu.edu/~cshalizi/ADAfaEPoV/ADAfaEPoV.pdf)
- Lecture materials: 
    - [Notebook](https://github.com/aschein/stat_348_2024/blob/main/lecture_materials/notebooks/W1_supervised_learning.ipynb)
    - [iPad notes](https://github.com/aschein/stat_348_2024/blob/main/lecture_materials/ipad_notes/lecture_1_ipad.pdf)

### Lecture 2 (March 21): Review of decision theory & supervised learning
- Reading / resources:
    - Materials for L1-L3 of Matthew Stephens' course: [STAT 348 (Spring 2021)](https://dynalist.io/d/ehiGZbaDzYG4q9tJvuCrag3U#z=Hu-cB8VnWnu5IXOgZ-3MaF6C)
    - Chap 3 of [Elements of Statistical Learning](https://hastie.su.domains/ElemStatLearn/)
    - Chap 5.1, 6.2, 7.1 of [An Introduction to Statistical Learning with Applications in Python](https://www.statlearning.com/)
    - Chap 7 of [Advanced Data Analysis
from an Elementary Point of View](https://www.stat.cmu.edu/~cshalizi/ADAfaEPoV/ADAfaEPoV.pdf)
- Lecture materials: 
    - [Notebook](https://github.com/aschein/stat_348_2024/blob/main/lecture_materials/notebooks/W1_supervised_learning.ipynb)
    - [iPad notes](https://github.com/aschein/stat_348_2024/blob/main/lecture_materials/ipad_notes/lecture_2_ipad.pdf)

### Lecture 3 (March 26): Intro to Bayesian modeling & decision theory
- Reading / resources:
    - Scott Linderman's [slides](https://github.com/slinderman/stats305c/blob/spring2023/slides/lecture01-bayes_normal.pdf) on Bayesian analysis of Gaussian models
    - Murphy (2007) ["Conjugate Bayesian analysis of the Gaussian distribution"](https://www.cs.ubc.ca/~murphyk/Papers/bayesGauss.pdf)
    - Jeffrey Miller's [slides](https://jwmi.github.io/BMB/5-Bayesian-linear-regression.pdf) on Bayesian linear regression
    - Chap 9 of ["Mathematics for Machine Learning"](https://mml-book.github.io/book/mml-book.pdf)
- Lecture materials: 
    - [Notebook](https://github.com/aschein/stat_348_2024/blob/main/lecture_materials/notebooks/W2_intro_bayes.ipynb)
    - [iPad notes](https://github.com/aschein/stat_348_2024/blob/main/lecture_materials/ipad_notes/lecture_3_ipad.pdf)

### Lecture 4 (March 26): Intro to Bayesian modeling & decision theory
- Reading / resources:
	- Chap 1 of Berger (1985) [_Statistical Decision Theory and Bayesian Analysis_](https://link.springer.com/book/10.1007/978-1-4757-4286-2)
	- Chap 15 "The Navy Searches" of [_The Theory That Would Not Die_](https://yalebooks.yale.edu/book/9780300188226/the-theory-that-would-not-die/)
- Lecture materials: 
    - [Notebook](https://github.com/aschein/stat_348_2024/blob/main/lecture_materials/notebooks/W2_bayes_decision_theory.ipynb)
    - [iPad notes](https://github.com/aschein/stat_348_2024/blob/main/lecture_materials/ipad_notes/lecture_4_ipad.pdf)
    
### Lecture 5 (April 2): Conjugacy, exponential families, and information theory
- Reading / resources:
	- David Blei's  [lectures notes](https://www.cs.columbia.edu/~blei/fogm/2015F/notes/exponential-family.pdf) on conjugacy in exponential families
	- Jeffrey Miller's  [slides](https://jwmi.github.io/BMB/3-Conjugate-priors.pdf) on conjugate priors
	- Chap 14.3 of John Duchi's [lecture notes](https://anilkeshwani.github.io/files/John-Duchi-Statistics-311-Electrical-Engineering-377.pdf) on exponential families as maximum entropy distributions
	- Chap 2.4-2.6 and 4.1-4.3 of Mackay (2005) [_Information Theory, Inference, and Learning Algorithms_](https://www.inference.org.uk/itprnn/book.pdf)
- Lecture materials: 
    - [iPad notes](https://github.com/aschein/stat_348_2024/blob/main/lecture_materials/ipad_notes/lecture_5_ipad.pdf)
    
### Lecture 6 (April 4): Information theory, compression, model selection
- Reading / resources:
	- Chap 4, 5.1-5.4, 8, 28 of Mackay (2005) [_Information Theory, Inference, and Learning Algorithms_](https://www.inference.org.uk/itprnn/book.pdf)
	- Kirsch (2004) ["On Bayesian Model Selection: The Marginal Likelihood, Cross-Validation, and Conditional Log Marginal Likelihood"](https://d2jud02ci9yv69.cloudfront.net/2024-05-07-clml-111/blog/clml/)
	- Fong & Holmes (2020) ["On the marginal likelihood and cross-validation"](https://academic.oup.com/biomet/article/107/2/489/5715611)
	- Gleick (2011) [_The Information_](https://jarrettfuller.com/tech/downloads/The-Information.pdf)
- Lecture materials: 
    - [iPad notes](https://github.com/aschein/stat_348_2024/blob/main/lecture_materials/ipad_notes/lecture_6_ipad.pdf)
    
### Lecture 7 (April 9): Probabilistic graphical models (PGMs)
- Reading / resources:
	- Chap 2 of Michael Jordan's [lecture notes](https://people.cs.pitt.edu/~milos/courses/cs3750-Spring2020/Readings/Graphical_models/chapter2.pdf)
	- David Blei's [lecture notes](https://www.cs.columbia.edu/~blei/fogm/2016F/doc/graphical-models.pdf) on basics of PGMs
- Lecture materials: 
    - [iPad notes](https://github.com/aschein/stat_348_2024/blob/main/lecture_materials/ipad_notes/lecture_7_ipad.pdf)

### Lecture 8 (April 11): Inference in PGMs: variable elimination, belief propagation, and message-passing
- Reading / resources:
	- [Chap 3](https://people.cs.pitt.edu/~milos/courses/cs3750-Spring2020/Readings/Graphical_models/chapter3.pdf) and [chap 4](https://people.cs.pitt.edu/~milos/courses/cs3750-Spring2020/Readings/Graphical_models/chapter4.pdf) of Michael Jordan's lecture notes
	- David Blei's [lecture notes](https://www.cs.columbia.edu/~blei/fogm/2016F/doc/inference.pdf) on inference in PGMs
	- Yedidia et al. (2001) ["Bethe free energy, Kikuchi approximations, and belief propagation algorithms"](https://www.merl.com/publications/docs/TR2001-16.pdf)
- Lecture materials: 
    - [iPad notes](https://github.com/aschein/stat_348_2024/blob/main/lecture_materials/ipad_notes/lecture_8_ipad.pdf)
    
### Lecture 9 (April 16): Learning and inference in hidden Markov models (HMMs)
- Reading / resources:
    - Chap 17 of Murphy (2012) ["Machine learning: a probabilistic perspective"](https://catalog.lib.uchicago.edu/vufind/Record/8919021) (available as e-book via the library)
    - Scott Linderman's [slides](https://github.com/slinderman/stats305c/blob/spring2023/slides/lecture13_hmms.pdf) on HMMs
- Lecture materials: 
    - [iPad notes](https://github.com/aschein/stat_348_2024/blob/main/lecture_materials/ipad_notes/lecture_9_ipad.pdf)
   
### Lecture 10 (April 18): Learning and inference in hidden Markov models (HMMs)
- Lecture materials: 
    - [iPad notes](https://github.com/aschein/stat_348_2024/blob/main/lecture_materials/ipad_notes/lecture_10_ipad.pdf)
    
### Lecture 11 (April 23): Bayesian mixture models and EM
- Reading / resources:
   - Chap 9 of Bishop (2006) [_Pattern Recognition and Machine Learning_](https://www.microsoft.com/en-us/research/uploads/prod/2006/01/Bishop-Pattern-Recognition-and-Machine-Learning-2006.pdf) on mixtures and EM
    - Scott Linderman's [slides](https://github.com/slinderman/stats305c/blob/spring2023/slides/lecture07-mixtures.pdf) on Bayesian mixtures
    - Scott Linderman's [slides](https://github.com/slinderman/stats305c/blob/spring2023/slides/lecture08-em.pdf) on EM
    - David Blei's [lecture notes](http://www.cs.columbia.edu/~blei/fogm/2016F/doc/gibbs.pdf) on Bayesian mixtures
- Lecture materials: 
    - [iPad notes](https://github.com/aschein/stat_348_2024/blob/main/lecture_materials/ipad_notes/lecture_11_ipad.pdf)
    
### Lecture 12 (April 25): Gibbs sampling and MCMC
- Reading / resources:
    - Chap 11.1.6-11.3 of Bishop (2006) [_Pattern Recognition and Machine Learning_](https://www.microsoft.com/en-us/research/uploads/prod/2006/01/Bishop-Pattern-Recognition-and-Machine-Learning-2006.pdf)
    - David Blei's [lecture notes](http://www.cs.columbia.edu/~blei/fogm/2016F/doc/gibbs.pdf) on Bayesian mixtures and Gibbs sampling
    - Matthew Stephen's [lecture notes](https://stephens999.github.io/fiveMinuteStats/gibbs1.html) on Gibbs sampling
    - Scott Linderman's [slides](https://github.com/slinderman/stats305c/blob/spring2023/slides/lecture04_mcmc.pdf) on MCMC
    - Geweke (2004): ["Getting it Right: Joint Distribution Tests of Posterior Simulators"](http://qed.econ.queensu.ca/pub/faculty/ferrall/quant/papers/04_04_29_geweke.pdf)
    - Roger Grosse's [blogpost](https://lips.cs.princeton.edu/testing-mcmc-code-part-2-integration-tests/) on Geweke testing
- Lecture materials: 
    - [iPad notes](https://github.com/aschein/stat_348_2024/blob/main/lecture_materials/ipad_notes/lecture_12_ipad.pdf)
 
### Lecture 13 (April 27): Poisson / non-negative matrix factorization and auxiliary-variable MCMC
- Reading / resources: 
   - Dunson & Herring (2005) ["Bayesian latent variable models for mixed discrete outcomes"](https://pubmed.ncbi.nlm.nih.gov/15618524/)
   - Gopalan et al. (2014) ["Scalable Recommendation with Poisson factorization"](https://arxiv.org/pdf/1311.1704)
   - Lee and Seung (1999) ["Learning the parts of objects by non-negative matrix factorization"](https://www.nature.com/articles/44565)
   - Gillis (2014) ["The How and Why of Nonnegative Matrix Factorization"](https://arxiv.org/pdf/1401.5226.pdf)
- Lecture materials: 
    - [iPad notes](https://github.com/aschein/stat_348_2024/blob/main/lecture_materials/ipad_notes/lecture_13_ipad.pdf)
 
### Midterm (May 2)

### Lecture 14 (April May 7):  Latent Dirichlet allocation (LDA) and variational inference (VI)
- Reading / resources:
    - Chap 27.3 of Murphy (2012) [_Machine Learning: A Probabilistic Perspective_](http://noiselab.ucsd.edu/ECE228/Murphy_Machine_Learning.pdf)
    - Scott Linderman's [slides](https://github.com/slinderman/stats305c/blob/spring2023/slides/lecture09-lda_cavi.pdf) on CAVI for LDA
    - Jeffrey Miller's [slides](https://jwmi.github.io/BMB/12-Variational-inference-and-LDA.pdf) on CAVI for LDA
    - Matt Gormley's [slides](https://www.cs.cmu.edu/~mgormley/courses/10701-f16/slides/lecture20-topic-models.pdf) on LDA
    - Blei, Ng, Jordan (2003) ["Latent Dirichlet Allocation"](https://www.jmlr.org/papers/volume3/blei03a/blei03a.pdf)
    - Pritchard, Stephens, Donnelly (2000) ["Inference of Population Structure Using Multilocus Genotype Data"](https://academic.oup.com/genetics/article/155/2/945/6048111)
- Lecture materials: 
    - [iPad notes](https://github.com/aschein/stat_348_2024/blob/main/lecture_materials/ipad_notes/lecture_14_15_ipad.pdf)

### Lecture 8 (April 17): Exact inference in discrete graphical models
- Reading / resources (optional; for reference) roughly in the order as they appeared in lecture:
    - [David Blei's lecture notes](https://www.cs.columbia.edu/~blei/fogm/2016F/doc/graphical-models.pdf) on the **basics of directed and undirected PGMs**
    - [David Blei's lecture notes](https://www.cs.columbia.edu/~blei/fogm/2016F/doc/inference.pdf) on the **inference in PGMs**
    - [Chapter 2 of Michael Jordan's lecture notes](https://people.cs.pitt.edu/~milos/courses/cs3750-Spring2020/Readings/Graphical_models/chapter2.pdf) on the **basics of directed and undirected PGMs**
    - [Chapter 3 of Michael Jordan's lecture notes](https://people.cs.pitt.edu/~milos/courses/cs3750-Spring2020/Readings/Graphical_models/chapter3.pdf) on the **variable elimination algorithm**
    - [Chapter 4 of Michael Jordan's lecture notes](https://people.cs.pitt.edu/~milos/courses/cs3750-Spring2020/Readings/Graphical_models/chapter4.pdf) on **sum-product and belief propagation**
     
- Lecture notes: 
    - [iPad notes](https://github.com/aschein/stat_348_2025/blob/main/lecture_materials/ipad_notes/lecture_8.pdf)

### Lecture 9 (April 22): Information theory
- Reading / resources (optional; for reference) roughly in the order as they appeared in lecture:
   	- Chapter 1 of David MacKay's [_Information Theory, Inference, and Learning Algorithms_](https://www.inference.org.uk/itprnn/book.pdf) (2005) on an **intro to information theory**
   	- Chapter 4 of David MacKay's [_Information Theory, Inference, and Learning Algorithms_](https://www.inference.org.uk/itprnn/book.pdf) (2005) on the **source coding theorem**
    - James Gleick' [_The Information_](https://jarrettfuller.com/tech/downloads/The-Information.pdf) (2011); a fantastically entertaining general-audience book on the **the history / context of information theory**.
     
- Lecture notes: 
    - [iPad notes](https://github.com/aschein/stat_348_2025/blob/main/lecture_materials/ipad_notes/lecture_9.pdf)
 
### Lecture 10 (April 29): Information theory (cont.); intro to variational inference
- Reading / resources (optional; for reference) roughly in the order as they appeared in lecture:
   	- Chapter 8 of David MacKay's [_Information Theory, Inference, and Learning Algorithms_](https://www.inference.org.uk/itprnn/book.pdf) (2005) on **mutual information**
   	- Chapter 28.3 of David MacKay's [_Information Theory, Inference, and Learning Algorithms_](https://www.inference.org.uk/itprnn/book.pdf) (2005) on the **minimum description length**
    - Chapter 14.3 of John Duchi's [lecture notes](https://anilkeshwani.github.io/files/John-Duchi-Statistics-311-Electrical-Engineering-377.pdf) on **exponential families as maximum entropy distributions**
    - [David Blei's lectures notes](https://www.cs.princeton.edu/courses/archive/fall11/cos597C/lectures/variational-inference-i.pdf) on **variational inference**
   
- Lecture notes:
    - [iPad notes](https://github.com/aschein/stat_348_2025/blob/main/lecture_materials/ipad_notes/lecture_9.pdf) (from last time)
    - [iPad notes](https://github.com/aschein/stat_348_2025/blob/main/lecture_materials/ipad_notes/lecture_10.pdf)
 
### Lecture 11 (May 1): Coordinate ascent variational inference (CAVI) and latent Dirichlet allocation (LDA)
- Reading / resources (optional; for reference) roughly in the order as they appeared in lecture:
    - ["Latent Dirichlet Allocation" by Blei, Ng, Jordan (2003)](https://www.jmlr.org/papers/volume3/blei03a/blei03a.pdf) **the original LDA paper**
    - ["Inference of Population Structure Using Multilocus Genotype Data" by Pritchard, Stephens, Donnelly (2000)](https://academic.oup.com/genetics/article/155/2/945/6048111) **the other original LDA paper**
    - Chapters 10.1-10.4 of Bishop (2006) [_Pattern Recognition and Machine Learning_](https://www.microsoft.com/en-us/research/uploads/prod/2006/01/Bishop-Pattern-Recognition-and-Machine-Learning-2006.pdf) on **variational inference**
    - [David Blei's lectures notes](https://www.cs.princeton.edu/courses/archive/fall11/cos597C/lectures/variational-inference-i.pdf) on **variational inference**
    - ["Variational inference: A review for statisticians" by Blei, Kucukelbir & McAuliffe (2017)](http://www.cs.columbia.edu/~blei/fogm/2018F/materials/BleiKucukelbirMcAuliffe2017.pdf) **an excellent review paper on VI**
    - Scott Linderman's [slides](https://github.com/slinderman/stats305c/blob/spring2023/slides/lecture09-lda_cavi.pdf) on **CAVI for LDA**
    - Jeffrey Miller's [slides](https://jwmi.github.io/BMB/12-Variational-inference-and-LDA.pdf) on **CAVI for LDA**

- Lecture notes:
    - [iPad notes](https://github.com/aschein/stat_348_2025/blob/main/lecture_materials/ipad_notes/lecture_11.pdf) (**updated**)

### Lecture 12 (May 6): Poisson matrix factorization, data augmentation, stochastic variational inference (SVI)
- Reading / resources:
    - ["Variational inference: A review for statisticians" by Blei, Kucukelbir & McAuliffe (2017) ](http://www.cs.columbia.edu/~blei/fogm/2018F/materials/BleiKucukelbirMcAuliffe2017.pdf) **an excellent review paper on VI and SVI**
    - [Slides from STAT 451](https://github.com/aschein/stat_451/blob/main/materials/lecture_2.pdf) on **CAVI and SVI**
    - ["Scalable Recommendation with Poisson factorization" by Gopalan et al. (2014)](https://arxiv.org/pdf/1311.1704) **Poisson MF for recommendation**
    - ["Cookbook-based Scalable Music Tagging with Poisson Matrix Factorization" by Liang, Paisley & Ellis (2014)](https://archives.ismir.net/ismir2014/paper/000363.pdf) **great example of CAVI/SVI for Poisson MF**
    - ["On the Connection Between Non-Negative Matrix Factorization and Latent Dirichlet Allocation" by Geiger (2024)](https://arxiv.org/html/2405.20542v1) **on the connection**
   
- Lecture notes:
    - [iPad notes](https://github.com/aschein/stat_348_2025/blob/main/lecture_materials/ipad_notes/lecture_11.pdf) (from last time; **updated**)
    - [iPad notes](https://github.com/aschein/stat_348_2025/blob/main/lecture_materials/ipad_notes/lecture_12.pdf)

### Lecture 13 (May 8): Tensor decomposition, research talk on modeling international relations data
- Reading / resources:
    - Chapters 1, 4, 9 of Ballard & Kolda's [_Tensor Decompositions for Data Science_](https://www.mathsci.ai/post/tensor-textbook/) (2024) **great intro / reference for tensor decomposition**
    - ["The ALL0CORE Tensor Decomposition..." by Hood & Schein (2024)](https://proceedings.mlr.press/v238/hood24a/hood24a.pdf) **the central paper of the talk; see references therein**
   
- Slides:
    - [Slides on research talk](https://github.com/aschein/stat_348_2025/blob/main/lecture_materials/slides/all0core_slides.pdf)

### Lecture 14 (May 13): Variational autoencoders (VAEs) and amortized VI
- Reading / resources:
    - Scott Linderman's [slides](https://github.com/slinderman/stats305c/blob/spring2023/slides/lecture11-12-vaes.pdf) on **VAEs and amortized VI**
    - Scott Linderman's [slides](https://github.com/slinderman/stats305c/blob/spring2023/slides/lecture05-continuous_lvms.pdf) on **PCA and connection to VAEs**
    - ["Auto-Encoding Variational Bayes" by Kingma & Welling (2014)](https://arxiv.org/pdf/1312.6114) **one of the two original VAE papers**
    - ["Stochastic Backpropagation and Approximate Inference in Deep Generative Models" by Rezende et al. (2014)](https://arxiv.org/abs/1401.4082) **one of the two original VAE papers**
    - ["Advances in Variational Inference" by Zhang et al. (2019)](https://ieeexplore.ieee.org/document/8588399) **excellent survey of modern VI**
    - ["Inference Suboptimality in VAEs" by Cremer et al. (2018)](https://arxiv.org/pdf/1801.03558) **on the amortization gap**
    - ["Amortized Variational Inference: When and Why?" by Margossian & Blei (2024)](https://arxiv.org/pdf/2307.11018) **on the amortization gap**
    - ["Backprop is not just the chain rule" by Tim Vieira](https://timvieira.github.io/blog/post/2017/08/18/backprop-is-not-just-the-chain-rule/) **famous blogpost on backprop**
    - ["Lossless compression with latent variable models using bits-back coding" by Brian Keng](https://bjlkeng.io/posts/lossless-compression-with-latent-variable-models-using-bits-back-coding/) **blogpost explaining the "bits-back" argument**
   
- Lecture notes:
    - [iPad notes](https://github.com/aschein/stat_348_2025/blob/main/lecture_materials/ipad_notes/lecture_14.pdf)
