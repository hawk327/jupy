# jupy
First trial of Jupyter Notebook setup <!--- test a comment here -->

# Example Jupyter notebook with Binder <!--- & Colab integration -->



[//]: < [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/hawk327/jupy/HEAD) OR >
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/hawk327/jupy/HEAD)
<!--- [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/) %update this -->



This simple [Jupyter](https://jupyter.org/) notebook demonstrates how the computational notebook format allows users to interleave text, code, and results in a single file.

But, unless you have Jupyter notebook installed on your computer, all you can do is view the notebooks, not play with them. (See for yourself: If you click `428jupyter01.ipynb` in this GitHub repository, you will be able to read the notebook, but only as a static document.) This is where [Binder](https://mybinder.org) or Google's [Colaboratory](https://research.google.com/colaboratory/) environment come into play. Binder is a free, open-source web service that packages Jupyter notebooks inside an executable container, which can be run within a web browser, no installation required. Colab allows users with Google accounts to execute Jupyter notebooks on the Google cloud.

**To execute the notebook in Binder:**

1. Click the `launch binder` button above. Once the demo launches, click `428jupyter01.ipynb` in the file listing.
2. Run the notebook by selecting `Cell > Run All`.
3. Take a look at the graph below the fifth cell (labeled 'The First 25 Fibonacci Numbers').
4. Uncomment the line in the fifth cell that reads `# ax.plot (range(25), ar)` by removing the leading hashtag (`#`)
5. Click `Cell > Run All` again. You should see a change in the graph below that cell.

**To execute the notebook in Colab:**

1. Click the `Open in Colab` button above. It will launch the notebook directly.
2. Make the notebook live by clicking 'Connect' in the Colab toolbar.
3. You'll need to uncomment a few lines of code to make the notebook work. Navigate to the first cell, which reads:  
   `# !pip install folium`  
   `# !curl -O https://raw.githubusercontent.com/b`
4. Uncomment this cell by removing the two leading `#`.  %update this
5. Select `Runtime > Run All` in the menu to execute the notebook. (You may get a warning that the page was not authored by Google.)
6. Take a look at the graph below the fifth cell (labeled 'The First 25 Fibonacci Numbers').
7. Uncomment the line in the fifth cell that reads `# ax.plot (range(25), ar)` by removing the leading hashtag (`#`)
8. Click `Runtime > Run All` again. You should see a change in the graph below that cell.
