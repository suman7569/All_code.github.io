%-------------------------
% Resume - Suman Kumar | Dec 2026 | ATS-Optimized v6
%-------------------------
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
\input{glyphtounicode}
\usepackage{multicol}

\pagestyle{fancy}
\fancyhf{}
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

\addtolength{\oddsidemargin}{-0.7in}
\addtolength{\evensidemargin}{-0.7in}
\addtolength{\textwidth}{1.4in}
\addtolength{\topmargin}{-.5in}
\addtolength{\textheight}{1.0in}

\urlstyle{same}
\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

\titleformat{\section}{
  \vspace{-2pt}\scshape\raggedright\large
}{}{0em}{}[\color{black}\titlerule \vspace{-2pt}]

\pdfgentounicode=1

% Highlight: use sparingly (at most one key term or metric per bullet)
\definecolor{lightblue}{RGB}{30,144,255}
\newcommand{\hl}[1]{\textcolor{lightblue}{\textbf{#1}}}

%-------------------------
% Custom commands
\newcommand{\resumeItem}[1]{
  \item\small{{#1 \vspace{-2pt}}}
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{0.97\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & #2 \\
      \textit{\small#3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeProjectHeading}[2]{
    \item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \small#1 & #2 \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubItem}[1]{\resumeItem{#1}\vspace{-4pt}}
\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}
\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.15in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}

%-------------------------------------------
\begin{document}

%----------HEADING----------
\begin{center}
    {\Huge \scshape Suman Kumar} \\ \vspace{2pt}
    \small +91-87890-35342 $|$
    \href{mailto:sumankumar7569@gmail.com}{\underline{sumankumar7569@gmail.com}} $|$
    \href{https://www.linkedin.com/in/suman-kumar11/}{\underline{linkedin.com/in/suman-kumar11}} $|$
    \href{https://github.com/suman7569}{\underline{github.com/suman7569}}
\end{center}

%----------PROFESSIONAL SUMMARY----------
\section{Professional Summary}
\hl{Backend Engineer} with \hl{4.5+ years} building production systems in Java 17, Spring Boot 3, and Go.
Spent 4+ years building \hl{telecom CDR rating and billing microservices}, including leading a VB.NET-to-Java
platform migration. Now building a JIRA-alternative issue-tracking platform in \hl{Go + PostgreSQL}, with
Tata Play as its first enterprise client. Targeting SDE-2 / Senior Backend roles.

%-----------TECHNICAL SKILLS-----------
\section{Technical Skills}
\resumeSubHeadingListStart
  \resumeSubItem{\textbf{Languages:} Java (8, 11, 17), Go (Golang), SQL}
  \resumeSubItem{\textbf{Java \& Spring:} Spring Boot 3, Spring MVC, Spring Security, Spring Cloud (Gateway, Config, Eureka), Hibernate / JPA, Resilience4j}
  \resumeSubItem{\textbf{Go:} Echo, GORM, Zap / Zerolog, Goroutines \& Channels, Context, Go Modules}
  \resumeSubItem{\textbf{Databases \& Caching:} PostgreSQL, MS SQL Server, MySQL, Redis (caching, pub/sub, distributed locks)}
  \resumeSubItem{\textbf{Cloud \& DevOps:} AWS (EC2, S3, RDS, IAM), Docker, GitLab CI/CD, Maven, Git}
  \resumeSubItem{\textbf{Testing \& Tools:} JUnit 5, Mockito, Postman, Swagger / OpenAPI, Micrometer, Spring Boot Actuator}
  \resumeSubItem{\textbf{Design:} System Design (HLD/LLD), Microservices, REST API Design, Multi-Tenant SaaS, RBAC, API Gateway, Circuit Breaker}
  \resumeSubItem{\textbf{Familiar with:} Kubernetes}
\resumeSubHeadingListEnd

%-----------WORK EXPERIENCE-----------
\section{Work Experience}
  \resumeSubHeadingListStart

    % Dec 2026 version (~3-4 months tenure). After ~1 year, expand to 4-5 bullets
    % and replace in-progress wording with outcomes (go-live, users, latency, clients onboarded).
    \resumeSubheading
      {Product Engineer (Backend)}{September 2026 -- Present}
      {Datamato Technologies}{Pune, Maharashtra}
      \resumeItemListStart
        \resumeItem{Building the backend of an in-house \hl{enterprise issue-tracking platform} (JIRA replacement) in Go (Echo, GORM) and PostgreSQL; Tata Play is the first enterprise client in rollout.}
        \resumeItem{Developing REST APIs for projects, issues, sprints, boards, and comments, with \hl{configurable workflow transitions} and role-based permissions, on a normalized PostgreSQL schema indexed for issue search; contributing to tenant-aware data isolation for future clients.}
        \resumeItem{Moved notification and audit-log processing off the request path using \hl{goroutines, channels, and context}, keeping user-facing APIs non-blocking; shipped production Go within the first month after moving from Java.}
      \resumeItemListEnd

    \resumeSubheading
      {Software Developer (Backend)}{March 2022 -- August 2026}
      {Aloha Technology Pvt. Ltd. \href{https://drive.google.com/file/d/1VKQSAtIMepc0H1igGIQ_W1PNllbv01UO/view?usp=drive_link}{\underline{[Experience Letter]}} \href{https://drive.google.com/file/d/1tzi-qlRiwsyXcJVoA9_-sDxlXT3Uh99l/view?usp=drive_link}{\underline{[Relieving Letter]}}}{Pune, Maharashtra}
      \resumeItemListStart
        % TODO: replace "10,000+ daily transactions" with the real CDR volume (records/day or /month) if you know it.
        \resumeItem{Built and maintained Spring Boot 3 + Java 17 microservices for a live \hl{telecom rating and CDR processing platform} (NRTC) --- ingestion, validation, rating, and downstream billing on MS SQL Server --- handling 10,000+ daily transactions at 99.9\% uptime with P95 latency under 200ms.}
        \resumeItem{Cut data retrieval latency by \hl{50\%} by adding targeted SQL indexes, fixing Hibernate N+1 queries, and tuning the connection pool; added Redis caching that reduced repeated DB calls by 35\%.}
        % TODO: name the actual external systems here if you can (e.g., carrier feeds, payment gateway).
        \resumeItem{Wrapped external service integrations in \hl{Resilience4j} circuit breakers and retries, reducing cascading-failure incidents by 30\%.}
        \resumeItem{Implemented \hl{Spring Security + JWT} role-based access with refresh-token rotation across all services; no unauthorized-access incidents in production.}
        \resumeItem{Led the migration of the Rating \& Billing platform from \hl{VB.NET to Java/Spring Boot}, lowering maintenance effort by 20\% and bringing it onto the CI/CD pipeline.}
        \resumeItem{Owned GitLab CI/CD, Docker builds, and AWS EC2/RDS environments for staging and production; \hl{mentored 5 junior developers} through code reviews and design sessions.}
      \resumeItemListEnd

  \resumeSubHeadingListEnd

%-----------PROJECTS-----------
\section{Key Projects}
  \resumeSubHeadingListStart

    \resumeProjectHeading
      {\textbf{Enterprise Issue-Tracking Platform (JIRA Replacement)} $|$ \textit{Datamato Technologies --- Client: Tata Play} \\ \textit{Go, Echo, GORM, PostgreSQL, Zap / Zerolog, REST APIs, RBAC}}{}
      \resumeItemListStart
        \resumeItem{Work-management product replacing JIRA for enterprise teams: projects, issues, sprints, \hl{Kanban/Scrum boards}, comments, and activity history.}
        \resumeItem{Built issue-lifecycle and \hl{configurable workflow} modules (custom statuses, allowed transitions, per-role permissions) on a normalized PostgreSQL schema indexed for issue search and filtering.}
        \resumeItem{Designed \hl{tenant-aware data access} so each enterprise client's projects and users stay isolated, supporting rollout to clients beyond Tata Play.}
      \resumeItemListEnd

    \resumeProjectHeading
      {\textbf{Delivery Route Optimization Engine} $|$ \textit{Aloha Technology} \\ \textit{Java 17, Spring Boot 3, Redis, Spring Data JPA, MySQL}}{}
      \resumeItemListStart
        \resumeItem{Modeled the delivery-hub network as a weighted graph and implemented \hl{Dijkstra's algorithm} (adjacency list + priority queue) to return shortest distance and full hub path through REST APIs.}
        \resumeItem{Cached frequent routes in Redis and held the graph in memory to avoid recomputation; Hub, Route, and Parcel entities support live route updates.}
      \resumeItemListEnd

  \resumeSubHeadingListEnd

%-----------INTERNSHIP-----------
\section{Internship}
  \resumeSubHeadingListStart
    \resumeSubheading
      {Associate Engineer Intern}{September 2021 -- February 2022}
      {Forcebolt Pvt. Ltd.}{Kurukshetra, Haryana}
      \resumeItemListStart
        \resumeItem{Built core modules of a Diagnostics Path Lab Management System in Java and Spring Boot, and integrated third-party diagnostic APIs over REST.}
      \resumeItemListEnd
  \resumeSubHeadingListEnd

%-----------EDUCATION-----------
\section{Education}
  \resumeSubHeadingListStart
    \resumeSubheading
      {Rajiv Gandhi Proudyogiki Vishwavidyalaya}{Bhopal, Madhya Pradesh}
      {Bachelor of Technology in Computer Science --- CGPA: 8.71 / 10.0 \href{https://drive.google.com/file/d/1zKo9yZ9Jc27gwqprZ8OIllFgBVi_IfWR/view?usp=drive_link}{\underline{[View Degree]}}}{August 2018 -- August 2022}
  \resumeSubHeadingListEnd

%-----------OM--------------------------------
\end{document}
