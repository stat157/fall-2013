This list is a quick sketch of many of the topics we'll cover in this
course. The list groups together related topics, but we will **not**
be covering the material in the order listed here, but rather as we
work on a real problem we'll address these issues as they arise and
are presented to us.

Reproducibility and Collaboration
---------------------------------
- Revision control systems: why?
- Introduction to git and github
- Introduction to Python and IPython notebook
- Some important Python libraries: scientific computing--numpy, scipy, matplotlib, basic Python libraries--collections, itertools
- Good coding hygiene
- Code "smells"
- Coding "Style". Python style
- File formats
- Documentation and comments
- Introduction to LaTeX and BibTeX
- Reproducibility and replicability; levels of reproducibility.
- Coding for Collaboration. Collaborating with your future self
- (Resources: http://nbviewer.ipython.org/urls/raw.github.com/fperez/reprosw/master/Version%20Control.ipynb, https://github.com/swcarpentry/boot-camps/tree/2013-04-ucb)

Computational Architecture
--------------------------
- Parallel computing: MIMD, SIMD, Hadoop, Map-Reduce. Inter-process communication (tools for scientific computing)
- Cloud computing
- Virtual machines
- Installing software on virtual machines

Security and Data Integrity
---------------------------
- Hashes and digests (PRNG, security)
- Key properties of ideal hashes: collision-free, one-way
- Sketch of SHA256 (cryptographically encode info) MD5 is broken.
- Hash chains
- Public key encryption
- Digital signatures

Data structures and formats
---------------------------
- XML
- JSON
- Unstructured data
- Geographic data
- regular expressions
- Relational databases; SQL
- Pickling

Content v. Presentation; Web standards
--------------------------------------
- Separating content from presentation
- XHTML, CSS
- HTML5
- JavaScript
- jQuery
- D3

Simulation
----------
- Pseudo-random number generators; seeds
- Tests of PRNGs: DIEHARD battery
- Connection between PRNGs and cryptography
- Cryptographically secure PRNGs
- Using hashes as PRNGs
- Pseudo random sampling. Why does the number of states of a PRNG matter?
- Simulation, reproducible simulation
- The probability transform
- Simulating arbitrary univariate distributions
- Application of Randomization: Permutation tests.
   + Null hypothesis: invariance under a group
   + Fisher’s exact test
   + 2-sample test for means
      + Tests based on ranks
      + Permutation t-test
   + Permutation versions of ANOVA
   + Tests of association
      + Spearman Rank correlation and test
      + Permutation version of Pearson test

Numerics
--------
- Floating point arithmetic
- Machine precision
- Underflow and overflow
- Error accumulation
- algebraic equality does not imply numerical equality: examples

Numerical linear algebra
------------------------
- Numerical linear algebra
- Packages: LAPACK, SCALAPACK
- Condition number
- Solving linear systems: avoid inverses
- Least squares: the Projection Theorem and its geometric interpretation.
- Underconstrained systems: The Pseudo-Inverse
- Regularized least squares and ridge regression

Optimization
------------
- Unconstrained optimization: the problem of local minima.
- Minimal values versus minimizing points
- Convex optimization. Local minima attain the global minimum.
- Newton’s method for convex, differentiable objectives
- Smooth vs non-smooth convex problems.
- Failure of steepest descent for nonsmooth convex problems: example
- Convex Constrained optimization: Kuhn-Tucker conditions.
- Linear and quadratic programs. Fundamental Theorem of Linear Programming; the Simplex Algorithm

Data Visualization
------------------
- Principles and best practices for graphical display of data
- Plotting, contour plots, mesh plots, false-color plots.
- Plotting on non-Cartesian domains

Code efficiency
---------------
- Profiling tools
- vectorization and nested loops
- reducing duplicated evaluations
- abstraction, modularity
- (Resources: http://scipy-lectures.github.io/ https://github.com/jrjohansson/scientific-python-lectures#online-read-only-versions)

© 2013 P.B. Stark and A. Culich
