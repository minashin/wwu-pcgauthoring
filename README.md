# PCG Authoring Tool

```diff
- All files have been moved to the school repository. This repo only has sample codes.
```
This repository is for my undergraduate research and a senior project. The Procedural Content Generation system is for creating content procedurally for a virtual environment. As part of this system, PCG Authoring will allow a user to input parameters used during the content generation process.

## Repository Structure
```bash
.
|-- Docs                            # Documentation files 
|-- PCGAuthoring                    # Web application for Authoring
|-- PCGAuthoring_Unity              # Source files for Unity side
```

## Project Status
This project is currently in development. Users can manage rooms and items easily through the Web UI, such as adding, updating, deleting, etc. For seamless integration with the existing generate application in Unity, the ASP.NET Core MVC framework was selected to build web service. Authoring tool will be extended to cover the whole house environment and the implementation to communicate between the web app and the unity app is in progress. Here are some future tasks planned.

#### 1. Web Application Side
- Communication between web and unity application using remote database
- More friendly UI/UX
- Extension to cover the whole house environment

#### 2. Unity Application Side
- Communication between web and unity application using remote database
- Functionality to create proper object based on parameters and trigger genenration process


## UML Diagrams
<div>
    <img width="40%" src="https://github.com/minashin/pcg-authoring/blob/master/docs/screenshot/uml.jpg">
    <img width="40%" src="https://github.com/minashin/pcg-authoring/blob/master/docs/screenshot/dbcommunication.png">
    <img width="40%" src="https://github.com/minashin/pcg-authoring/blob/master/docs/screenshot/dbtables.png">
    
</div>


## Screenshots
<div>
    <img width="45%" src="https://github.com/minashin/pcg-authoring/blob/master/docs/screenshot/create.png">
    <img width="45%" src="https://github.com/minashin/pcg-authoring/blob/master/docs/screenshot/detail.png">
</div>


## Research Poster
<div>
    <img src="https://github.com/minashin/pcg-authoring/blob/master/docs/screenshot/poster.png">
</div>


## Tech/Framework used
- ASP.NET Core MVC
- Entity Framework
- Unity Engine
