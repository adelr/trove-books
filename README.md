# Topic modelling of Trove Books
### The data can be downloaded from the [GLAM Workbench website](https://glam-workbench.github.io/trove-books/).

-----

#### Created by Adel Rahmani

### The data
The data comes from the [GLAM Workbench website](https://glam-workbench.github.io/trove-books/) (follow the link at the bottom of the page to download the data),
and is comprised of 9,738 documents harvested and kindly made available by [Tim Sherratt](https://timsherratt.org/).

### The analysis
The code `Trove_Digitised_Books.ipynb` file is a [Jupyter](https://jupyter.org/) notebook documenting my initial exploration of the data.
The code is written in Python 3.7. The notebook can also be viewed [here](https://nbviewer.jupyter.org/github/adelr/trove-books/blob/master/Trove_Digitised_Books.ipynb).

### Requirements
If you are using the [Anaconda distribution](https://www.anaconda.com/distribution/), you can reproduce my virtual environment
by using the provided  `environment.yml` configuration file. This can be done by running
```
conda env create -f environment.yml
```
in a terminal.

__Note__: On macOS I had to use the following to install the [CLD2 library](https://github.com/CLD2Owners/cld2):

```
export CC=clang; CFLAGS=-stdlib=libc++ pip install --ignore-installed pycld2
```

### Credits
[Adel Rahmani](https://twitter.com/dinkumdata)

The text is released under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/), and the code is released under the [MIT license](https://opensource.org/licenses/MIT).


