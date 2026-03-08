# curriculum_vitae
%-------------------------
% Resume in Latex
% Author : Sourabh Bajaj
% License : MIT
%------------------------

\documentclass[letterpaper,11pt]{article}

\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage{fancyhdr}
\usepackage{multirow}
\usepackage{url}

\usepackage{fancyhdr}
\usepackage{lipsum} % for dummy text
\usepackage[colorlinks=true,urlcolor=blue]{hyperref}



% Adjust margins
\addtolength{\oddsidemargin}{-0.375in}
\addtolength{\evensidemargin}{-0.375in}
\addtolength{\textwidth}{1in}
\addtolength{\topmargin}{-.5in}
\addtolength{\textheight}{1.0in}

\urlstyle{same}

\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

%-------------------------
% Custom commands
\newcommand{\resumeItem}[2]{
  \item\small{
    \textbf{#1}{: #2 \vspace{-2pt}}
  }
}

\newcommand{\resumeItemNH}[1]{
  \item\small{
    {#1 \vspace{-2pt}}
  }
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-1pt}\item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textbf{#1} & #2 \\
      \textit{\small#3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-5pt}
}

\newcommand{\resumeSubItem}[2]{\resumeItem{#1}{#2}\vspace{-4pt}}

\renewcommand{\labelitemii}{$\circ$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=*,label={}]}
\newcommand{\resumeSubHeadingListStartBullets}{\begin{itemize}[leftmargin=*]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}}

\usepackage{array}
\makeatletter
\newcommand\HUGE{\@setfontsize\Huge{38}{47}} 
\newcolumntype{L}{>{\hb@xt@\z@\bgroup}l<{\hss\egroup}}
\newcolumntype{C}{>{\centering\arraybackslash}c}
\newcolumntype{R}{>{\hb@xt@\z@\bgroup\hss}r<{\egroup}}
\makeatother

\newcommand{\chapsubhead}[1]{{\Large #1 \vspace{2ex}}}
\newcommand{\chaptype}[1]{{\Large \itshape (#1) \vspace{2ex}}}

%-------------------------------------------
%%%%%%  CV STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%

\begin{document}

%----------HEADING-----------------
\begin{tabular*}{\textwidth}{L@{\extracolsep{\fill}}C@{\extracolsep{\fill}}R}
  \href{mailto:sak3qf@virginia.edu}{sak3qf@virginia.edu}  &
  \multirow{2}{*}{\Large \textbf{Samy Kebaish, M.Sc, MSDS}} \\
  Cell: (434) 249-0727 & & US Citizen \\ \url{github.com/sak3qf}
\end{tabular*}
\begin{center} \chapsubhead{Curriculum Vitae} \end{center}
\section{Intro}

AI/ML Engineer and current doctoral candidate at GWU. Dedicated to helping others through problem solving and collaboration, leveraging more than ten years of experience in consulting, research, data analysis, programming, and advanced modeling techniques. 



\section{Education}
  \resumeSubHeadingListStart
      \resumeSubheading
      {George Washington University}{Washington D.C.}
      {Doctor of Engineering Student in AI \& ML -- Cumulative GPA (Coursework): 3.7} {2025 -- }
    \resumeItemListStart
        \resumeItem{About}{Current Doctoral candidate in George Washington University's Doctorate of Engineering (D.Eng) in AI and Machine Learning program.Coursework is conducted part-time, over the weekends.}
        \resumeItem{Dissertation}{Evaluating Bio-Inspired Modular Architectures and Homeostatic Regulation in Robust Embodied AI using a MuJoCo PPO RL Simulation}
       
    \resumeItemListEnd
    \resumeSubheading
      {University of Virginia}{Charlottesville, VA}
      {Masters of Science in Data Science | Cumulative GPA: 3.9} {2021 -- 2024}
    \resumeItemListStart
        \resumeItem{Coursework}{Ex. Deep Learning, Big Data Systems, Bayesian Machine Learning, Applications of Data Science, Statistics and Probability, Linear Algebra,  Programs \& Systems for Data Engineering, etc.}
       
    \resumeItemListEnd
      
    \resumeSubheading
      {Johns Hopkins University}{Baltimore, MD}
      {Masters of Science in Biotechnology | Cumulative GPA: 4.0}{2017 -- 2019}
      \resumeItemListStart
        \resumeItem{Concentration}{Bioinformatics}
      \resumeItemListEnd
    \resumeSubheading
      {University of Virginia}{Charlottesville, VA}
      {Double Major with B.Sc. in Biochemistry \& B.A. Cognitive Neuroscience | Cumulative GPA 3.4}{2010 -- 2015}
  \resumeSubHeadingListEnd
%-----------EXPERIENCE-----------------
\section{Work Experience}
  \resumeSubHeadingListStart
      \resumeSubheading
      {University of Virginia - Student Health \& Wellness Department}{Charlottesville, VA}
      {Student Research Intern - Data Science [Part-time, Remote]}{October 2024 -- Current}
      \resumeItemListStart
        \resumeItemNH{Under the tutelage of Dr. Rita Farah, and Dr. Christopher Holstege, I lead the AI and data science analysis of a robust linked dataset capturing more than 500,000 rows of unique deidentified student dataset from 2018-2023.}
        \resumeItemNH{In my role, I have led the technical investigations related to the study, leveraging tools such as deep-learning models (e.g. Binary Classification of Emergency Department visits), Bayesian and other probabilistic approaches, temporal analyses, and have developed unique algorithms for sliding window incidence detection, and enrichment analysis }
        \resumeItemNH{This project has led to novel findings about unique features related to risk drinking, and above behaviors, towards informing future programs, including treatment, prevention, and outreach. Of note, this is an extension of the Datascience Capstone Project I conducted as a MSDS Student alongside my collaborator, Mr. Nicholas Cagliuso, which was published in the Newsletter of the Data Science program, "Across Grounds", in 2024, \href{https://datascience.virginia.edu/news/data-science-capstone-project-examines-covids-impact-alcohol-related-health-incidents-uva}{Article}}

      \resumeItemListEnd
  \resumeSubheading
      {Tambourine Innovation Ventures (TIV)}{Vienna, VA}
      {Senior Research Associate \& Data Scientist - AI \& Emerging Technologies}{August 2020 -- Current}
    \resumeItemListStart
        \resumeItemNH{As a Senior Research Associate at TIV \& Data Scientist, I am primarily responsible for our research and consultancy efforts at the intersection of technical and policy issues related to AI and emerging technologies (e.g. IoT, UAVs, Blockchain, etc). I work with our clients, agencies, and University partners on a vast spectrum of problems, ranging from conducting data analytics, administering international surveys, model development, applying deep learning and machine learning approaches, grant and proposal writing, desk research, and more.}
        \resumeItemNH{While at TIV, I have had the fortune to assist numerous domestic and international organizations, such as the Inter-American Development Bank (IADB) in 2021-2022. Then, I was contracted to develop and analyze surveys of Belize's secondary school system, polling teachers from more than 60 schools and technical and vocational education training (TVET) centers nationwide. The goal of the study was to assess the skill gap of rising Belizean Secondary School Students and characterize their career ambitions in light of the newfound demands brought by technological progress, or "the Fourth Industrial Revolution (4IR)". Additionally, from 2022-2023, I contributed data analytics and desk research for the Asia Pacific Economic Cooperation (APEC), when TIV was tasked with publishing their flagship report, "Women and Patents: Towards Gender Parity in APEC".}
        \resumeItemNH{I also help to mentor our SBIR/STTR Phase I and II Clients across numerous agencies (DoD, DHS, NIH, DOE, etc), to help actualize the scientific, commercial, and societal potential of their cutting-edge innovations. This opportunity has exposed me to numerous technologies, ranging from using digital twins for hydrological dam monitoring, to novel concepts for molten salt reactors, thereby requiring the ability to quickly digest and understand the client's technical and commercial aims while balancing those of the soliciting agency, to optimally assist.}
        \resumeItemNH{Spearheaded TIV's recent successful application for the 2024 Small Business Administration (SBA) Growth Accelerator Fund Competition (GAFC) in the Category of National and Economic Security. Our proposal focused on advancing the United States' AI leadership through cultivation of R\&D, Technology Commercialization, and Entrepreneurship, in addition to promoting a diverse pipeline of participants.}
    
    \resumeItemListEnd
    \resumeSubheading
      {Schumpeter Circle (SC)}{Vienna, VA}
      {Editor (Part-Time Unpaid Role)}{August 2020 -- Current}
      \resumeItemListStart
        \resumeItemNH{Editor for \textit{Schumpeter Circle}, TIV's digital blog on innovation, featuring contributions from thought leaders of various disciplines, such as former President of Peru, Dr. Francisco Sagasti, in addition to Dr. Pramod Chaudhair, CEO of Praj Industries, and former Intel Director of Industrial Innovation, Dr. Irene Petrick, among other pioneers \url{https://www.schumpetercircle.com/}}
      \resumeItemListEnd
    \resumeSubheading
      {General Foods U.S.A.}{Richmond, VA}
      {Head of Data Analytics (Part-Time)}{June 2021 -- Current}
      \resumeItemListStart
        \resumeItemNH{Conduct data analysis, market research, and modeling for a major importer and exporter of goods (e.g. Premier Protein; Kirkland Brand goods) to the Gulf Region, working directly with partners and clients in the United States and the Middle East.}
      \resumeItemListEnd
    \resumeSubheading
      {University of Virginia - Department of Student Athletics}{Charlottesville, VA}
      {General Chemistry Tutor (Part-Time)}{August 2020 -- December 2020}
      \resumeItemListStart
        \resumeItemNH{Tutored University of Virginia Student-Athletes General Chemistry in the evenings over the Fall 2020 Semester}
      \resumeItemListEnd
    \resumeSubheading
      {Software Engineering Consultant}{Falls Church, VA}
      {Part-Time}{December 2017 - March 2020}
      \resumeItemListStart
        \resumeItemNH{During my graduate studies at Johns Hopkins University, I worked as a freelance software engineer and consultant, helping clients with full-stack web development and website design, in addition to managing the National Orthopedic Clinic in a part-time capacity}
      \resumeItemListEnd
    \resumeSubheading
      {Hack Reactor}{San Francisco, CA}
      {Associate Software Engineering Instructor (Contract)}{March 2017 -- September 2017}
      \resumeItemListStart
        \resumeItemNH{Responsible for assisting in the instruction and mentoring of over 30 students for the competitive software engineering immersive, Hack Reactor. Students enroll for 12-14 weeks, studying up to 12 hours a day, six days a week in the subject of Software Engineering. My responsibilities included instruction and mentoring of students on: data structures and algorithms; full-stack development using JavaScript-based frameworks (e.g. Node.js, React, Angular); computer science theory and fundamentals; Agile methodologies; problem solving; Test-driven development (TDD), and more}
      \resumeItemListEnd
          \resumeSubheading
      {Augmedix}{San Francisco, CA}
      {Senior Implementation Specialist}{August 2015 - January 2017}
      \resumeItemListStart
        \resumeItemNH{Served as a consultant to major health systems including Dignity Health, TriHealth and CHI healthcare in the implementation of Google Glass and remote scribing services. I was responsible for software integration and implementation of Google Glass, troubleshooting the associated dictation and audio-video streaming software, manaaging EHR integration, and medical scribe training of unique medical specialities.}
      \resumeItemListEnd
    \resumeSubheading
      {University of Virginia}{Charlottesville, VA}
      {Head Organic Chemistry Lab TA}{May 2012 - July 2015}
      \resumeItemListStart
        \resumeItemNH{Starting in Summer of  2012, I was selected and hired by the University Virginia Chemistry Department as an Organic Chemistry Lab TA, considered one of the most difficult laboratory courses for students, and one of the most selective for TAs. I retained this role until the 2014-2015 academic school year, during which I had the privilege to be selected as one of the first Undergraduates to ever serve as the Head Undergrad Organic Chemistry Lab TA (for more than 400 students), and also to instruct the Post-Baccalaureate Pre-Med Program (for more than 60 students over two yeasr), under Dr. Hoitung Leung and Dr. Robert Burnett, respectively (Note: the Post-Baccalaureate Pre-Med Program at U.Va is a one year intensive for a highly competitive class of students who were aiming to transition to the field of Medicine [the success rate was nearly 95 percent for first time applications from cohorts]. All these individuals came from non-traditional backgrounds, with real-world examples including a former Olympic Track and Field Athlete, a helicopter pilot veteran, an English Teacher, a Cambridge trained attorney etc)}.
      \resumeItemListEnd

    \resumeSubheading
      {University of Virginia}{Charlottesville, VA}
      {Emergency Department Medical Scribe (Contract)} {January 2014 - July 2015}
      \resumeItemListStart
        \resumeItemNH{Worked directly under University of Virginia Emergency Medicine Physicians, assisting in their documentation of patient visits, from acute care to trauma cases. Of note, I led the first "Resident's Appreciation Day" in which Scribes expressed their gratitude to the Interns and Residents of the Emergency Department in a banquet.}
      \resumeItemListEnd
  \resumeSubHeadingListEnd
\fancyhf{} % clear all header and footer fields
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

%-----------PUBLICATIONS-----------------
\section{Publications}

\begin{itemize}
    \item \noindent Farah, R. \textbf{Kebaish, S.},Ferrara, R., Nixon, S., Tashman, A.,  \& Holstege, C. (2025). \textit{Leveraging a comprehensive student database to characterize 
alcohol-related visits to the emergency department: a six-year study}.45th International Congress of the European Association of Poisons Centres and Clinical Toxicologists (EAPCCT), 27–30 May 2025. Retrieved from \url{https://www.tandfonline.com/doi/full/10.1080/15563650.2025.2481800}
    \item \noindent Farah, R. \textbf{Kebaish, S.},Ferrara, R., Nixon, S., Tashman, A.,  \& Holstege, C. (2025). \textit{Multiple visits to the emergency  department for alcohol-related diagnosis among university students: a longitudinal study}.45th International Congress of the European Association of Poisons Centres and Clinical Toxicologists (EAPCCT), 27–30 May 2025. Retrieved from \url{https://www.tandfonline.com/doi/full/10.1080/15563650.2025.2481800}
    \item \noindent Neftenov, N. \textbf{Kebaish, S.}, Stankovic, M., Ristovska, A. Kotnala, R. \& Gupta, R. (2021). \textit{Propelling LDCs in the Digital Age}. United Nations Industrial Development Organization (UNIDO). Retrieved from \url{https://hub.unido.org/sites/default/files/publications/Propelling%20LDCs%20in%20the%20Digital%20Age_2021_EN_0.pdf}
    \item \noindent Anderson, J. \textbf{Kebaish, S.}, Lewis, J., \& Taylor, A. (2014). \textit{Effects of cranial electrical stimulation on activity in regions of the basal ganglia in individuals with fibromyalgia}.The Journal of Complementary and Alternative Medicine. 20(3). Retrieved from \url{https://doi.org/10.1089/acm.2014.1501}
\end{itemize}

\textit{In Preparation}

\begin{itemize}
    \item \noindent \textbf{Kebaish, S.}, \& Adelwole, S. (TBD) \textit{Multimodal Emotion Analysis for Nuanced
INterpretation \& Grading (MEANING) of Media}. 
    \item \noindent  Stankovich, M., Massey, S., \textbf{Kebaish, S.}, Rohrbaugh, M. \& Gupta, R. (TBD). \textit{Ethical, Legal and Social Implications of Decentralized Science (DeSci) in Computational Genomics}. 
\end{itemize}

\textit{Online Articles}
\begin{itemize}
    \item \noindent \textbf{Kebaish, S.} \& Stankovic, M. (2020). \textit{The Paradox of Networks: How Technology Makes and Breaks Connections at the Global Scale}. Small Business Association for International Companies (SBAIC). Retrieved from \href{https://sbaic.org/tambourine-innovation-ventures-the-paradox-of-networks-how-technology-makes-and-breaks-connections-at-the-global-scale/}{SBAIC}.
\end{itemize}


%-----------PROJECTS-----------------
\section{Projects}
  \resumeSubHeadingListStartBullets
    \resumeSubItem{MSDS Caspstone (U.Va Student Health \& Wellness, 2024)}
      {Implemented multiple machine learning and deep learning approaches towards capturing novel insights of alcohol abuse in deidentified student data (i.e. each student assigned a distinct serial number) spanning several years of linked datasets corresponding to more than one million student records. Models leveraged included numerous regression and ML techniques for classification of emergency room visits, LSTMS and transformers for temporal prediction of students vulnerable to alcohol abuse, Bayesian hierarchical modeling, time-series data based on COVID-19 impacts (e.g. changepoint analyses), epidemiological techniques (e.g. prevalence ratios), among others. Project was selected by the Department to be Featured on the UVa MSDS Website
     \href{https://datascience.virginia.edu/news/data-science-capstone-project-examines-covids-impact-alcohol-related-health-incidents-uva}{ UVa Data Science Capstone Article : Published on September 5, 2024}}
    \resumeSubItem{Multimodal Fusion methods of Deep Neural Networks for Emotion Classification and Sentiment Grading (University of Virginia MSDS, January 2024 - Current)}
      {Under the auspices of my former Professor of Deep learning in the U.Va MSDS program, Dr. Sodiq Adewole, I have been continuing research on different approaches to multimodal fusion of deep learning models towards emotion classification and sentiment grading, refining my data analysis and research as I prepare the manuscript for peer-review publication or application as a Conference Paper. My project, Multimodal Emotion Analysis for Nuanced INterpretation \& Grading (MEANING) of Media, involves the use of three datasets for multimodal classification, text, audio, video, involving feature generation, and the development of meaningful sequences in order to leverage temporal data across the diverse modalities (e.g., for audio, Mel-Frequency Cepstral Coefficients capture the short-term power spectrum of sound, correlating timbral character with emotional states in speech and music; facial landmarks using OpenCV library can be used for visual data towards characterizing emotional expression.) Different fusion methods included "Early", and late "Fusion", using various model architectures (e.g. CNNs, LSTMs), and ensemble methods. Currently finalizing data analysis and manuscript towards hopeful publication in a peer-reviewed journal} 
    \resumeSubItem{Determining Gerrymandering through Dynamic Programming (U.Va MSDS, 2021)}
      {As part of select group of graduate students, I was able to participate in an optional project outside the course curriculum involving developing a dynamic programming algorithm to determine whether gerrymandering was possible based on the contiguity of voting districts}
   \resumeSubItem{Plantr (Group Project, 2017 - 2018)}
      {An app I developed with Ryan Perry (who would go on to found Pyroscope), Nathan Brewer-Davis, and Ariel Salem, to help individuals plan their home gardens, with dynamic cost, weather, and botanical analysis.  Designed in React with Redux for state management, Plantr allows users to generate responsive 2D gardens with underlying logic and realism. Using Three.js, gardens can be rendered in 3D allowing for an immersive VR experience.Implemented social media functionality to allow users to friend other “Planters”, rate gardens, and ask questions in the forum.}
    \resumeSubItem{Git-It-Together (Independent, 2017)}
      {GitHub project management catered for team-based work allowing for real-time communication and planning. Incorporated React with a PostGres Database and Express/Node on the backend to create a team, GitHub project management tool allowing for real-time collaboration and planning.}
    \resumeSubItem{Youthoria Learning (Independent, 2017)}
      {Leveraging games to encourage learning; statistical analysis for teachers to visualize student progress. Interfaced Angular and Chart.js with real-time allocated MongoDB student data to generate dynamic graphs, filterable by parameter, type, and content. Used Phaser.js within the Angular framework to generate games of varying subject matter linked to a database. Allowed for user customization with selectable avatars and badge accrual based on performance and encouraged participation through gamification.}
  \resumeSubHeadingListEnd

%-----------Research-----------------
\section{Research}
  \resumeSubHeadingListStartBullets
    \resumeSubItem{Longitudinal Analysis of Alcohol Abuse at the University of Virginia from Linked Student Datasets, 2017-2023 (University of Virginia Student Health and Wellness Department, June 2024 - Current)}
      {Upon completion of my MSDS Capstone, I was asked to remain on the research team by Dr. Christopher Holstege (Professor of Emergency Medicine and Executive Director of Elson Student Health Center) and Dr. Rita Farah (Epidemiologist) to finalize modeling and assist in drafting an anticipated 2-3 research papers from the work conducted thus far.}
    \resumeSubItem{AI-Facilitated Autonomous Resource Management System (AI FARMS) (TIV \& IIIT-hyderabad, August 2023 - Current)} {For the 11th Solicitation of the USISTEF Competition, TIV (Co-Principal Investigator, Dr. Atul Wad) partnered with IIIT-Hyderabaad Professor of Control Systems, Dr. Spandan Roy (Co-Principal Investigator) on a Research project towards an AI-enhanced UAV, leveraging computer vision and a proprietary adaptive control algorithm. My role involved assisting with the AI elements of the proposal and integration with the UAV, in addition to conducting patent landscape analysis and market research to address the technology commercialization component of the solicitation}.
    \resumeSubItem{Ethical, Legal and Social Implications of Decentralized Science (TIV \& University of Puerto Rico, Rio Piedras, December 2022 - Current)} {Under the Dr. Mirjana Stankovic (PI), in collaboration with UPR-RP's Dr. Massey, and Dr. Mark Rohrbaugh (former head of technology transfer at the NIH), TIV has been conducting research on the ethical, legal and social implications of a novel form of crowd-sourced, citizen science, "Decentralized Science", on  computational genomics. I have led the proposal writing, which entails a focus on issues relating to data governance, international difference in data rights and policies, issues related to patent ownership and technology transfer, etc. We are currently working on the manuscript, and hope to submit it for peer-review in Fall of 2024}
    \resumeSubItem{Stem Cell Research (Johns Hopkins University, Summer 2018)} {Investigation of human mesenchymal cells using comparative bioreactor culture systems with enzymatic activity (IDO) measured by ELISA.}
    \resumeSubItem{Enzyme Kinetics Biochemistry Research (University of Virginia, Spring 2015)}{ Research on enzyme characteristics and behavior of a putative aromatic amino aminotransferase from Thermatoga maritime by inducing an L278E site-directed mutagenesis. Enzyme was successfully expressed and purified using transformed HK100 E. Coli, purified via IMAC and characterized based on Michaelis Menten kinetics.}

    \resumeSubItem{Neuroimmunology Research (Kipnis Lab, University of Virginia, 2013)}
      {Under the tutelage of Dr. Noel Derecki of the Kipnis lab, I spent a year as a research assistant studying the potential relationship between osteocytes and neurons.}
    \resumeSubItem{Impact of Cranial Electrical Stimulation Son Patients with Fibromyalgia (University of Virginia Center for the Study of Complementary and Alternative Therapies, 2012 - 2015)}
      {Desk research and sleep study analysis of fibromyalgia patients. Served also as a researcher on other projects by CCAT under Dr. Joel Anderson and Dr. Ann Taylor( Professor of Nursing and Director at Center for Study of Complementary Therapies}
  \resumeSubHeadingListEnd
  
%-----------AWARDS-----------------
\section{Honors \& Awards}
  \resumeSubHeadingListStartBullets
    \resumeSubItem{UVa MSDS Featured Capstone Project, Summer 2024}
      {Featured as part of U.Va MSDS Communications team,  highlighting the success of the research conducted for the UVa Student Health \& Wellness Department, for which I had the fortune of being one of the two student researchers.}
    \resumeSubItem{UVa MSDS Student Feature, Summer 2024}
      {Invited to be a featured student for the U.Va MSDS program by the U.Va MSDS Communications team, by recommendation of program staff}
    \resumeSubItem{United States - India Science and Technology Endowment Fund (USISTEF) Finalist - Top 20, Spring 2024} {I was part of the TIV-IIIT Hyderabaad Team which reached thefinals for the USISTEF Special Call for Safe and Trustworthy AI through our AI-Farms applications (final results anticipated to be announced in Fall of 2024) }
    \resumeSubItem{Robert Burnett Teaching Assistant Award, 2015}{Given by the University of Virginia Department of Chemistry at the Spring 2015 Graduation Ceremony to commemorate excellence and leadership as the Department's top Teaching Assistant (TA) to undergraduate and post-baccalaureate students}
    \resumeSubItem{U.Va MLK Celebration Event Speaker - 2015}
      {Was invited by U.Va School of Nursing to serve as a Guest Speaker to middle school students visiting the University for MLK Day in celebration embracing diverse and unique backgrounds. In particular, I discussed how my unique upbringing in a multicultural household informed my research pursuits and goals due to the experiences of poverty endure by my parents, towards trying to find solutions for meaningful societal impact}
 

    \resumeSubItem{Multiple Time Dean's List \& Honor Roll Recipient}{University of Virginia and Johns Hopkins University}
  \resumeSubHeadingListEnd

%--------PROGRAMMING SKILLS------------
\section{Skills}
  \resumeSubHeadingListStart
    \resumeSubItem{Spoken Languages}
      {English (Native Fluency), French (Native Fluency), Spanish (Professional Fluency) and Arabic (Elementary Fluency)}
    \resumeSubItem{Technologies}
      {Python, Pandas, Tensorflow, Pytorch, Seaborn, Git, Azure, Google Cloud, Power BI, Vite, Node.js, React, MySQL, MongoDB, Elasticsearch, Flask, AWS, Docker, Linux, HTML/CSS, R, and more.}
    \resumeSubItem{Additional Expertise}
      {Fintech, Blockchain, UAVs, AI \& ML, Big Data, Data Governance, Digital Transformation, Digital Policy, AI Policy, Data Ethics, IoT, Robotics, Sustainability, Cloud Computing, Cybersecurity, Business Analytics, and more}
  \resumeSubHeadingListEnd
  
  
\section{Other}
  \resumeSubHeadingListStart
    \resumeSubItem{Volunteering}
      {Volunteered at the Mercy House Thrift Store during weekends  of Summer 2023, helping to manage inventory, hang clothes, and assist customers. I have previously also volunteered as a patient advocate in the University of Virginia Hospital, sitting with solitary patients who were in need of conversation and human engagement}
    \resumeSubItem{Hobbies}
      {Reading, Journaling, Weightlifting, Soccer, working on AI \& Software Hobby Projects, and Gardening/farming (My family and I have successfully grown hardy and golden kiwis in Northern Virginia for the past ten years)}
  \resumeSubHeadingListEnd



%-------------------------------------------
\end{document}
