# History of Jupyter

It's early 2000's -- Python 2 was still fresh, SciPy had just had its debut,
Matplotlib was under preparation: the IPython went through its first release.
That is when the history of Jupyter starts.

Let's go through the timeline development of the project to understand
*why* and *when* the different components of Jupyter came to be;
from a tunned-up Python shell, to language-agnostic code notebooks,
to extendable data analysis web interfaces.

## **IPython**

> 2001

First released in 2001, IPython -- short for *Interactive Python* --
started from a set of enhancements to the basic interactive Python shell
(ref: ipython-paper, 2007).

During the following 13 years, IPython evolved in the open and established
many of the fundamental components we use today in our workflows,
such as the notebook document format.

### The Big Split

> 2014

Given the growth experienced by IPython in those years, it was decided
in 2014 that spliting the then monolithic repository was necessary
not only to improve maintenance but also to allow the largely independent
components of that code base to be used and evolve independetly
(ref: big-split, 2015).

The big split generated many repositories, most of them would be the seeds
of the Jupyter's Github organization:

- [Jupyter-Notebook](https://github.com/jupyter/notebook)
- [Jupyter-Console](https://github.com/jupyter/jupyter_console)
- [Jupyter-Client](https://github.com/jupyter/jupyter_client)
- [NbConvert](https://github.com/jupyter/nbconvert)
- [NbFormat](https://github.com/jupyter/nbformat)
- [QtConsole](https://github.com/jupyter/qtconsole)

And some repositories, libraries for the Python language, would remain under
IPython's Github organization:

- [IPyParallel](https://github.com/ipython/ipyparallel)
- [IPyKernel](https://github.com/ipython/ipykernel)
- [Traitlets](https://github.com/ipython/traitlets)

From this point in time, IPython and Jupyter would still share many jargons
and resources but each would live in separate houses:

- https://ipython.org
- https://jupyter.org


## **Jupyter**

> 2014

Not only IPython's codebase was being reorganized but the community itself:
the Jupyter project spin-off ["to support interactive data science and
scientific computing across all programming languages"](https://jupyter.org/about).

The new structure of the project Jupyter encouraged the formation of
community-managed subprojects by establishing guidelines and a body of
expertise to support new developers and their ideas.

## JupyterHub

> 2014

As soon as Jupyter (the project) is born, JupyterHub takes place as the
first argely independent sub-project.

## JupyterLab

> 2016

As handful as Notebook server was, there was demand for a more concise user
interface, and an UI that allow for greater integration with visualization
libraries and trends such as data science dashboards that were now popping-up
in the Python and Javascript communities.

To handle the growing demand for a modern UI to (executable) notebooks,
JupyterLab was created.
As an independent project, Jupyter-Lab could recreate a whole new interface
around Jupyter-Server without breaking Jupyter-Notebook.

## References

- *"IPython: A System for Interactive Scientific Computing"*,
F. Perez and B.E. Granger (2007)
https://dl.acm.org/doi/10.1109/MCSE.2007.53

- *"The Big Split™"*,
Jupyter Blog (2015)
https://blog.jupyter.org/the-big-split-9d7b88a031a7

- *"Jupyter receives the ACM Software System Award"*,
Jupyter Blog (2018)
https://blog.jupyter.org/jupyter-receives-the-acm-software-system-award-d433b0dfe3a2
