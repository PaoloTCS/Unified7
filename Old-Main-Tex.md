\documentclass[12pt,a4paper]{article}

% Packages
\usepackage[T1]{fontenc}
\usepackage{lmodern}
\usepackage{amsmath, amssymb, amsfonts}
\usepackage{amsthm}
\usepackage{xcolor}
\usepackage{graphicx}
\usepackage{braket}  % Added for quantum mechanics notation
\usepackage{natbib}  % Added for bibliography management
\usepackage[colorlinks=true, linkcolor=blue, urlcolor=blue, citecolor=blue]{hyperref}

% Theorem-like environments
\newtheorem{definition}{Definition}[section]
\newtheorem{theorem}{Theorem}[section]
\newtheorem{proposition}{Proposition}[section]
\newtheorem{conjecture}{Conjecture}[section]
\newtheorem{hypothesis}{Hypothesis}[section]

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
\title{Unified Framework for Fundamental Interaction and Communication across Physical, Linguistic, and Computational Systems}
\author{Paolo Pignatelli}
\date{\today}

\begin{document}

\maketitle
\newpage
\tableofcontents
\newpage

\input{introduction-section-C1}
\input{fil-section-C2}
\input{language-union-section-C1}
\input{nibbler-algorithm-section-C1}
\input{quantum-connections-section}
\input{integration-section}
\input{implications-applications-section}
\input{ethical-considerations-section}
\input{conclusion-section}

% References section
\bibliographystyle{plainnat}  % Changed to plainnat for natbib compatibility
\bibliography{references}  % Uncommented this line

\end{document}