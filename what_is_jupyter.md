# What is Jupyter

[jupyter.org/about]: https://jupyter.org/about
[subprojects]: https://jupyter.org/governance/list_of_subprojects.html

There is a lot in the name *Jupyter*; the project, the software, the notebooks.
It is not unusual to feel confused with the many terms around "Jupyter".
But confusion is never nice so let's try to clarify them.

If you are completely new to *Jupyter*, the [`jupyter.org/about`][jupyter.org/about]
page is good reading for an overview of the **project**.
Completely open-source, the software developed by the project grew
into many pieces; those *pieces* (i.e. Notebook, Lab, Hub)
are developed by the different Jupyter [**subprojects**][subprojects]

Let's review Jupyter and its components to
better understand the common terms referring to the *software*.


## *Notebook* vs *notebook*

Let's start from the most popular concept, what most of the discussions
about *Jupyter* talk about: the "notebook".

"Notebook" has two meanings: the notebook file format -- the `.ipynb` files --,
and the graphical user interface -- the application -- used to create
our notebooks.


## Notebook and Lab

There are two graphical user interface (software) to edit notebooks:
Jupyter-Notebook and Jupyter-Lab.

As presented in the [*History of Jupyter*](history_of_jupyter.md), Jupyter-Lab
is an evolution of Jupyter-Notebook to provide a more concise interface to
the many activities in that environment such as files management, simultaneous
view of multiple notebooks or parallel views of the notebook.

The Notebook keeps providing the classic interface, that may be advantageous
for some communities.

## Jupyter Hub

To many users not used to the management of software systems,
setting up a Jupyter Notebook or Lab may be an obstacle to the final goal,
that of data analysis.
Furthermore, a it is desirable in many scenarios to have a common software
setup shared among a team of data analists; a multi-user system.

Jupyter-Hub is a multi-user Jupyter system, responsible for managing
multiple Jupyter Notebook or Lab servers.

## Jupyter Server

In the previous sections we learned the difference -- or similarity -- of
Jupyter Notebook and Jupyter Lab, and the role of Jupyter Hub in managing
those *servers*.

The slightly different user interfaces provided by Notebook and Lab are
backed by the same engine: the Jupyter Server.
Jupyter Server is responsible for rendering the (`.ipynb`) notebooks,
managing configurations, and integrating the extensions.

## Kernels

Kernels are at the very core of the Jupyter software ecosystem, they are
responsible for interpreting the code cells in a notebook.
When a Jupyter application -- Notebook or Lab, for instance -- is installed,
a Python kernel is provided by default.
But, as you may already know, other programming languages can be used in
notebooks, such as R and Julia, provided the corresponding kernels are
installed.

Kernels are the abstraction layer between the Jupyter application and
different programming languages.

## IPython

If you use Python, you know you can run Python code directly in the command-line
interface through the `python` interactive interpreter (aka, Python *shell*).

IPython is the Python shell with super-powers.
IPython is where Jupyter started (see [History of Jupyter](history_of_jupyter.md)),
a command-line interface with high-level functionalities such as the
[*magic commands*](https://ipython.readthedocs.io/en/stable/interactive/magics.html)
(available in Jupyter Notebook and Lab).

As a matter of fact, the extension used for Jupyter notebook files, `ipynb`,
is reminiscent from when Jupyter was simply IPython Notebooks.
Besides the files extension and magic commands, IPython is very much alive and integrated
in the Jupyter ecosystem through `ipykernel`, the Python kernel engine.
(To be more precise and technically correct, the magic commands are
part of ipykernel's job.)
