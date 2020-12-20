# Resume: David Sanders

https://github.com/shangxiao/resume/

## Developer Profile

I'm a developer who loves working with open source and giving back to the open source community.  You may find me hanging around #django on freenode answering questions on Django.  I mainly work with Python/Django/Postgres/React but I've always liked to explore new horizons and am not limited to the Django realm.  I'm also currently re-learning functional programming through Haskell with a view to exploring Elm, Reason, Clojure or Scala and also feeding this back into my Python development.

In the web development world I tend to value [simplicity over complexity](https://en.wikipedia.org/wiki/Zen_of_Python), [boring over exciting](https://mcfunley.com/choose-boring-technology) and [readability/maintainability over optimised](https://en.wikiquote.org/wiki/Donald_Knuth#Computer_Programming_as_an_Art_(1974)). I'm a fan of [YAGNI - You Aren't Gunna Need It (yet)](https://en.wikipedia.org/wiki/You_aren't_gonna_need_it) which encourages simple designs to satisfy initial business requirements with a view to enhancing later once necessity has been established. My methods may seem counterintuitive, such as [delaying DRYness](https://sandimetz.com/blog/2016/1/20/the-wrong-abstraction), but these approaches have been curated from experience. I also tend to avoid over-commenting code, focusing on the WHY rather than the WHAT and readable, self-documenting code. I find that Python is great for this. Although I find scalable architectures & microservices interesting, the [Monolithic architecture](https://changelog.com/posts/monoliths-are-the-future) with proven frameworks such as Django are my go-to.

I love testing, albeit with a somewhat controversial approach of [preferring integration testing over unit testing](https://kentcdodds.com/blog/write-tests). I find TDD useful but not required. I value coverage but I also recognise that it should be more of a [guide than a goal](https://martinfowler.com/bliki/TestCoverage.html). Testing strategy depends on the circumstances.

Finally, I rather enjoy teaching people (and learning myself) - especially the things that only come with experience.  I value the roles that pair-programming, impromptu discussions and merge requests have in providing an opportunity to convey these experiences.


## Employment History

### Alliance Software: Lead Software Developer

May 2018 - Current

Developing web systems in Python, Django, PostgreSQL & React / Scientific applications in NumPy, Pandas & HPC.

 - Consulting for the Bureau of Meteorology: Working on the AWRA-CMS project modelling landscape waterflow on their in-house supercomputers using scientific programming methods & tools. Includes helping the existing team of developers improve their software development processes & practices.
 - Consulting for previous client: maintaining an existing Django/React stack while also assisting in the crossover to a serverless, microservice, event-sourced architecture while also transitioning to a continuous deployment process with trunk-based development.
 - Setup & run a commercial project while teaching programmers how to work with Django, PostgeSQL, React along with HTML/CSS & friends.
 - Maintainance & further implementation additions to a legacy project with various technologies across different application compoonents (Django templates + Vue.js, DRF + React).  Involved converting a component from Django admin to a custom admin interface.
 - Assisting developers of various experience with technical questions on Django, Python & PostgreSQL.
 - Delivering presentations/writing up tips on Slack on Django, Python & PostgreSQL.

### Common Code: Software Developer (Contractor)

November 2017 - January 2018

Assisted in maintenance of various projects involving Django & Node (Hapi).

### Everproof: Software Developer (Contractor)

July 2017 - November 2017

Started work on the backend Everproof's rework of their verification platform with Django & PostgreSQL.
This involved lengthy design discussions with the CTO and other developers on the database & REST api design.

Some noteworthy features implemented:

- Implementation of organisational trees in a relational database via recursive subqueries
- Database level constraints via https://github.com/shangxiao/django-db-constraints
- Postgres specific database audit trail adapted from Matt Schinckel's [`django-postgres`](https://bitbucket.org/schinckel/django-postgres/src/7792ba7443880cd7ed7fa4418d64524fefbc53e5/postgres/?at=default)

### Common Code: Senior Software Engineer

Sept 2015 - April 2017

Worked on various projects from e-commerce sites to front ends for medical devices.
Most of our projects are managed as agile (or at least striving to maintain some
sense of agility).  Typically we like to use our favourite components: Django with
Postgres (and Celery and/or Redis if needed) and React, Redux, Bootstrap and SASS
(using BEM).

During my time at Common Code I worked as a lead/senior frontend & backend developer
which meant being involved in the technology decision making process & teaching/mentoring
junior developers.

#### Key Technologies:

React, Redux, Angular, Django, Hapi (Node), PostgreSQL, Celery, Redis, GraphQL, Relay, Bootstrap, SASS, BEM

#### Notable Projects

 - Rebuild the client-facting frontend and web server components for the Aussie Farmers Direct eCommerce platform
   using React, Redux, Bootstrap & Django.
 - Frontend development for touchscreen for a medical device.  Implemented with Angular.


### Freelancing, various clients

2011 - 2015

During this period I chose to freelance in order to allow myself some time to try and write
& sell my own products & services.  Although eventually unsuccessful at gaining any notable
traction with my own products, I did have an interesting time working on a few different paid projects.

The projects I worked on were either solo or in a small team.  I was responsible
for being both a business analyst (requirements discovery & management with the client)
and a software developer.

#### Key Technologies:

Used various backend & frontend frameworks, libs & tools including:

 - Python:
   - Django
 - Java:
   - Spring, GWT, Maven, Gradle
 - Databases:
   - PostgreSQL, MySQL, SQL Server, Mongo
 - JavaScript
   - React, Angular, Meteor
 - Mobile:
   - PhoneGap
 - Frontend:
   - Bootstrap 
   - SASS
   
#### Notable Projects

 - "Coles Value Hunter" a proof-of-concept iPhone app for finding on-sale & discounted items for Coles supermarket (store specific).  Written with Angular, Bootstrap & PhoneGap.
 - Implemented improved frontend for searching & browsing Corrs Chambers Westgarth's document management system.  Written in Angular & Bootstrap.

### Baseline Solutions, Senior Software Engineer

2003 - 2011

I worked as a both a full-stack developer and a business analyst responsible for working with
clients to define requirements and to deliver their product.  This role involved developing
MVPs for people with business ideas as well as long term projects to support government based consulting work.

#### Key Technologies:

 - PHP, jQuery, PEAR, Zend Framework

### Adacel, Software Engineer

2000 - 2003

 - Air traffic control systems with Lockheed Martin (ATOP)
 
#### Key Technologies:
 - C on IBM AIX
 - Sybase


## Open Source Contributions

 - Python package to convert functions into CLIs by using its signature to define argparse arguments: https://github.com/shangxiao/bargeparse
 - Python package to make adding table-level database constraints to Django models a little easier: 
https://github.com/shangxiao/django-db-constraints
 - Django: minor documentation updates & freenode/#django assistance (nick: shangxiao)
 - OpenMRS: module contribution
 - PEAR: authored various packages

## Education

 - The University of Melbourne: Bachelor of Engineering (Software) 1998 - 2001

## Example work

All example work can either be found in my GitHub profile, a few selected repositories are listed below:

 - GitHub profile: https://github.com/shangxiao
 - "Djello", A Trello clone written in Django & used as a learning aide to show new programmers how far you can get without using an SPA: https://github.com/shangxiao/djello
 - A typical React/Django example (albeit from 2017): https://github.com/shangxiao/django-shopfront
