# awesome-category-theory
A curated list of awesome Category Theory resources.

## Table of contents

- [Awesome Category Theory](#awesome-category-theory)
    - [Archive](#archive)
    - [Articles](#articles)
    - [Blogs](#blogs)
    - [Books](#books)
    - [Companies](#companies)
    - [Community](#community)
    - [Conferences](#conferences)
    - [Journals](#journals)
    - [Lectures](#lectures)
    - [Meetups](#meetups)
    - [Podcasts](#podcasts)
    - [Related](#related)
    - [Software Libraries](#software-libraries)
    - [Tools](#tools)
    - [Video Lectures](#video-lectures)
    - [Wiki](#wiki)

## Archive

  * [Functor theory](https://github.com/CategoryTheoryArchive/archive/blob/main/resources/1960_freyd_functor-theory.pdf) - Explores the concept of exact categories and the theory of derived functors, building upon earlier work by Buchsbaum. Freyd investigates how properties and statements applicable to abelian groups can extend to arbitrary exact categories. Freyd aims to formalize this observation into a metatheorem, which would simplify categorical proofs and predict lemmas. Peter J. Freyd's dissertation, presented at Princeton University (1960)

  * [Algebra valued functors in general and tensor products in particular](https://github.com/CategoryTheoryArchive/archive/blob/main/resources/1966_freyd_algebra-valued.pdf) - Discusses the concept of valued functors in category theory, particularly focusing on tensor products. Freyd explores the application of algebraic theories in non-standard categories, starting with the question of what constitutes an algebra in the category of sets, using category predicates without elements. The text outlines the axioms of a group using category theory language, emphasizing objects and maps. Peter Freyd (1966)

  * [Continuous Yoneda Representation of a small category](https://github.com/CategoryTheoryArchive/archive/blob/main/resources/1966_kock_continuous-yoneda.pdf) -  Discusses the embedding of a small category A into the category of contravariant functors from A to Set (the category of sets), which preserves inverse limits but does not generally preserve direct limits. Kock introduces a "codensity monad" for any functor from a small category to a left complete category and explores the universal generator for this monad. He demonstrates that the Yoneda embedding followed by this generator provides a full and faithful embedding that is both left and right continuous. Additionally, the relationship with Isbell's adjoint conjugation functors and the definition of generalized (direct and inverse) limit functors are addressed, by Anders Kock (1966).

  * [Abstract universal algebra](https://github.com/CategoryTheoryArchive/archive/blob/main/resources/1967_davis_abstract-universal.pdf) - Explores advanced subjects in the realm of universal algebra. The core content is organized into two chapters, each addressing different aspects of universal algebra within the framework of category theory. The first chapter introduces the concept of triplable categories, inspired by the theory of modules over a ring, and explores the equivalence between categories of triples in any given category and theories over that category. In the second chapter, Davis shifts focus to equational systems of functors, a more generalized approach to algebra that encompasses both the triplable and structure category theories. Dissertation by Robert Clay Davis (1967)

  * [A triple miscellany: some aspects of the theory of algebras over a triple](https://github.com/CategoryTheoryArchive/archive/blob/main/resources/1967_manes_triple-miscellany.pdf) - Explores the field of universal algebra with a particular focus on the concept of algebras over a triple. The work is grounded in the realization that categories of algebras, traditionally defined with finitary operations and satisfying a set of equations, can be extended to include infinitary operations as well, thereby broadening the scope of universal algebra. Manes starts by discussing the conventional understanding of universal algebra, tracing back to G.D. Birkhoff's definition in the 1930s, and then moves to explore how this definition can be expanded by considering sets with infinitary operations. Dissertation by Ernest Gene Manes (1967)

  * [Limit Monads in Categories](https://github.com/CategoryTheoryArchive/archive/blob/main/resources/1967_kock_limit-monads.pdf) - The work introduces the notion that the category of complete categories is monadic over the category of all categories, utilizing a family of monads associated with various index categories to define "completeness." A significant portion of the thesis is dedicated to defining associative and regular associative colimits, arguing for their naturalness and importance in category theory. Dissertation by Anders Jungersen Kock (1967)

  * [On the concreteness of certain categories](https://github.com/CategoryTheoryArchive/archive/blob/main/resources/1969_freyd_concreteness-certain.pdf) - This work discusses the concept of concreteness in categories, stating that a concrete category is one with a faithful functor to the category of sets, and must be locally-small. He highlights the homotopy category of spaces as a prime example of a non-concrete category, emphasizing its abstract nature due to the irrelevance of individual points within spaces and the inability to distinguish non-homotopic maps through any functor into concrete categories. Peter Freyd (1969)
## Articles

#### Bayesian/Causal inference
  * [A Categorical Foundation for Bayesian probability](https://arxiv.org/abs/1205.1488) - Bayesian inference and decision making on measurable spaces with countably generated σ-algebras, using regular conditional probabilities and Eilenberg--Moore algebras by Jared Culbertson, Kirk Sturtz (2013)
  * [A Channel-Based Perspective on Conjugate Priors](https://arxiv.org/abs/1707.00269) - Introduces channels in a graphical language to define and study conjugate priors in Bayesian probability, and shows how they ensure the same class of distributions for prior and posterior by Bart Jacobs (2017)
  * [A Type Theory for Probabilistic and Bayesian Reasoning](https://arxiv.org/abs/1511.09230) - A new type theory and logic for probabilistic reasoning with fuzzy predicates and normalisation and conditioning of states by Robin Adams, Bart Jacobs (2015)
  * [A category theory framework for Bayesian Learning](https://arxiv.org/abs/2111.14293) - Drawing from Spivak, Fong, and Cruttwell et al.'s foundational works, this study establishes a categorical framework for Bayesian inference, incorporating concepts of Bayesian inversions by Kotaro Kamiya, John Welliaveetil (2021)
  * [Automatic Backward Filtering Forward Guiding for Markov processes and graphical models](https://arxiv.org/abs/2010.03509) - Describing a Backward Filtering Forward Guiding (BFFG) paradigm for inference on latent states and parameters, and transforms a forward generative model into a data-guided pre-conditional mode by Frank van der Meulen, Moritz Schauer (2020)
  * [Bayesian Open Games](https://arxiv.org/abs/1910.03656) - Extends compositional game theory to handle stochasticity and incomplete information using category theory and coend optics by Joe Bolt, Jules Hedges, Philipp Zahn (2019)
  * [Bayesian Updates Compose Optically](https://arxiv.org/abs/2006.01631) - Utilizing lens pattern and a fibred category to model the compositional structure of Bayesian inversion by Toby St. Clere Smithe (2020)
  * [Bayesian machine learning via category theory](https://arxiv.org/abs/1312.1445) - Using categorical methods, the study frames machine learning concepts within the realm of conditional probabilities, building models for both parametric and nonparametric Bayesian reasoning on function spaces, and exemplifies the Kalman filter's relation to the hidden Markov model by Jared Culbertson, Kirk Sturtz (2013)
  * [Categorical Stochastic Processes and Likelihood](https://arxiv.org/abs/2005.04735) - Explores the link between probabilistic modeling and function approximation, introduces two extensions of function composition related to stochastic processes by Dan Shiebler (2020)
  * [Causal Inference by String Diagram Surgery](https://arxiv.org/abs/1811.08338) - Extract causal relationships from correlations, using string diagram syntax and semantics, and showcases a method to compute causal effects by Bart Jacobs, Aleks Kissinger, Fabio Zanasi (2018)
  * [Causal Theories: A Categorical Perspective on Bayesian Networks](https://arxiv.org/abs/1301.6201) - This dissertation introduces a graphical framework for causal reasoning, based on monoidal categories, and presents a new structure called a causal theory by Brendan Fong (2013)
  * [Compositionality in algorithms for smoothing](https://arxiv.org/abs/2303.13865) - Backward Filtering Forward Guiding with optics and prove that different ways of composing the building blocks of BFFG correspond to equivalent optics by Moritz Schauer, Frank van der Meulen (2023)
  * [Denotational validation of higher-order Bayesian inference](https://arxiv.org/abs/1711.03219) - Introduces Bayesian inference algorithms in probabilistic programming using higher-order functions and quasi-Borel spaces (2017)
  * [Dependent Bayesian Lenses: Categories of Bidirectional Markov Kernels with Canonical Bayesian Inversion](https://arxiv.org/abs/2209.14728) - Extends the concept of Bayesian Lenses to include cases where one object depends on another, providing a framework to study specific stochastic maps by Dylan Braithwaite, Jules Hedges (2022)
  * [Disintegration and Bayesian Inversion via String Diagrams](https://arxiv.org/abs/1709.00322) - Abstract graphical representations of disintegration and Bayesian inversion concepts in conditional probability by Kenta Cho, Bart Jacobs (2017)
  * [Relational Reasoning for Markov Chains in a Probabilistic Guarded Lambda Calculus](https://arxiv.org/abs/1802.09787) - A guarded λ-calculus with discrete probabilities and a program logic to understand relational aspects of probabilistic computations, such as Markov chains (2018)
  * [The Compositional Structure of Bayesian Inference](https://arxiv.org/abs/2305.06112) - Examines how Bayes' rule, which updates beliefs based on new evidence, can be applied piecewise to complex processes, linking it to the lens pattern in programming by Dylan Braithwaite, Jules Hedges, Toby St Clere Smithe (2023)
  * [The Geometry of Bayesian Programming](https://arxiv.org/abs/1904.07425) - A geometric interaction model for a typed lambda-calculus equipped with tools for continuous sampling and soft conditioning by Ugo Dal Lago, Naohiko Hoshino (2019)
#### Databases
  * [Algebraic databases](http://www.tac.mta.ca/tac/volumes/32/16/32-16abs.html) - Enhances traditional category-theoretic database models to better handle concrete data like integers or strings using multi-sorted algebraic theories by Patrick Schultz, David I. Spivak, Christina Vasilakopoulou and Ryan Wisnesky (2017)
  * [Algebraic Model Management: A survey](https://www.categoricaldata.net/cql/wadt.pdf) - We survey the field of model management and describe a
new model management approach based on algebraic specification by Patrick Schultz, David I. Spivak, and Ryan Wisnesky (2017)
  * [Functorial data migration](https://www.sciencedirect.com/science/article/pii/S0890540112001010) - A database language based on categories and functors, where a schema is depicted as a category and its instance as a set-valued functor by David I. Spivak (2012)
#### Data Types
  * [Categories of Containers](https://www.cs.nott.ac.uk/~psztxa/publ/fossacs03.pdf) - Introduces containers as a mathematical model of datatypes with templated data storage, demonstrating their robustness under various constructions, including initial algebras and final coalgebras by Michael Abbot, horsten Altenkirch and Neil Ghani (2003)
#### Deep Learning
  * [Backprop as Functor](https://arxiv.org/abs/1711.10455) - Describes a category for supervised learning algorithms that search for the best approximation of an ideal function using example data and update rules by Brendan Fong, David I. Spivak, Rémy Tuyéras (2017)
  * [Categorical Foundations of Gradient-Based Learning](https://arxiv.org/abs/2103.01931) - Categorical interpretation of gradient-based machine learning algorithms using lenses, parametrised maps, and reverse derivative categories (2021)
  * [Categories of Differentiable Polynomial Circuits for Machine Learning](https://arxiv.org/abs/2203.06430) - Reverse Derivative Categories (RDCs) as a framework for machine learning. We introduce 'polynomial circuits' as an apt machine learning model by Paul Wilson, Fabio Zanasi (2022)
  * [Compositional Deep Learning](https://arxiv.org/abs/1907.08292) - Category-theoretic structure for a class of neural networks like CycleGAN, using this framework to design a new neural network for image object manipulation, and showcases its effectiveness through tests on multiple datasets by Bruno Gavranović (2019)
  * [Compositionality for Recursive Neural Networks](https://arxiv.org/abs/1901.10723) - Simplified recursive neural tensor network model aligns with the categorical approach to compositionality, offering a feasible computational method and opening new research avenues for both vector space semantics and neural network models by Martha Lewis (2019)
  * [Deep neural networks as nested dynamical systems](https://arxiv.org/abs/2111.01297) - Argues that the common comparison between deep neural networks and brains is wrong, and proposes a new way of thinking about them using category theory and dynamical systems by David I. Spivak, Timothy Hosgood (2021)
  * [Dioptics: a Common Generalization of Open Games and Gradient-Based Learners](https://research.protocol.ai/publications/dioptics-a-common-generalization-of-open-games-and-gradient-based-learners/dalrymple2019.pdf) - Relationship between machine-learning algorithms and open games, suggesting both can be understood as instances of "categories of dioptics". It expands on gradient-based learning, introducing a category that embeds into the category of learners (2019)
  * [Learning Functors using Gradient Descent](https://arxiv.org/abs/2009.06837) - A category-theoretic understanding of CycleGAN, a notable method for unpaired image-to-image translation by Bruno Gavranović (2020)
  * [Lenses and Learners](https://arxiv.org/abs/1903.03671) - Shows a strong connection between lenses, which model bidirectional transformations like database interactions, and learners, which represent a compositional approach to supervised learning by Brendan Fong, Michael Johnson (2019)
  * [Neural network layers as parametric spans](https://arxiv.org/abs/2208.00809) - Linear layer in neural networks, drawing on integration theory and parametric spans by Mattia G. Bergomi, Pietro Vertechi (2022)
  * [Reverse Derivative Ascent](https://arxiv.org/abs/2101.10488) - Reverse Derivative Ascent, a categorical counterpart to gradient-based learning techniques, formulated within the context of reverse differential categories by Paul Wilson, Fabio Zanasi (2021)
#### Differentiable Programming / Automatic Differentiation
  * [Correctness of Automatic Differentiation via Diffeologies and Categorical Gluing](https://arxiv.org/abs/2001.02209) - Semantic validation for Automatic Differentiation (AD), characterizing a forward-mode AD in a higher-order language with algebraic data types by Mathieu Huot, Sam Staton, Matthijs Vákár (2020)
  * [Denotationally Correct, Purely Functional, Efficient Reverse-mode Automatic Differentiation](https://arxiv.org/abs/2212.09801) - Pure and efficient reverse-mode differentiation for functional languages using a 'unary form' by Mathieu Huot, Amir Shaikhha (2022)
  * [Differentiable Causal Computations via Delayed Trace](https://arxiv.org/abs/1903.01093) - Causal computations in sequences using a category-theoretical model featuring a "delayed trace" operation, by applying an abstract form of backpropagation through time by David Sprunger, Shin-ya Katsumata (2019)
  * [Functorial String Diagrams for Reverse-Mode Automatic Differentiation](https://arxiv.org/abs/2107.13433) - String diagram calculus with hierarchical features to capture monoidal structures, develop an automatic differentiation algorithm for simply typed lambda calculus, and represent the diagrams as "hypernets" (2021)
  * [Higher Order Automatic Differentiation of Higher Order Functions](https://arxiv.org/abs/2101.06757) - Semantic proofs for automatic differentiation in a higher order language, using diffeological spaces for rich semantics by Mathieu Huot, Sam Staton, Matthijs Vákár (2021)
  * [Reverse Derivative Categories](https://arxiv.org/abs/1910.07065) - Axiomatization of a category for reverse derivatives in machine learning, analogous to Cartesian differential categories for forward derivatives (2019)
  * [Simple Essence of Automatic Differentiation](https://arxiv.org/abs/1804.00746) - Simplified and generalized automatic differentiation in reverse mode (RAD) algorithm, derived from a clear specification by Conal Elliott (2018)
  * [Space-time tradeoffs of lenses and optics via higher category theory](https://arxiv.org/abs/2209.09351) - Compare and compose optics and lenses, which are ways of modeling bidirectional data flow, using 2-category theory by Bruno Gavranović (2022)
  * [Towards formalizing and extending differential programming using tangent categories](http://www.cs.ox.ac.uk/ACT2019/preproceedings/Jonathan%20Gallagher,%20Geoff%20Cruttwell%20and%20Ben%20MacAdam.pdf) - This paper explores how a simple differential programming language can be interpreted using synthetic differential geometry, proving it can consistently integrate manifolds and certain functions, while detailing the necessary frameworks and structures, by Geoff Cruttwell, Jonathan Gallagher, and Ben MacAdam (2019)
  * [Using Rewrite Strategies for Efficient Functional Automatic Differentiation](https://arxiv.org/abs/2307.02447) - This paper integrates Automatic Differentiation (AD) with dual numbers in a functional programming language, using rewrite rules and strategy languages for optimization, aiming to efficiently combine differentiation accuracy with strategic optimization scheduling, supported by promising preliminary results from a micro-benchmark by Timon Böhler, David Richter, Mira Mezini (2023)
#### Dynamical Systems
  * [A categorical approach to open and interconnected dynamical systems](https://arxiv.org/abs/1510.05076) - This paper presents a comprehensive graphical theory for discrete linear time-invariant systems, expanding on classical signal flow diagrams to handle streams with infinite pasts and futures, introduces a new structural view on controllability, and is grounded in the extended theory of props by Brendan Fong, Paolo Rapisarda and Paweł Sobociński (2015)
#### Game Theory
  * [A semantical approach to equilibria and rationality](https://arxiv.org/abs/0905.3548) - This paper connects game theoretic equilibria and rationality to computation, suggesting that viewing processes as computational instances can offer new algebraic and coalgebraic methods to understand equilibrium and rational behaviors by Dusko Pavlovic (2009)
  * [Compositional game theory](https://arxiv.org/abs/1603.04641) - Open games offer a new foundation for economic game theory, enabling larger models through a compositional approach that uses "coutility" to represent games in relation to their environment, and can be visually represented with intuitive string diagrams, capturing key game theory outcomes by Jules Hedges, Neil Ghani, Viktor Winschel and Philipp Zahn (2016)
  * [The game semantics of game theory](https://arxiv.org/abs/1904.11287) - We reinterpret compositional game theory, aligning game theory with game semantics by viewing open games as Systems and their contexts as Environments; using lenses from functional programming, we then construct a category of 'computable open games' based on a specific interaction geometry by Jules Hedges (2019)
#### Graph Neural Networks
  * [Asynchronous Algorithmic Alignment with Cocycles](https://arxiv.org/abs/2306.15632) - Current neural algorithmic reasoners use graph neural networks (GNNs) that often send unnecessary messages between nodes; in our work, we separate node updates from message sending, enabling more efficient and asynchronous computation in algorithms and neural networks (2023)
  * [Graph Convolutional Neural Networks as Parametric CoKleisli morphisms](https://arxiv.org/abs/2212.00542) - We categorically define Graph Convolutional Neural Networks (GCNNs) for any graph and connect it to existing deep learning constructs, allowing the GCNN's adjacency matrix to be treated globally, shedding light on its inherent biases, and discussing potential generalizations and connections to other learning concepts by Bruno Gavranović, Mattia Villani (2022)
  * [Graph Neural Networks are Dynamic Programmers](https://arxiv.org/abs/2203.15544) - Using category theory and abstract algebra, we dive deeper into the presumed alignment between graph neural networks (GNNs) and dynamic programming, uncovering a profound connection, validating previous studies, and presenting improved GNN designs for specific tasks, hoping to bolster future algorithm-aligned GNN advancements by Andrew Dudzik, Petar Veličković (2022)
  * [Learnable Commutative Monoids for Graph Neural Networks](https://arxiv.org/abs/2212.08541) - Using the concept of commutative monoids, we introduce an efficient O(logV) depth aggregator for GNNs, offering a balance between speed and expressiveness by Euan Ong, Petar Veličković (2022)
  * [Local Permutation Equivariance For Graph Neural Networks](https://arxiv.org/abs/2111.11840) - Our Sub-graph Permutation Equivariant Networks (SPEN) method improves graph neural networks' scalability and expressiveness by focusing on unique sub-graphs, proving competitive on benchmarks and saving GPU memory by Joshua Mitton, Roderick Murray-Smith (2021)
  * [Natural Graph Networks](https://arxiv.org/abs/2007.08349) - We introduce the concept of naturality in graph neural networks, offering a broader and efficient design alternative to traditional equivariance, with our design showing strong benchmark performance by Pim de Haan, Taco Cohen, Max Welling (2020)
  * [Neural Sheaf Diffusion: A Topological Perspective on Heterophily and Oversmoothing in GNNs](https://arxiv.org/abs/2202.04579) - Using cellular sheaf theory, we connect graph geometry to Graph Neural Network performance, leading to improved diffusion models that bridge algebraic topology and GNN studies (2022)
  * [Sheaf Neural Networks for Graph-based Recommender Systems](https://arxiv.org/abs/2304.09097) - Using Sheaf Neural Networks, we enrich recommendation systems by representing nodes with vector spaces, leading to significant performance improvements in collaborative filtering and link prediction across multiple datasets (2023)
  * [Sheaf Neural Networks with Connection Laplacians](https://arxiv.org/abs/2206.08702) - Using Riemannian geometry, we refine Sheaf Neural Network design, optimally aligning data points and reducing computational overhead, offering a bridge between algebraic topology and differential geometry for enhanced performance (2022)
  * [Sheaf Neural Networks](https://arxiv.org/abs/2012.06333)
  * [Topologically Attributed Graphs for Shape Discrimination](https://arxiv.org/abs/2306.17805) - We've developed attributed graphs that combine Mapper graph approximations with stable homology, enhancing shape representation and boosting classification results in graph neural networks (2023)
#### Linguistics
  * [Free compact 2-categories](https://hal-lirmm.ccsd.cnrs.fr/lirmm-00137681v2/document) - The paper introduces the notion of a compact 2-category, and gives some examples, such as the 2-category of monoidal categories, the 2-category of bimodules over a ring, and the 2-category of finite-dimensional vector spaces by Joachim Lambek and Anne Preller (2007)
  * [Mathematical foundations for a compositional distributional model of meaning](https://arxiv.org/abs/1003.4394) - Using vector spaces and Lambek's Pregroup algebra, we derive sentence meanings from words, enabling comparisons. Our model visually represents sentence construction and can adapt to Boolean semantics by Bob Coecke, Mehrnoosh Sadrzadeh and Stephen Clark (2010)
  * [The Frobenius anatomy of word meanings I: subject and object relative pronouns](https://arxiv.org/abs/1404.5278) - We use vectors and Frobenius algebras in a categorical approach to understand the semantics of relative pronouns. Two models are introduced: a truth-based and a corpus-based approach by Mehrnoosh Sadrzadeh, Stephen Clark and Bob Coecke (2014)
#### Manufacturing
  * [String diagrams for assembly planning](https://arxiv.org/abs/1909.10475) - This paper introduces CompositionalPlanning, a tool that uses string diagrams to unify CAD designs with planning algorithms, optimizing assembly plans which are then tested in simulations, showcasing its efficiency in the LEGO assembly context by Jade Master, Evan Patterson, Shahin Yousfi, Arquimedes Canedo (2019)
#### Metric Space Magnitude
  * [Approximating the convex hull via metric space magnitude](https://arxiv.org/abs/1908.02692) - This paper introduces CompositionalPlanning, a tool that uses string diagrams to unify CAD designs with planning algorithms, optimizing assembly plans which are then tested in simulations, showcasing its efficiency in the LEGO assembly context by Glenn Fung, Eric Bunch, Dan Dickinson (2019)
  * [Magnitude of arithmetic scalar and matrix categories](https://arxiv.org/abs/2304.08334) - We create tools that build categories from data and operate using scalar and matrix math, identifying features similar to outliers in various systems like computer programs and neural networks by Steve Huntsman (2023)
  * [Practical applications of metric space magnitude and weighting vectors](h2020ttps://arxiv.org/abs/2006.14063) - The magnitude of a metric space quantifies distinct points and its weighting vector, especially in Euclidean spaces, offers new algorithms for machine learning, proven through benchmark experiments (2020)
  * [The magnitude vector of images](https://arxiv.org/abs/2110.15188) - We explore the metric space magnitude in images, revealing edge detection abilities, and introduce an efficient model that broadens its use in machine learning (2021)
  * [Weighting vectors for machine learning: numerical harmonic analysis applied to boundary detection](https://arxiv.org/abs/2106.00827) - Using the metric space magnitude's weighting vector, we enhance outlier detection in Euclidean spaces and link it to efficient nearest neighbor SVM techniques (2021)
#### Petri Nets
  * [Generalized Petri Nets](https://arxiv.org/abs/1904.09091) - We present Q-net, an extension of Petri nets using Lawvere theory Q, and offer a functorial approach to delineate their operational semantics across multiple net systems by Jade Master (2019)
  * [The Mathematical Specification of the Statebox Language](https://arxiv.org/abs/1906.07629) - The Statebox language is built on a solid mathematical foundation, synergizing theoretical structures for reliability; this document shares that foundation to aid understanding and auditing by Fabrizio Genovese, Jelle Herold (2019)
#### Probability and Statistics
  * [A Convenient Category for Higher-Order Probability Theory](https://arxiv.org/abs/1701.02547) - Quasi-Borel spaces improve higher-order probabilistic programming by supporting advanced functions and continuous distributions, offering better proof principles and refining core probability theory constructs (2017)
  * [A Probabilistic Dependent Type System based on Non-Deterministic Beta Reduction](https://arxiv.org/abs/1602.06420) - Introducing the Probabilistic Dependent Type Systems (PDTS) in a functional language, we provide sampling-based semantics and derive a universal probabilistic logic for finite discrete distributions (2016)
  * [A Probability Monad as the Colimit of Spaces of Finite Samples](https://arxiv.org/abs/1712.05363) - We introduce a probability monad for metric spaces, simplifying integration theory, and linking it to the category of convex subsets in Banach spaces by Tobias Fritz, Paolo Perrone (2017)
  * [A categorical approach to probability theory](https://www.chrisstucchio.com/blog_media/2016/probability_the_monad/categorical_probability_giry.pdf) - The paper introduces the Giry monad as a categorical tool for defining and studying random processes and related concepts by Michèle Giry (2016)
  * [A synthetic approach to Markov kernels, conditional independence and theorems on sufficient statistics](https://arxiv.org/abs/1908.07021) - The paper uses Markov categories to study probability and statistics in a general and abstract way, covering many topics and examples from different kinds of probability theory by Tobias Fritz (2019)
  * [Bimonoidal Structure of Probability Monads](https://arxiv.org/abs/1804.03527) - We examine joints, marginals, and independence in categorical probability using mathematical structures, exemplified by the Kantorovich monad by Tobias Fritz, Paolo Perrone (2018)
  * [Categorical Probability Theory](https://arxiv.org/abs/1406.6030) - We reinterpret probability measures categorically, linking them to specific mathematical structures and demonstrating their connection to the Giry monad, with a theorem on the integral operator provided by Kirk Sturtz (2014)
  * [Causal inference by string diagram surgery](https://arxiv.org/abs/1811.08338) - We use a categorical approach with string diagrams to understand causality, showcasing a method to compute interventions, exemplified by analyzing smoking's effect on cancer by Bart Jacobs, Aleks Kissinger and Fabio Zanasi (2018)
  * [Compositional Semantics for Probabilistic Programs with Exact Conditioning](https://arxiv.org/abs/2101.11351) - We design a language for Gaussian variables with advanced conditioning, tackle Borel's paradox, and use categorical concepts to generalize its semantics by Dario Stein, Sam Staton (2021)
  * [Computable Stochastic Processes](https://arxiv.org/abs/1409.4667) - We present a computable theory of probability, applying it to discrete-time systems and the Wiener process, grounded in Turing computation for clarity by Pieter Collins (2014)
  * [De Finneti's construction as a categorical limit](https://arxiv.org/abs/2003.01964) - We recast de Finetti's 1930s probability theorem using modern categorical language, linking it to the Giry monad's Kleisli category and identifying the final exchangeable coalgebra by Bart Jacobs, Sam Staton (2020)
  * [Infinite products and zero-one laws in categorical probability](https://arxiv.org/abs/1912.02769) - We enhance Markov categories' approach to probability, exploring infinite products and introducing generalized zero-one laws of Kolmogorov and Hewitt-Savage, applicable beyond traditional probability settings by Tobias Fritz, Eigil Fjeldgren Rischel (2019)
  * [Information structures and their cohomology](https://arxiv.org/abs/1709.07807) - We define information structures to model contextuality in classical and quantum domains, linking them to observables, and delve into information cohomology, emphasizing the role of specific entropies by Juan Pablo Vigneaux (2017)
  * [Markov Categories and Entropy](https://arxiv.org/abs/2212.11719) - We merge Markov categories with classic information theory, offering a fresh view on determinism, entropy, and encompassing various entropy indices by Paolo Perrone (2022)
  * [Markov categories](https://arxiv.org/abs/1908.07021) - We use Markov categories for a unified categorical view on key probability concepts, enabling a consistent approach across various probability theories, from discrete to Gaussian by Tobias Fritz (2019)
  * [Probability, valuations, hyperspace: Three monads on Top and the support as a morphism](https://arxiv.org/abs/1910.03752) - We study three monads related to topological aspects of probability, unify two using double dualization, and show the tau-smooth probability measures' connection within this framework by Tobias Fritz, Paolo Perrone, Sharwin Rezagholi (2019)
  * [Representable Markov Categories and Comparison of Statistical Experiments in Categorical Probability](https://arxiv.org/abs/2010.07416) - We expand on Markov categories in probability, addressing stochastic dominance and presenting a generalized Blackwell-Sherman-Stein Theorem. We also explore their relation with Kleisli categories of probability monads (2020)
#### Set Theory
  * [Set theory for category theory](https://arxiv.org/abs/0810.1279) - This paper compares set-theoretic foundations for category theory, exploring their implications for standard categorical usage, tailored for those with minimal logic or set theory background by Michael A. Shulman (2008)
#### Topological Data Analysis
  * [On Characterizing the Capacity of Neural Networks using Algebraic Topology](https://arxiv.org/abs/1802.04443) - This paper uses algebraic topology to determine how data complexity impacts neural network architecture choices by William H. Guss, Ruslan Salakhutdinov (2018)
  * [Persistent-Homology-based Machine Learning and its Applications - A Survey](https://arxiv.org/abs/1811.00252) - This paper reviews the integration of persistent homology in machine learning and its application in protein structure classification by Chi Seng Pun, Kelin Xia, Si Xian Lee (2018)
  * [Topological Expressiveness of Neural Networks](https://run.unl.pt/bitstream/10362/129615/1/TAA0115.pdf) - This paper introduces a topological measure of a neural network's expressive power, analyzing how it varies with architecture properties like depth and width by António Leitão (2020)


## Blogs

* [Category Theory | Bartosz Milewski's Programming Cafe](https://bartoszmilewski.com/category/category-theory/) - Personal blog of Bartosz Milewski, author of the book "Category for Programmers"
* [The Comonad.Reader by Edward Kmett](http://comonad.com/reader/) - Personal blog of Edward Kmett, author of many high profile Haskell libraries like lens
* [What is category theory, anyway?](https://www.math3ma.com/blog/what-is-category-theory-anyway) - Personal blog of Tai-Danae Bradley a research mathematician, explains concepts related to Category Theory and many other fields of math with illustrations in an accessible way
* [On compositionality](https://julesh.com/2017/04/22/on-compositionality/) - Personal blog of Jules Hedges a mathematics and computer science researcher affiliated
* [From design patterns to category theory](https://blog.ploeh.dk/2017/10/04/from-design-patterns-to-category-theory/) - ploeh blog by Mark Seeman is his professional blog, where he writes about programming, software development, and architecture
* [The n-Category Cafe](https://golem.ph.utexas.edu/category/) - A group blog on math, physics and philosophy
* [Elementary Introduction to Category Theory](https://elincath.blogspot.com/) - Elementary Introduction to Category Theory
* [The Topos Lab](https://topos.site/tags/category-theory/) - The Topos Institute works to shape technology for public benefit by advancing sciences of connection and integration. Current research personnel includes Brendan Fong, John Baez and David Spivak
## Books

* [Category Theory](https://amzn.to/2HAe42N) - This book offers an in-depth yet accessible introduction to category theory, targeting a diverse audience and covering essential concepts; the second edition includes expanded content, new sections, and additional exercises by Steve Awodey (2010)
* [Categories for the Working Mathematician](https://www.amazon.de/-/en/Saunders-Mac-Lane/dp/1441931236) - The content is in-depth, and its mathematical aspects can be challenging for the reader. It's advisable to explore this book after reading one or two of the more introductionary books. This book is a classic by Saunders Mac Lane (1971)
* [Category Theory for Programmers](https://github.com/hmemcpy/milewski-ctfp-pdf) - This book introduces Category Theory at a level appropriate for computer scientists and provides practical examples (in Haskell) in the context of programming languages by Bartosz Milewski (2019)
* [Category Theory for the Sciences](https://mitpress.mit.edu/books/category-theory-sciences) - An introduction to category theory as a rigorous, flexible, and coherent modeling language that can be used across the sciences by David I. Spivak (2014)
* [Conceptual Mathematics: A First Introduction to Categories](https://s3.amazonaws.com/arena-attachments/325201/2ff932bf546d8985eb613fccf02b69c7.pdf) - This book demonstrates the power of 'category' to make mathematics easier and more connected for anyone. It begins with basic definitions and creates simple categories, such as discrete dynamical systems and directed graphs, with examples, by Schanuel, Lawvere (2009)
* [Draft of "Categorical Systems Theory"](http://davidjaz.com/Papers/DynamicalBook.pdf) - This draft book is about categorical systems theory, the study of the design and analysis of systems using category theory by Jaz Myers (2022)
* [Polynomial Functors: A General Theory of Interaction](https://topos.site/poly-book.pdf) - This book offers an interdisciplinary approach to the categorical study of general interaction, aiming to bridge diverse fields under a unified language to understand interactive systems; it provides detailed explanations and resources for learning, but assumes a foundational knowledge of category theory and graph-theoretic trees by Spivak, Niu (2023)
* [Seven Sketches in Compositionality: An Invitation to Applied Category Theory](https://arxiv.org/abs/1803.05316) - This book by David I. Spivak and Brendan Fong (2019) provides an introductory glimpse into Category Theory by covering 7 key topics. It highlights practical, real-world examples to give readers a feel for the abstract theoretical concepts
* [The Joy of Abstraction](https://www.cambridge.org/core/books/joy-of-abstraction/00D9AFD3046A406CB85D1AFF5450E657) - The book by Eugenia Cheng (2022) is written in a clear and engaging style. Cheng is a gifted writer who is able to make complex mathematical concepts accessible to a general audience
* [Basic Category Theory](https://arxiv.org/abs/1612.09375) - Tom Leinster's (2014) book represents an edited version of his lecture notes. As such, it is a concise work that provides focused coverage of the Category Theory topics it addresses
* [Category Theory in Context](https://math.jhu.edu/~eriehl/context.pdf) - This text book by Emily Riehl (2016) is advanced and is suitable for diligent students who have mastered prior readings. It's praised for its well-crafted prose on Category Theory. Initially, it adopts an example-based methodology before illustrating how category theoretical language can encapsulate the concepts
* [Categories for Quantum Theory: An Introduction](https://www.amazon.com/Categories-Quantum-Theory-Introduction-Mathematics/dp/0198739621?_encoding=UTF8&qid=&sr=&linkCode=sl1&tag=saxxie-20&linkId=970d027b9ed176eadeca7e50c0a9c07f&language=en_US&ref_=as_li_ss_tl) - Monoidal category theory provides an abstract language to describe quantum theory, emphasizing intuitive graphical calculus, and explores structures modeling quantum phenomena, classical information, and probabilistic systems, with connections to other disciplines highlighted throughout by Chris Heunen, Jamie Vicary (2020)
* [From Categories to Homotopy Theory](https://www.math.uni-hamburg.de/home/richter/bookdraft.pdf) - by Birgit Richter (2020), gets advanced, but Part I ‘Category Theory’ is pretty accessible
* [An Introduction to Category Theory](https://www.amazon.com/Introduction-Category-Theory-Harold-Simmons/dp/0521283043) - This book offers a beginner-friendly introduction to category theory, a versatile conceptual framework used across various disciplines, detailing fundamental concepts, examples, and over 200 exercises, making it ideal for self-study or as a course text, by Harold Simmons (2011)

## Companies

* [Conexus](https://conexus.com/) - A start-up developing CQL, a generalization of SQL to data migration and integration that contains an automated theorem prover to rule out most semantic errors at compile time
* [Statebox](https://statebox.org/) - building a formally verified process language using robust mathematical principles to prevent errors, allow compositionality and ensure termination
* [IOHK](https://iohk.io/) - builds cryptocurrencies and blockchain solutions, based on peer reviewed papers; formally verified specifications in Agda, Coq and k-framework
* [RChain](https://github.com/rchain/) - blockchain ecosystem it's foundational language - Rholang is implementation of rho-calculus wih deep roots in higher category theory and enriched Lawvere theories

## Community
* [nForum](https://nforum.ncatlab.org/search/?PostBackAction=Search&Type=Topics&Tag=category-theory) - A discussion forum about contributions to the nLab wiki and related areas of mathematics, physics, and philosophy
* [ZulipChat](https://categorytheory.zulipchat.com/) - A Category Theory Zulip server, that requires invite
* [/r/CategoryTheory on Reddit](https://reddit.com/r/categorytheory) - A Category Theory subreddit
* [Applied Category Theory on Discord by Topos Institute](https://discord.gg/hTEpgYv) - A Discord Server about Applied Category Theory by the Topos Institute
* [Category Theory on Discord Math](https://discord.com/channels/268882317391429632/497227343337881640) - Category Theory Channel on the biggest Discord Math Server

## Conferences

* [ACT](http://www.appliedcategorytheory.org/) - Applied Category Theory Conference
* [Statebox Summit](https://summit.statebox.org/) - An yearly gathering of category theorists and functional programmers
* [SYCO](http://events.cs.bham.ac.uk/syco) - Symposium on Compositional Structures

## Journals

* [Categories and General Algebraic Structures with Applications](https://cgasa.sbu.ac.ir/) - Categories and General Algebraic Structures with Applications is an international biannual journal published by Shahid Beheshti University, Tehran, Iran, founded in 2013
* [Compositionality](http://www.compositionality-journal.org/) - Open-access journal for research using compositional ideas, most notably of a category-theoretic origin, in any discipline
* [Theory and Applications of Categories](http://www.tac.mta.ca/tac/) - Theory and Applications of Categories (ISSN 1201 - 561X) is the all-electronic, refereed journal on Category Theory, categorical methods and their applications in the mathematical sciences.

## Lectures
  * [Applied Category Theory](https://ocw.mit.edu/courses/mathematics/18-s097-applied-category-theory-january-iap-2019/) - David Spivak and Brendan Fong
  * [What is Applied Category Theory](https://arxiv.org/abs/1809.05923) - This is a collection of introductory, expository notes on applied category theory, inspired by the Applied Category Theory Workshop by Tai-Danae Bradley (2018)
  * [18.S097: Programming with Categories](http://brendanfong.com/programmingcats.html), [lecture notes](http://brendanfong.com/programmingcats_files/cats4progs-DRAFT.pdf) - In this course we explain how category theory has become useful for writing elegant and maintainable code. In particular, we'll use examples from the Haskell programming language to motivate category-theoretic constructs. By Brendan Fong, Bartosz Milewski, and David Spivak (2020)
  * [CS 353: Algebraic Logic - Chapter 4: Category theory](http://boole.stanford.edu/cs353/handouts/book4.pdf) - Lecture Notes from Stanford University (2022)
  * [Quantum Processes and Computation](http://www.cs.ru.nl/A.Kissinger/teaching/qpc2019/) - Lecture Notes from Radboud University (Netherlands) by Aleks Kissinger and John van de Wetering (2019)
  * [Category theory](http://www.mathematik.uni-muenchen.de/~pareigis/Vorlesungen/04SS/Cats1.pdf) - Lecture Notes from University of Munich by Bodo Pareigis (2004)
  * [Commutative algebra](https://www.youtube.com/watch?v=QOTf8KfrZFU&list=PL8yHsr3EFj53rSexSz7vsYt-3rpHPR3HB) - This lecture is part of an online course on commutative algebra, following the book
"Commutative algebra with a view toward algebraic geometry" by David Eisenbud. By Richard E. Borcherds (2020).
  * [Introduction to Category Theory and Categorical Logic](https://www2.mathematik.tu-darmstadt.de/~streicher/CTCL.pdf) - Lecture Notes of Darmstadt University of Technology by Thomas Streicher (2003)

## Meetups
* [Boston](https://www.meetup.com/Categorical-Databases/) - This group is about applying category theory to problems in information management
* [New York](https://www.meetup.com/NYC-Category-Theory/) - NYC Category Theory and Algebra is a group for people interested in studying Category Theory (CT) and/or Abstract Algebra together. One of our purposes is to meet and read basic texts in Category Theory.
* [San Francisco Bay Area](https://www.meetup.com/Category-Theory) - A meetup dedicated to teaching category theory, and especially applications, including functional programming, data management, block-chain, quantum computing, and AI.

## Podcasts

* [Corecursive: Category Theory With Bartosz Milewski](https://corecursive.com/035-bartosz-milewski-category-theory/) - Adam talks to Bartosz Milewski, the author of a popular blog series, lecture series, and now book on Category Theory for programmers
* [Sean Carroll's Mindscape: Emily Riehl on Topology, Categories, and the Future of Mathematics](https://www.preposterousuniverse.com/podcast/2021/05/10/146-emily-riehl-on-topology-categories-and-the-future-of-mathematics/) - Emily Riehl discusses how mathematical concepts, like topology and category theory, enrich our understanding of the universe and its possibilities
* [Category Theory for Normal Humans with Dr. Eugenia Cheng](https://www.greaterthancode.com/category-theory-for-normal-humans) - A podcast with Dr. Eugenia Cheng on Category Theory and her mathematical background (2017)
* [Eric Daimler on Conexus and Category](https://soundcloud.com/max-sklar-637976507/ep-243-eric-daimler-on-conexus-and-category-theory) - Todays guest is CEO and co-founder of Conexus, the first spinoff of the MIT math department that takes discoveries in high level mathematics (category theory) and applies them to make databases intelligent across many industries (2022)

## Related

#### Books

* [Homotopy Type Theory: Univalent Foundations of Mathematics](https://homotopytypetheory.org/book/) - Homotopy type theory is an emerging field in mathematics that uniquely merges elements from diverse areas
* [A Book of Abstract Algebra: Second Edition](https://www.amazon.com/Book-Abstract-Algebra-Second-Mathematics/dp/0486474178/ref=as_li_ss_tl?crid=9UYHEJVLG8UX&dchild=1&keywords=a+book+of+abstract+algebra&qid=1601150629&sprefix=A+Book+of+Abstract,aps,401&sr=8-1&linkCode=sl1&tag=prathyvsh-20&linkId=862e18748d7d6025561022da3fadbcfd&language=en_US) - Comprehensive yet approachable, this exceptional book covers all subjects addressed in a standard introductory abstract algebra course

#### Podcasts

* [Type Theory Forall](https://www.typetheoryforall.com) - Podcast hosted by Pedro Abreu (Pronounced ‘Ahbrel’), PhD Student in Programming Languages at Purdue University
* [Lambda Cast](https://soundcloud.com/lambda-cast) - LambdaCast is a podcast about functional programming for working developers

## Software Libraries

* [Category Theory in Coq](https://github.com/jwiegley/category-theory) - Axiom-free formalization of category theory in Coq
* [Catlab.jl](https://github.com/epatters/Catlab.jl) - Experimental framework for applied category theory
* [Lens](https://hackage.haskell.org/package/lens) - Lens: Lenses, Folds and Traversals
* [Semigroupoids](https://hackage.haskell.org/package/semigroupoids) - Semigroupoids: Category sans id
* [UniMath](https://github.com/UniMath/UniMath/tree/master/UniMath/CategoryTheory) - Categories formalized using univalent mathematics, in Coq
* [copumpkin/categories](https://github.com/copumpkin/categories) - Categories parametrized by morphism equality, in Agda
* [free](https://hackage.haskell.org/package/free) - Free monads are useful for many tree-like structures and domain specific languages
* [idris-ct](https://github.com/statebox/idris-ct) - Formally verified category theory library written in Idris
* [Category Theory in Lean4](https://leanprover-community.github.io/mathlib_docs/category_theory/category/basic.html) - Experimental category theory library for Lean
* [WildCats](https://wildcatsformma.wordpress.com/) - Mathematica package for computational category theory

## Tools

* [Quiver](https://github.com/varkor/quiver) - Modern commutative diagram editor for the web
* [Cartographer.id](http://cartographer.id/) - Tool for string diagrammatic reasoning
* [Homotopy.io](https://homotopy.io/) - Web-based proof assistant for finitely-presented globular n-categories
* [KdMonCat](https://edit.statebox.cloud/) - Tool for drawing morphisms in monoidal categories
* [XyJax](https://sonoisa.github.io/xyjax-v3/xyjax-v3.html) - Xy-pic extension for MathJax, that lets you draw commutative diagrams in browser

## Video Lectures

* [Applied Category Theory @ MIT 2019](https://www.youtube.com/playlist?list=PLhgq-BqyZ7i5lOqOqqRiS0U5SwTmPpHQ5) - Series of lectures based on the "Seven Sketches" book - by Brendan Fong and David I. Spivak
* [Applied Category Theory at Topos Institute](https://www.youtube.com/watch?v=UusLtx9fIjs&list=PLhgq-BqyZ7i5lOqOqqRiS0U5SwTmPpHQ5)
* [Bartosz Milewski's video lectures](https://www.youtube.com/watch?v=I8LbkfSSR58&list=PLbgaMIhjbmEnaH_LTkxLI7FMa2HsnawM_)
* [Category Theory, The essence of interface-based design](https://www.youtube.com/watch?v=JMP6gI5mLHc) - Introduces concepts like Curry-Howard isomorphism, tuples, products, and functors, and explains how they relate to programming by Erik Meijer (2014)
* [Programming with Categories](https://www.youtube.com/watch?v=NUBEB9QlNCM) Video lectures at MIT by Brendan Fong, Bartosz Milewski, David Spivak (2020)
* [The Catsters](https://www.youtube.com/user/TheCatsters) - Videos on various topics in category theory (2014)
* [Lenses, Folds, and Traversals](https://www.youtube.com/watch?v=cefnmjtAolY) - Talk from Edward Kmett (2012) at the second New York Haskell User Group Meeting on the new lens library, which provides a highly composable toolbox for accessing and modifying multiple parts of data structures
* [Category theory foundations](https://www.youtube.com/playlist?list=PLGCr8P_YncjVjwAxrifKgcQYtbZ3zuPlb) - Steve Awodey has an excellent series, aimed a little higher (with a compsci flavour), going a little further
* [Lecture Videos and Readings](https://ocw.mit.edu/courses/18-s097-applied-category-theory-january-iap-2019/pages/lecture-videos-and-readings/) - B. Fong and D. Spivak: elementary lectures on applied category theory
* [OPLSS 2016 - Category Theory Background](https://www.youtube.com/playlist?list=PLiHLLF-foEexKDi7tmiO5tP8Uxt0ueK-L) - Ed Morehouse: four basic level lectures to accompany his 2016 notes listed above
* [Category Theory Foundations, Oregon Programming Languages Summer School 2012](https://www.youtube.com/watch?v=ZKmodCApZwk) - Material will be presented at a tutorial level that will help graduate students and researchers understand the critical issues and open problems confronting the field. By Steve Awodey (2012)
* [Category Theory Lecture 1 (NGA CoE-MaSS) - 2022](https://www.zurab.online/2022/08/category-theory-course-2022.html) - This is a video-based course aimed at post-graduate students and as well academics interested to learn about category theory, with live participation of the audience shaping the content of the course. (2022)

## Wiki
* [ncatlab](https://ncatlab.org) - A wiki with content varying from pure category theory, to categorical perspectives on other areas of maths, to random unrelated bits of maths
* [Wikipedia](https://en.wikipedia.org/wiki/Outline_of_category_theory) - Has some good articles about category theory

