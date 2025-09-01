

```markdown
# Professional LaTeX Resume for RAFIK SHAH

This repository contains a **modern, ATS-friendly LaTeX resume** for Rafiksha Shaha. The resume includes sections for **Education, Projects, Technical Skills, Internship, Achievements, Profile Links, and Certifications**. Icons from FontAwesome are used for contact info.

---

## 📝 AI Prompt Used to Generate this Resume

You can use this prompt with **ChatGPT / OpenAI** or any AI assistant to generate professional LaTeX resumes:

```

Create a professional LaTeX resume using article class for the following details:

* Full Name: RAFIKSHA SHAHA
* Location: Aurangabad, Maharashtra
* Phone: +917028352298
* Email: [rafikshah3262@gmail.com](mailto:rafikshah3262@gmail.com)
* LinkedIn: [https://www.linkedin.com/in/muhammad-rafik-179875209/](https://www.linkedin.com/in/muhammad-rafik-179875209/)
* Education:

  1. CSMSS, Chh. Shahu College Of Engineering (2021-2024) - B.Tech in CSE, CGPA 8.5, Aurangabad
  2. Government Polytechnic Aurangabad (2018-2021) - IT, 90.94%, Aurangabad
  3. Swami Vivekanand Vidyalaya (2017-2018) - 10th, 93.40%, Jalna
* Projects:

  1. Movie Recommendation System - Python, ML, GitHub link, user auth, content-based filtering, responsive UI
  2. Multi-Language Text Summarizer - Python, GitHub link, supports English, Marathi, Hindi
* Technical Skills:

  * Languages: C/C++, Python, Java, HTML/CSS, JS, SQL, Word, Excel
  * Frameworks/Libraries: Django, Numpy, Pandas, Matplotlib, PowerBI, Tableau
  * Version Control: Git, GitHub
* Internship:

  1. Technical Trainer at Campus Credential Pvt Ltd (Oct 2023-Present) - Python, DSA, GitHub, SQL
  2. Accenture Technology Virtual Experience Program (Aug 2020-Sep 2021)
* Achievements: Smart India Hackathon, college-level SDE, user-friendly interfaces
* Profile Links: CodeChef (Brown), HackerRank (Silver), LeetCode (100+ solved)
* Certifications: Python Programming, NPTEL (DAA, Cloud Computing, DBMS), Python + Django
* Use modern LaTeX template: article class, fullpage margins, fancyhdr (no header/footer lines)
* Sections: Education, Projects, Technical Skills, Internship, Achievements, Profile Links, Certifications
* FontAwesome icons for phone, email, LinkedIn, GitHub
* ATS-friendly PDF output
* Proper bullet points and horizontal rules

````

---

## 📄 Instructions to Compile

1. Make sure you have **LaTeX installed** (TeX Live, MiKTeX, or use Overleaf).  
2. Copy the LaTeX code below into a file named `Rafiksha_Resume.tex`.  
3. Compile using `pdflatex Rafiksha_Resume.tex` to generate PDF.  

---

## ✨ LaTeX Code
\documentclass[letterpaper,11pt]{article}

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
\setlength{\multicolsep}{-3.0pt}
\setlength{\columnsep}{-1pt}
\input{glyphtounicode}
\usepackage{fontawesome5}


%----------FONT OPTIONS----------
% sans-serif
% \usepackage[sfdefault]{FiraSans}
% \usepackage[sfdefault]{roboto}
% \usepackage[sfdefault]{noto-sans}
% \usepackage[default]{sourcesanspro}

% serif
% \usepackage{CormorantGaramond}
% \usepackage{charter}


\pagestyle{fancy}
\fancyhf{} % clear all header and footer fields
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

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
  	\textbf{#1} & \textbf{\small #2} \\
  	\textit{\small#3} & \textit{\small #4} \\
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
  	\small#1 & \textbf{\small #4}\\
	\end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubItem}[1]{\resumeItem{#1}\vspace{-4pt}}

\renewcommand\labelitemi{$\vcenter{\hbox{\tiny$\bullet$}}$}
\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.0in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}

%-------------------------------------------
%%%%%%  RESUME STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%


\begin{document}

%----------HEADING----------
% \begin{tabular*}{\textwidth}{l@{\extracolsep{\fill}}r}
%   \textbf{\href{http://sourabhbajaj.com/}{\Large Sourabh Bajaj}} & Email : \href{mailto:sourabh@sourabhbajaj.com}{sourabh@sourabhbajaj.com}\\
%   \href{http://sourabhbajaj.com/}{http://www.sourabhbajaj.com} & Mobile : +1-123-456-7890 \\
% \end{tabular*}
\begin{center}
	{\Huge \scshape RAFIKSHA SHAHA} \\ \vspace{1pt}
	   Aurangabad, Maharastra \\ \vspace{1pt}
	\small \raisebox{-0.1\height}\faPhone\ +917028352298 ~ \href{mailto:rafikshah3262@gmail.com.com}{\raisebox{-0.2\height}\faEnvelope\  \underline{rafikshah3262@gmail.com.com}} ~
	\href{https://www.linkedin.com/in/muhammad-rafik-179875209/}{\raisebox{-0.2\height}\faLinkedin\ \underline{linkedin.com/in/Muhammed-rafik}}
	\vspace{-8pt}
\end{center}



%-----------EDUCATION-----------
\section{Education}
  \resumeSubHeadingListStart
	\resumeSubheading
  	{CSMSS, Chh. Shahu College Of Engineering}{2019-2022}
  	{Bachelor of Technolog in Computer Science and Engineering(CGPA of 8.5)}{Aurangabad, Maharastra}
   \resumeSubheading
  	{Government Polytechnic aurangabad }{2016-2019}
  	{Information Technology -- 90.94\%,}{Aurangabad, Maharastra}
   
  \resumeSubHeadingListEnd

%-----------PROJECTS-----------
\section{Projects}
	\vspace{-5pt}
	\resumeSubHeadingListStart
	\resumeProjectHeading
      	{\textbf{Fitness application } $|$ \href{https://github.com/}{\faIcon{github}} $|$ \emph{android,java}  {}}{}
      	\resumeItemListStart
        	\resumeItem{Developed User Authentication and Profile Management}
        	\resumeItem{
Created systems for tracking various workouts including cardio, strength training, and yoga.
}
            \resumeItem{Designed responsive interfaces for seamless user experience across devices.}
            
      	\resumeItemListEnd
	\vspace{-13pt}
  	\resumeProjectHeading
      	{\textbf{Women Safety app } $|$ \href{https://github.com/}{\faIcon{github}} $|$ \emph{android,java}  $ {}}{}
      	\resumeItemListStart
        	\resumeItem{Implemented emergency alert functionality for distress signals with location tracking.
Enabled quick communication with predefined emergency contacts or services.

}}
            \resumeItem{Provided safety tips and guidelines within the app for various situations.
Integrated features for accessing emergency hotlines or services directly}
            \resumeItem{designed a simple and intuitive user interface for easy navigation and understanding}
            
      	\resumeItemListEnd
	\resumeSubHeadingListEnd
\vspace{-15pt}

%
%-----------PROGRAMMING SKILLS-----------
\section{Technical Skills }
 \begin{itemize}[leftmargin=0.15in, label={}]
	\small{\item{
 	\textbf{Languages}{: C/C++, Python, Java, HTML/CSS, JavaScript, SQL ,word,excel} \\
 	\textbf{Technologies/Frameworks/Libraries}{: android,powerbi,django flask}
	}}
 \end{itemize}
 \vspace{-16pt}

\section{Internship}
  \resumeSubHeadingListStart
	\resumeSubheading
  	{1)Currently Working as a Technical Consultant in Campus
Credential pvt ltd(oct-2022-Working) }{}
  	
     
	\resumeItemListEnd

 \resumeSubheading
  	{Accenture's Technology Virtual Experience Program}{}
  	{Technology Virtual experience Program
One month internship during S.E. (Aug 2020 to Sep. 2021) }{}
  	\resumeItemListStart
    	\resumeItem{
 }


     
	\resumeItemListEnd
    
  \resumeSubHeadingListEnd
\vspace{-16pt}
%-----------EXPERIENCE-----------
\section{Achievements}
  \resumeSubHeadingListStart
	\resumeSubheading
  	{coding chos participation }{}
  	
     
	\resumeItemListEnd

 \resumeSubheading
  	{Smart India Hackathon}{}
  	{Software Development Engineer }{Aurangabad, India}
  	\resumeItemListStart
    	\resumeItem{Our team was selected in the college-level hackathon to solve \textbf{real-world problems} related to Designed user-friendly interfaces for seamless document verification, enhancing user experience and trust in the system.}. }


     
	\resumeItemListEnd
    
  \resumeSubHeadingListEnd
\vspace{-16pt}


%-----------Achievements-----------
% \section{Achievements [Add all kind of achievements that shows your skills]}
%  \begin{itemize}[leftmargin=0.15in, label={}]
% 	\resumeItemListStart
%     	\resumeItem{Ranked under \textbf{xyz} at Codechef which ranks among the top sites for competitive programmers. Highest rating of 2299 and rated \textbf{6*}. }
%     	\resumeItem{Qualified the prestigious ACM-ICPC regionals \textbf{thrice} and ranked Z in one of the attempts. }
%     	\resumeItem{Secured all India rank of \textbf{r, s, t} respectively in Codechef's Long Challenge in the month of February, April and May xyzh among 12k+ participants.}
%     	\resumeItem{Secured all India rank of \textbf{uh} in TCS codevita 2019.}
%     	\resumeItem{Written over \textbf{0987643} articles at Geeksforgeeks, most of them being on Data Structure and Algorithms}
%     	\resumeItem{Solved more than 2000+ problems across platforms.}
%     	\resumeItem{Awarded with Geek of the year accolade from GeeksforGeeks for contribution to the community. \href{https://www.geeksforgeeks.org/geek-of-the-year/}{(Link)} }
%   	\resumeItemListEnd
%  \end{itemize}
%  \vspace{-16pt}
 
%  %


%-----------Profile Links-----------
\section{Profile Links}
 \begin{itemize}[leftmargin=0.15in, label={}]
	\resumeItemListStart
    	\resumeItem {\href{https://https://www.codechef.com/users/rafik_01}
     {Codechef- Brown Badge}}
    	
    	\resumeItem {\href{https://www.hackerrank.com/profile/rafikshah2272}{Hackerank -Silver level}}
    	\resumeItem {\href{https://leetcode.com/u/rafikshah2272/}{LeetCode- 100+}}
  	\resumeItemListEnd
 \end{itemize}
 \vspace{-16pt}

% %
% %


%-----------CERTIFICATIONS-----------

\section{Certifications}
 \begin{itemize}[leftmargin=0.15in, label={}]
	\resumeItemListStart
                \resumeItem
% {\href{https://www.udemy.com/certificate/UC-67aaf204-b816-424b-ad12-d84ca8513930/}
     { python Programming-Udemy Certification 
     }}
    	\resumeItem 
    % {\href{https://drive.google.com/file/d/1JyxxJfpAMEGdefIFV0-GkWmordUcSSyj/view}
     {NPTEL certification in Design analysis and algorithm }}
    	\resumeItem
% {\href{https://drive.google.com/file/d/1xDNF1BdHgx2gIs3tHnjpXBYdPKBbRy0v/view}
     {NPTEL Cloud Computing}}

     \resumeItem
% {\href{https://drive.google.com/file/d/1xDNF1BdHgx2gIs3tHnjpXBYdPKBbRy0v/view}
     {NPTEL Database management System
     }}
  	\resumeItemListEnd
 \end{itemize}
 \vspace{-16pt}


% %-----------HOBBIES-----------

% \section{Hobbies}
%  \begin{itemize}[leftmargin=0.15in, label={}]
% 	\resumeItemListStart
%     	\resumeItem 
%      {Solving coding problems}
%      \resumeItem
%      {swimming}
%     	\resumeItem
%      {YouTube-850+ subscriber}
%   	\resumeItemListEnd
%  \end{itemize}
%  \vspace{-16pt}


\end{document}

1. **AI prompt used to generate the resume**
2. **Step-by-step LaTeX instructions**
3. **Full LaTeX code ready to compile**

