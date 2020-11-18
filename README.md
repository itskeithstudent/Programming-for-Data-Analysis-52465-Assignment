# Programming-for-Data-Analysis-52465-Assignment
This repository contains a jupyter notebook to explain the numpy.random package and several of it's functions therein, it uses Markdown sections to structure the notebook and provide write-up and commentary for the various sections. Code cells are also used to provide examples of the functions specified within numpy.random. The markdown and code cells are used in tandem to both explain and show the usage of numpy.random.

Please see the pdf file in this repository for further clarity on the assignment requirements.

## The general structure of the notebook is as follows:
- At the very start is the title and following that an initial set of imports for packages used throughout the notebook.
- The first main section is a overview of the purpose of the numpy.random package and includes subsections on Random Number Generators and the distinction between Generators and Bit Generators.
- The second section then covers Simple Random Data and Permutations, with subsections covering the specific functions using code cells to execute examples of the different functions to demonstrate their usage.
- The third section details Distributions, within this section it covers Uniform, Normal, Binomial, Exponential, Logistic and Laplace Distributions which again feature code cells executing examples of them and also include matplotlib and seaborn plot's to visualise them to show what the different distributions look like.
- The fourth section is about seeds and again code cells are used here to illustrate the use of seeds for generating a consistent set of random numbers.
- Finally there is a small section comparing the current and previous default Bit Generators, PCG64 and Mersenne Twister respectively, this section is a little out of place as structurally did not seem to fit with any of the previous sections (the reasoning behind for the inclusion of this was that it is an area mentioned by lecturer Brian McGinley in one of his videos on numpy.random, but is not explicitly called out in the assignment problem statement)
