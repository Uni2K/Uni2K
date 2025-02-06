Hallo! My name is Jan 👋
===========================================================================================================================

I am a Berlin based software developer who enjoys designing and developing web applications, desktop software and Android apps. 
Below you will find an overview of selected projects.

------------

## Projects

### <a href="judict.eu">judict.eu</a>

Developed over a period of 4 years, judict.eu is a research tool for European financial supervisory law. The technical
framework is based on Next.js 15 in the frontend and several Go servers hosted on AWS, which together form a
microservice architecture.
Another aspect is the daily retrieval of legal documents, which is realized via an independent Go server. The raw data
is obtained via a large number of web scrapers and then evaluated and condensed using natural language processing (NLP)
algorithms.
The entire frontend design, illustrations, compositions and layouts have been made exclusively by me using FIGMA,
Illustrator and PS.

In detail, the following is used:

* <b>Frontend</b>: Next.js 15 with TS + TailwindCSS, JUnit, Cypress, PM2
* <b>Backend</b>: Go with Gin REST API, gRPC API for microservice communication, PostgreSQL, SPARQL API for data
  retrieval
* <b>DevOps/Misc</b>: Docker, AWS EC2, Route53, Load Balancer, RDS
  
<img alt="landing page" src="/assets/judict1.png">

| <img alt="landing page" src="/assets/judict4.png"> | <img alt="toc page" src="/assets/judict2.png"> | <img alt="article page" src="/assets/judict3.png"> |
|----------------------------------------------------|------------------------------------------------|----------------------------------------------------|

------

### beA-to-email

Full Stack development of desktop Java software based on the "besonderes elektronisches Anwaltspostfach" (beA). The aim
of the software is to make the beA, which serves as a kind of message portal for lawyers, available via normal e-mail
clients. The focus of the development was therefore on the implementation of various e-mail protocols and the conversion
of encrypted messages.
Due to the strict requirements for the use of the beA, only Java was considered as a programming language. The GUI was
thus developed using JavaFX close to the customer's requirements.

In detail, the following is used:

* <b>Frontend</b>: Java, JavaFX, Spring, Maven, JUnit
* <b>Backend</b>:  Node.js, MySQL, Express.js, LDAP, IMAPS, SMTPS Server
* <b>DevOps/Misc</b>: Fully automated test pipelines, Update-Bootstrapping routine, cross-platforming on Windows,
  Linux & MacOS

| <img alt="landing page" src="/assets/beA1.png"> | <img alt="toc page" src="/assets/beA2.png"> | <img alt="toc page" src="/assets/beA3.png"> |
|-------------------------------------------------|---------------------------------------------|---------------------------------------------|

----

### Multiple Freelance projects

Several small to medium-sized freelance projects were realized in the field of web development using Next.js and
relation databases. Since many of those are closed-source, they are not be named here.

One open source project is for example: <a href="qblitz.de">qblitz.de</a>

| <img alt="landing page" src="/assets/qblitz1.png"> | <img alt="toc page" src="/assets/qblitz2.png"> | <img alt="article page" src="/assets/qblitz3.png"> |
|----------------------------------------------------|------------------------------------------------|----------------------------------------------------|

------
### Android Apps

Over a period of 4 years, several lifestyle-based Android apps were developed using Java and later Kotlin. The apps
reached a total of more than 4 million individual users and were provided with regular security and content updates over
the years. Today, most of the apps are outdated and cannot be used anymore.

* <a href="https://play.google.com/store/apps/details?id=com.desireapps.profilbilder_erstellen_bearbeiten_dp">PicMine -
  Profilbilder erstellen Bilder bearbeiten</a>
* <a href="https://play.google.com/store/apps/details?id=com.desireapps.statussprueche">Status Sprüche & Zitate to
  go</a>
* <a href="https://play.google.com/store/apps/details?id=wap.desireapps.com.whatsappprofilbilder">Profile pictures for
  WhatsApp</a>
* Wallpapers for chats

| <img alt="landing page" src="/assets/picmine1.png"> | <img alt="toc page" src="/assets/picmine2.png"> | <img alt="article page" src="/assets/picmine3.png"> |
|-----------------------------------------------------|-------------------------------------------------|-----------------------------------------------------|
| <img alt="landing page" src="/assets/wss1.png">     | <img alt="toc page" src="/assets/core1.png">    | <img alt="article page" src="/assets/swag1.png">    |
------
### <a href="https://github.com/Uni2K/RootReader">RootReader & RootAnalysis</a>

C++ and Bash CLI data analysis based on the CERN ROOT framework. The created software suite is able to use advanced
integration, multi-threading, curve-fitting and IO reading to process terabytes of raw binary data into readable data.
<img alt="landing page" src="/assets/root1.png">

           