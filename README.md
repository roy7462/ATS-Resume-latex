\documentclass[letterpaper,10pt]{article}

\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage[english]{babel}
\usepackage{tabularx}
\usepackage{fontawesome5}
\usepackage{multicol}
\usepackage{graphicx}
\setlength{\multicolsep}{-3.0pt}
\setlength{\columnsep}{-1pt}
\input{glyphtounicode}

\RequirePackage{tikz}
\RequirePackage{xcolor}
\RequirePackage{fontawesome}
\usepackage{tikz}
\usetikzlibrary{svg.path}


\definecolor{cvblue}{HTML}{0E5484}
\definecolor{black}{HTML}{130810}
\definecolor{darkcolor}{HTML}{0F4539}
\definecolor{cvgreen}{HTML}{3BD80D}
\definecolor{taggreen}{HTML}{00E278}
\definecolor{SlateGrey}{HTML}{2E2E2E}
\definecolor{LightGrey}{HTML}{666666}
\colorlet{name}{black}
\colorlet{tagline}{darkcolor}
\colorlet{heading}{darkcolor}
\colorlet{headingrule}{cvblue}
\colorlet{accent}{darkcolor}
\colorlet{emphasis}{SlateGrey}
\colorlet{body}{LightGrey}



%----------FONT OPTIONS----------
% sans-serif
% \usepackage[sfdefault]{FiraSans}
% \usepackage[sfdefault]{roboto}
% \usepackage[sfdefault]{noto-sans}
% \usepackage[default]{sourcesanspro}

% serif
% \usepackage{CormorantGaramond}
% \usepackage{charter}


% \pagestyle{fancy}
% \fancyhf{}  % clear all header and footer fields
% \fancyfoot{}
% \renewcommand{\headrulewidth}{0pt}
% \renewcommand{\footrulewidth}{0pt}

% Adjust margins
\addtolength{\oddsidemargin}{-0.6in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1.19in}
\addtolength{\topmargin}{-.7in}
\addtolength{\textheight}{1.4in}

\urlstyle{same}

\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large\bfseries
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

% Ensure that generate pdf is machine readable/ATS parsable
\pdfgentounicode=1

%-------------------------
% Custom commands
\newcommand{\resumeItem}[1]{
  \item\small{
    {#1 \vspace{-2pt}}
  }
}

\newcommand{\classesList}[4]{
    \item\small{
        {#1 #2 #3 #4 \vspace{-2pt}}
  }
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{1.0\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{\large#1} & \textbf{\small #2} \\
      \textit{\large#3} & \textit{\small #4} \\
      
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubSubheading}[2]{
    \item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textit{\small#1} & \textit{\small #2} \\
    \end{tabular*}\vspace{-7pt}
}


\newcommand{\resumeProjectHeading}[2]{
    \item
    \begin{tabular*}{1.001\textwidth}{l@{\extracolsep{\fill}}r}
      \small#1 & \textbf{\small #2}\\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubItem}[1]{\resumeItem{#1}\vspace{-4pt}}

\renewcommand\labelitemi{$\vcenter{\hbox{\tiny$\bullet$}}$}
\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.0in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}


\newcommand\sbullet[1][.5]{\mathbin{\vcenter{\hbox{\scalebox{#1}{$\bullet$}}}}}

%-------------------------------------------
%%%%%%  RESUME STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%


\begin{document}

%----------HEADING----------


\begin{center}
    {\Huge \scshape ROHIT CHAVAN } \\ \vspace{1pt}
    PUNE MAHARASHTRA , INDIA - 411047 \\ \vspace{1pt}
    \small \href{tel:+xxxxxxxxxxxx}{ \raisebox{-0.1\height}\faPhone\ \underline{+91-9172726218} ~} \href{mailto:yourname@gmail.com}{\raisebox{-0.2\height}\faEnvelope\  \underline{rc0129955@gmail.com}} ~ 
    \href{https://linkedin.com/in/yourid}{\raisebox{-0.2\height}\faLinkedinSquare\ \underline{}}  
    
    \href{https://github.com/yourid}{\raisebox{-0.2\height}\faGithub\ \underline{https://www.linkedin.com/in/rohit-chavan-943191243/}} ~
    
    \vspace{-8pt}
\end{center}


%------RELEVANT COURSEWORK-------
\section{ SKILLS}
    %\resumeSubHeadingListStart
        \begin{multicols}{4}
            \begin{itemize}[itemsep=-2pt, parsep=5pt]
                \item OOPS  
                \item C++
                  \item MYSQL
                \item Python
             \item Artificial Intelligence
                 \item HTML,CSS,JS
                \item Bootstrap
                 \item Machine Learning 
                  \item Tableau 
               \item Scikit Learn
                   \item Excel VBA Dev 
                   \item HTML5
                   \item Numpy
                   \item Data Analytics 
                \item Pandas
                \item  Matlab
                \item  R
                \item FastAPI
                \item RestAPI
                \item Fine Tuning
                
                    
            \end{itemize}
        \end{multicols}
        \vspace*{2.0\multicolsep}
    %\resumeSubHeadingListEnd

%-----------EXPERIENCE-----------
%-----------EXPERIENCE-----------
\section{PROJECTS}
  \resumeSubHeadingListStart

    \resumeSubheading
      { Bartino \href{certificate Link}{\raisebox{-0.1\height}\faExternalLink }}{Apr 2023 - Apr 2024} 
      {\underline{Machine Learning Intern }}{Pune, Maharashtra}
      \resumeItemListStart
        \resumeItem{\normalsize{ \textbf{}Developed and optimized an Applicant Tracking System (ATS) using machine learning algorithms, improving candidate screening efficiency by 30\%. \textbf{.}}}
        \resumeItem{\normalsize Built recommendation systems to enhance the recruitment process, leading to a 25\% improvement in matching candidates with job descriptions.}
        \resumeItem{\normalsize Leveraged data analytics to identify key performance metrics for recruitment, reducing the hiring process time by 15\%.}
      \resumeItemListEnd  
  \resumeSubHeadingListEnd
  
  \resumeSubHeadingListStart

    \resumeSubheading
      { AI Variant \href{certificate Link}{\raisebox{-0.1\height}\faExternalLink }}{Jun 2024 - Sep 2024} 
      {\underline{Data Analyst Intern }}{Pune, Maharashtra}
      \resumeItemListStart
        \resumeItem{\normalsize{ \textbf{}Analyzed bank customer behavior data, identifying patterns in savings, spending, and transactions that resulted in a 10\% increase in customer retention.\textbf{.}}}
        \resumeItem{\normalsize Developed interactive Power BI dashboards for data visualization, resulting in a 20\% improvement in stakeholder decision-making through insightful reports.}
        \resumeItem{\normalsize Applied data imputation and cross-validation techniques to improve model accuracy and reliability by 20\%.}
        \resumeItem{\normalsize Delivered detailed data insights and analysis to both technical and non-technical teams, driving a 15\% improvement in business strategies.}
      \resumeItemListEnd  
  \resumeSubHeadingListEnd
\vspace{-12pt} 


%-----------PROJECTS-----------
\section{UNIVERSITY PROJECTS}
\vspace{-5pt}
\resumeSubHeadingListStart
   \resumeProjectHeading
      {\href{ProjectLink.com}{\textbf{\large{\underline{Applicant Tracking System (ATS)}}} \href{Project Link}{\raisebox{-0.1\height}\faExternalLink }} $|$ \large{\underline{Python, Django, Sklearn, FastAPI, REST API}}}{April 2024}
      \resumeItemListStart
        \resumeItem{\normalsize{Developed and deployed an Applicant Tracking System (ATS) using Python, Django, and Sklearn, improving recruitment efficiency by 30\%.}}
        \resumeItem{\normalsize Designed and implemented a robust backend system with Django to manage candidate data, reducing data entry errors by 20\%.}
        \resumeItem{\normalsize Integrated machine learning models to assess candidate fit, improving resume screening accuracy by 25\%.}
        \resumeItem{\normalsize Trained and fine-tuned models to enhance candidate data parsing and scoring mechanisms.}
        \resumeItem{\normalsize Created an intuitive front-end interface that streamlined the recruiter’s workflow, improving hiring speed by 20\%.}
        \resumeItem{\normalsize Leveraged REST APIs and FastAPI to enable seamless integration with external systems.}
      \resumeItemListEnd  
      \vspace{-13pt}

   \resumeProjectHeading
      {\href{ProjectLink.com}{\textbf{\large{\underline{Healthcare Chatbot}}} \href{Project Link}{\raisebox{-0.1\height}\faExternalLink }} $|$ \large{\underline{Python, Sklearn, Pyttsx3, Numpy, LLMs, REST API}}}{July 2022}
      \resumeItemListStart
        \resumeItem{\normalsize{Developed an AI-powered healthcare chatbot to provide enhanced medical support, improving user engagement by 30\%.}}
        \resumeItem{\normalsize{A sophisticated virtual assistant tailored for the healthcare industry, enabling 24/7 assistance for medical inquiries.}}
        \resumeItem{\normalsize{Utilized advanced AI and natural language processing (NLP) techniques to answer medical questions, achieving a 95\% accuracy rate in symptom analysis.}}
        \resumeItem{\normalsize{Trained and fine-tuned large language models (LLMs) to specialize in medical terminology and responses.}}
        \resumeItem{\normalsize{Integrated scheduling functionalities and basic diagnostic capabilities, improving healthcare access for 20\% of users in remote or underserved areas.}}
        \resumeItem{\normalsize{Implemented REST APIs for seamless integration with third-party healthcare systems.}}
      \resumeItemListEnd 

\resumeSubHeadingListEnd

%

 %-----------CERTIFICATIONS---------------
\section{CERTIFICATION & ACHIVEMENTSS}

$\sbullet[.75] \hspace{0.1cm}$ {\href{certificateLink.com}{Data Analyst - NASSCOM }} \hspace{1.6cm}

$\sbullet[.75] \hspace{0.2cm}${\href{certificateLink.com}{Data visualization using python - Great Learning }} \hspace{1.6cm}

$\sbullet[.75] \hspace{0.2cm}${\href{certificateLink.com}{Machine Learning using python - Pantech Learning}} \hspace{1.6cm}

$\sbullet[.75] \hspace{0.2cm}${\href{certificateLink.com}{German Language - Grade C}} \hspace{1.6cm}



%-----------EDUCATION-----------
\section{EDUCATION}
  \resumeSubHeadingListStart
    \resumeSubheading
      {Ajeenkya D Y Patil School of Engineering - ADYPSOE}{2020 - 2024}
      {BE - Artificial Intelligence and Data Science - \textbf{CGPA} - \textbf{7.74 / 10.00}}{Pune, Maharashtra }
  \resumeSubHeadingListEnd
  \resumeSubHeadingListStart
    \resumeSubheading
      {JiJau Dnyanteerth Junior College}{2020}
      {12th - HSC  - \textbf{66.40\%} - \textbf{}}{Pune, Maharashtra }
  \resumeSubHeadingListEnd
  \resumeSubHeadingListStart
    \resumeSubheading
      {Bal Vidya Vihar Primary School }{2017}
      {10th - SSC  - \textbf{90.60\%} - \textbf{}}{Pune, Maharashtra }
  \resumeSubHeadingListEnd


\end{document}
