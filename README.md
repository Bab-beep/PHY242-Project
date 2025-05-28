# PHY242-Project
\documentclass[a4paper,12pt]{article}
\usepackage{amsmath, amssymb, amsfonts}
\usepackage{graphicx}
\usepackage{hyperref}
\usepackage{physics}
\usepackage{mathtools}

\title{Symmetry Protection of Edge States in a 2D Topological Insulator}
\author{Name1, Name2, Name3, Name4}
\date{\today}

\begin{document}

\maketitle

\begin{abstract}
  Investigate how time-reversal symmetry protects the gapless edge states in a 2D $Z_2$ topological insulator (like the Bernevig-Hughes-Zhang (BHZ) model).
\end{abstract}

\section{Mathematical Derivation}
\begin{enumerate}
    \item Start with the effective four-band BHZ model Hamiltonian in 2D:
    
    \[
    H(\mathbf{k}) = \begin{pmatrix}
    m(\mathbf{k}) & A k_x & 0 & -A k_y \\
    A k_x & -m(\mathbf{k}) & -A k_y & 0 \\
    0 & -A k_y & -m(\mathbf{k}) & -A k_x \\
    -A k_y & 0 & -A k_x & m(\mathbf{k})
    \end{pmatrix},
    \]
    where $m(\mathbf{k}) = M - B(k_x^2 + k_y^2)$.

    \item Identify the time-reversal symmetry operator $\Theta$ for this system: $\Theta = \tau_0 \otimes i\sigma_y K$, where $K$ is complex conjugation.

    \item Analyze the bulk band structure and demonstrate the topological nature of the insulating phase by calculating the $Z_2$ topological invariant.

    \item Consider a finite-size strip geometry with open boundary conditions.

    \item Analytically derive the dispersion relation of the edge states that appear within the bulk band gap.

    \item Mathematically show how time-reversal symmetry enforces the Kramers degeneracy of the edge states at any momentum $k$ and prevents backscattering between counter-propagating edge states with opposite spin, thus protecting their gaplessness.
\end{enumerate}

\end{document}
