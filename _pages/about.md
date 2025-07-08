---
layout: about
title: about ℹ️
permalink: /
description: Full-Stack Developer| FullStack Developer | Web Senior Developer| Linux | Backend Developer| Vue developer

profile:
  align: right
  #image: prof_pic.jpg
  #address: >
  #  <p>555 your office number</p>
  #  <p>123 your address street</p>
  #  <p>Your City, State 12345</p>

news: false  # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
experience: true  # includes social icons at the bottom of the page

proficientBackend: 
skills: [
  {
    title: 'Backend',
    description: 'Python,PHP,Java,C#, Bash-scripting, Databases: PostgresQL, Mysql, Redis. Others: Git,Linux(Centos, Fedora). Tools/Standards:Docker, Docker-compose, Vagrant, Vim, Tmux. Frameworks: JAVA:Spring , Spring Boot, JPA;Python:Flask;Nodejs, Makefile; PHP: Symfony',
  },
   {
    title: 'Devops',
    description: 'Jenkings, Gitlab CD/CI, Docker',
  }
  ,{
    title: 'Frontend',
    description: 'Vue,Vuex,Javascript, Typescript, Angular 2-4,8; Native Android(java). ',
  },{
    title: 'Tools',
    description: 'Scrum: User Stories,Scrum Daily; Jira, Trello,Version Control::Gitlab, Github , API Tools:Swagger, Open API, Insomnia, PostMan. Test: JMeter, Cypress',
  },
  {
    title: '',
    description: 'Languages: Ruby , Lua, Powershell, sed ,awk Other Command-line Tools. Tools: SoapUI: Database:MongoDB',
  },

  
]
design: 'BPMN, UML, Mockups'
---
Senior Full-stack engineer with 8+ years of experience designing, modeling, and developing web-based solutions: applications, APIs, SOAP, and REST services/microservices using Python, Django, PHP, Java and multiple frameworks. Proven ability to optimize performance, upgrade systems, resolve complex technical challenges, and deliver high-quality solutions. Proposed and implemented standards, guides, resources and developed internal tools for the DEV, QA and Help Desk areas. Seeking a challenging role in an environment where I can contribute to innovative projects with the best industry practices. 

 👀 I’m interested in developing impactful projects, especially web projects as a fullstack developer, I like to improve things with new ideas, features, better architecture, code design, patterns, and practices.  I enjoy to find ways to make things easier, less prone to errors,more robust and mantainable.

📫 You can reach me via LinkedIn, sorry If I'm not so active in this social network but I will answer as soon as I notice your message and I have the appropriate time.

### VS code extensions contributions:
I have contributed to VsCode Extensions:

  [Context-Organizer](https://github.com/devaniljr/context-organizer) A vscode extension that allow to group related files by context.

  [vscode-php-getters-setters](https://github.com/DanNYSPD/vscode-php-getters-setters) A vscode extension that provides functionalities for PHP code such as creating useful methods based on propeties.


You can know more about me in  [LinkedIn](https://www.linkedin.com/in/daniel-hernandez-fco). You can know about my [experience](/experience)



<h3>Tech Skills</h3>

<strong class="text-primary"> Tech Skills: </strong>
{% for s in page.skills %}  
<div class="row">
  <strong class=""> {{s.title}}: </strong>
  <p>{{s.description}}</p>
</div>
{% endfor %}

<div class="row">
  <strong class=""> Design and Modeling: </strong>
  <p>{{page.design}}</p>
</div>

