# SiriusWeb Manuals
Create your custom Domain Specific Modelling Language (DSML) through SiriusWeb.
# Noted
This document is made for supporting people who are new to SiriusWeb and DSML. More detailed information and guideline are given in the [Obeo offical documentation](http://docs.obeostudio.com).
# Getting Started
[SiriusWeb](https://www.eclipse.org/sirius/sirius-web.html) is a open-source low-code platform to define custom web applications supporting your DMSLs.
## Environment
```Bash
# MacOS Ventura 13.2.1
# Safari 16.3
```
## 1. Sign up
Before generating your own modelling project, you are required to ask for an Obeo account, which is avaliable for every one. To ask for an Obeo account, you should go to the [Signup page](https://demo.obeostudio.com/signup) and fill the form to provide required personal information (e.g, Username, Password...).
## Log in
Head to the [Login page](https://demo.obeostudio.com/login) and log in with your Username and Password.
## Create New Definition Project
To start your project, you should first create a new studio definition project.
+ Naviagate to the [Home page](https://demo.obeostudio.com/projects).
+ Click on the *'+ Blank project'*.

<img src="./Image/ObeoPlatform.png" width = "800" height = "500"/> 

+ Enter the project name.
+ Choose visualbility of your project.
+ Click on *Create*.

<img src="./Image/CreateNewProject.png" width = "800" height = "500"/> 

Then you will be redirected to the newly created project. It will be initially empty; see following sections to learn how to use the project editor view to create your own models and representations.
## Create New Domain 
To create a new domain:
+ Open your studio definition project.
+ Underneath *Create a new Model* , choose *Domain* to create a new one.

<img src="./Image/ProjectWorkshop.png" width = "800" height = "500"/>

+ Underneath *Create a new Representation*, choose *Domain* to visualise new domain.

<img src="./Image/NewDomain.png" width = "800" height = "500"/>

**Domain* is the root element which identifies your domain. Its only attribute is a name, which should be globally unique on a particular Obeo Studio server, and not contain any space or special character.

## Add New Elements
Inside a domain you can create *Entities* which represent the concepts in your domain. 
An *Entity* has a name, and zero of more super types. Besides, an *Entity* can be abstract, meaning no concrete instances can be created from it.
To create a new *Entity*:

+ Hang your mouse over the panel to activate the tool bar, in which you can add a new *Entity*.

<img src="./Image/NewMetaModel.png" width = "800" height = "500"/>

+ In right content box, you can modify the *Entity*.

<img src="./Image/NewEntity.png" width = "800" height = "500"/>

Inside an *Entity* you can create *Attributes* and *Relations*.

```bash
# Attribute is defined by an unique name, type and whether it is optional and many-valued 
# Relation is defined by unique name, type and whether it is a containment relation or not
```


To create a new *Attribute/Relation*:

+ Click on the *Entity* to activate the tool bar, in which you can add new attributes/relations to the *Entity*.

<img src="./Image/SampleMetamodel.png" width = "800" height = "500"/>

**DSML Sample**

<img src="./Image/sampleModel.png" width = "800" height = "500"/>

## Apply Custom DSML
Generate a new model based on the previously defined DSML:
+ Create a new definition project
  + On the [Home page](https://demo.obeostudio.com/projects), create a blank project
  + Name the project
  + Choose visualbility
+ Create a new Model
  + Underneath *Create a new Model*, click on the *Other*
  + You can see a new domain named *New* in the left content box
+ Create a new root *Object* for *New*
  + Create new *Object* under *New*
  + Choose existing DSML
  + Choose root *Object* type
  

<img src="./Image/creaeteRootOb.png" width = "800" height = "500"/>

+ Create new child *Objects*
  + Create a new *Object* under the *root Object*
  + Choose *Object* type
  + Edit *Object* details in right content box
  

<img src="./Image/createOb.png" width = "800" height = "500"/>

<img src="./Image/editOb.png" width = "800" height = "500"/>

## Generate View for DSML
5.1. Go to previsouly-built custom desctiption project
5.2. Create new view
5.3. Create new diagram description
5.4. Add node objects
5.5. Add edge objects
5.6. Go to model project
5.7. Create new representation
## Personalisation
Personalise visual notations
