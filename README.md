# Liquimap

Liquimap is an EMF-based domain-specific language for user experience (UX) mapping.

## Installation

-  Install OpenJDK 11 (LTS) - HotSpot from https://adoptopenjdk.net/

- Install the Epsilon Eclipse distribution, following the instructions in https://www.eclipse.org/epsilon/download/

- Clone this repository and import the `liquimap` Eclipse project, as instructed in section 9.2 of https://www.vogella.com/tutorials/Eclipse/article.html

- In the `Project Explorer` view of Eclipse, locate and right-click on the `liquimap.emf` file and click `Register EPackages`

- Open the `Picto` view through Eclipse’s `Window` → `Show View` → `Other...` menu

- Double-click on the `FinancialServices.flexmi` file in the `Project Explorer` view to open it. Once the Flexmi file is opened, your Eclipse should look like this

![](doc/eclipse.png)

## Gallery

Below are examples of diagrams produced by Liquimap.

### Service Blueprints

#### Global Service Blueprint

![participant-blueprint-liquimap](doc/blueprint-liquimap.png)

#### Service Blueprint by Participant

![participant-blueprint-liquimap](doc/participant-blueprint-liquimap.png)

#### Service Blueprint by Stage

![stage-blueprint-liquimap](doc/stage-blueprint-liquimap.png)

### User Experience Flow Diagrams

#### Global User Experience Flow Diagram

![userflow-liquimap](doc/userflow-liquimap.png)

#### User Experience Flow Diagram by Stage

![stage-userflow-liquimap](doc/stage-userflow-liquimap.png)

### User Journey diagrams

#### End-to-end User Journey Diagram

![userjourney-liquimap](doc/userjourney-liquimap.png)

#### User Journey Diagram by Stage

![stage-userjourney-liquimap](doc/stage-userjourney-liquimap.png)

### Sankey Diagram

![](doc/sankey-liquimap.png)
