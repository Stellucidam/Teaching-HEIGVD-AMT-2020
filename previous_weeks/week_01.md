# Welcome to AMT 2020



## Week 1

* **Objectives**

  * Be able to explain what a "layered" or "tiered" architecture is.
  * Be able to explain how Java EE is one of the platforms for building multi-tiered architectures.
  * Be able to explain what the MVC design pattern means in web development and why it is useful.
  * Be able to implement the MVC design pattern with selected Java EE APIs (Servlets, JSPs, JSTL) 
  * Be able to explain what Docker Compose is and how it complements Docker

* **Project**

  * Get started with the ~~Stack Over~~(Flow) project
  * *Understand the constraints for project 1. We will not use Spring Boot. We will not implement a REST API. We will not use a Javascript framework such as Vue.js or React in the front-end. We will not immediately use JPA or another ORM. This will come later.*
  * Create mockups for your version of the application
  * Create Servlets and JSPs for
  * Investigate [CodeceptJS](https://codecept.io/) for automated user acceptance testing

* **The Question of the Week**: 

  * *Pour développer une application avec la Servlet API, il est nécessaire d'utiliser un serveur d'application Java EE (maintenant Jakarta EE). Donnez votre avis sur cette proposition et justifiez vos arguments.*

  * *Ma réponse :* Je ne pense pas qu'il soit impératif d'avoir un serveur d'application **Java EE**. Les servlets sont conçus pour pouvoir être utilisés avec un serveur quel que soit son type.

  * *Correction :* 
  Applications mt. Il existe plsr plates-formes pour développer des application de ce type.
    * Servlet API :exemple de code
    * Serveur d'application : exemple de serveurs
    * Java EE : perspective historique, ensemble de spécifications
    
  Non, ce n'est pas une condition stricte. Un logiciel peut implémenter une partie des APIs spécifiées dans Java EE. Dans ce cas, il peut ne pas être certifié en tant que serveur d'application conforme à la norme cpmpléte. Au sens stricte, ce n'est pas un serveur d'application.
  Tomcat est un exemple de serveur qui permet de déployer des servlets et des JSPs, mais qui n'est pas un serveur Java EE certifié.


* **Repos**

  * Here is the repo for the first Java EE demo: https://github.com/SoftEng-HEIGVD/Teaching-HEIGVD-AMT-Discovery

* **Notes about the YouTube Playlist:**

  * I have added 4 videos (Bootcamp 1.1 - 1.4) with explanations and demonstrations about Java EE (what is an application server? how do I deploy a .war file into an application server?). I have also added 5 videos (Bootcamp 2.1 - 2.6). *You are not supposed to follow the instructions step-by-step*, because the videos have been produced when I was still using Netbeans. However, because the core of the Servlet API is stable, the concepts and code that you see in the videos are still valid.




