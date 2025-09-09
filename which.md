# Which template should I use?

We offer three templates, each with its own (dis)advantages. We specify below the characteristics in order to help you pick the 'best' template that fits your needs and level of expertise.

All templates provide the same starting chapters, telling a little about the markdown language, and providing some exercises to help you get started.


## Jupyter Demo Book
The [Jupyter Demo Book template](https://tud-jb-templates.github.io/OIT-JB/) (adapted from the original Jupyter Book templated by Timon Idema) is based on the Jupyter Book 1 software and utilizes TU Delft Gitlab. Full software installation is required to produce an output.

**Positives:**
- bare bone version
- software developed and support by JB1 developers

**Negatives:**
- Full software installation to see output
- No full control unless coded yourself
- Difficult to set up
- OIT support needed to get started
- PDF export suboptimal

Example book made utilizing the template: [A Brief Introduction to Biochemistry: Biochemistry for non-chemists](https://interactivetextbooks.tudelft.nl/biochemistry)

### Requirements

- VSC
    * Extensions
        -   Jupyter
        -   Markdown
        -   Github Actions
        -   Python
- Python
    * Dependencies
        -   jupyter-book
        -   numpy
        -   scipy
        -   matplotlib
        -   plotly==5.24.1
        -   myst_nb
        -   jupyterquiz
        -   sphinx-exercise
        -   sphinx-proof
        -   pydata-sphinx-theme

- Gitlab



## Teachbooks
The [Teachbooks template](https://tud-jb-templates.github.io/TB) (developed by Tom van Woudenberg, Robert Lanzafame and Dennis den Ouden-van der Horst) is based on the Jupyter Book 1 software and utilizes Microsoft Github. It is recommended to install full software to run the book locally, but is not required through the use of GitHub Pages. 

**Positives:**
- Quick start
- Additional functionality built by teachers
- Full customizable through CSS

**Negatives:**
- Understanding all possibilities and functionalities
- Connecting Github and Gitlab to comply with TUD publishing regulations
- PDF export suboptimal
- Public from start

Example book made utilizing the template: [Linear Algebra](https://interactivetextbooks.tudelft.nl/linear-algebra/)

### Requirements

- Github

**optional:**
- VSC
    * Extensions
        -   Jupyter
        -   Markdown
        -   Github Actions
        -   Python
- Python
    * Dependencies
        -   Teachbooks
        -   git+https://github.com/TeachBooks/TeachBooks-Favourites
        -   sphinx-tudelft-theme


## Jupyter Book 2
The [Jupyter Book 2 template](https://github.com/TUD-JB-Templates/JB2) (developed by Freek Pols) is based on the Jupyter Book 2 software and utilizes Microsoft GitHub. 

**Positives:**
- High quality pdf with ease
- Newest technology, still in development
- Used in science publication 

**Negatives:**
- Not all functionality from JB1 is available (yet)
- In browser Python is not editable 
- Not full control of style 

### Requirements

- Github

**optional:**
- VSC
    * Extensions
        -   Jupyter
        -   Markdown
        -   Github Actions
        -   Python
        -   MyST-Markdown
- Python
    * Dependencies
        -   mystmd


Example book made utilizing the template: [Introducing Classical Mechanics & Special Relativity](https://interactivetextbooks.tudelft.nl/dev/mecharela/)

## Which one than?


```{table}
| Teachbooks | Jupyter Demo Book | Jupyter Book 2 |
| --- | --- | --- |
| JB 1 | JB 1 | JB 2 |
| Customized sphinx extension | Traditional Jupyter packages | |
| Full control / adaptable / customizable layout through extensions | Full control through own code  | Less control |
| | | |
```
