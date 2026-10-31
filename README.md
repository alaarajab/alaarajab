<h1 align="center">Hi 👋, I'm Alaa Rajab</h1>
<h3 align="center">Software Engineer building AI solutions for real businesses 🤖<br/>RAG assistants · LLM evaluation · Full-stack web · Master's in Information Systems 🎓</h3>
<p align="left"> <img src="https://komarev.com/ghpvc/?username=alaarajab&label=Profile%20views&color=0e75b6&style=flat" alt="alaarajab" /> </p>
🤖 Featured: Cosmo Dental AI Assistant (repo · live)
A bilingual (English/Spanish) RAG assistant that answers patient questions on a real dental clinic's website, using only the clinic's own documents, with a source cited for every answer. I built the whole pipeline myself:
Retrieval: PDF extraction → sentence-aware chunking → `bge-m3` embeddings → Cloudflare Vectorize → top-k search with a similarity threshold
Generation: Llama 3.1 8B on Workers AI with grounded prompts and guardrails: no medical advice, no invented links, "please call the clinic" when the documents don't know
Evaluation in Python (pandas, matplotlib, Jupyter): a 38-question test set, chunk-size and threshold experiments, and before/after prompt runs
Result	
Answer accuracy (prompt v1 → v2)	89% → 97%
Out-of-scope questions correctly refused	100%
Average response time	~0.6 s
Running cost for the clinic	$0/month (Cloudflare free plan)
Stack: TypeScript · Cloudflare Workers · Workers AI · Vectorize · D1 (SQL) · Vitest · Python
🛠️ More projects
🦷 Cosmo Dental Clinic website: designed and built a bilingual, accessible (WCAG 2.2 AA), SEO-optimized site for a dental clinic in Northlake, IL, with React + Vite on Cloudflare. The AI assistant above runs on it.
🔭 Currently building AI Sales Commission Tracker
💡 What I work on
AI assistants grounded in a business's own data (RAG), not generic chatbots
Measuring AI quality: test sets, retrieval metrics (hit@k, MRR) and experiments before shipping changes
Practical, low-cost deployment on serverless platforms, with privacy and accessibility built in
🎓 Background
Master's in Information Systems
🌱 Graduate of the TripleTen Software Engineering Bootcamp
👯 Volunteered on the MedKids project with Rebecca Everlene Trust Co
⚡ Fun fact: 🤖 I've coached students in national robotics competitions like the First Lego League (FLL). Yes, I've built more robots than IKEA furniture!
📫 Contact
alaa88rajab@gmail.com
<p align="left">
<a href="https://linkedin.com/in/alaa-rajab-890a9b24" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn: alaa-rajab-890a9b24" height="30" width="40" /></a>
</p>
🧰 Languages and Tools
AI & data: Workers AI · Vectorize · embeddings · RAG · prompt engineering · Python · pandas · matplotlib · Jupyter
<p align="left">
<a href="https://www.python.org" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/></a>
<a href="https://www.typescriptlang.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="typescript" width="40" height="40"/></a>
<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/></a>
<a href="https://nodejs.org" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/></a>
<a href="https://reactjs.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/></a>
<a href="https://www.cloudflare.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cloudflare/cloudflare-original.svg" alt="cloudflare" width="40" height="40"/></a>
<a href="https://jupyter.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/jupyter/jupyter-original-wordmark.svg" alt="jupyter" width="40" height="40"/></a>
<a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/></a>
</p>
Also worked with:
<p align="left">
<a href="https://aws.amazon.com" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" width="40" height="40"/></a>
<a href="https://azure.microsoft.com/" target="_blank" rel="noreferrer"><img src="https://www.vectorlogo.zone/logos/microsoft_azure/microsoft_azure-icon.svg" alt="azure" width="40" height="40"/></a>
<a href="https://www.mysql.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/></a>
<a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/></a>
<a href="https://www.microsoft.com/en-us/sql-server" target="_blank" rel="noreferrer"><img src="https://www.svgrepo.com/show/303229/microsoft-sql-server-logo.svg" alt="mssql" width="40" height="40"/></a>
<a href="https://www.java.com" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/></a>
<a href="https://www.php.net" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="php" width="40" height="40"/></a>
<a href="https://git-scm.com/" target="_blank" rel="noreferrer"><img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/></a>
<a href="https://www.gnu.org/software/bash/" target="_blank" rel="noreferrer"><img src="https://www.vectorlogo.zone/logos/gnu_bash/gnu_bash-icon.svg" alt="bash" width="40" height="40"/></a>
<a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/></a>
<a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/></a>
<a href="https://www.figma.com/" target="_blank" rel="noreferrer"><img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="40" height="40"/></a>
</p>
<p><img align="center" src="https://github-readme-stats.vercel.app/api/top-langs?username=alaarajab&show_icons=true&locale=en&layout=compact" alt="Top languages" /></p>
