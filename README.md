```latex
\documentclass[a4paper,10pt]{article}

% --------------------- Packages ---------------------
\usepackage[utf8]{inputenc}
\usepackage[a4paper,top=0.55in,bottom=0.55in,left=0.65in,right=0.65in]{geometry}
\usepackage{enumitem}
\usepackage{titlesec}
\usepackage{hyperref}
\usepackage{fontawesome5}
\usepackage{ragged2e}
\usepackage{setspace}
\usepackage{xcolor}

% --------------------- Hyperlink Setup ---------------------
\hypersetup{
    colorlinks=true,
    urlcolor=black,
    linkcolor=black
}

% --------------------- General Formatting ---------------------
\pagenumbering{gobble}
\setstretch{1.0}
\setlength{\parindent}{0pt}
\setlength{\parskip}{0pt}

\setlist[itemize]{
    leftmargin=15pt,
    label=\textbullet,
    nosep,
    topsep=1pt,
    partopsep=0pt
}

% --------------------- Section Formatting ---------------------
\titleformat{\section}
    {\large\bfseries}
    {}
    {0em}
    {}
    [\vspace{-5pt}\titlerule]

\titlespacing*{\section}
    {0pt}
    {7pt}
    {4pt}

% --------------------- Document ---------------------
\begin{document}

% ===================== HEADER =====================
\begin{center}

{\LARGE \textbf{Manoja Nalini Mohanty}}\\[4pt]

Kendrapara, Odisha\\[5pt]

\small
\faPhone\ 8249232193
\quad | \quad
\faEnvelope\ 
\href{mailto:manojanalinimohanty@gmail.com}
{manojanalinimohanty@gmail.com}
\quad | \quad
\faLinkedin\ 
\href{https://www.linkedin.com/in/manoja-nalini-mohanty-085a95284/}
{LinkedIn}
\quad | \quad
\faGithub\ 
\href{https://github.com/MANOJA-NALINI-MOHANTY}
{GitHub}

\end{center}

\vspace{-2pt}

% ===================== EDUCATION =====================
\section*{EDUCATION}

\textbf{Kalinga Institute of Industrial Technology (KIIT), Bhubaneswar}
\hfill \textbf{Sep 2024 -- May 2026}\\
Master of Computer Application
\hfill Bhubaneswar, Odisha\\
\textbf{CGPA: 7.95} \hfill \textbf{SGPA: 9.22}

\vspace{3pt}

\textbf{Institute of Technical Education and Research (ITER), SOA Deemed to be University}
\hfill \textbf{Aug 2021 -- Jun 2024}\\
Bachelor of Computer Application
\hfill Bhubaneswar, Odisha\\
\textbf{CGPA: 7.70} \hfill \textbf{SGPA: 9.42}

% ===================== COURSEWORK =====================
\section*{RELEVANT COURSEWORK}

Data Structures \quad $\bullet$ \quad Algorithms Analysis \quad
$\bullet$ \quad Database Management \quad
$\bullet$ \quad Frontend Development \quad
$\bullet$ \quad Backend Development \quad
$\bullet$ \quad Operating Systems \quad
$\bullet$ \quad Computer Networks

% ===================== PROJECTS =====================
\section*{PROJECTS}

\textbf{Grievance Application for College Students}
\hfill \textbf{2026}\\
\textit{Tech Used: XML, Java, SQL}
\begin{itemize}
    \item Developed a mobile application for college students to submit and track grievances related to hostel, food, classroom, and other campus issues.
    \item Designed the application to provide a structured platform for submitting complaints and monitoring their resolution status.
\end{itemize}

\vspace{2pt}

\textbf{Smart Symptom Analysis and Remote Healthcare Assistance Platform}
\hfill \textbf{Dec 2025}\\
\textit{Tech Used: HTML, CSS, JavaScript, MERN Stack, Python ML}
\begin{itemize}
    \item Developed an AI-based healthcare platform that analyzes user symptoms and provides preliminary health-related assistance.
    \item Integrated a machine learning model with a MERN-based web application to support symptom analysis and remote healthcare assistance.
\end{itemize}

\vspace{2pt}

\textbf{Daily Weather Reporter}
\hfill \textbf{Aug 2025}\\
\textit{Tech Used: UiPath}
\begin{itemize}
    \item Automated daily weather reporting by retrieving weather updates and sending them through email using UiPath.
\end{itemize}

% ===================== TECHNICAL SKILLS =====================
\section*{TECHNICAL SKILLS}

\textbf{Languages:} C++, Python, Java, HTML, CSS, JavaScript, SQL\\[2pt]
\textbf{Frameworks \& Libraries:} React.js, Node.js, MongoDB\\[2pt]
\textbf{Networking:} Computer Networks, Network Configuration\\[2pt]
\textbf{Tools \& Technologies:} Git, GitHub, VS Code

% ===================== CERTIFICATIONS =====================
\section*{CERTIFICATIONS}

\textbf{UiPath Tool and Automation -- Kareer School, KIIT}
\hfill \textbf{Jul -- Aug 2025}\\
Certificate of Completion for successful completion of the UiPath Upskilling Session.

\vspace{2pt}

\textbf{Red Hat System Administration I (RH124 - RHA) -- Ver. 9.3}
\hfill \textbf{Aug 2025}\\
Linux administration and system management skills.

\vspace{2pt}

\textbf{Palo Alto Networks}
\hfill \textbf{Jul 2025}\\
Cloud Security, Cyber Security, Network Security, Security Operations

% ===================== LANGUAGES =====================
\section*{LANGUAGES}

English \quad $\bullet$ \quad Hindi \quad $\bullet$ \quad Odia

\end{document}
```
