# What is Jupyter

> Jupyter "notebook" is a term used to express both: the *file* with containing the notebook
> code and the classic *application* (Jupyter-Notebook) for creating and running those files.
> There are other applications providing similar functionalities, Jupyter-Lab is one of them.

We can group the subprojects in the following categories. (The subprojects are described below)

### Applications and Interfaces
- Jupyter Notebook
- JupyterLab
  - JupyterHub
- Binder
  - BinderHub
- Voilà
- IPython

### Server and Gateway
- Jupyter Server
  - Jupyter Console
- Enterprise Gateway
- Kernel Gateway

### Widgets and Interactive Tools
- Jupyter Widgets
- QtConsole

### Kernels and Computational Engines
- Jupyter Kernels
- jupyter-xeus
- IPykernel
- ipyparallel

### Security and Accessibility
- Jupyter Security
- Jupyter Accessibility

### Foundations and Standards
- Jupyter Notebook Format (nbformat)
- Jupyter Core
- Jupyter Client
- Jupyter-packaging
- Terminado
- Telemetry
- Traitlets

### NB tools
- nbclient
- nbconvert
- nbdime
- nbgrader
- nbviewer

### Miscellaneous
- JEPs repo (Jupyter Enhancement Proposals)
- Docker stacks


# Jupyter Subprojects

Project Jupyter is composed by many subprojects, each subproject focuses on different components
or aspects of the Jupyter ecosystem.
Subprojects differ in size, activity, and governance.

Jupyter products span from the definition of the Notebook *file 
format* all the way to multi-user deployment of Notebook or Lab *applications*.
Subprojects will take ownership of the different components or take over broader aspects such
as accessibility and security.

Regarding their governance, some subprojects have their own Council and SSC (Software Steering Committee), and the others are governed directly by the Project SSC.

The major subprojects with their own formal Subproject Council are:

- JupyterLab: An extensible environment for interactive and reproducible computing.
- JupyterHub and Binder: Focused on multi-user capabilities and sharing of interactive notebooks.
  * JupyterHub: Multi-user version of the notebook.
  * Binder: Allows turning a Git repository into a collection of interactive notebooks.
  * BinderHub: Related to Binder, focusing on the deployment aspect.
- Voilà: Turns Jupyter notebooks into interactive web applications.
- Jupyter Server: Provides the backend (core services, APIs, and REST endpoints) for Jupyter web applications.
  * Enterprise Gateway: Enhances Jupyter Server for enterprise needs.
  * Kernel Gateway: Simplifies the process of running Jupyter kernels.
- Jupyter Widgets: Interactive widgets for the Jupyter notebook.
- Jupyter Notebook: The traditional web application for creating and sharing Jupyter notebooks.
- Jupyter Kernels: Focused on the computational engines for various programming languages.
- jupyter-xeus: A collection of Jupyter kernels.
- IPykernel: The IPython kernel for Jupyter.
- IPython: Provides a rich toolkit to help you make the most out of using Python interactively.
- Jupyter Foundations and Standards: Focuses on foundational components and standards across Jupyter projects.
- Jupyter Security: Addresses security-related aspects of Jupyter projects.
- Jupyter Accessibility: Dedicated to ensuring Jupyter projects are accessible to all users.

Smaller, less active subprojects include:

- nbdime: Tools for diffing and merging Jupyter notebooks.
- nbgrader: A system for assigning and grading Jupyter notebooks.
- nbviewer: Shares Jupyter notebooks as static HTML on the web.
- ipyparallel: A package for parallel and distributed computing in Python using IPython.
- QtConsole: A rich Qt-based console for working with Jupyter kernels, maintained by the Spyder team.

Additionally, there are various other repositories that form part of the broader Jupyter ecosystem, including services like Binder and nbviewer. These services are generally managed by working groups that report to the Executive Council of Project Jupyter.

For a complete and detailed list, you can refer to the official Jupyter documentation and the Jupyter governance repository on GitHub.

## Official list diagram

- https://jupyter.org/governance/list_of_subprojects.html

## Jupyter Project Subprojects (website)

### Official Subprojects with SSC Representation

- **JupyterLab**
- **JupyterHub and Binder**
  - JupyterHub
  - Binder
  - BinderHub
- **Voilà**
- **Jupyter Server**
  - Jupyter Server
  - Enterprise Gateway
  - Kernel Gateway
- **Jupyter Widgets**
- **Jupyter Notebook**
- **Jupyter Kernels**
  - jupyter-xeus
  - IPykernel
  - IPython
- **Jupyter Foundations and Standards**
- **Jupyter Security**
- **Jupyter Accessibility**

### Official Subprojects without SSC Representation

- nbdime (jupyter/nbdime)
- nbgrader (jupyter/nbgrader)
- nbviewer (jupyter/nbviewer)
- ipyparallel (ipython/ipyparallel)
- QtConsole (jupyter/qtconsole)

### Part of Jupyter Foundations and Standards

- Jupyter Client (jupyter/jupyter_client)
- Jupyter Notebook Format (jupyter/nbformat)
- JEPs repo (jupyter/enhancement-proposals)
- nbconvert (jupyter/nbconvert)
- Jupyter Core (jupyter/jupyter_core)
- Jupyter-packaging (jupyter/jupyter-packaging)
- Terminado (jupyter/terminado)
- nbclient (jupyter/nbclient)
- Telemetry (jupyter/telemetry)
- Traitlets (ipython/traitlets)
- Jupyter Console (jupyter/jupyter_console)
- Docker stacks (jupyter/docker-stacks)


