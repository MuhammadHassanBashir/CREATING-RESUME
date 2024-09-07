# CREATING-RESUME

Steps:
    - Go to **overleaf.com** and create project name: Hassan
    - Then create 2 file having .tex and .cls extension file and paste below code accordingly. (files like main.tex and resume.cls)

.TEX FILE For DOCUMENT Setting
------------------------------

    \documentclass{resume} % Use the custom resume.cls style
    \usepackage{multicol}
    \usepackage{enumitem}
    \usepackage[left=0.4 in,top=0.4in,right=0.4 in,bottom=0.4in]{geometry} % Document margins
    \newcommand{\tab}[1]{\hspace{.2667\textwidth}\rlap{#1}} 
    \newcommand{\itab}[1]{\hspace{0em}\rlap{#1}}
    \name{Hassan Bashir} % Your name
    % You can merge both of these into a single line, if you do not have a website.
    \address{\href{muhammadhassanb122@gmail.com}{muhammadhassanb122@gmail.com}}
    \address{\href{https://www.linkedin.com/in/muhammad-hassan-bashir-57972a192}{linkedin.com/in/muhammad-hassan-bashir-57972a192} \\ \href{https://github.com/MuhammadHassanBashir}{github.com/MuhammadHassanBashir}} 
    \address{+923209453393 \\ Lahore, Pakistan} 
    \begin{document}
    
    %----------------------------------------------------------------------------------------
    %	OBJECTIVE
    %----------------------------------------------------------------------------------------
    
    \begin{rSection}{OBJECTIVE}
    
    {DevOps engineer having years of experience, mostly in AWS and GCP Cloud, with a professional attitude who works
    with dedication and is always ready to accept challenges. I bring value to the team by always trying to give the best long-
    term solutions for bigger problems.}
    
    \end{rSection}
    
    %----------------------------------------------------------------------------------------
    \begin{rSection}{PROFESSIONAL EXPERIENCE}
    
    \textbf{DevOps Engineer - Full Time} \hfill Dec 2023 - Present\\
    Alpha9 Solutions · Remote \hfill Lahore, Pakistan
     \begin{itemize}
        \itemsep -3pt {} 
        \item Successfully delivered a \textbf{GCP Marketplace} project by deploying and configuring \textbf{Kubernetes base applications}. Utilized \textbf{Helm} as the package manager to streamline the deployment of ready-to-use \textbf{software services} on the client’s platform, ensuring \textbf{seamless integration} with GCP Marketplace standards and optimizing for performance and scalability.
        \item  Successfully \textbf{implemented centralized logging and monitoring infrastructure} using \textbf{GCP Elastic Cloud} and \textbf{GCP Managed Prometheus}. The key components and tasks completed include, Configured \textbf{Fluentd} as the \textbf{logging agent} to send all application logs to \textbf{GCP Elastic Cloud}, Created a \textbf{dedicated team channel} for notifying the development team about \textbf{error logs}, ensuring prompt detection and resolution of issues. \textbf{Implemented GCP Managed Prometheus} for \textbf{collecting infrastructure metrics}, Configured collectors to gather relevant \textbf{metrics} for monitoring the health and performance of the infrastructure, Developed \textbf{custom dashboards} to visualize metrics and enable effective \textbf{monitoring of system resources and performance indicators}, Set up a \textbf{team channel for notifying abnormal infrastructure metrics}, allowing proactive intervention to prevent potential issues and ensure system stability.
        \item   Successfully implemented the \textbf{migration of self managed elastic search} hosted in \textbf{GKE Cluster to GCP Elastic Cloud}. Also, \textbf{implement backup policies} and \textbf{restoration policies} on GCP Elastic Cloud to schedule \textbf{regular backups} of Elasticsearch \textbf{indices} and \textbf{snapshots} to a designated storage location. this enhanced the \textbf{reliability, scalability, and manageability} of our Elasticsearch infrastructure while ensuring \textbf{data protection} and resilience against potential disruptions.  
        \item  Led to provision all infrasturture resources on cloud using terraform.
        \item   Design, \textbf{implement, and manage CI/CD pipelines using Jenkins} to automate build, test, and deployment processes. Ensure seamless integration of code changes, \textbf{enabling continuous delivery and continuous integration}.
        \item \textbf{Implement and manage cron jobs} for Kubernetes nodes to automatically \textbf{scale down or delete nodes during off-peak periods}. This optimization helps on \textbf{reducing the overall project expenses}.
        \item  Experienced in \textbf{deploying and configuring OpenVPN} for secure remote access and \textbf{GCP HA VPN} for robust, high-availability connectivity between cloud and on-premises environments.
        
     \end{itemize}
    
    \textbf{IT Infrastructure and DevOps Engineer - Full Time} \hfill Oct 2021 - Dec 2023\\
    Cheetay Logistics · On-Site \hfill Lahore, Pakistan
     \begin{itemize}
        \itemsep -3pt {} 
        \item Responsible for overseeing both \textbf{local and remote network infrastructure}, I excel in installing, configuring, and troubleshooting a range of network devices, \textbf{including routers, switches, and firewalls}. My role involves vigilant monitoring of \textbf{network performance} and \textbf{security}, swiftly identifying and resolving issues. I contribute to \textbf{designing} and \textbf{implementing network solutions} tailored to meet business requirements..
        \item Conducted \textbf{network monitoring} and \textbf{maintenance} for various IT infrastructure components, including \textbf{email systems, devices, storage, operating systems, and security measures}.
        \item Oversaw servers, \textbf{support services}, databases, and applications, implementing corrective actions to \textbf{resolve issues efficiently}.
        \item Coordinated \textbf{new deployments} and addressed \textbf{network outages} promptly to maintain service continuity.
        \item Implemented \textbf{DevOps practices} to streamline \textbf{deployment} processes, \textbf{automate} configurations, and \textbf{enhance system integration}.
        \item Utilized tools like \textbf{Linux Docker, Jenkins, Git, GitHub, AWS and Terraform} to improve infrastructure management and application deployment.
        
     \end{itemize}
    
    \textbf{Network Support Engineer -  Full Time} \hfill Nov 2019 - Sep 2021 \\
    Optixfiber · On-Site \hfill Lahore, Pakistan
     \begin{itemize}
        \itemsep -3pt {} 
        \item Delivered \textbf{Level-2 technical support} for the \textbf{FTTx Project}, assisting both \textbf{Home and Enterprise} Business Units..
        \item Oversaw new \textbf{deployments}, ensuring successful \textbf{integration and operation}.
        \item Addressed and resolved \textbf{network outages} promptly, maintaining \textbf{service reliability}.
        \item Provided \textbf{real-time troubleshooting} and issue resolution for \textbf{network-related incidents}.
        \item Collaborated with teams to enhance \textbf{network performance} and \textbf{customer satisfaction}.
     
     \end{itemize}
    
    \textbf{Network Operations Center Engineer - Internship} \hfill Sep 2019 - Oct 2019\\
    WorldCall Telecom Limited · On-Site \hfill Lahore, Pakistan
     \begin{itemize}
        \itemsep -3pt {} 
        \item Monitored and maintained \textbf{network performance}, ensuring uptime and quick resolution of \textbf{network issues}.
        \item Conducted real-time troubleshooting and provided \textbf{Tier 1/2} support for \textbf{network incidents and outages}.
        \item Collaborated with \textbf{cross-functional} teams to resolve issues, \textbf{escalating} to higher support when necessary.
        
     \end{itemize}
    
    \end{rSection} 
    
    
    %----------------------------------------------------------------------------------------
    %	EDUCATION SECTION
    %----------------------------------------------------------------------------------------
    
    \begin{rSection}{Education}
    
    % University name, 1 font size larger
    \textbf{\fontsize{12pt}{13.6pt}\selectfont BACHELORS IN ELECTRICAL ENGINEERING  \textbar\ COMSATS University Islamabad, Lahore Campus} \hfill Aug 2015 - Sep 2019\\
    
    % Degree and CGPA, normal font size
    \textbf{B.S. in Electrical Engineering(Telecommunications)  \textbar\ Senior Year Student}  \hfill June 2018\\
    {\bf Relevant Coursework:} Digital Communication Systems, \textbf{Data Communication and Computer Networks}, Telecommunication Systems Engineering, \textbf{Optical Fiber Communications, Broadband Technologies}, Antenna and Radio Wave Propagation, Wireless Communication Systems, Network Programming
    
    \end{rSection}
    
    %----------------------------------------------------------------------------------------
    % TECHNICAL STRENGTHS	
    %----------------------------------------------------------------------------------------
    \begin{rSection}{ TECHNICAL SKILLS AND TOOLS}
    
    \begin{multicols}{2}
        \begin{itemize}[label={}, left=0pt, labelsep=5pt, itemsep=0pt, topsep=0pt, wide=0pt]
            \item \textbf{Cloud Platforms:} AWS, GCP
            \item \textbf{Operating Systems:} Linux (Ubuntu, Debian)
            \item \textbf{Containerization:} Docker
            \item \textbf{CI/CD:} Jenkins
            \item \textbf{Version Control:} Git, GitHub
            \item \textbf{Container Orchestration:} Kubernetes
            \item \textbf{Helm:} Helm (Package manager for Kubernetes)
            \item \textbf{GitOps:} ArgoCD
            \item \textbf{Secrets Management:} Kubernetes Sealed Secrets
            \item \textbf{Scripting:} Bash
            \item \textbf{Service Mesh:} Istio
            \item \textbf{Configuration Management:} Ansible
            \item \textbf{Infrastructure as Code:} Terraform, CloudFormation
            \item \textbf{Monitoring/Logging:} ELK/EFK, Prometheus/Grafana
        \end{itemize}
    
    \end{multicols}
    
    \end{rSection}
    
    %----------------------------------------------------------------------------------------
    \begin{rSection}{TECHSTACK} 
    \textbf{The other stack I have worked on includes the following: } 
    
    {\bf AWS:} VPC , EC2 , Route Table , Route53 , RDS , S3 Storage , ECS , ECR , CodePipeline ,Elastic Beanstalk, Lambda
    Functions , Transit Gateways , CloudWatch , ELK , API Gateway
    
    {\bf GCP:} VPC, Compute Engine, GCP Route, Cloud DNS, Cloud SQL, Cloud Storage, Kubernetes Engine, GCP
    Container Registry, Cloud Build, App Engine, Cloud Functions, Cloud Interconnect, CLoud Logging, GCP Elastic
    Cloud.
    \end{rSection}
    
    \begin{rSection}{CERTIFICATIONS AND TRAININGS} 
    \begin{itemize}
        \item AWS CERTIFIED SOLUTIONS ARCHITECT ASSOCIATE \hfill May 2021
        \item RHEL, RHCSA , LINUX FOUNDATION  
        \item CKA,  CKAD
        \item AWS,  GCP
        \item TERRAFORM 
    \end{itemize}
    \end{rSection}
    
    \begin{rSection}{PERSONAL SKILLS} 
    \begin{itemize}
        \item Interpersonal communication and presentation skills.
        \item Effective team player (both as a leader and follower)
    \end{itemize}
    \end{rSection}
    
    \begin{rSection}{LANGUAGES} 
    \begin{itemize}
        \item URDU
        \item ENGLISH
    \end{itemize}
    \end{rSection}
    \end{document}





.cls file for styling
-------------------------

        %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
        % Medium Length Professional CV - RESUME CLASS FILE
        %
        % This template has been downloaded from:
        % http://www.LaTeXTemplates.com
        %
        % This class file defines the structure and design of the template. 
        %
        % Original header:
        % Copyright (C) 2010 by Trey Hunner
        %
        % Copying and distribution of this file, with or without modification,
        % are permitted in any medium without royalty provided the copyright
        % notice and this notice are preserved. This file is offered as-is,
        % without any warranty.
        %
        % Created by Trey Hunner and modified by www.LaTeXTemplates.com
        %
        %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
        
        \ProvidesClass{resume}[2010/07/10 v0.9 Resume class]
        
        \LoadClass[11pt,letterpaper]{article} % Font size and paper type
        
        \usepackage[parfill]{parskip} % Remove paragraph indentation
        \usepackage{array} % Required for boldface (\bf and \bfseries) tabular columns
        \usepackage{ifthen} % Required for ifthenelse statements
        
        \usepackage{hyperref}
        \hypersetup{
            colorlinks=true,
            linkcolor=blue,
            filecolor=magenta,      
            urlcolor=blue,
        }
        
        \pagestyle{empty} % Suppress page numbers
        
        %----------------------------------------------------------------------------------------
        %	HEADINGS COMMANDS: Commands for printing name and address
        %----------------------------------------------------------------------------------------
        
        \def \name#1{\def\@name{#1}} % Defines the \name command to set name
        \def \@name {} % Sets \@name to empty by default
        
        \def \addressSep {$\diamond$} % Set default address separator to a diamond
        
        % One, two or three address lines can be specified 
        \let \@addressone \relax
        \let \@addresstwo \relax
        \let \@addressthree \relax
        
        % \address command can be used to set the first, second, and third address (last 2 optional)
        \def \address #1{
          \@ifundefined{@addresstwo}{
            \def \@addresstwo {#1}
          }{
          \@ifundefined{@addressthree}{
          \def \@addressthree {#1}
          }{
             \def \@addressone {#1}
          }}
        }
        
        % \printaddress is used to style an address line (given as input)
        \def \printaddress #1{
          \begingroup
            \def \\ {\addressSep\ }
            \centerline{#1}
          \endgroup
          \par
          \addressskip
        }
        
        % \printname is used to print the name as a page header
        \def \printname {
          \begingroup
            \hfil{\MakeUppercase{\namesize\bf \@name}}\hfil
            \nameskip\break
          \endgroup
        }
        
        %----------------------------------------------------------------------------------------
        %	PRINT THE HEADING LINES
        %----------------------------------------------------------------------------------------
        
        \let\ori@document=\document
        \renewcommand{\document}{
          \ori@document  % Begin document
          \printname % Print the name specified with \name
          \@ifundefined{@addressone}{}{ % Print the first address if specified
            \printaddress{\@addressone}}
          \@ifundefined{@addresstwo}{}{ % Print the second address if specified
            \printaddress{\@addresstwo}}
             \@ifundefined{@addressthree}{}{ % Print the third address if specified
            \printaddress{\@addressthree}}
        }
        
        %----------------------------------------------------------------------------------------
        %	SECTION FORMATTING
        %----------------------------------------------------------------------------------------
        
        % Defines the rSection environment for the large sections within the CV
        \newenvironment{rSection}[1]{ % 1 input argument - section name
          \sectionskip
          \MakeUppercase{{\bf #1}} % Section title
          \sectionlineskip
          \hrule % Horizontal line
          \begin{list}{}{ % List for each individual item in the section
            \setlength{\leftmargin}{0em} % Margin within the section
          }
          \item[]
        }{
          \end{list}
        }
        
        %----------------------------------------------------------------------------------------
        %	WORK EXPERIENCE FORMATTING
        %----------------------------------------------------------------------------------------
        
        \newenvironment{rSubsection}[4]{ % 4 input arguments - company name, year(s) employed, job title and location
         {\bf #1} \hfill {#2} % Bold company name and date on the right
         \ifthenelse{\equal{#3}{}}{}{ % If the third argument is not specified, don't print the job title and location line
          \\
          {\em #3} \hfill {\em #4} % Italic job title and location
          }\smallskip
          \begin{list}{$\cdot$}{\leftmargin=0em} % \cdot used for bullets, no indentation
           \itemsep -0.5em \vspace{-0.5em} % Compress items in list together for aesthetics
          }{
          \end{list}
          \vspace{0.5em} % Some space after the list of bullet points
        }
        
        % The below commands define the whitespace after certain things in the document - they can be \smallskip, \medskip or \bigskip
        \def\namesize{\LARGE} % Size of the name at the top of the document
        \def\addressskip{\smallskip} % The space between the two address (or phone/email) lines
        \def\sectionlineskip{\medskip} % The space above the horizontal line for each section 
        \def\nameskip{\medskip} % The space after your name at the top
        \def\sectionskip{\medskip} % The space after the heading section
