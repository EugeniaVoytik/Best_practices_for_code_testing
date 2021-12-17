[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/EugeniaVoytik/Best_practices_for_code_testing.git/HEAD?labpath=Software_testing.ipynb)

# Best_practices_for_code_testing

This notebook was created as a tutorial on best practices for code testing for the Bioinformatics journal club (MannLabs).
The tutorial covers the following topics:
- Exceptions and their hierarchy in Python;
- Exception raising and catching;
- Why do we need to test code?
- Comparison of pytest and unittest;
- Advantages of pytest;
- Theoretical structure of an assertion statement;
- Testing for NumPy and pandas;
- Pytest plugins;
- Fixtures;
- Parameterisation of tests;
- How many tests do we need to write for one function?
- Example of a test-driven development.

---
## Usage

There are two different ways to use this repository depending on programming experience:

* [**Binder**](#binder): This way is suitable for users not experienced in programming and does not require any installation. It allows you to execute code online without installing any software. To run Binder use the `launch binder` logo at the top of the README.md file or click [here](https://mybinder.org/v2/gh/EugeniaVoytik/Best_practices_for_code_testing.git/HEAD?labpath=Software_testing.ipynb).

**NOTE:** The first time you run Binder on your machine it often takes a while for the GitHub repository to be built on the Binder server. During all subsequent times of use, Binder simply runs an already created repository, so it should be much faster.

* [**Python and Jupyter notebooks**](#python-and-jupyter-notebooks): Choose this option if you are familiar with Python, conda and Jupyter notebooks. It provides the ability to reproduce all the graphs from the review and apply the written code to explore your own data.

**IMPORTANT:** For the first use in Binder or in Jupyter Notebook, comment out the first code cell in the notebook which looks like this

```
## Install all packages directly in the notebook  
#!pip install {some_packages}
```

and run it in the notebook. This will install the libraries used in the current notebook. The installation should only be done once. After this you can comment out this cell again.

**NOTE:** You can use this notebook as a presentation. To do so, you need to install RISE (a slide show extension for Jupyter notebook). You can find more information about it in [documentation](https://rise.readthedocs.io/en/stable/installation.html).
