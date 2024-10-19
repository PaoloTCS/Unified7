\documentclass[12pt,a4paper]{article}

% Packages
\usepackage[utf8]{inputenc}
\usepackage[T1]{fontenc}
\usepackage{amsmath,amssymb,amsfonts}
\usepackage{graphicx}
\usepackage{hyperref}
\usepackage{xcolor}
\usepackage{amsthm}
\usepackage{algorithm}
%   \usepackage{algorithmic}
% adding 2 lines below
\usepackage{algorithmicx}
\usepackage{algpseudocode}


\usepackage{algpseudocode}
\usepackage{braket}

% Theorem-like environments
\newtheorem{definition}{Definition}
\newtheorem{theorem}{Theorem}
\newtheorem{proposition}{Proposition}
\newtheorem{conjecture}{Conjecture}
\newtheorem{hypothesis}{Hypothesis}

% Custom environment for dedication
\newenvironment{dedication}
  {\cleardoublepage
   \thispagestyle{empty}
   \vspace*{\stretch{1}}
   \itshape
   \raggedright
  }
  {\vspace{\stretch{3}}
   \clearpage
  }

% Title information
\title{\textbf{Unified Framework for Fundamental Interaction and Communication across Physical, Linguistic, and Computational Systems}}
\author{Paolo Pignatelli, ChatGPT, and Claude (Anthropic AI Assistant)}
\date{October 2024}

\begin{document}

\maketitle

\input{dedication-section}

\tableofcontents

\input{introduction-section-C1}
\input{fil-section-C2}
\input{language-union-section-C1}
\input{nibbler-algorithm-section-C1}
\input{quantum-connections-section}
\input{integration-section}
%  New to be worked on
\input{Blockchain-Enhanced-Knowledge-Validation.tex}  
\input{implications-applications-section}
\input{ethical-considerations-section}
\input{conclusion-section}

\input{acknowledgments-section}

% References section
\bibliographystyle{plain}
\bibliography{references}

\end{document}