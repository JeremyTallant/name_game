# Name Game: Gender Prediction using Sound
## Description
The same name can be spelled out in a many ways (for example, Marc and Mark, or Elizabeth and Elisabeth). Sound can, therefore, be a better way to match names than spelling. In this project, we will use the Python package [Fuzzy](https://pypi.org/project/Fuzzy/) to find out the genders of authors that have appeared in the New York Times Best Seller list for Children's Picture books.

First, using fuzzy (sound) name matching, we will search for author names in a dataset provided by the US Social Security Administration that contains names and genders of all individuals who have applied for Social Security Cards. Next, we'll aggregate the author dataset by including gender. Finally, we will use the new dataset to plot the gender distribution of children's picture books authors over time.
## Usage
Clone this repository and open the Jupyter notebook file (`*.ipynb`) in a Jupyter environment with Python kernel support. Make sure to install the required packages such as `pandas`, `fuzzy`, `numpy`, and `matplotlib`. You can do this by running the following commands in a code cell within the notebook:
```python
!pip install pandas fuzzy numpy matplotlib
```
Once the packages are installed, run the code cells in the notebook to generate the plots and analyses.

If you don't have a Jupyter environment set up, you can install Jupyter Notebook and the Python kernel using the following steps:

1. Install Jupyter Notebook by following the instructions on the [official Jupyter website](https://jupyter.org/install).

2. Ensure you have Python installed. If not, you can download and install Python from the [official Python website](https://www.python.org/downloads/).
## Contents
1. **Sound it out!:** Explore the NYSIIS algorithm.
2. **Authoring the authors:** Read in the book data and extract the authors' first names.
3. **It's time to bring on the phonics..._again_!:** Create an NYSIIS equivalent of authors' first names.
4. **The inbetweeners:** Read in the baby name dataset and add to it a new column that indicates gender.
5. **Playing matchmaker:** Figure out the genders of the authors.
6. **Tally up:** Tally up the gender of the authors over time.
7. **Foreign-born authors?:** Visualize the foreign-born authors using a bar chart.
8. **Raising the bar:** Compare male and female authorship using a grouped bar chart.