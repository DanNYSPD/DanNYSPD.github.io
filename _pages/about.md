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
    title: 'Proficient- Backend',
    description: 'Java,C#, PHP, bash-scripting, Databases: PostgresQL, Mysql. Others: Git,Linux(Centos, Fedora)',
  },{
    title: 'Proficient-Frontend',
    description: 'Vue,Vuex, Axios, Javascript. ',
  },{
    title: 'Intermediate-Backend',
    description: 'Python 3, Typescript Tools/Standards:Docker, Docker-compose, Vagrant, Vim, Tmux. Frameworks: JAVA:Spring , Spring Boot, JPA;Python:Flask;Nodejs, Makefile; PHP: Symfony',
  },{
    title: 'Intermediate-Frontend',
    description: 'Typescript, Angular 2-4,8; Native Android(java). ',
  },{
    title: 'Intermediate-Others',
    description: 'Scrum: User Stories,Scrum Daily; Jira, Trello,Version Control::Gitlab, Github , API Tools:Swagger, Open API, Insomnia, PostMan. Test: JMeter, Cypress',
  },
  {
    title: 'Basic',
    description: 'Languages: Ruby , Lua, Powershell, sed ,awk Other Command-line Tools. Tools: SoapUI: Database:MongoDB',
  },

  
]
design: 'BPMN, UML, Mockups'
---
😄 Self-learner, curious, adaptable full-stack engineer with 4+ years of experience developing web-based solutions: applications, APIs, SOAP, and REST services/microservices focused in PHP and Java. Development of SDK and examples in many programming languages to allow customers to integrate easier with the company services. Proposed standards and guides and developed internal tools for the QA and Help Desk areas. Experience leading a team of junior developers for web projects.


 👀 I’m interested in developing interesting and useful projects, especially web projects as a fullstack developer, I like to improve things with new ideas, features, better architecture, code design, patterns, and practices. Something that I enjoy to find ways to make things easier, less prone to errors, and more understandable.

📫 You can reach me via LinkedIn, sorry If I'm not so active in this social network but I will answer as soon as I notice your message and I have the appropriate time.

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
