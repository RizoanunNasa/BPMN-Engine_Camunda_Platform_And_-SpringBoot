# BPMN Implementation of the Users Life Cycle process

Main target of the project is to demonstrate the advantages of a BPMN Engine in the enterprise to carry on and track most of the repetitive tasks and processes happening in the organization.

The scope of this section of the project is:
* Model the actual interactions (as described in this document) between the involved groups of people in the “User Life Cycle Process” in a BPMN 2.0 format, including information moving between involved groups of people.
* Propose one or more versions of the model with some automation included, meaning with some Manual Task converted to Service Tasks, explaining how the process should change, if needed, and how the automated task should be implemented.
* Optionally providing one or more implementations of some of the service tasks identified by the optimization step. Implementations should focus on the Active Directory system first, then moving on the Intranet System.

## Get Started <a name="get_started"/>

* First of all, make sure to have [Camunda](https://camunda.com/download/) running.
<img width="1788" alt="Screenshot 2022-06-18 at 12 00 46" src="https://user-images.githubusercontent.com/45004856/174432801-f2d51aa2-463f-408e-9f01-9b4c27af5c31.png">

* After that, make sure to have at least one process deployed on the Camunda Platform Engine. 

* Then go to the Cockpit link [CockPit-Processes](http://localhost:8080/camunda/app/cockpit/default/#/processes) and verify that the version of the process is correct by clicking on it.

# Tools and processes.
BPMN diagrams and implementation should be produced using the Camunda platform, comprising the Camunda Engine Community Edition and the Camunda Modeler.

Examples of the messages exchanged between the systems will be provided, and all enterprise systems interactions, will be represented in the form of c# interfaces, that can be either implemented on a test system or entirely mocked. Realization of the project can be executed remotely, outside the enterprise but regular meetings to analyze project progresses are required, every two weeks.

An email channel with the project tutors inside the company will be available at any time.


Now the process is correctly running and the external task client is subscribed to it's relative Service Task.

## Technologies <a name="technologies"/>

1. [Camunda Platform 7](https://camunda.com/) <a name="platform"/>

<img src="https://camunda.com/wp-content/uploads/2021/06/Organic-Social-Previews-Camunda-Website_1200x627_Camunda-Platform.png" alt="SpringBoot" width="300" height="150" />

2. [SpringBoot](https://spring.io/projects/spring-boot) <a name="springboot"/>

<img src="https://spring.io/images/spring-logo-9146a4d3298760c2e7e49595184e1975.svg" alt="SpringBoot" width="300" height="100" />
3. [Apache Tomcat](https://tomcat.apache.org/) <a name="Apache Tomcat"/>
