\documentclass{article}
\usepackage[utf8]{inputenc}
\usepackage[spanish]{babel}
\usepackage{blindtext}
\usepackage{amsmath, amsthm, amsfonts}
\usepackage{latexsym, amssymb}
\usepackage{multicol}
% Set page size and margins
% Replace `letterpaper' with `a4paper' for UK/EU standard size
\usepackage[letterpaper,top=2cm,bottom=2cm,left=3cm,right=3cm,marginparwidth=1.75cm]{geometry}

% Useful packages
\usepackage{amsmath}
\usepackage{graphicx}
\usepackage{pifont}
\usepackage[colorlinks=true, allcolors=blue]{hyperref}


\renewcommand{\qedsymbol}{$\blacksquare$}
\theoremstyle{definition}
\newtheorem{prop}{Proposición}
\newtheorem{teor}{Teorema}
\newtheorem{defin}{Definición}
\newtheorem{obs}{Observación}
\newtheorem{ejem}{Ejemplo}
\newtheorem{nota}{Nota}

\begin{document}
\subsubsection{Medida}
\begin{itemize}
\item[--] Por \textit{espacio medible} entendemos un par ordenado $(\Omega,B)$ que consta de un conjunto $\Omega$ y un $\sigma$ -álgebra $B$ de subconjuntos de $\Omega$-. Un subconjunto $A$ de $\Omega$ se llama \textit{medible} si $A \in B$.
\item[--] Una \textit{medida} $\Omega$ en un espacio medible $(\Omega,B)$ es una función $\mu : B \mapsto [0, \infty]$ que satisface:
\begin{align*}
\mu(\phi) &= 0\\
\mu( \bigcup_{i}^{\infty} E_i) &=  \sum_{i}^{\infty} \mu(E_i)
\end{align*}
para cualquier sucesión $\{E_i\}$ de conjuntos medibles disjuntos, es decir: $E_i \bigcap E_j=\o$, $E_i \in B$, $i\neq j$.
\item[--] $(\Omega, B, \mu)$ se llama \textit{espacio de medida}.

\end{itemize}
\begin{teor}\label{teorema}
\textit{Las siguientes afirmaciones son ciertas para un grupo $G$}.
\end{teor}
\begin{multicols}{2}
\begin{enumerate}
\item[\textit{1.}] $P(G)=1$.
\item[\textit{2.}] $G$ \textsl{es abeliano}.
\item[\textit{3.}] $Z(G)=G$.
\item[\textit{4.}] ${G}'=\{1\}$.
\item[\textit{5.}] $C_{G}(a)=G$ \textsl{para todo} $a \in G$.
\item[\textit{6.}] $G/{G}'\cong G$.
\end{enumerate}
\end{multicols}
    
\begin{proof}[\textbf{{Demostración.}}] Si $P(G)=1$, entonces $|L(G)|=|G|^2$. Luego $L(G)=G^2$, y esto significa que $xy=yx$ para todo $x \in G$ y para todo $y \in G$. Así, $G$ es un grupo abeliano. Es una observación inmediata que el razonamiento inverso también es cierto, lo que prueba que 1 es equivalente a 2.
\end{proof}
Según este resultado, para tener grupos de conmutatividad diferentes de 1, debemos analizar grupos no abelianos.
\end{document}
