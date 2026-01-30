\documentclass[a4paper,9pt]{article}
\usepackage[margin=0.3in]{geometry}
\usepackage{enumitem}
\usepackage{hyperref}
\usepackage{multicol}
\usepackage{titlesec}

\hypersetup{
    colorlinks=true,
    linkcolor=blue,
    urlcolor=blue,
    breaklinks=true
}

% Global setting to remove all extra space between list items
\setlength{\parindent}{0pt}
\setlist[itemize]{leftmargin=0.35cm, itemsep=0pt, topsep=0pt, parsep=0pt, partopsep=0pt}
\renewcommand{\baselinestretch}{0.9}

\begin{document}
\small

% Header compressed to save space
{\centering
    \Large \textbf{Prem Kumar Mahanty} \\
    \vspace{1pt}
    \normalsize GEN AI Developer \\
    \footnotesize
    \vspace{1pt}
    \href{https://www.linkedin.com/in/prem-kumar-mahanty-21b4aa317}{\underline{LinkedIn}} \,|\, 
    \href{https://github.com/prem-cre}{\underline{GitHub}} \,|\, 
    \href{https://leetcode.com/u/prem_code/}{\underline{LeetCode}} \,|\, 
    \href{https://www.codechef.com/users/prem_2007}{\underline{CodeChef}} \\
    \vspace{1pt}
    \textbf{Location:} Visakhapatnam, Andhra Pradesh, India \,|\, 
    \textbf{Phone:} +91 9492975838 \,|\, 
    \textbf{Email:} \href{mailto:mahantypremkumar2007@gmail.com}{\underline{mahantypremkumar2007@gmail.com}} \par
}

\vspace{-0.5em}

% Education Section
\section*{Education}
\vspace{-0.8em}
\noindent\rule{\textwidth}{0.4pt}
\vspace{-0.4em}
\begin{itemize}
    \item \textbf{VIGNAN'S INSTITUTE OF INFORMATION TECHNOLOGY (B.Tech. Computer Science)} \hfill 2024--2028\\
    CGPA: 8.6/10
    \item \textbf{INDIAN INSTITUTE OF TECHNOLOGY, Madras (B.Sc. Data Science and AI)} \hfill 2024--2028\\
    CGPA: 7.79/10
\end{itemize}

\vspace{-0.9em}

% Experience Section
\section*{Experience}
\vspace{-0.8em}
\noindent\rule{\textwidth}{0.4pt}
\vspace{-0.4em}
\textbf{LawVriksh — GenAI Intern} \hfill Aug 2025 -- Present
\vspace{2pt}
\begin{itemize}
    \item Built a full \textbf{compliance-aware LLM pipeline} with deterministic prompting, source-grounded generation, and multi-layer verification, reducing hallucination rates by 72\% across legal drafting workflows.

    \item Engineered an \textbf{automated fact-checking engine} using retrieval-augmented verification, cosine-similarity scoring, and cross-document conflict detection, improving factual accuracy by 68\%.

    \item Developed a \textbf{reference-manager-driven citation architecture} with summary embeddings, weighted keyword ranking, and auto-generated citation blocks, lowering retrieval latency by 55\%.

    \item Implemented a \textbf{multi-agent system} (ingestion, retrieval, analysis, generation, compliance agents) using MCP servers, enabling controllable tool use, traceable outputs, and safe agentic reasoning.

    \item Designed a \textbf{real-time gap analysis engine} that identifies missing arguments, supporting principles, and counter-reasoning using hybrid RAG + rule-based logic, boosting document completeness by 40\%.

    \item Integrated \textbf{LLM observability modules} to log prompt-output lineage, ensure auditability, and support compliance teams in reviewing AI-generated drafts.

    \item Enhanced legal drafting UX with \textbf{context-aware suggestion generation} (research-grounded vs. context-only modes), achieving 2.3× faster drafting throughput for end-users.
\end{itemize}
\vspace{2pt}
\textbf{Somtax Solutions — AI Intern} \hfill Aug 2025 -- December 2025
\begin{itemize}
    \item Designed and deployed multimodal AI agents and a citation engine using custom MCP servers \& APIs, achieving seamless data integration and automation while cutting operational costs by 40\%.
    \item Orchestrated a scalable microservices architecture with Django \& Docker, implementing CI/CD pipelines that reduced deployment time by 40\% and improved system reliability by 25\% while leading a team of 5 engineers.
    \item Pioneered a next-generation recommendation engine with Graph Neural Networks (GNNs) + Faiss, replacing legacy systems to boost processing speed by 60\% and optimize cost efficiency.
\end{itemize}

\vspace{-0.9em}

% Projects Section
\section*{Projects}
\vspace{-0.4em}
\noindent\rule{\textwidth}{0.2pt}
\vspace{-0.4em}
\begin{itemize}
    \item \textbf{Compliance-Aware LLM Writing & Verification Engine} 
    \hfill \textit{Python, FastAPI, LangChain, FAISS, Gemini/GPT, Redis, Async IO}
    \begin{itemize}
        \item Designed and deployed a multi-stage retrieval and compliance pipeline that reduced hallucinated statements by \textbf{~72\%} through deterministic prompting, reference validation, and hybrid RAG scoring.
        \item Built an optimized embedding + vector search layer using FAISS and Redis caching, decreasing retrieval latency by \textbf{40–55\%} across high-volume requests.
        \item Implemented asynchronous FastAPI endpoints and batched inference flows, improving end-to-end response time from \textbf{1.9s → 0.8s}.
        \item Developed an automated citation-insertion and fact-violation detection module that increased correct citation placement accuracy by \textbf{65\%}.
        \item Created a context-window reduction algorithm that shrank token consumption by \textbf{~38\%} while preserving relevance via ranked chunking and adaptive windowing.
        \item Oversaw system profiling, regression tests, and latency audits, enabling stable performance at \textbf{10k+} monthly compliance-check executions.
    \end{itemize}

    \item \textbf{E-Commerce Website} \hfill \textit{React, Django, MySQL,}
    \begin{itemize}
        \item Designed and developed a fully functional e-commerce website with responsive UI.
        \item Integrated the e-commerce site with third-party APIs for shipping, payment, and tax calculation, automating order fulfillment processes; reduced manual order processing time by 4 hours weekly.
        \item Utilized Django for backend logic and MySQL for data storage.
    \end{itemize}

    \item \textbf{Swaply} \hfill \textit{Tailwind CSS, Django, PostgreSQL, JS,MCP Servers,GNN's,Agentic Architect} \href{https://v0-swaply-web-design-3a.vercel.app/chat}{Live}
    \begin{itemize}
       \item Developed a coupon trading platform with Django and PostgreSQL, supporting secure transactions, chat, and wallet systems.
       \item Implemented real-time screen sharing and live coupon verification using WebRTC and Django Channels with WebSockets.
       \item Designed a mobile-first responsive interface using Tailwind CSS, enabling seamless user experience and profile management.
    \end{itemize}
\end{itemize}

\vspace{-0.9em}

% Skills Section
\section*{Skills}
\vspace{-0.8em}
\noindent\rule{\textwidth}{0.4pt}
\vspace{-0.4em}
\begin{itemize}
    \item \textbf{Programming Languages and Databases:} SQL, Java, MongoDB, Python, PHP, JavaScript, MySQL
    \item \textbf{Web tools and Frameworks:} HTML, CSS \& ReduxToolkit, Django, Bootstrap, React
    \item "Led a team of four to develop a YouTube clone, demonstrating excellent teamwork."
    \item \textbf{AI/ML \& Data Science:} PyTorch, TensorFlow, Scikit-learn
    \item \textbf{Recommendation Systems:} Graph Neural Networks (GNNs), Faiss (vector similarity search)
    \item \textbf{DevOps \& Infrastructure:} Docker, CI/CD Pipelines, Microservices Architecture, Git/GitHub
    \item \textbf{APIs \& Backend Development:} Django REST Framework, Custom MCP Servers, REST API design
\end{itemize}

\vspace{-0.9em}

% Certifications Section
\section*{Certifications and Achievements}
\vspace{-0.8em}
\noindent\rule{\textwidth}{0.4pt}
\vspace{-0.4em}
\begin{itemize}
    \item \textbf{Hacakthon winner of WOW GOOGLE DEVELOPERS GROUP 2025 and finalist in the Gen E-Summit AI Ideathon  }
    
\end{itemize}

\end{document}
