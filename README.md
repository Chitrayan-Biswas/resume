# resume\documentclass[letterpaper,11pt]{article}

%---------- PACKAGES ----------
\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}
\usepackage[english]{babel}
\usepackage{tabularx}
\usepackage{fontawesome5}
\usepackage{multicol}

%---------- PAGE SETUP ----------
\pagestyle{fancy}
\fancyhf{}
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

\addtolength{\oddsidemargin}{-0.6in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1.19in}
\addtolength{\topmargin}{-.7in}
\addtolength{\textheight}{1.4in}

\urlstyle{same}

\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

%---------- SECTION FORMATTING ----------
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large\bfseries
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

%---------- CUSTOM COMMANDS ----------
\newcommand{\resumeItem}[1]{
  \item\small{
    {#1 \vspace{-2pt}}
  }
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{1.0\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & \textbf{\small #2} \\
      \textit{\small#3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeProjectHeading}[2]{
    \item
    \begin{tabular*}{1.0\textwidth}{l@{\extracolsep{\fill}}r}
      \small#1 & \textbf{\small #2}\\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubHeadingListStart}{
  \begin{itemize}[leftmargin=0.0in, label={}]
}

\newcommand{\resumeSubHeadingListEnd}{
  \end{itemize}
}

\newcommand{\resumeItemListStart}{
  \begin{itemize}
}

\newcommand{\resumeItemListEnd}{
  \end{itemize}\vspace{-5pt}
}

%---------- DOCUMENT ----------
\begin{document}

%---------- HEADING ----------
\begin{center}
    {\Huge \scshape Chitrayan Biswas} \\ \vspace{3pt}
    Kolkata, West Bengal -- 711103 \\ \vspace{3pt}
    \small
    \raisebox{-0.1\height}\faPhone\ 9064707580 ~
    \href{mailto:biswaschitrayan@gmail.com}{
        \raisebox{-0.2\height}\faEnvelope\ 
        \underline{biswaschitrayan@gmail.com}
    } ~
    \href{https://github.com/Chitrayan-Biswas}{
        \raisebox{-0.2\height}\faGithub\ 
        \underline{github.com/Chitrayan-Biswas}
    }
    \vspace{-8pt}
\end{center}

%---------- EDUCATION ----------
\section{Education}
\resumeSubHeadingListStart

\resumeSubheading
{Indian Institute of Engineering Science and Technology, Shibpur}
{Aug. 2023 -- May 2027}
{Bachelor of Technology in Mechanical Engineering}
{Kolkata, West Bengal}

\resumeSubHeadingListEnd

%---------- RELEVANT COURSEWORK ----------
\section{Relevant Coursework}
\begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
        Matlab, ANSYS, Simulink, SolidWorks, Machine Design, 
        Robotic Kinematics, Numerical Analysis
    }}
\end{itemize}

%---------- PROJECTS ----------
\section{Projects}
\resumeSubHeadingListStart

%---------- PROJECT 1 ----------
\resumeProjectHeading
{\textbf{Machine Learning in Welding of Dissimilar Metals}}{Aug. 2024 -- Dec. 2024}

\resumeItemListStart
    \resumeItem{
        Conducted a technical literature review analyzing the integration of 
        Machine Learning (ML) with Finite Element Analysis (FEA) for modeling 
        the welding of dissimilar metals.
    }

    \resumeItem{
        Investigated ML-driven optimization of thermal processes and heat 
        transfer analysis to control residual stress and minimize defects 
        such as cracking and porosity.
    }

    \resumeItem{
        Synthesized research on predicting stress distribution and mechanical 
        properties, including tensile strength and elongation, from simulated 
        FEA data to reduce the need for extensive physical prototyping.
    }

    \resumeItem{
        Evaluated computational modeling approaches for predicting 
        microstructure evolution, including grain size and phase distribution, 
        and analyzed their impact on joint integrity under mechanical loading.
    }
\resumeItemListEnd

%---------- PROJECT 2 ----------
\resumeProjectHeading
{\textbf{3-RRR Planar Parallel Manipulator: Kinematic Analysis and Simulation}}
{Mar. 2025 -- Apr. 2025}

\resumeItemListStart

    \resumeItem{
        Performed complete kinematic analysis, including DOF calculation, 
        forward kinematics, and inverse kinematics, of a 3-DOF parallel 
        manipulator using vector-loop and Newton-Raphson methods.
    }

    \resumeItem{
        Developed a system of six nonlinear loop-closure equations and 
        implemented a numerical solver using MATLAB to compute unknown joint 
        angles, achieving a highly accurate solution within five iterations.
    }

    \resumeItem{
        Identified and cataloged singular configurations by analyzing the 
        Jacobian determinant to define operational limits.
    }

    \resumeItem{
        Mapped Jacobian singularities to provide insights for safe and optimal 
        path planning while avoiding loss of controllability.
    }

    \resumeItem{
        Visualized the mechanism's motion through computational animation, 
        validating the theoretical kinematic model.
    }

\resumeItemListEnd

\resumeSubHeadingListEnd

%---------- TECHNICAL SKILLS ----------
\section{Technical Skills}

\begin{itemize}[leftmargin=0.15in, label={}]
    \small{
        \item{
            \textbf{Languages \& Software:} C, Python, MATLAB, ABAQUS, ANSYS, 
            Simulink, SolidWorks
        }

        \item{
            \textbf{Kinematics \& Dynamics:} Robotic Kinematics 
            (Forward/Inverse), Mechanism Design, Linkage Analysis, 
            Kinematic Modeling, Jacobian Analysis, Singularity Analysis
        }

        \item{
            \textbf{Engineering Computation:} Finite Element Analysis (FEA), 
            Stress Analysis, Heat Transfer Analysis, Numerical Analysis
        }

        \item{
            \textbf{Development Environments:} VS Code, Google Colab, 
            Jupyter Notebook
        }

        \item{
            \textbf{Other Skills:} Linux, Problem Solving, Communication, 
            AI-Powered Solutions
        }
    }
\end{itemize}

\vspace{-10pt}

%---------- LEADERSHIP / EXTRACURRICULAR ----------
\section{Leadership / Extracurricular}

\resumeSubHeadingListStart

\resumeItem{
    District-Level U17, U17 CAB, Inter-NIT, Subdivision, and Superdivision 
    Cricket Player.
}

\resumeItem{
    Member, Photography Club ``Catharsis'', IIEST Shibpur -- Contributed to 
    creative campaigns and photography initiatives across campus.
}

\resumeSubHeadingListEnd

\end{document}
```
