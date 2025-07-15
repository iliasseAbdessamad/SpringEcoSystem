# Spring (C'est quoi réelement ?)

<br />

**Spring** est un écosystème complet et modulaire, il se compose de **Spring Framework** et **d'autres projets Spring (Spring Security, Spring Data...)**.

<br /> 

L’objectif de cette recherche est d’explorer en profondeur le projet **Spring Framework**, afin d’en comprendre son architecture modulaire, le rôle de chaque module, et ces mécanismes internes qui en font un pilier du développement d’applications Java modernes.

<br />

🔹 1. **Spring Framework (le cœur)**

<br />
Il fourni la base pour développer des applications java (qui pevent (ou non) intégrer des projets Spring complémentaires), il founit nottament :
<ul>
<li>
<a href="./springCore/coreTech/README.md">Core technologies: </a>
Inversion de controle et l'injection de dépendence, 
la gestion des évenements, 
la gestion de ressources, 
l'internationalisation (i18n), 
la validation et le data binding, 
la conversion des types, 
Spring Expression Language (SpEL), 
Aspect Oriented Programing AOP.
</li>
<li>
<a href="./springCore/dataAccess/README.md">Data Access: </a>
les transactions, 
le support de Data Access Object (DAO), 
JDBC  (pour l'accès aux bases de données), 
ORM (Object Relational Mapping), 
Marshalling XML.
</li>
<li>
<a href="./springCore/web/README.md">Spring MVC et Spring WebFlux web frameworks: </a> 
Application web, Rest ...
</li>
<li>
<a href="./springCore/testing/README.md">Testing: </a>
mock objects, TestContext framework, Spring MVC Test, WebTestClient.
</li>
<li>
<a href="./springCore/integration/README.md">Integration: </a>
remoting, JMS, JCA, JMX, email, tasks, scheduling, cache and observability.
</li>
</ul>


<br />
<br />


🔹 2. Projets Spring complémentaires (autonomes, mais intégrés) : 

<br />

Voici les projets Spring les plus connus : 
<br />
<table>
<thead>
<tr>
<th>Projet</th>
<th>Déscription</th>
</tr>
</thead>
<tbody>

<tr>
<td>Spring Security</td>
<td>Authentification, autorisation, sécurité web/API</td>
</tr>

<tr>
<td>Spring Data</td>
<td>Accès simplifié aux bases de données (JPA, MongoDB, Redis, etc.)</td>
</tr>

<tr>
<td>Spring Batch</td>
<td>Traitement de gros volumes de données par lots</td>
</tr>

<tr>
<td>Spring WebFlux</td>
<td>Programmation réactive (basée sur Reactor, non bloquante)</td>
</tr>

<tr>
<td>Spring Cloud</td>
<td>Développement d’architectures microservices cloud-ready</td>
</tr>

<tr>
<td>Spring Integration</td>
<td>intégration de systèmes (messagerie, workflows, ETL)</td>
</tr>

<tr>
<td>Spring Boot</td>
<td>Démarrage ultra-rapide des applis Spring avec configuration auto</td>
</tr>

<tr>
<td>Spring AI</td>
<td>
Pour interagir facilement avec des modèles d'IA générative (comme OpenAI, Azure OpenAI, Hugging Face, Ollama, Mistral, etc.) 
dans les applications Spring 
</td>
</tr>
</tbody>
</table>