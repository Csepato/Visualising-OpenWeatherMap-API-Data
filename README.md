# Web Visualization Dashboard

## Latitude - Latitude Analysis Dashboard 
![Images/landingResize.png](Images/landingResize.png)

The purpose of this project was to analyze how weather across 500+ cities across the world changes as you get closer to the equator.

In building this dashboard, I created individual pages for each plot and a means by which I can navigate between them. These pages contain the visualizations and their corresponding explanations. I also have a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

### Website Requirements

The website consists of 7 pages in total, including:

* A [landing page](#landing-page) containing:
  * An explanation of the project.
  * Links to each visualizations page.
* Four [visualization pages](#visualization-pages), each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A ["Comparisons" page](#comparisons-page) that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a bootstrap grid for the visualizations.
    * The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
* A ["Data" page](#data-page) that:
  * Displays a responsive table containing the data used in the visualizations.
    * The table must be a bootstrap table component.
    * The data must come from exporting the `.csv` file as HTML, or converting it to HTML. Try using a tool you already know, pandas. Pandas has a nifty method approprately called `to_html` that allows you to generate a HTML table from a pandas dataframe. See the documentation [here](https://pandas.pydata.org/pandas-docs/version/0.17.0/generated/pandas.DataFrame.to_html.html)

The website at the top of every page, have a navigation menu that:

* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown on the right of the navbar named "Plots" which provides links to each individual visualization page.
* Provides two more links on the right: "Comparisons" which links to the comparisons page, and "Data" which links to the data page.
* Is responsive (using media queries).

Finally, the website has been deployed to GitHub pages.

### Considerations

* I had any option to use the weather_data or another dataset. I used the [cities dataset](Resources/cities.csv) and pulled the images from the [assets folder](Resources/assets).
* I used bootstrap. This includes bootstrap `navbar` component for the header on every page, the bootstrap table component for the data page, and the bootstrap grid for responsiveness on the comparison page.
* I deployed the website to GitHub pages, with the website working on a live, publicly accessible URL as a result.
* Used a CSS media query for the navigation menu.
* Ensured the website works at all window widths/sizes. 

### Screenshots

#### Landing page

Large screen:

![Landing page large screen](Images/landing-lg.png)

Small screen:

![Landing page small screen](Images/landing-sm.png)
￼

#### Comparisons page

Large screen:

![comparison page large screen](Images/comparison-lg.png)

Small screen:

![comparison page small screen](Images/comparison-sm.png)

#### Data page

Large screen:

![data page large screen](Images/data-lg.png)

Small screen:

![data page small screen](Images/data-sm.png)

#### Visualization pages

Large screen:

![visualize page large screen](Images/visualize-lg.png)

Small screen:

![visualize page small screen](Images/visualize-sm.png)

#### Navigation menu

Large screen:

![nav menu large screen](Images/nav-lg.png)

Small screen:

![nav menu small screen](Images/nav-sm.png)
