---
layout: page
title: experience 🔅
permalink: /experience/
description: Experience
nav: true
display_categories: [work, fun]
horizontal: false
description: Experience reversed chronological order.
years: [2020,1956, 1950, 1935, 1905]
nav: true

jobs: [
  {
    title: 'Backend',
    year: '2021-current',
    company: 'Eiya',
    tecnologies: ['Python','Django','Django Rest','kubernates','Bash scripting'],
    databases: ['postgres','redis','mongodb',''],
    description: 'As a backend engineer, I'm in charge of multiple microservices, improving performance, maintaining and updating the company's technology stack, as well as adding new features and improve workflows.',
    bullet_points: [
      'Responsible for more than 5 backend projects with an average of 210k lines of code, and more than 300 endpoints, with a test coverage of 80%..',
    'Achieved response time optimization by 50% of the time by implementing concurrency strategies, async, batch processing, and ORM query optimizations in Python Django-based backend systems.',
    'Resolved technical debt in 80% of systems by upgrading the tech stack in 4 projects which include technologies like:  Django, and Python among other dependencies, and updated container images for KS8/kubernetes production  environments. ',
  'Improved Jenkins pipelines, fixed troubles with database setups and name collisions, and set up AWS such as S3 and IAM.'

    ]
    
  },
  {
    title: 'Senior developer',
    year: '2020-2021',
    company: 'Sifei',
    tecnologies: ['php','java','net','vue','python'],
    databases: ['postgres','mysql','mongodb',''],
    description: 'As a Senior Full Stack Developer I lead a small team of developers and proposed product ideas that match with the company goals.',
    bullet_points: [
      'Devised and proposed a set of web microservice-based solutions regarding the company businesses that were necessary and complement other solutions to offer more features to customers by presenting them to executives.',
  'Implemented multiple system optmizations at platform level with memory optmizations and at database level with queries optmizations, indexes, among other tecniques.',
'Reduced the number of development style conflicts/decisions and reduced the number of QA review observations by 80% by implementing standard development and UI guides.',

'Ensured QA and accelerated release feature process by 90% implementing different execution environments for outsourced software developed by a third-party company and  then by standardizing environments in web projects. ',

'Decreased the number of questions and tickets about how to integrate with company services by 90% by proposing and implementing the GitHub examples repository initiative where customers can find examples.Github',
'Took charge of more than 5 web projects, achieved to maintain them, added features, and implemented a source version control without any transition process nor technical documentation.'

    ]
    
  },
  {
    title: 'Junior developer',
    year: '2017-2019',
    company: 'Sifei',
    tecnologies: ['php','java','net','vue','python'],
    databases: ['postgres','mysql','mongodb',''],
    description: '',
    bullet_points: [
     'Increased customer integrations by 20% by documenting and developing API, WS, and SDK.',
'Implemented new technologies such as Angular, Vue in the new projects which allow us to implement more complex projects and avoid deprecation in our technologies.',
'Accelerated and improved software release flow by 95% by proposing, designing, and implementing a Web System to manage software version release and by implementing a WS to check software latest versions and collect logs that help to automate updates on desktop applications and detect update problems.',
'Expanded business opportunities with customers by developing a new web system that allows downloading invoices(CFDI) from the federal tax administration into the application so users can retrieve and keep a backup of their invoices to create reports and to audits. ',


    ]
    
  },
  {
    title: 'Junior developer',
    year: '2017-2019',
    company: 'Sifei',
    tecnologies: ['php','java','net','vue','python'],
    web_tech_stack: 'Vue,PHP(Symfony 3,Slim),Postgresql 9,Mysql +5, Json, Redux,Bootstrap 4, Web Scraping,SOAP WS-Security, HTTPS, Typescript, Angular 2-4. SDK',
    tech_stack: 'JAVA, C#, PHP, Python. ',
    databases: ['postgres','mysql','mongodb',''],
    description: '',
    bullet_points: [
     'Increased customer integrations by 20% by documenting and developing API, WS, and SDK.',
'Implemented new technologies such as Angular, Vue in the new projects which allow us to implement more complex projects and avoid deprecation in our technologies.',
'Accelerated and improved software release flow by 95% by proposing, designing, and implementing a Web System to manage software version release and by implementing a WS to check software latest versions and collect logs that help to automate updates on desktop applications and detect update problems.',
'Expanded business opportunities with customers by developing a new web system that allows downloading invoices(CFDI) from the federal tax administration into the application so users can retrieve and keep a backup of their invoices to create reports and to audits. ',


    ]
    
  },
   {
    title: 'Junior developer',
    year: '2016-2016',
    company: 'Gecosoft',
    tecnologies: ['net',],
    databases: ['SQL Server',],
    description: '',
    bullet_points: [
  'Developed and native Android apps that connect to an API and a RSTP server stream to query guides and videos for people to learn and practice.',
  'Developed an API with Web API 2.0 for mobile app consumption that allows users to log in, query courses, and catalogs on topics.',
  'Documented the developed software with UML'

    ],
    tech_stack: 'Java(Android SDK) , REST, JSON, JACKSON, Retrofit, Fragments, Web API 2.0(net)  , SQL Server, C#, Entity Framework, Linq. Balsamiq Mockups, JustinMind. Telerik, UML.',
    
  }

]
---

<div class="publications">
<!-- Here a iteration is make over the file *.bib, it makes a query for the year -->
 
{% for j in page.jobs %}
  
  <h2 class="year">{{j.year}}</h2>
  <h2 class="text-primary">{{j.title}} - {{j.company}}</h2>

  <p>{{j.description}}</p>

  {% for p in j.bullet_points %}  
  <li>{{p}}</li>
  {% endfor %}

  <h3>Tech-Stack</h3>
  <h4>   Tecnologies   </h4>
  {% for t in j.tecnologies %}  
  <span class="badge badge-info">{{t}}|</span>
  {% endfor %}

  {% if j.web_tech_stack %}
  <div class="row">
    <strong>Web Tech-Stack: </strong>
    <p>{{j.web_tech_stack}}</p> 
  </div>
  {% endif %}
  {% if j.tech_stack %}
  <div class="row">
    <strong>Tech-Stack: </strong>
    <p>{{j.tech_stack}}</p> 
  </div>
  {% endif %}
  <h4>   Databases   </h4>
  {% for d in j.databases %}  
  <span class="badge badge-success">{{d}}</span>
  {% endfor %}



{% endfor %}
    


</div>