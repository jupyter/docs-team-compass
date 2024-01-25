# Jupyter Subprojects

Project Jupyter is composed by many subprojects, each focusing on different aspects of the Jupyter ecosystem. 
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


## Jupyter Project Subprojects (categorized)

### Applications and Interfaces
- IPython
- Jupyter Notebook
- JupyterHub
- JupyterLab

- Binder/BinderHub
- Voilà

### Server and Gateway
- Jupyter Server
- Enterprise Gateway
- Kernel Gateway

- Jupyter Console

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


-----
## High-Level Overview of Jupyter Subprojects Dependency Diagram

### Applications and Interfaces
- **JupyterLab**: Depends on Jupyter Server, Jupyter Widgets, IPykernel, and nbformat.
- **Jupyter Notebook**: Depends on Jupyter Server, nbformat, nbconvert.
- **JupyterHub**: Integrates with Binder, JupyterLab, Jupyter Notebook.
- **Binder/BinderHub**: Relies on JupyterHub, JupyterLab, Jupyter Notebook.

### Server and Gateway
- **Jupyter Server**: Core server for Jupyter applications. Dependencies include nbformat, Jupyter Client.
- **Enterprise Gateway**: Extends Jupyter Server for enterprise needs.
- **Kernel Gateway**: Simplifies the management of Jupyter kernels.

### Widgets and Interactive Tools
- **Jupyter Widgets**: Integrated with JupyterLab and Jupyter Notebook.

### Kernels
- **IPykernel**: Primary Python kernel, based on IPython.
- **jupyter-xeus**: Set of Jupyter kernels.
- Other Kernels: Various language kernels connecting to Jupyter interfaces.

### Foundations and Standards
- **Jupyter Client**: Used by Jupyter Server and various kernels.
- **nbformat**: Fundamental for Jupyter Notebook, JupyterLab, nbviewer, nbconvert.
- **Jupyter Core**: Basic components used across Jupyter applications.
- **Terminado**, **nbclient**, **Telemetry**, **Traitlets**: Utilities and libraries supporting various Jupyter components.
- **Jupyter Console**: An interface using IPython kernel.
- **Docker Stacks**: Containerized Jupyter applications.

### Conversion and Rendering Tools
- **nbconvert**: Converts Jupyter Notebooks to other formats, dependent on nbformat.
- **nbviewer**: Renders notebooks as static web pages, dependent on nbformat.

### Development and Testing Tools
- **nbdime**: Diffing and merging for notebooks, dependent on nbformat.
- **nbgrader**: Assignment creation and grading, dependent on Jupyter Notebook.
- **ipyparallel**: Parallel computing in Python, extends IPython.
- **QtConsole**: A Qt-based console interface for Jupyter kernels.
-----

