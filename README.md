# AI/Cyber Foundry Workshop on Practical Data Manipulation and Exploration with Python (28-May-2021)

## In Preparation for the Workshop

It would be useful for participants to have a Google account and be ready to use Google Colab for the practical side of things. Some suggestions of resources for getting acquainted with [Google Colab](https://colab.research.google.com/) are:

- [Introduction to Google Colab](https://youtu.be/inN8seMm7UI): just to giving a feel of what notebooks look like and of the interactivity and exploratory programming aspects; please ignore the Deep Learning stuff.
- [Overview of Colab Features](https://colab.research.google.com/notebooks/basic_features_overview.ipynb)
- [Markdown Guide](https://colab.research.google.com/notebooks/markdown_guide.ipynb)
- [External Data: Drive, Sheets, and Cloud Storage](https://colab.research.google.com/notebooks/io.ipynb)


Other resources on practical Data Science and Machine Learning with Python which I tend to recommend to our MSc Data Science students before they start are:

- DataCamp's introductory Data Science and Machine Learning Python courses:
    - https://learn.datacamp.com/courses/intro-to-python-for-data-science
    - https://learn.datacamp.com/courses/supervised-learning-with-scikit-learn
    - https://learn.datacamp.com/courses/introduction-to-data-science-in-python

- the Carpentry series (e.g., http://swcarpentry.github.io/python-novice-inflammation/).


In addition, one might want to browse/go through selected sections of the recommended textbooks:

- A Whirlwind Tour of Python (https://jakevdp.github.io/WhirlwindTourOfPython/)
- Python Data Science Handbook (https://jakevdp.github.io/PythonDataScienceHandbook/)
- Introduction to Machine Learning with Python (http://shop.oreilly.com/product/0636920030515.do).
    + Andreas Müller's lectures deal with more up-to-date `scikit-learn` constructs: https://www.cs.columbia.edu/~amueller/comsw4995s20/schedule/.


Not needed for our workshop but, for the future, participants might find useful to have a local Python installation with Jupyter Lab on their machine. My suggestion is to go for the Anaconda distribution (https://www.anaconda.com/distribution/). Of course, a good programming text editor/environment (e.g., Sublime Text, Visual Code Studio) alongside is always helpful.


## Some Keypoints on Google Colab

* Based on **Jupyter** (in turn, derived from `IPython`/`RStudio` notebooks).

* A **notebook** is a collection of cells containing **code** or **text**, which can be evaluated and rendered as code output, text, graphs, and other multimedia artefacts.

* Useful for **reproducible**, **exploratory**, **interactive** data science/machine learning/programming.

* Two main modes: **Command** and **Edit** modes. The former concerns the structure of the notebook (e.g., inserting, deleting, navigating through cells); the latter, with editing the content of a cell.

- Typically, functionality is accessible via a menu or a toolbar. Most of the time, in Command mode, one will be adding code or text cells, or running cells.

* You might find using keyboard shortcuts more efficient; (`Ctrl`/`Cmd`+)`H` shows you the current bindings.

* Some essential keyboard shortcuts are: {>> need to check that these work in Colab, not Jupypter Notebook<<}

    - `Enter`: goes into **Edit** mode on current cell.

    - `Esc` brings one back from **Edit** to **Command** mode.

    - `Shift+Enter` runs the current cell or selection. Typically, running a text cell means rendering its content into HTML; for code, output such as printed text or a graph is shown below the cell.

    - `Ctrl`/`Cmd`+`M` makes a cell of the type _Markdown_ (for a lightweight-formatted text); `Ctrl`/`Cmd`+`Y` changes it to code.
 
    - (`Ctrl`/`Cmd`+)`A` create a new cell above the current one; (`Ctrl`/`Cmd`+)`B`, below.

    <!-- executing commands -->
    - (`Ctrl`/`Cmd`+)`Shift`+`P`: execute a Colab command.    

<!-- need the CC license here: link to short and long versions -->
