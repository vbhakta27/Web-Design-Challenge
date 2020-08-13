# Global Weather Analysis Webpage

## Background
Using the graphs and data from [Global Weather Analysis repoisitory](https://github.com/vbhakta27/Global_Weather_Analysis) I wanted to create a webpage using HTML and CSS.

## Website
I created individual pages for each plot and a means by which the user can navigate between them. These pages contain the visualizations and their corresponding explanations. There is also have a landing page, a page where the user can see a comparison of all of the plots, and another page where he/she can view the data used to build them.

The website consists of 7 pages total, including:

* A landing page containing:
  * An explanation of the project.
  * Links to each visualizations page.
* Four vizualization pages, each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A comparisons page that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a bootstrap grid for the visualizations which will auto adjust for window sizing
* A Data page that:
  * Displays a responsive table containing the data used in the visualizations.

The website has a navigation menu at the top of every page that:

* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown on the right of the navbar named "Plots" which provides links to each individual visualization page.
* Provides two more links on the right: "Comparisons" which links to the comparisons page, and "Data" which links to the data page.
* Is responsive (using media queries).

The website has been deployed to GitHub pages.

#### Navigation menu

Large screen:
![nav menu large screen](Images/nav-lg.png)

Small screen:
![nav menu small screen](Images/nav-sm.png)

### Copyright

Trilogy Education Services © 2019. All Rights Reserved.
