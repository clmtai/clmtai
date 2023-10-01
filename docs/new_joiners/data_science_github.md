# Data Science in Github
For data science we will use jupyter notebooks. These are great to run quick
experiments with feedback. One area where notebooks are a bit harder to work
with is repositories are pull requests. Here we will cover how to simplify the
pull request process my ensuring that every notebook `ipynb` file is linked to
a markdown `md` file. To sync these, we use [jupytext](https://github.com/mwouts/jupytext).

## Tutorial Jupytext
### Step 1: Install Jupytext

You can install Jupytext using pip or mamba. Open a terminal or command prompt and run the following command:
```
pip install jupytext
```
Or, if you prefer to use mamba, you can install Jupytext with the following command:
```
mamba install jupytext
```

#### Step 2: Activate Jupytext in Jupyter

After installing Jupytext, you need to activate it in Jupyter. To do this, first install the extension,


```sh
$ jupyter nbextension install --py jupytext --user
```

then enable it,


```sh
$ jupyter nbextension enable jupytext --user --py
```

### Step 3: Create a New Jupyter Notebook

Create a notebook as you would normally do.

### Step 4: Link the Jupyter Notebook to a Markdown File 

To link a markdown file to a notebook, you head to Jupyter notebook. There, in the menu go to `File > Jupytext > Pair Notebook with Markdown`

#### Step 5: Save the Notebook as a Markdown File

Save the notebook. Now a markdown file will be automatically generated.

#### Step 6: Commit your work

When you commit, make sure to commit your notebook and markdown file.

#### Step 8: Review the Markdown in a Pull Request

Finally, when you're ready to share your notebook with others, you can include the Markdown file in a pull request. This allows reviewers to easily view and comment on the notebook without having to open it in Jupyter.

That's it! With Jupytext, you can easily save Jupyter notebooks as Markdown files and vice versa. This makes it much easier to collaborate with others and review notebooks in pull requests.
