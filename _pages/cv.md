% LaTeX Curriculum Vitae Template
%
% Copyright (C) 2004-2009 Jason Blevins <jrblevin@sdf.lonestar.org>
% http://jblevins.org/projects/cv-template/
%
% You may use use this document as a template to create your own CV
% and you may redistribute the source code freely. No attribution is
% required in any resulting documents. I do ask that you please leave
% this notice and the above URL in the source code if you choose to
% redistribute this file.

\documentclass[letterpaper]{article}

\usepackage{hyperref}
\usepackage{geometry}
\PassOptionsToPackage{hyphens}{url}\usepackage{hyperref}
\usepackage{hanging}
\usepackage{parskip}
\usepackage{etaremune}

% Comment the following lines to use the default Computer Modern font
% instead of the Palatino font provided by the mathpazo package.
% Remove the 'osf' bit if you don't like the old style figures.
\usepackage[T1]{fontenc}
\usepackage[sc,osf]{mathpazo}

% Set your name here
\def\name{Jacob Ausubel}

% Replace this with a link to your CV if you like, or set it empty
% (as in \def\footerlink{}) to remove the link in the footer:
\def\footerlink{http://jblevins.org/projects/cv-template/}

% The following metadata will show up in the PDF properties
\hypersetup{
  colorlinks = true,
  urlcolor = black,
  pdfauthor = {\name},
  pdfkeywords = {economics, statistics, mathematics},
  pdftitle = {\name: Curriculum Vitae},
  pdfsubject = {Curriculum Vitae},
  pdfpagemode = UseNone
}

\geometry{
  body={6.5in, 8.5in},
  left=1.0in,
  top=1.25in
}

% Customize page headers
\pagestyle{myheadings}
\markright{\name}
\thispagestyle{empty}

% Custom section fonts
\usepackage{sectsty}
\sectionfont{\rmfamily\mdseries\Large}
\subsectionfont{\rmfamily\mdseries\itshape\large}

% Other possible font commands include:
% \ttfamily for teletype,
% \sffamily for sans serif,
% \bfseries for bold,
% \scshape for small caps,
% \normalsize, \large, \Large, \LARGE sizes.

% Don't indent paragraphs.
\setlength\parindent{0em}

% Make lists without bullets
\renewenvironment{itemize}{
  \begin{list}{}{
    \setlength{\leftmargin}{1.5em}
  }
}{
  \end{list}
}

\begin{document}

% Place name at left
%{\huge \name}

% Alternatively, print name centered and bold:
\centerline{\huge \bf \name}

\vspace{0.2in}

\begin{minipage}{0.45\linewidth} 
  \begin{tabular}{l}
Monroe Hall \\
%George Washington University \\  
2115 G Street N.W., Suite 451 \\
Washington, D.C. 20052 \\
   \end{tabular}

\end{minipage}
\begin{minipage}{0.45\linewidth}
  \begin{tabular}{ll}
%Phone: 202-294-2020   \\
%Fax: 202-994-1974  \\
Email:  \href{mailto:jacobausubel@gwmail.gwu.edu}{\tt jacobausubel@gwmail.gwu.edu}   \\
Linkedin: \href{https://www.linkedin.com/in/jacob-ausubel}{\tt https://www.linkedin.com/in/jacob-ausubel} \\
ORCID: \href{https://orcid.org/0000-0001-6681-4961}{\tt https://orcid.org/0000-0001-6681-4961}    
  \end{tabular}
\end{minipage}

\section*{Education}

\begin{itemize}

\item \textbf{George Washington University}, Washington, DC


  \subitem Ph.D., Political Science, 2027 (expected) 
  %  \subitem Advisors: Jonathan Rodden, Simon Jackman, Barry Weingast, and  David Brady
%  \subitem Dissertation: "Issue Representation in the 107-111th Congresses"
	
      \leftskip 0.5in
\parindent -0.5in
   \item Fields: American Politics, Research Methods
  \item Advisors: Ethan Porter, Christopher S. Warshaw
  %\subitem Dissertation: "xxx."
  \subitem M.A., Political Science, 2025 

  %\item {\bf George Washington University}, M.A., Political Science, 2025

\end{itemize}

\begin{itemize}

\item \textbf{University of Pennsylvania}, Philadelphia, PA
    \subitem B.A., Political Science, {\it magna cum laude}, 2019
	
      \leftskip 0.5in
\parindent -0.5in
\item	Advisor: John S. Lapinski
\item Honors Thesis: "Social media and the 2018 midterms: An analysis of House candidates' \\ Twitter posts."
	
\end{itemize}

\section*{Research Interests}
\begin{itemize}
\item
American Elections, Democratic Norms, Mis/Disinformation, Public Opinion, Religion and Politics
\end{itemize} 

\section*{Research}

\subsection*{Academic Publications}

\begin{itemize}

\item {\bf Peer Reviewed Articles}
%\item {\bf Journal Articles}
\begin{etaremune}

\parindent -0.5in

\item "Measuring age differences among opposite-sex couples: Across religions and 130 countries, men are older than their female partners." 2022. {\it Population Studies}.  76(3): 465-476. (with Stephanie Kramer, Anne Fengyan Shi, and Conrad Hackett)

\item "Measuring the size of the U.S. Jewish population: New estimates from a Pew Research Center survey of Jewish Americans." 2021. {\it Journal of Religion and Demography}. 8(1-2): 89-100. (with Conrad Hackett)

\end{etaremune}

\end{itemize}

\leftskip 0.in
\parindent -0.0in

\begin{itemize}

\item {\bf Works in Progress}

\begin{etaremune}

\parindent -0.5in

\item "Age and representation: The link between elected officials’ ages and their favorability."

\item "Election denialism and candidate favorability: Insights from survey experiments."

\item "The reputational penalty: How fact-checking can penalize those who spread misinformation.” (with Annika Davies and Ethan Porter)

\item "The lingering effect of religion: Does it matter that one in ten American adults identify as Catholic, Jewish, Muslim, or Mormon ‘aside from religion’?” (with Conrad Hackett and Besheer Mohamed)

\end{etaremune}

\end{itemize}

\leftskip 0.in
\parindent -0.0in

\leftskip 0.in
\parindent -0.0in
\subsection*{Other Publications}
\begin{itemize}

\parindent -0.5in

\parindent -0.5in

\item {\bf Pew Research Center}

\begin{etaremune}

\item "Christians, religiously unaffiliated differ on whether most things in society can be divided into good, evil." \textit{Pew Research Center}. December 21, 2021.
\item "Denominational switching among U.S. Jews: Reform Judaism has gained, Conservative Judaism has lost." \textit{Pew Research Center}. June 22, 2021. (with Gregory A. Smith and Alan Cooperman)
\item "Populations skew older in some of the countries hit hard by COVID-19." \textit{Pew Research Center}. April 22, 2020.
\item "Older people are more likely to live alone in the U.S. than elsewhere in the world." \textit{Pew Research Center}. March 10, 2020.
\item "Globally, women are younger than their male partners, more likely to age alone." \textit{Pew Research Center}. January 3, 2020.

\end{etaremune}

\end{itemize}

%\section*{Professional Development}
\section*{Conferences and Workshops}
\begin{itemize}
    \item \raggedright American Politics Workshop (GW), 2025
    \item \raggedright Annual Meeting of the Midwest Political Science Association, 2025, 2024
    \item \raggedright Annual Meeting of the American Political Science Association, 2024
    \item \raggedright Second Year Paper Workshop (GW), 2024
    \item \raggedright Society for Practical Theology in South Africa, 2021
    \item \raggedright Society for the Scientific Study of Religion, 2021
\end{itemize}

\section*{Teaching Experience}
\begin{itemize}
\item {\bf Teaching Assistant}	
\subitem   Scope and Methods of Political Science (GW), 2024, 2023
\subitem   Introduction to American Politics (GW), 2023
\end{itemize}

\section*{Research Experience}
\begin{itemize}
\item {\bf Research Assistant}	
\subitem   Dr. Ethan Porter, George Washington University, 2022-
\subitem   Pew Research Center, Demography of Religion, 2019-2022
\item {\bf Research Intern}	
\subitem   Brookings Institution, Governance Studies, 2018
\item {\bf Student Fellow}	
\subitem   Penn Program on Opinion Research and Election Studies, 2018
\end{itemize}

\section*{Professional Development}
\begin{itemize}
\item {ICPSR Summer Program in Quantitative Methods, 2024}	
\item {American Political Science Association, member, 2023-}	
\end{itemize}

\section*{Skills}
\begin{itemize}
\item {\textbf{Tools and Languages}: R, Stata, \LaTeX, SPSS, Tableau}	
\end{itemize}

\bigskip

% Footer
\begin{center}
  \begin{footnotesize}
    Last updated: \today \\
  \end{footnotesize}
\end{center}

\end{document}
