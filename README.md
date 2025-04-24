This Jupyter Notebook uses web scraping libraries to create a site map from a given base URL. It then finds every link on every page associated with the base site, and checks the status of that link. The program returns a dataframe of each link, the page the link was found on, and the response status code from the link. Follow the steps below to use the notebook.

1) Run the Notebook cells in order.
2) Enter the starting URL as base_url. Add any links to skip from including in the site map, in quotes separated by a comma. This could include links to Facebook or LinkedIn, for example.
3) Run the cell to create functions and session settings.
4) Run the cell to create a site map and collect all links. Warning: may take several minutes to compelte depending on the size of the site.
5) Run the next cell to check the status of each link. **Warning: this can take up to several hours.**
6) Display and export the link status table to a CSV file.


Run the interactive notebook at: https://mybinder.org/v2/gh/mxjmartell/LinksChecker/HEAD
Or click the launcher below:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mxjmartell/LinksChecker/HEAD)
