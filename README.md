# SiriusWeb Manuals
## Noted

This document is made for people who are new to Sirius Web and modelling project. More detailed information and guideline are given in the [Obeo offical documentation](http://docs.obeostudio.com).

## Getting Started

[Sirius Web](https://www.eclipse.org/sirius/sirius-web.html) is an open-source low-code platform to define custom web applications supporting your specific visual languages. It enables users to easily create and deploy graphical studios to the web.

### 1. Sign up

Before generating your own modelling project, you are required to ask for an Obeo account.

Obeo account is avaliable for every one.

To ask for an Obeo account, you should go to the [Signup page](https://demo.obeostudio.com/signup) and fill the form to provide required personal information (e.g, Username, Password...).

### 2. Log in

Head to the [Login page](https://demo.obeostudio.com/login) and log in with your Username and Password. Everyone with account is allowed to log out through clicking on the avatar on the up right corner on any Obeo platform page.

### 3. Create New Custom Metamodel

This section is going to introduce how to create the metamodel for the whole project.

Metamodel is the model of a series models. A model is an abstraction of a domain in the real world; a metamodel is yet another abstraction, highlighting properties of the model itself, and is widely used to represent the collection of concepts within a certain domain.

Therefore, designing and realising the metamodel are prior for the entire project.

#### 3.1. Create New Project

To start your project, you should first create a new studio definition projec.

In Obeo platform, you are provided with several official project templates, but in this manual, we are going to introduce how to create your own modeling project. So, we recommend you to create a new blank project with no initial content:

+ Naviagate to the [Home page](https://demo.obeostudio.com/projects).
+ Click on the **'+ Blank project'**.

<img src="./Image/ObeoPlatform.png" width = "800" height = "500"/> 

+ Enter the project name.
+ Choose visualbility of your project.
+ Create your new project.

<img src="./Image/CreateNewProject.png" width = "800" height = "500"/> 

You will be redirected to the newly created project. It will be initially empty; see following sections to learn how to use the project editor view to create your own models and representations.

#### 3.2. Create Your Custom Domain 

To create your domain:

+ Open your studio definition project.

+ In the *Create a new Model* section, choose *Domain* to create a new one.

<img src="./Image/ProjectWorkshop.png" width = "800" height = "500"/>

+ In the *Create a new Representation* section, choose *Domain* representation to visualise the Custom Domain.

<img src="./Image/NewDomain.png" width = "800" height = "500"/>

+ In the newly-created representation panel, you are allowed to add new elements for the Domain as you wish.

<img src="./Image/NewMetaModel.png" width = "800" height = "500"/>

The Domain is the root element which identifies your domain. Its only attribute is a name, which should be globally unique on a particular Obeo Studio server, and not contain any space or special character (technically, the name should be a valid Java identifier).

#### 3.3. Add new Elements

Inside a domain you can create *Entities* which represent the concepts in your domain and are similar to classes in Java, UML or Ecore. 

An *Entity* has a name, which should be unique inside a given domain, and follow that same rules as for domains, and zero of more super types, which can be used to inherit the attributes and relations from other entities. Besides, an entity can be abstract, meaning no concrete instances can be created from it. Such entities are only useful to be shared as super types for other (concrete) entities.

To create a new *Entity*:

+ Hang your mouse over the panel, then there will be a tool bar, in which you can choose to add a new *Entity*.
+ In Details box, you can modify the name and other features of the *Entity*.

<img src="./Image/NewEntity.png" width = "800" height = "500"/>

Inside an *Entity* you can create *Attributes* that describe their characteristics, and *Relations* from that entity to another one (or itself).

An *Attribute* is defined by a name, type and whether it is optional and many-valued. Name should should be unique among all the attributes and relations inside a given entity, including the inherited ones. The current system only support types of: *STRING, BOOLEAN and NUMBER*.

A *Relation* is defined by unique name and type as well as whether it is a containment relation or not.

To create a new *Attribute/Relation*:

+ Click on the Entity, there will be a tool bar, in which you can add a new attribute or relation to this entity.

<img src="./Image/SampleMetamodel.png" width = "800" height = "500"/>
<img src="./Image/sampleModel.png" width = "800" height = "500"/>

### 4. Generate Model

To generate a model based on the existing domain:

+ Create new description project
  + On the Home page, create a blank project
  + Rename the project
  + Choose visualbility

+ Create a new Model
  + Click on the *Other*

+ Create a new root *Object*
  + Create new *Object* under the *Other* model
  + Choose existing *Domain* template
  + Choose root *Object* type

<img src="./Image/creaeteRootOb.png" width = "800" height = "500"/>

+ Create new child *Object*
  + Create a new *Object* under *root Object*
  + Choose Object type

<img src="./Image/createOb.png" width = "800" height = "500"/>

+ Edit *Object* details

<img src="./Image/editOb.png" width = "800" height = "500"/>

### 5. Generate View
5.1. Go to previsouly-built custom desctiption project
5.2. Create new view
5.3. Create new diagram description
5.4. Add node objects
5.5. Add edge objects
5.6. Go to model project
5.7. Create new representation

### 6. Personalisation

Personalise visual notations
