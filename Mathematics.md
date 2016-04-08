**Only [Mathematical](http://en.wikipedia.org/wiki/Lists_of_mathematics_topics) libraries and packages, and related resources.**
NB: Many packages may not be regularly updated to work with Julia nightlies or the currently released stable version of Julia.

+ [CRYPTOGRAPHY](#cryptography)
   + [Cryptocurrency](#cryptocurrency)
+ [MATH](#math)
   + [Computer Arithmetic](#computer-arithmetic)
      + [Floating Point](#floating-point)
+ [Algebra](#algebra)
   + [Abstract Algebra](#abstract-algebra)
   + [Boolean Algebra](#boolean-algebra)
   + [Orthogonal Polynomials](#orthogonal-polynomials) 
   + [Symbolic Computation](#symbolic-computation)
+ [Calculus & Applied Math](#calculus-&-applied-math)
   + [DSP](#dsp)
      + [Org-JuliaDSP](#org-juliadsp)
      + [FFT](#fft) 
   + [Functions](#functions)
      + [Ordinary Differential Equation](#ordinary-differential-equation)
         + [Org-JuliaLang](#org-julialang)
         + [Org-JuliaDiff](#org-juliadiff)
      + [Special Functions](#special-functions)
+ [Discrete Math](#discrete-math)
+ [Geometry](#geometry)
   + [Algebraic Geometry](#algebraic-geometry)
   + [Solid Geometry](#solid-geometry)
+ [Numerical Analysis](#numerical-analysis)
   + [Linear Algebra](#linear-algebra)
   + [Numerical Linear Algebra](#numerical-linear-algebra)
        + [Org-JuliaFEM](#org-juliafem)
        + [Org-JuliaSparse](#org-juliasparse) 
+ [PUZZLES](#puzzles)

----

# CRYPTOGRAPHY
+ [BlockCipherSelfStudy.jl](https://github.com/andrewcooke/BlockCipherSelfStudy.jl) :: Blocks, and RC5.
+ [Crypto.jl](https://github.com/danielsuo/Crypto.jl) :: A library that wraps OpenSSL, but also has pure Julia implementations for reference.
+ [Hashlib.jl](https://github.com/samgre/Hashlib.jl) :: SHA1 implementation for Julia.
+ [MbedTLS.jl](https://github.com/malmaud/MbedTLS.jl) :: Wrapper around mbedtls.
+ [Nettle.jl](https://github.com/staticfloat/Nettle.jl) :: is a simple wrapper around libnettle, a cryptographic library.
+ [OpenSSL.jl](https://github.com/dirk/OpenSSL.jl) :: WIP OpenSSL bindings for Julia.
+ [OpenSSLCrypto.jl](https://github.com/amitmurthy/OpenSSLCrypto.jl) :: Julia interface to the crypto API of openssl.
+ [RNGTest.jl](https://github.com/andreasnoackjensen/RNGTest.jl) :: A package that is a Julia interface to the test suite TestU01 of Pierre l'Ecuyer to test random numbers.
+ [RNGTesting](https://github.com/johnmyleswhite/RNGTesting) :: Scripts for testing Julia's RNG's.
+ [SHA.jl](https://github.com/staticfloat/SHA.jl) :: a performant, 100% native-julia SHA2-{224,256,384,512} implementation.
+ [Sha256.jl](https://github.com/mad4alcohol/Sha256.jl) :: [Sha256 hash algorithm for Julia.
+ [Stupid.jl](https://github.com/andrewcooke/Stupid.jl) :: Analysis of an 8 bit version of the cipher at http://news.quelsolaar.com/#comments101.

### Cryptocurrency 
+ Bit[Coin.jl](https://github.com/danielsuo/Coin.jl) :: A library for working with Bitcoin written in Julia.

----

# MATH 
+ DOCS : [Mathematical Operations](http://docs.julialang.org/en/release-0.3/manual/mathematical-operations/) and a [list of all overloadable operators](https://github.com/JuliaLang/julia/blob/master/src/julia-parser.scm#L1-L19) in Julia.
+ [BasisFunctions.jl](https://github.com/daanhb/BasisFunctions.jl) :: A collection of routines for working with a number of standard basis functions, mainly for use in the FrameFuns package.
+ [Bijections.jl](https://github.com/scheinerman/Bijections.jl) :: Bijection datatype for Julia.
+ [Church.jl](https://github.com/LaurenceA/Church.jl) :: helps you perform inference in complex, and simple, probabilistic models.
+ [Cartesian.jl](https://github.com/timholy/Cartesian.jl) :: Fast multidimensional algorithms.
+ [Catalan.jl](https://github.com/andrioni/Catalan.jl) :: a combinatorics library for Julia.
+ [CRF.jl](https://github.com/slyrz/CRF.jl) :: Conditional Random Fields in Julia.
+ [CellularAutomata.jl](https://github.com/natj/CellularAutomata.jl) :: Cellular Automata package.
+ [ContinuedFractions.jl](https://github.com/johnmyleswhite/ContinuedFractions.jl) :: Types and functions for working with continued fractions in Julia.
+ [Devectorize.jl](https://github.com/lindahua/Devectorize.jl) :: A Julia framework for delayed expression evaluation.
+ [DiffModels.jl](https://github.com/jdrugo/DiffModels.jl) : Diffusion Model simulation and first-passage time densities in Julia.
+ [Entropy.jl](https://github.com/grero/Entropy.jl) :: This package contains functionality for computing binless estimates of entropy from discrete and continuous samples for continuous distributions.
+ [Equations.jl](https://github.com/jhlq/Equations.jl) :: Derive mathematical relations.
+ [ExtremeValueDistributions.jl](https://github.com/sammorris81/ExtremeValueDistributions.jl) :: A Julia package to fit extreme value distributions.
+ [FastGauss.jl](https://github.com/ajt60gaibb/FastGauss.jl) :: Computes Gauss quadrature rules to 16-digit precision (so far Legendre, Jacobi, Lobatto, Radau).
+ [FloorLayout.jl](https://github.com/joehuchette/FloorLayout.jl) ::  Framework and various drivers for floor layout formulation analysis.
+ [FrameFuns.jl](https://github.com/daanhb/FrameFuns.jl) :: Exploring practical possibilities of approximating functions with frames rather than with a basis.
+ [GSL.jl](https://github.com/jiahao/GSL.jl) :: Julia interface to the GNU Scientific Library - GSL.
+ [Hecke.jl](https://github.com/thofma/Hecke.jl).
+ [Hexagons.jl](https://github.com/dcjones/Hexagons.jl) :: Useful tools for working with hexagonal grids.
+ [MathToolkit.jl](https://github.com/baruchel/MathToolkit.jl) :: A Julia package providing various functions mainly for the purpose of experimental mathematics. 
+ [Measures.jl](https://github.com/dcjones/Measures.jl) :: Unified measure and coordinates types.
+ [MPFR.jl](https://github.com/andrioni/MPFR.jl) :: A Julia package for the GNU MPFR library.
+ [Multicombinations.jl](https://github.com/jlep/Multicombinations.jl) :: An iterator for k-combinations with repetitions, k-multicombinations, k-multisubsets.
+ [NaNMath.jl](https://github.com/mlubin/NaNMath.jl) :: Julia math built-ins which return NaN.
+ [NLreg.jl](https://github.com/dmbates/NLreg.jl) :: Nonlinear regression in Julia.
+ [NLsolve.jl](https://github.com/EconForge/NLsolve.jl) :: Julia solvers for systems of nonlinear equations.
+ [nrmm.jl](https://github.com/juho-lee/nrmm.jl) :: Posterior inference algorithms for normalized random measure mixtures.
+ [OEIS.jl](https://github.com/MurrayT/OEIS.jl) :: A basic wrapper to allow access to OEIS from within Julia. 
+ [Quadrature.jl](https://github.com/kofron/Quadrature.jl) : Gauss quadrature in Base.
+ [Quat.jl](https://github.com/forio/Quat.jl) :: Quaternions, octonions and dual-quaternions.
+ [quaternion.jl](https://github.com/peakbook/quaternion.jl) :: Quaternion for Julia Language.
+ [Sieve of Atkin](https://gist.github.com/Ismael-VC/179790a53c549609b3ce) :: Implemented by @Ismael-VC as per the [WP pseudocode](https://en.wikipedia.org/wiki/Sieve_of_Atkin#Pseudocode) with a comparision of ["atkin" with "Base.primes"](http://nbviewer.ipython.org/gist/Ismael-VC/25b1a0c1e11f306a40ae), tested on JuliaBox version `0.4.0-dev+5491`.
+ [Shannon.jl](https://github.com/kzahedi/Shannon.jl) :: Entropy, Mutual Information, KL-Divergence related to Shannon's information theory and functions to binarize data.
+ [SimilarityMetrics.jl](https://github.com/johnmyleswhite/SimilarityMetrics.jl) :: Standard similarity metrics in Julia.
+ [Smolyak](https://github.com/EconForge/Smolyak) :: Efficient implementations of Smolyak's algorithm for function approxmation in Python and Julia.
+ [Sobol.jl](https://github.com/stevengj/Sobol.jl) :: is a generation of Sobol low-discrepancy sequence (LDS) implementation, that generates "quasi-random" sequences of points in N dimensions which are equally distributed over an N-dimensional hypercube.
+ [SymPy.jl](https://github.com/jverzani/SymPy.jl) :: Julia interface to SymPy via PyCall.
+ [TSne.jl](https://github.com/lejon/TSne.jl) :: Julia port of L.J.P. van der Maaten and G.E. Hinton's T-SNE visualisation technique. Read about the [t-Distributed Stochastic Neighbor Embedding](http://homepage.tudelft.nl/19j49/t-SNE.html)
+ [TwoBasedIndexing.jl](https://github.com/simonster/TwoBasedIndexing.jl) :: Two-based indexing.
+ [Uncertain.jl](https://github.com/rephorm/Uncertain.jl) :: Uncertain quantities and error propagation for the Julia language.
+ [univariate__opt.jl](https://github.com/matthewclegg/univariate_opt.jl) :: Univariate optimization and root-finding code for Julia and its [newly maintained fork](https://github.com/EconForge/univariate_opt.jl).
+ [Unums.jl](https://github.com/tbreloff/Unums.jl) :: Unum (Universal Number) types and operations.  {Usable: 1, Robust: 1, Active: 1}
+ [UnumTests.jl](https://github.com/goedman/UnumTests.jl) :: Some experiments with Unums. {#NonCuratedPackage}
+ [utils.jl](https://github.com/juho-lee/utils.jl) :: basic utilities needed for scientific coding with julia.

## [Computer Arithmetic](https://en.wikipedia.org/wiki/Category:Computer_arithmetic)
+ [DeepConvert.jl](https://github.com/jlapeyre/DeepConvert.jl) :: This package provides convenient literal construction of values of large data types.
+ [ErrorFreeArith.jl](https://github.com/J-Sarnoff/ErrorFreeArith.jl) :: Error-Free transformations for arithmetic ops.

### [Floating Point](https://en.wikipedia.org/wiki/Category:Floating_point)
+ [DecFP.jl](https://github.com/stevengj/DecFP.jl) :: The package provides 32-bit, 64-bit, and 128-bit binary-encoded decimal floating-point types following the IEEE 754-2008, implemented as a wrapper around the (BSD-licensed) Intel Decimal Floating-Point Math Library. 
+ [DoubDouble.jl](https://github.com/J-Sarnoff/DoubDouble.jl).
+ [DoubleDouble.jl](https://github.com/simonbyrne/DoubleDouble.jl) :: A Julia package for performing extended-precision arithmetic using pairs of floating-point numbers.
+ [ErrorFreeTransforms.jl](https://github.com/dsiem/ErrorFreeTransforms.jl) :: Map the rounding errors in floating point arithmetic with error-free transformations (EFT).
+ [FlexFloat.jl](https://github.com/J-Sarnoff/FlexFloat.jl) :: Allows values to stretch in a way that preserves accuracy durring mathematical computations.
+ [Floats512.jl](https://github.com/J-Sarnoff/Floats512.jl) :: Accurate floating point math at extended precision for Float-512.
+ [Floats1024.jl](https://github.com/J-Sarnoff/Floats1024.jl) :: Accurate floating point math at extended precision for Float-1024.
+ [FloatHigher.jl](https://github.com/J-Sarnoff/FloatHigher.jl) :: accurate floating point math at extended precisions.
+ [UnumX.jl](https://github.com/JuliaComputing/UnumX.jl) :: Experimental Unums.
+ [ValidatedNumerics.jl](https://github.com/dpsanders/ValidatedNumerics.jl) :: Rigorous floating-point calculations via interval arithmetic.

###### Resources
+ [Elementary Number Theory](https://github.com/williamstein/ent) :: Primes, Congruences, and Secrets.

----

# Algebra
+ [algebra](https://github.com/alrahimi/algebra/) :: A hierarchy of abstract algebraic structures in Julia.
+ [AMVW.jl](https://github.com/andreasnoackjensen/AMVW.jl) :: Fast and backward stable computation of roots of polynomials in Julia
+ [CLBLAS.jl](https://github.com/ekobir/CLBLAS.jl) :: CLBLAS integration for Julia.
+ [Clockwork.jl](https://github.com/malmaud/Clockwork.jl) :: Represent modular arithmetic via clock symbols. 
+ [Cuhre.jl](https://github.com/tflovorn/Cuhre.jl) :: Simplified Julia interface to Cuhre integration routine.
+ [Digits.jl](https://github.com/greenflash1357/Digits.jl) :: A module for integer digit manipulation.
+ [FirstOrderLogic.jl](https://github.com/TotalVerb/FirstOrderLogic.jl) :: 
This package aims to include functions that manipulate mathematical logic.
+ [Hecke](https://github.com/thofma/hecke) :: A package for algebraic number 
theory that works on top of `Nemo.jl` by Tommy Hofmann and Claus Fieker.
+ [Juniper.jl](https://github.com/jcrist/Juniper.jl) :: A simple computer algebra system.
+ [Lifts.jl](https://github.com/scheinerman/Lifts.jl) :: Linear fractional transformations in Julia. This module defines a Lift data type to represent a complex linear fractional transformation. 
+ [Mods.jl](https://github.com/scheinerman/Mods.jl) :: Easy modular arithmetic for Julia.
+ [MultiPoly.jl](https://github.com/daviddelaat/MultiPoly.jl) :: Sparse multivariate polynomials in Julia.
+ [Nemo.jl](http://nemocas.org/) :: A computer algebra package for the Julia programming language. The [source code](https://github.com/wbhart/Nemo.jl) is maintained by William Hart, Tommy Hofmann, Claus Fieker, Fredrik Johansson, Oleksandr Motsak and other contributors.
+ [QNaN.jl](https://github.com/J-Sarnoff/QNaN.jl) :: Quiet NaNs were designed to propagate information from within numerical computations.
+ [OrderedCollections.jl](https://github.com/kmsquire/OrderedCollections.jl) :: OrderedDict and OrderedSet for Julia.
+ [SemiringAlgebra.jl](https://github.com/ViralBShah/SemiringAlgebra.jl) :: Semiring Algebra.

###### Resources
+ [adeles](https://github.com/williamstein/adeles) :: Ideles adeles algebraic number theory.

## [Abstract Algebra](http://en.wikipedia.org/wiki/Abstract_algebra)

## [Boolean Algebra](http://en.wikipedia.org/wiki/Category:Boolean_algebra)
+ [BitCircuits.jl](https://github.com/um-tech-evolution/BitCircuits.jl) :: Boolean circuit evaluation using bitwise operations.
+ [ShowSet.jl](https://github.com/scheinerman/ShowSet.jl) :: Nicer output for Set and IntSet objects.

## Orthogonal Polynomials
+ [ChebyshevApprox](https://github.com/RJDennis/ChebyshevApprox) :: Julia code to approximate continuous functions using Chebyshev polynomials.
+ [InterPol.jl](https://github.com/pwl/InterPol.jl) :: Interpolating polynomial for Julia.
+ [Jacobi.jl](https://github.com/pjabardo/Jacobi.jl) :: Jacobi polynomials and Gauss quadrature related functions.
+ [Orthopolys.jl](https://github.com/daviddelaat/Orthopolys.jl) :: Orthogonal Polynomials - Currently supports Jacobi polyonomials, Gegenbauer polynomials, Hermite polynomials.
+ [Polynomial.jl](https://github.com/vtjnash/Polynomial.jl) :: Polynomial manipulations and [PolyExt.jl](https://gist.github.com/mathpup/8514578), an extension of Polynomial.jl to support polynomial division, with handy conversions and promotion rules. 
+ [TempInterp.jl](https://github.com/cc7768/TempInterp.jl) :: Evaluation of Chebyshev polynomials and splines.

## [Symbolic Computation](https://en.wikipedia.org/wiki/Symbolic_computation)
+ [SJulia](https://github.com/jlapeyre/SJulia) :: A partial implementation of a language for symbolic computation, based on pattern matching and an evaluation sequence closely modeled on Mathematica.
+ [Symbolic.jl](https://github.com/scidom/Symbolic.jl) :: Symbolic computations and computer algebra in Julia.
+ [SymEngine.jl](https://github.com/symengine/SymEngine.jl) :: Julia wrappers of SymEngine.

----

# Calculus & [Applied Math](http://en.wikipedia.org/wiki/Applied_mathematics)
+ [ad4julia](https://github.com/bsxfan/ad4julia) :: Some automatic diffferentiation coding experiments in Julia. 
+ [Calculus.jl](https://github.com/johnmyleswhite/Calculus.jl) :: Calculus package.
+ [Calculus2.jl](https://github.com/johnmyleswhite/Calculus2.jl) :: A draft of a new interface for the Calculus package.
+ [FDM.jl](https://github.com/grasingerm/FDM.jl) :: Finite difference methods in Julia.
+ [FeynmanKacSpde.jl](https://github.com/scidom/FeynmanKacSpde.jl) :: Feynman-Kac SPDE Inference.
+ [HemirealFactorization.jl](https://github.com/timholy/HemirealFactorization.jl) :: Matrix factorizations over the hemireals.
+ [HemirealNumbers.jl](https://github.com/timholy/HemirealNumbers.jl) :: Implementation of hemireal arithmetic for Julia.
+ [HyperNumbers.jl](https://github.com/goedman/HyperNumbers.jl) :: Julia implementation of HyperNumbers.
+ [IFastSum.jl](https://github.com/J-Sarnoff/IFastSum.jl) :: Accurate summation (Yuhang Zhao's iFastSum).
+ [pdetools.jl](https://github.com/GaZ3ll3/pdetools.jl) :: Toolbox for solving PDEs.
+ [PowerSeries.jl](https://github.com/jwmerrill/PowerSeries.jl) :: Truncated Power Series for Julia, which exports a Series type that represents a truncated power series by its coefficients. You can do arithmetic on Series and apply functions to series just as you would Real or Complex numbers.
   * _Power Series Blog_::
   * Jason Merrill's blog series highlighting the basic aspects of floating point arithmetic with examples in Julia - [The first one, on bisecting floating point numbers](http://squishythinking.com/2014/02/22/bisecting-floats/)
+ [PolyMath.jl](https://github.com/cfbaptista/PolyMath.jl) :: a package for polynomial arithmetic, calculus, interpolation and quadrature algorithms implemented in Julia.
+ [RAD.jl](https://github.com/adamkapor/RAD.jl) :: package defines a macro, @autodiff, for reverse-mode automatic differentiation.
+ [RDE.jl](https://github.com/scidom/RDE.jl) :: Simulation and Bayesian Inference for Rough Differential Equations (RDEs).
+ [ReverseDiffOverload.jl](https://github.com/LaurenceA/ReverseDiffOverload.jl) :: Reverse mode differentiation for pre-defined functions.
+ [ReverseDiffSparse.jl](https://github.com/mlubin/ReverseDiffSparse.jl) :: Hessian algorithmic differentiation to compute hessian sparsity pattern.
+ [ReverseDiffSparse2.jl](https://github.com/mlubin/ReverseDiffSparse2.jl) :: Prototype replacement for ReverseDiffSparse based on flattened out expression graphs. 
+ [ReverseDiffTape.jl](https://github.com/fqiang/ReverseDiffTape.jl) :: A Julia package for reverse mode differentiation on a tape.
+ [RiemannComplexNumbers.jl](https://github.com/scheinerman/RiemannComplexNumbers.jl) :: The RiemannComplexNumbers module is an alternative Complex type for Julia (with a single complex infinity value). 
+ [TaylorSeries.jl](https://github.com/lbenet/TaylorSeries.jl) :: A julia package for Taylor expansions in one independent variable.

###### Resources
+ [Riemann Hypothesis book](http://wstein.org/rh/) with the [source code on github](https://github.com/williamstein/rh).
+ [Calculus With Julia](https://github.com/CalculusWithJulia/CalculusWithJulia.github.io) :: Introductory Calculus with the Julia Programming Language. 
+ An IJulia notebook showing [Taylor's method integration of the pendulum](http://nbviewer.ipython.org/gist/lbenet/616fa81f3c12c9cfcf97)

## [DSP](https://en.wikipedia.org/wiki/Digital_signal_processing)
+ [APES.jl](https://github.com/codles/APES.jl) :: Amplitude and Phase Estimation of a Sinusoid.
+ [ChaosCommunications.jl](https://github.com/scidom/ChaosCommunications.jl) :: Simulation of chaos-based communication systems in Julia.
+ [CompressedSensing](https://github.com/dahlend/CompressedSensing) :: A basic compressed sensing algorithms available via the official package list with [documentation](http://compressedsensing.readthedocs.org/en/latest/).
+ [Fdtd.jl](https://github.com/nantonel/Fdtd.jl) :: 3D Room Acoustics Finite Difference Time Domain (FDTD) Simulator.
+ [KDSP.jl](https://github.com/kofron/KDSP.jl) :: Yet another implementation of common DSP routines in Julia.
+ [KernelRecursiveLeastSquares.jl](https://github.com/the-moliver/KernelRecursiveLeastSquares.jl) :: Julia implementation of Kernel Recursive Least Squares algorithm.
+ [MDCT.jl](https://github.com/stevengj/MDCT.jl) :: This module computes the modified discrete cosine transform (MDCT) in the Julia language and the inverse transform (IMDCT), using the fast type-IV discrete cosine tranform (DCT-IV) functions in Julia (via FFTW).
+ [Multirate.jl](https://github.com/JayKickliter/Multirate.jl) :: Streaming polyphase DSP filters with sample rate conversion.
+ [RIM.jl](https://github.com/nantonel/RIM.jl) :: Julia implementation of a Room Acoustics Impulse Response Generator using the Randomized Image Method (RIM).
+ [wavechaos](https://github.com/amyascwk/wavechaos) 
+ [WDSP.jl](https://github.com/pjabardo/WDSP.jl) :: Digital signal processing used in turbulence implemented in Julia.

### Org-[JuliaDSP](https://github.com/JuliaDSP)
+ [DSP.jl](https://github.com/JuliaDSP/DSP.jl) :: The DSP ver-0.0.1 package, includes functions for periodogram estimation, generating window functions, filter design and FFT-based FIR filtering, works on Julia 0.2 and 0.3-prerelease. The [documentation is available via RTD.org](http://dspjl.readthedocs.org/en/latest/)

### [FFT](https://en.wikipedia.org/wiki/Fast_Fourier_transform)
+ [CLFFT.jl](https://github.com/JuliaGPU/CLFFT.jl) :: Julia bindings for AMD's clFFT library.
+ [CUFFT.jl](https://github.com/JuliaGPU/CUFFT.jl) :: Wrapper for the CUDA FFT library.
+ [NFFT.jl](https://github.com/tknopp/NFFT.jl) :: Julia implementation of the NFFT : Non-equidistant Fast Fourier Transform.
+ [SnFFT.jl](https://github.com/GDPlumb/SnFFT.jl) :: A Julia package designed to facilitate harmonic analyis on the symmetric group of order n, denoted Sn. 


## [Functions](http://en.wikipedia.org/wiki/Category:Types_of_functions)
+ [Elliptic.jl](https://github.com/nolta/Elliptic.jl) :: Elliptic integral and Jacobi elliptic special functions.
+ [FastAnonymous.jl](https://github.com/timholy/FastAnonymous.jl) :: Fast "anonymous functions" for Julia.

### [Integral Equation](https://en.wikipedia.org/wiki/Integral_equation)
+ [ApproxFun](https://github.com/dlfivefifty/ApproxFun) :: Julia IFun Implementation is a package for approximating functions. It currently supports intervals, the real line, periodic intervals and the unit circle. It is heavily influenced by the Matlab package chebfun and the Mathematica package RHPackage.
+ [SIE.jl](https://github.com/ApproxFun/SIE.jl) :: Julia package for solving singular integral equations and Riemann–Hilbert problems Julia package for solving singular integral equations and Riemann–Hilbert problems.
+ [SingularIntegralEquations.jl](https://github.com/ApproxFun/SingularIntegralEquations.jl) :: Julia package for solving singular integral equations and Riemann–Hilbert problems.

###### Resources
+ [NumericalMath’s documentation for Integration](http://hwborchers.lima-city.de/JuliaMeetup/numerical/integration.html).

### [Ordinary Differential Equation](http://en.wikipedia.org/wiki/Ordinary_differential_equation)
+ [AutoDiff.jl](https://github.com/scidom/AutoDiff.jl) :: Juila 自动微分（[Automatic Differentiation](https://en.wikipedia.org/wiki/Automatic_differentiation)）程序包
+ [DASSL.jl](https://github.com/pwl/DASSL.jl) :: 微分代数系统求解器（DASSL: Differential Algebraic System SoLver）的算法实现，用于求解微分代数方程组（DAE: Differential Algebraic Equations）
+ [DualNumbers2.jl](https://github.com/johnmyleswhite/DualNumbers2.jl) :: Another Julia implementation of dual numbers for automatic differentiation.
+ [DynamicalSystems.jl](https://github.com/timothyrenner/DynamicalSystems.jl) :: 用于生成各种动态系统函数的包。（注，这些动态系统函数用作[龙格库塔求解器](https://github.com/timothyrenner/RungeKutta.jl)的输入） 
+ [IVPTestSuite.jl](https://github.com/mauro3/IVPTestSuite.jl) :: 微分方程求解器测试套装，用于常微分方程组(ODE)和微分代数方程组(DAE).
+ [HPFEM.jl](https://github.com/pjabardo/HPFEM.jl) :: Julia的HP有限元分析
+ [JFinEALE.jl](https://github.com/PetrKryslUCSD/JFinEALE.jl) :: 一种有限元分析学习环境包 (FinEALE)，用于对连续统的有限元分析。这个工具包是在Matlab包的基础上重新设计的。
+ [Makhno.jl](https://github.com/pjabardo/Makhno.jl) :: Spectral element code implemented in Julia.
+ [ODEDSL.jl](https://github.com/AleMorales/ODEDSL.jl) :: 确切定义域语言（Domain Specific Language），用于描述动态系统模型（状态空间模型）并且自带测试。这是一个用于Julia，R，Cpp（通过Rcpp）的代码自动生成器。
+ [odesolver](https://github.com/insideloop/odesolver) :: 常微分方程组（ODE）求解器包
+ [RiemannHilbert.jl](https://github.com/dlfivefifty/RiemannHilbert.jl) :: Riemann–Hilbert problems, named after [Bernhard Riemann and David Hilbert](http://en.wikipedia.org/wiki/Riemann%E2%80%93Hilbert_problem), are a class of problems that arise in the study of differential equations in the complex plane.

###### Resources
+ [FinealeBook.jl](https://github.com/goedman/FinealeBook.jl) :: Trying to understand Petr Krysl's FinEALE book.

#### Org-JuliaLang
+ [AppleAccelerate.jl](https://github.com/JuliaLang/AppleAccelerate.jl) :: Julia interface to OS X's Accelerate framework.
+ [ODE.jl](https://github.com/JuliaLang/ODE.jl) :: Assorted basic Ordinary Differential Equation solvers.
+ [Options.jl](https://github.com/JuliaLang/Options.jl) :: A framework for providing optional arguments to functions.
+ [Roots.jl](https://github.com/JuliaLang/Roots.jl) :: Root finding functions for Julia.
+ [SortingAlgorithms.jl](https://github.com/JuliaLang/SortingAlgorithms.jl) :: extra sorting algorithms extending Julia's sorting API.
+ [Sundials.jl](https://github.com/JuliaLang/Sundials.jl) :: A Julia package that interfaces to the Sundials library and includes a nonlinear solver (KINSOL), ODE's (CVODE), and DAE's (IDA).

#### Org-[JuliaDiff](http://www.juliadiff.org/)
+ [ReverseDiffSource.jl](https://github.com/JuliaDiff/ReverseDiffSource.jl) :: Automated differentiation by reverse accumulation. [Documentation](http://reversediffsourcejl.readthedocs.org/en/master/index.html).
+ [HyperDualNumbers.jl](https://github.com/JuliaDiff/HyperDualNumbers.jl) :: Hyper-Dual Numbers for Exact Second-Derivative Calculations, is structured similar to the DualNumbers package, which aims for complete support for HyperDual types for numerical functions within Julia's Base. Currently, basic mathematical operations and trigonometric functions are supported.
+ [ForwardDiff.jl](https://github.com/JuliaDiff/ForwardDiff.jl) :: Julia包,用于前向自动微分(Forward AD).
+ [DualNumbers.jl](https://github.com/JuliaDiff/DualNumbers.jl) :: Julia package for representing dual numbers and for performing dual algebra.
+ [NDuals.jl](https://github.com/JuliaDiff/NDuals.jl) :: Experimental package for stack-allocated dual numbers with multiple epsilon components.

### [Special Functions](http://en.wikipedia.org/wiki/Category:Special_functions)
+ [LambertW.jl](https://github.com/jlapeyre/LambertW.jl) :: A package implementing the Lambert_W function and associated omega constant.

----

# [Discrete Math](https://en.wikipedia.org/wiki/Category:Discrete_mathematics)
+ [ClosedIntervals.jl](https://github.com/scheinerman/ClosedIntervals.jl) :: 闭区间运算包：形如[a,b]的（实数轴上的）闭区间和他们的运算。
+ [DiscreteFactor.jl](https://github.com/wlbksy/DiscreteFactor.jl) :: Discrete factor and its operations in Probabilistic Graphical Models.
+ [DiscreteInference.jl](https://github.com/lindahua/DiscreteInference.jl) :: Viterbi algorithm.
+ [Intervals.jl](https://github.com/andrioni/Intervals.jl) :: A pure Julia reimplementation of MPFI, a multiple precision interval arithmetic library.
+ [IntModN.jl](https://github.com/andrewcooke/IntModN.jl) :: 模算数包：同余整数所构成的环和多项式环，和他们的运算。
+ [IPPMath.jl](https://github.com/lindahua/IPPMath.jl) :: A Julia package for vectorized math computation based on Intel IPP.
+ [PermPlain.jl](https://github.com/jlapeyre/PermPlain.jl) :: Permutations implemented with plain data types - This package implements methods for manipulating permutations. The methods operate on data types in the Base module, or in modules providing generic data types. 
+ [Permutations.jl](https://github.com/scheinerman/Permutations.jl) by @scheinerman :: 用于Julia的置换(Permutations)类:
+ [PermutationsA.jl](https://github.com/jlapeyre/PermutationsA.jl) by @jlapeyre :: Permutation data types and methods. 
+ [PrimeSieve.jl](https://github.com/jlapeyre/PrimeSieve.jl) :: This package provides an interface to tables of primes and a sieve library.
+ [RomanNumerals.jl](https://github.com/anthonyclays/RomanNumerals.jl) :: Support for Roman numerals in Julia.
+ [Shannon.jl](https://github.com/kzahedi/Shannon.jl) :: Entropy, Mutual Information, KL-Divergence related to Shannon's information theory and functions to binarize data.
+ [SimplePosets.jl](https://github.com/scheinerman/SimplePosets.jl) :: Simple partially ordered sets for Julia.
+ [ZChop.jl](https://github.com/jlapeyre/ZChop.jl) :: This package replaces small numbers with zero, works on complex and rational numbers, arrays, and some other structures. The idea is for zchop to descend into structures, chopping numbers, and acting as the the identity on anything that can't be sensibly compared to eps.

----

# [Geometry](http://en.wikipedia.org/wiki/Geometry)
+ [AffineTransforms.jl](https://github.com/timholy/AffineTransforms.jl) :: Computational geometry with affine transformations
+ [ConicHulls.jl](https://github.com/toivoh/ConicHulls.jl) :: Exact dynamic conic hulls of integer vectors.
+ [ConvexHull.jl](https://github.com/joehuchette/ConvexHull.jl) :: A Julia library for polyhedral computations.
+ [D4.jl](https://github.com/khwilson/D4.jl) :: An attempted implementation of Enumerating Quartic Dihedral Extensions of Q by Cohen, Diaz y Diaz, and Olivier in Composito Mathematica 2002.
+ [GeoAlg.jl](https://github.com/andrioni/GeoAlg.jl) :: A basic geometric 
algebra library in Julia.
+ [Geometry2D.jl](https://github.com/mroughan/Geometry2D.jl) :: 2D computational geometry package for Julia programming language.
+ [mbr.jl](https://github.com/intdxdt/mbr.jl) :: axis aligned minimum bounding box.
+ [Tau.jl](https://github.com/Aerlinger/Tau.jl) :: A simple module providing definition of the Tau constant. 
+ [Tensors.jl](https://github.com/pgawron/Tensors.jl) :: Julia package for tensor decompositions.
+ [TensorOperations.jl](https://github.com/Jutho/TensorOperations.jl) :: Julia package for tensor contractions and related operations.

## [Algebraic Geometry](http://en.wikipedia.org/wiki/Category:Algebraic_geometry)
+ [CSoM.jl](https://github.com/goedman/CSoM.jl) :: Investigate Julia version of "Programming the FEM" by I M Smith, D V Griffiths.
+ [EllipticCurves.jl](https://github.com/wwilson/EllipticCurves.jl) :: Elliptic Curves in Julia.
+ [khypot.jl](https://github.com/intdxdt/khypot.jl) :: k dimensional hypotenuse.
+ [FEM.jl](https://github.com/pjabardo/FEM.jl) :: Simple finite elements in Julia.
+ [ols.jl](https://github.com/forio/ols.jl) :: Julia type for multiple (multivariate) regression using OLS - Performs least squared regression on linear equations of multiple independent variables.
+ [SurfaceMesh.jl](https://github.com/michelk/SurfaceMesh.jl) :: A Finite element surface mesh manipulation library to work with polygon-surface-meshes.
+ [TrussPlotter.jl](https://github.com/sjkelly/TrussPlotter.jl) :: This is a package to plot trusses for finite element results.

## [Solid Geometry](https://en.wikipedia.org/wiki/Solid_geometry)
+ [Descartes.jl](https://github.com/FactoryOS/Descartes.jl) :: A research project into the representation of solid geometry.

----

# [Numerical Analysis](https://en.wikipedia.org/wiki/Category:Numerical_analysis)
+ [ApproXD.jl](https://github.com/floswald/ApproXD.jl) :: B-splines and linear high-dimensional approximators in multiple dimensions for Julia.
+ [Dopri.jl](https://github.com/helgee/Dopri.jl) :: A Julia wrapper for the DOPRI5 and DOP853 integrators.
+ [Dierckx.jl](https://github.com/kbarbary/Dierckx.jl ):: A Julia wrapper for the Dierckx Fortran library for spline fitting.
+ [EiSCor.jl](https://github.com/andreasnoack/EiSCor.jl) :: A Julia wrapper of the Fortran library "eiscor" (Fortran 90 subroutines for structured matrix eigenvalue problems using 2x2 unitary matrices) for efficiently solving structured matrix eigenvalue problems using unitary core transformations 
+ [Expokit.jl](https://github.com/acroy/Expokit.jl) :: A package that provides Julia implementations of some routines contained in EXPOKIT.
+ [FastGaussQuadrature.jl](https://github.com/ajt60gaibb/FastGaussQuadrature.jl) :: A Julia package to compute n-point Gauss quadrature nodes and weights to 16-digit accuracy and in O(n) time.
   + Fork by [dlfivefifty](https://github.com/dlfivefifty/FastGaussQuadrature.jl) :: Gauss quadrature nodes and weights in Julia. 
+ [Grid.jl](https://github.com/timholy/Grid.jl) :: Interpolation and related operations on grids.
+ [GridInterpolations.jl](https://github.com/sisl/GridInterpolations.jl) :: Multi-dimensional grid interpolation in arbitrary dimensions on a recti-linear grid. 
+ [InplaceOps.jl](https://github.com/simonbyrne/InplaceOps.jl) :: Convenient macros for in-place matrix operations in Julia.
+ [Interpolations.jl](https://github.com/tlycken/Interpolations.jl) :: B-spline interpolation in Julia.
+ [LinearExpressions.jl](https://github.com/cdsousa/LinearExpressions.jl) :: is a Julia package to manipulate symbolic linear expressions with both scalar and matrix coefficients - large linear matrix inequalities (LMI) for SDP optimization.
+ [LinearMaps.jl](https://github.com/Jutho/LinearMaps.jl) :: A Julia package for defining and working with linear maps, also known as linear transformations or linear operators acting on vectors. The only requirement for a LinearMap is that it can act on a vector (by multiplication) efficiently.
+ [LowRankApprox.jl](https://github.com/klho/LowRankApprox.jl) :: Fast low-rank matrix approximation in Julia.
+ [RandomMatrices.jl](https://github.com/jiahao/RandomMatrices.jl) :: Random Matrices.
   + [Video](https://www.youtube.com/watch?v=68yy33jOkOs) of Jiahao and Andreas talk on __Free probability, random matrices and disorder in organic semiconductors__ at MIT CSAIL.
+ [Knitro.jl](https://github.com/yeesian/Knitro.jl) :: Julia interface to the Knitro solver.
+ [LinearMaps.jl](https://github.com/Jutho/LinearMaps.jl) :: A Julia package for defining and working with linear maps, also known as linear transformations or linear operators acting on vectors. The only requirement for a LinearMap is that it can act on a vector (by multiplication) efficiently.
+ [MovcolN.jl](https://github.com/pwl/MovcolN.jl) :: Moving collocation method to solve one dimensional partial differential equations.
+ [NAG.jl](https://github.com/StefanKarpinski/NAG.jl) :: Julia package to wrap the NAG Numerical Library, a propreitary software library of numerical analysis routines, mathematical and statistical algorithms for linear algebra, optimization, quadrature, the solution of ordinary and partial differential equations, regression analysis, and time series analysis.
+ [SortedVectors.jl](https://github.com/colintbowers/SortedVectors.jl) :: A WIP package that implements a SortedVector type.

### Linear Algebra
+ [AxisAlgorithms.jl](https://github.com/timholy/AxisAlgorithms.jl) :: Efficient filtering and linear algebra routines for multidimensional arrays.
+ [CUSPARSE.jl](https://github.com/kshyatt/CUSPARSE.jl) :: Julia interface to NVIDIA's CUSPARSE library.
+ [CUSOLVER.jl](https://github.com/kshyatt/CUSOLVER.jl) :: Julia bindings for the NVIDIA CUSOLVER library. CUSOLVER is a high-performance direct-solver matrix linear algebra library.
+ [green-fairy](https://github.com/carnaval/green-fairy) :: Lattice trees.
+ [Hypre.jl](https://github.com/jgoldfar/Hypre.jl) :: A wrapper for the [Hypre](http://acts.nersc.gov/hypre/) library.
+ [IDRsSolver.jl](https://github.com/mschauer/IDRsSolver.jl) :: Induced Dimension Reduction method [IDR(s)] for solving general linear equations. 
+ [juliaSpot](https://github.com/slimgroup/juliaSpot) :: The Julia implementation of the Spot Linear Algebra Package.
+ [KrylovSolvers.jl](https://github.com/cfbaptista/KrylovSolvers.jl) :: Solve sparse linear systems in an efficient and iterative manner with Krylov Solvers.
+ [LinearAlgebra.jl](https://github.com/andreasnoack/LinearAlgebra.jl) :: Eigenvalue and -vector calculations in Julia.
+ [LMesh.jl](https://bitbucket.org/maurow/lmesh.jl) :: A Mesh package that implements the type of mesh sugessted by Logg (2012).
+ [LDA.jl](https://github.com/remusao/LDA.jl) :: Linear Discriminant Analysis and Kernel Fisher Analysis.
+ [LLLplus.jl](https://github.com/christianpeel/LLLplus.jl) :: LLL lattice reduction, sphere decoder, and related lattice tools.
+ [LMCLUS.jl](https://github.com/wildart/LMCLUS.jl) :: Julia's package for Linear Manifold Clustering.
+ [MUMPS](https://github.com/lruthotto/MUMPS) :: A wrapper for a MUltifrontal Massively Parallel sparse direct Solver of large linear systems in Julia.
+ [MUMPS1.jl](https://github.com/dmbates/MUMPS1.jl) :: An alternative implementation of a Julia interface to the sparse direct solver MUMPS. A MUMPS package for Julia is already registered but that package does not conform to the packaging standards for Julia.
+ [NonuniformArray.jl](https://github.com/ReidAtcheson/NonuniformArray.jl) :: This library handles the case of "array of arrays" where each subarray may have different lengths - but enforces contiguity of data for ease of passing to outside linear algebra packages.
+ [PolarFact.jl](https://github.com/weijianzhang/PolarFa.jl) :: A Julia package for the matrix polar decomposition.
+ [SALT.jl](https://github.com/xdavidliu/SALT.jl) :: SALT (steady-state ab-initio laser theory) solver package for Julia. 
+ [SuperLU.jl](https://github.com/dmbates/SuperLU.jl) :: Julia interface to the SuperLU solver package for sparse systems.

### Numerical Linear Algebra (NLA)
__Julia implementations of solvers for Numerical Linear Algebra (NLA) == Numerical Analysis and Linear Algebra algorithms for the numerical solution of matrix problems.__
+ [Accelereval.jl](https://github.com/lindahua/Accelereval.jl) :: A Julia framework for accelerated re-compiled evaluation of numerical functions that ensures faster computation.
+ [BSplines.jl](https://github.com/gusl/BSplines.jl) :: This package provides B-Splines for 1D signals, i.e. functions of type Real -> Real.
+ [Elemental.jl](https://github.com/JuliaParallel/Elemental.jl) :: A Julia interface to the [Elemental linear algebra library](http://libelemental.org/) with third-party interfaces. [Source code](https://github.com/elemental/Elemental).
+ [IncrementalSVD.jl](https://github.com/aaw/IncrementalSVD.jl) :: Simon Funk's approach to collaborative filtering using the singular value decomposition, implemented in Julia.
+ [InteriorPoint.jl](https://github.com/IainNZ/InteriorPoint.jl) :: Primal-dual interior point solver for linear programs.
+ [IterativeLinearSolvers.jl](https://github.com/andreasnoackjensen/IterativeLinearSolvers.jl).
+ [IterativeSolvers.jl](https://github.com/JuliaLang/IterativeSolvers.jl) :: Implement Arnoldi and Lanczos methods for svds and eigs. 
+ [NumericalShadow.jl](https://github.com/pgawron/NumericalShadow.jl) :: Library to calculate numerical shadows in Julia language.
+ [NumericExtensions.jl](https://github.com/lindahua/NumericExtensions.jl) :: Julia extensions to provide high performance computational support for fast vectorized computation.
   + _DOCS_:: are available at [numericextensionsjl.readthedocs.org](http://numericextensionsjl.readthedocs.org/en/latest/)
+ [NumericFuns.jl](https://github.com/lindahua/NumericFuns.jl) :: Math functions and functors for numerical computations.
+ [NumericFunctors.jl](https://github.com/lindahua/NumericFunctors.jl) :: Typed functors for numerical computations.
+ [ParallelLinalg.jl](https://github.com/intirb/ParallelLinalg.jl) :: Distributed Dense Linear Algebra for Julia.
+ [PNLA_Julia](https://github.com/kbatseli/PNLA_Julia) :: Polynomial Multi-functional Numerical Linear Algebra package for solving all kinds of problems with multivariate polynomials in double precision in Julia.
+ [RK4.jl](https://github.com/ntezak/RK4.jl) :: This package implements a fairly fast Runge-Kutta 4th order with fixed stepsize, also implements a stochastic solver that is not technically provably accurate, but works well for finite bandwidth SDE's.
+ [SpecialMatrices.jl](https://github.com/timbers/SpecialMatrices.jl) :: Package that adds support for several common matrices: Strang, Hankel, Toeplitz, and Vander matrices.
+ [SpecialMatrices.jl](https://github.com/jiahao/SpecialMatrices.jl) :: Julia package for working with special matrix types.
+ [ToeplitzMatrices.jl](https://github.com/andreasnoackjensen/ToeplitzMatrices.jl) :: Fast matrix multiplication and division for Toeplitz matrices in Julia.
+ [VML.jl](https://github.com/JuliaLang/VML.jl) :: Julia bindings for the Intel Vector Math Library.

#### Org-[JuliaFEM](https://github.com/JuliaFEM)
__Finite element methods__
+ [JuliaFEM.jl](https://github.com/JuliaFEM/JuliaFEM.jl) :: Finite Element method solver.
+ [MiniBall.jl](https://github.com/JuliaFEM/MiniBall.jl).
+ [TetGen.jl](https://github.com/JuliaFEM/TetGen.jl) :: Finite Element method solver.

#### Org-[JuliaSparse](https://github.com/JuliaSparse) 
__For the development of interfaces to sparse matrix solvers such as sequential MUMPS, SuperLU, perhaps Pastix and fill-reducing permutation software such as Metis and Scotch.__
+ [HarwellRutherfordBoeing.jl](https://github.com/JuliaSparse/HarwellRutherfordBoeing.jl) :: A Julia Reader for the Harwell-Boeing and Rutherford-Boeing Formats.
+ [MatrixMarket.jl](https://github.com/JuliaSparse/MatrixMarket.jl) :: A package to read the MatrixMarket file format.
+ [Meshpart.jl](https://github.com/JuliaSparse/Meshpart.jl) :: A Julia port of some of the functions from John Gilbert and Shang Hua Teng's Meshpart toolbox.
+ [Metis.jl](https://github.com/JuliaSparse/Metis.jl) :: Julia interface to the Metis graph-partitioning algorithms.
+ [MKLSparse.jl](https://github.com/JuliaSparse/MKLSparse.jl) :: Override sparse-dense operations when MKL is available.
+ [MultiFrontalCholesky.jl](https://github.com/JuliaSparse/MultiFrontalCholesky.jl) :: The Cholesky decomposition of a Hermitian, positive-definite matrix into the product of a lower triangular matrix and its conjugate transpose, used for efficient numerical solutions and Monte Carlo simulations.
+ [MUMPS.jl](https://github.com/JuliaSparse/MUMPS.jl) :: An interface to MUMPS (a MUltifrontal Massively Parallel sparse direct Solver) to efficiently solve large and sparse linear systems in scientific computing.
+ [MUMPSseq.jl](https://github.com/JuliaSparse/MUMPSseq.jl) :: Alternative Julia interface to MUMPS sparse system solver. 
+ [SparseVectors.jl](https://github.com/JuliaSparse/SparseVectors.jl) :: A Julia package to support sparse vectors.


###### Resources
+ [JuliaCon2015](https://github.com/JuliaSparse/JuliaCon2015) :: Sparse Matrices in Julia worksho at JuliaCon2015.
+ 2015Apr09 : [Video of Andreas Noack and Jiahao Chen](https://www.youtube.com/channel/UCizxnsw19qcTOdJdIJVtl0Q) speaking at the Linear Algebra and Optimization seminar at the Institute for Computational and Mathematical Engineering at Stanford. [Notebook presentation of the talk](http://andreasnoack.github.io/talks/2015AprilStanford_AndreasNoack.ipynb).
+ Learn the [theory of linear algebra](https://github.com/ULAFF/notebooks) hand-in-hand with the practice of [software library development](https://www.edx.org/course/linear-algebra-foundations-frontiers-utaustinx-ut-5-02x)
+ [The Performance Cost of Integer Overflow Checking](http://danluu.com/integer-overflow/)

----

# PUZZLES
**Puzzles, problem solving games**
+ [Deepthought.jl](https://github.com/dejakaymac/Deepthought.jl)
+ [euler](https://github.com/somu/euler) :: Project Euler solutions in Julia.
+ [PlayingCards.jl](https://github.com/DataWookie/PlayingCards.jl) :: Package for simulating Playing Cards games in Julia.
+ [Project_Euler_Julia.ipynb](http://nbviewer.ipython.org/github/punkrockpolly/Playing-with-Julia/blob/master/Project_Euler_Julia.ipynb) :: Solutions to [Project Euler](http://projecteuler.net) Problems, algorithm & math puzzles.
+ [sudoku](https://github.com/Alexander-N/sudoku) :: Reimplementing the Python version of Peter Norvig's Sudoku solver in Julia by @Alexander-N.
+ [sudoku.jl](https://github.com/johnmyleswhite/sudoku.jl) :: A simple Sudoku solver in Julia by @johnmyleswhite.
+ [Sudoku.jl](https://github.com/hayd/Sudoku.jl) :: A port of Peter Norvig's "Solving Every Sudoku Puzzle" to Julia by @hayd.
+ [SudokuService](https://github.com/IainNZ/SudokuService) :: Sudoku-as-a-service, powered by Julia, JuMP modelling, and CoinOR CBC integer programming solver.
+ [TowerOfHanoi.jl](https://github.com/thiruk/TowerOfHanoi.jl) :: Solution to Tower Of Hanoi using Julia.

