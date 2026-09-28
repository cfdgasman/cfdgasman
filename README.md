# Hi, I'm Adam 

I consider myself an **applied mathematician with an engineering background** who enjoys solving difficult mathematical equations, physical models, and engineering problems through computation.

My work is rooted in **classical numerical methods, computational fluid dynamics (CFD), and scientific computing**. My main area of expertise is **incompressible and low-speed flows**, particularly **pressure–velocity coupling and finite-volume methods**. My broader experience spans **finite difference, finite element, discontinuous Galerkin, and particle-based methods**, including **Molecular Dynamics (MD) and Direct Simulation Monte Carlo (DSMC)**, as well as **linear algebra, linear solvers, and multigrid methods** for solving the discrete systems from discretisation.

What I enjoy most is taking a difficult problem, understanding the mathematics and physics behind it, and turning it into a **numerical method, computational algorithm that can actually solve the problem**.

I also enjoy implementing numerical methods efficiently, including using **MPI and GPU/CUDA programming where parallelisation and computational performance matter**. Alongside scientific computing, I develop **end-to-end software and full-stack applications** that turn computational methods into usable tools.

More recently, I have been exploring **machine learning and artificial intelligence**. My interest is not in replacing classical CFD with black-box models, but in understanding how AI might complement established numerical methods and make scientific computing **faster, more efficient, and more capable**.

---

## ❤️ Why I Do It

I am a CFD numerics expert, and most of my work is focused on the mathematical and computational foundations of numerical simulation—developing, understanding, and improving the methods that make CFD possible.

What motivates me, beyond the technical challenge, is hoping these tools can truly support and uplift people in their everyday lives. I have a particular appreciation for the idea that CFD, applied mathematics, thermodynamics, and computational science can be used to improve human life. I would love to see advances in fluid mechanics and numerical simulation contribute to better understanding of universe, improved healthcare technologies, and solutions that can ultimately improve human health, quality of life, and longevity.

## 🤖 AI & Vibe Coding

I enjoy using AI and exploratory coding to learn about and build in diverse areas—trading systems and market analysis, website creation, Python development, and mobile app design. It's a way to rapidly explore ideas across different domains while staying curious and engaged.

### 🧩 Small public projects

| Project | What it is | Tech |
|---|---|---|
| [gas-dynamics-ai](https://github.com/cfdgasman/gas-dynamics-ai) | Python companion code for a gas dynamics book chapter | Python |
| [4dimensional-images](https://github.com/cfdgasman/4dimensional-images) | Turning a video into a "4-dimensional" image, with time as the fourth axis | Python |
| [website-creation-example](https://github.com/cfdgasman/website-creation-example) | A 9-page website built with AI and no frameworks | HTML, CSS |
| [weather-dash](https://github.com/cfdgasman/weather-dash) · [live](https://cfdgasman.github.io/weather-dash/) | Weather dashboard with city search and a 7-day forecast | JavaScript, Open-Meteo |
| [pomodoro-timer](https://github.com/cfdgasman/pomodoro-timer) · [live](https://cfdgasman.github.io/pomodoro-timer/) | Minimal Pomodoro focus timer | JavaScript |
| [cli-todo](https://github.com/cfdgasman/cli-todo) | Command-line to-do list with no dependencies, tested with CI | Python |

### 🧮 Computational mechanics portfolio

Small, self-contained solvers written from scratch. Each one is **validated against an exact solution or a published benchmark**, has tests running in CI, and has a README with the discretisation and results.

| Project | What it shows | Validation |
|---|---|---|
| [lid-driven-cavity](https://github.com/cfdgasman/lid-driven-cavity) | Incompressible Navier–Stokes, FV staggered MAC grid, projection method | Ghia et al. (1982); observed order 2.04 |
| [sod-shock-tube](https://github.com/cfdgasman/sod-shock-tube) | Compressible Euler, MUSCL + HLLC, exact Riemann solver | Sod, Lax, Toro test 3 |
| [turbulent-channel-rans](https://github.com/cfdgasman/turbulent-channel-rans) | Mixing-length and Wilcox k-ω RANS, integrated to the wall | Law of the wall, Dean's C<sub>f</sub> (0–2.5 %) |
| [vof-interface-advection](https://github.com/cfdgasman/vof-interface-advection) | Geometric PLIC-VOF, exact mass conservation | Single vortex, Zalesak disk |
| [dgsem-couette](https://github.com/cfdgasman/dgsem-couette) | DGSEM on curvilinear elements, BR1 + penalty | Exponential convergence to 10⁻¹³ |
| [dgsem-entropy-stable](https://github.com/cfdgasman/dgsem-entropy-stable) | Entropy-stable split-form DGSEM (SBP, flux differencing) | Tam acoustic pulse, KHI robustness |
| [fem-cantilever](https://github.com/cfdgasman/fem-cantilever) | Plane-stress FEM, Q4 vs incompatible modes (shear locking) | Timoshenko–Goodier exact solution |
| [fd-operator-splitting](https://github.com/cfdgasman/fd-operator-splitting) | FD stability (von Neumann), Lie vs Strang splitting | Fisher–KPP exact wave |
| [cylinder-wake-pod-dmd](https://github.com/cfdgasman/cylinder-wake-pod-dmd) | Lattice Boltzmann wake + POD (SVD) + DMD | Strouhal from two methods (0.1 %) |
| [dsmc-rarefied-gas](https://github.com/cfdgasman/dsmc-rarefied-gas) | Hard-sphere DSMC (Bird's NTC) | H-theorem, slip and free-molecular limits |
| [boltzmann-dvm](https://github.com/cfdgasman/boltzmann-dvm) | Boltzmann–BGK with discrete velocities, asymptotic preserving | Exact Euler and free-molecular limits, vs DSMC |
| [sparse-matrix-lab](https://github.com/cfdgasman/sparse-matrix-lab) | Reordering and fill-in, spectra and CFL limits, pseudospectra, CG/GMRES with IC(0)/ILU(0) | Orszag (1971) eigenvalue, Reddy–Henningson transient growth |
| [schrodinger-orbitals](https://github.com/cfdgasman/schrodinger-orbitals) | Schrödinger equation as sparse eigenproblems, hydrogen on a 262k-point 3D grid | E<sub>n</sub> = −1/(2n²), oscillator n + ½ |
| [many-electron-atoms](https://github.com/cfdgasman/many-electron-atoms) | Many-electron Schrödinger four ways: Hartree–Fock & LDA atoms (He–Ar) on a log grid, exact 1D helium, Hylleraas helium, H₂⁺ on a 3D grid | NIST LDA and HF limit to 10⁻⁶, exact He to 10⁻⁸ |
| [equation-discovery](https://github.com/cfdgasman/equation-discovery) | SINDy / PDE-FIND sparse regression (Brunton & Kutz) | Recovers the Navier–Stokes vorticity equation and ν (0.09 %) |

---

## 🌊 Computational Fluid Dynamics

CFD is at the core of much of my work.

My strongest focus is on **incompressible and low-speed flows**, particularly the numerical challenges associated with pressure, velocity, and continuity.

I work with:

- Incompressible Navier–Stokes equations
- Low-speed and low-Mach-number flows
- Pressure–velocity coupling
- SIMPLE, SIMPLEC, and PISO
- Pressure correction methods
- Pressure Poisson equations
- Collocated and staggered formulations
- Mass conservation
- Convection and diffusion discretisation
- Flux and gradient reconstruction
- Steady and transient solvers
- Laminar and turbulent flows
- Numerical stability and convergence
- Verification and validation

I am interested in CFD **at the solver level**—not simply using an existing package, but understanding how governing equations become discrete equations, how pressure and velocity are coupled, how the resulting systems are solved, and why a numerical solution behaves the way it does.

---

## 🔢 Numerical Methods

My background spans a broad range of classical numerical approaches for differential equations, conservation laws, and physical systems.

### Finite Volume Methods — FVM

One of my strongest areas.

- Conservative control-volume formulations
- Pressure–velocity coupling
- Convection and diffusion schemes
- Upwind and central discretisation
- Higher-order reconstruction
- TVD and MUSCL methods
- Flux reconstruction
- Gradient reconstruction
- Pressure interpolation
- Iterative solution methods
- AMG and Linear Algebra
- Non-Conformal Interfaces
- Degenerated and poor quality Meshes

### Finite Difference Methods — FDM

- Explicit and implicit schemes
- Crank–Nicolson methods
- Stability and convergence analysis
- Modified-equation analysis
- High-order discretisation
- Parabolic and hyperbolic PDEs

### Finite Element Methods — FEM

- Galerkin and Petrov–Galerkin formulations
- Mixed formulations
- Stabilised FEM
- Continuous and discontinuous formulations

### Discontinuous Galerkin — DG

- High-order formulations
- Nodal and modal methods
- Unstructured meshes
- BR2 / LDG
- hp-adaptivity
- Entropy Stable schemes
- Conservation laws

### Particle-Based Methods

I also work with computational approaches that move beyond continuum discretisation.

**Molecular Dynamics (MD)**

- Molecular interactions
- Particle dynamics
- Statistical mechanics
- Thermodynamic properties

**Direct Simulation Monte Carlo (DSMC)**

- Rarefied and transitional flows
- Kinetic theory
- Particle transport
- Collision modelling
- Gas–particle interactions
- Micro-scale flow

---

## ⚙️ Parallel & Scientific Computing

For computationally demanding problems, I use parallelisation techniques where they are useful.

My experience includes:

- **MPI** for distributed and parallel computation
- **CUDA / GPU programming** for computational acceleration
- Parallel numerical algorithms
- Linear algebra and linear solvers
- Direct and iterative methods
- Domain decomposition
- Performance-oriented implementation
- Load Balancing and Efficient Coding

I am interested in how numerical algorithms can be implemented efficiently without losing sight of the **mathematics, accuracy, and physical correctness** of the underlying method.

---

## 💻 Scientific Software & Full-Stack Development

I also enjoy taking computational algorithms beyond research prototypes and turning them into **complete, usable applications**.

My software work spans:

- Scientific computing
- Numerical solver development
- Computational backends
- APIs
- Backend development
- Frontend development
- Databases
- Interactive scientific visualisation
- Full-stack applications
- Deployment and production systems

I particularly enjoy connecting a **complex mathematical or scientific engine to an intuitive interface**, making sophisticated computational methods accessible to people who may not need to understand everything happening underneath.

---

## 📐 Applied Mathematics

At the foundation of everything I do is a fascination with **difficult equations and mathematical models**.

I enjoy working with:

- Ordinary differential equations
- Partial differential equations
- Nonlinear systems
- Boundary-value problems
- Initial-value problems
- Conservation laws
- Numerical linear algebra
- Iterative methods
- Stability and convergence
- Numerical optimisation
- Approximation theory
- Transport equations
- Mathematical modelling

