![Image header "Power BI macguyver toolbox templates and examples for your Power BI reports"](powerbi-macguyver-toolbox.png)

Power BI report visual templates and patterns. These templates are intended to help you solve specific visual requirements in your projects, or inspire you for your report design.

You can use them for free, but I'd appreciate that you please cite [data-goblins.com](https://www.data-goblins.com) if you do.

**SVG measure templates contributed by Štěpán Rešl. Thanks Štěpán!**

## ⚠️ Notice
These templates are provided as-is without warranties or guarantees. They are not maintained nor are they all necessarily suitable for use in production solutions.

Feel free to use them, but do so at your own risk.
	
## 💡 To use these templates
Templates are provided either as Power BI Desktop (.pbix) or [Power BI projects (.pbip)](https://learn.microsoft.com/en-us/power-bi/developer/projects/projects-overview) files. I recommend that you use the .pbip format. 

![A header image "how to clone a Git repo if you're new to git or unfamiliar with it"](clone-repo-github-header.png)

### How to clone a repository by using Git
To use these templates, I recommend that you _clone_ (or copy) this Git repo to your local machine. If you're unfamiliar with Git, cloning allows you to ensure you have a syncronized local copy of the repository. You use a tool like VS Code to open the folder, check for changes, and sync to get the latest updates. To clone the Git repo:

1. __Install [Git](https://git-scm.com/download/win).__ Typically, you want to use the 64-bit Git for Windows Setup.
2. __Download a graphical user interface (GUI) to manage Git, like [GitHub Desktop](https://desktop.github.com/) or [VS Code](https://code.visualstudio.com/).__ You can also manage it from the command line, but if you're new to Git, this isn't recommended. I recommend that you [download and install VS Code](https://code.visualstudio.com/), since it's used for other code authoring experiences in Power BI.
3. __Create a [GitHub account](https://github.com/signup).__ Follow the steps to validate your account and set up multi-factor authentication.
4. __Link your GitHub account to the GUI you downloaded.__ This differs depending on the tool you used. Generally, you should just follow the user interface's instructions; in [VS Code](https://code.visualstudio.com/docs/sourcecontrol/github) you sign in via the Source Control tab or GitHub extension.
5. __Clone the repository.__ In the GUI, you should select an option "clone repository". From here, you can enter the HTTPS URL. You can also initiate this from GitHub, itself, via the _code_ button.

> <br>
> Use this URL when cloning the repo: https://github.com/data-goblin/powerbi-macguyver-toolbox.git
> <br><br>

<br>

![An image depicting how to clone a repository in VS code](clone-repo-vscode.png)

![An image depicting how to clone a repository in GitHub](clone-repo-github.png)

![A header image "how to enable and use PBIP files"](how-to-enable-pbip-format-header.png)

### How to enable and use .pbip files

1. Open Power BI Desktop (~May 2023 version or later)
2. Open the 'File' menu
3. Navigate to _Options and settings_ and then _Options_
4. Enable the preview feature _Power BI Project (.pbip) save option
5. Restart Power BI Desktop
6. Open the .pbip files in Power BI Desktop

![An image depicting how to enable .pbip format in Power BI Desktop](how-to-enable-pbip-format.png)

__I recommend the .pbip format for templates for the following reasons:__
- Lightweight sharing of report + model metadata.
- Report metadata allows you to programmatically modify the templates before opening them.
- Track changes of the individual objects and formatting in the GitHub repo.

<br><br>

![Image header "bar chart templates"](bar-chart-templates.png)

## Bar chart templates
You can download these templates either as standalone or combined files. Click the below image for the combined file:

<a href="bar-charts/all-bar-chart-templates/"><img src="bar-charts/all-bar-chart-templates/Bar Charts in Power BI.png"/></a>

_Note: Any chart with a MacGuyver Rating of 3 or above_ (🟩🟩🟩⬜⬜+) _is not recommended for production deployment. That's because they require too many report-specific objects and have too high a risk to break or effort to maintain. For these charts, you should use Deneb._

The following templates are available:

| Image (Click for Template) | Name | Description |
|:-----:|:----:|:------------|
| <a href="bar-charts/bar-chart/"><img src="bar-charts/bar-chart/bar-chart.png"/></a> | __Bar chart (Horizontal bar)__ | The standard horizontal bar chart. Tried and true, best used to compare categories. Consider turning off axes and gridlines and using data labels with conditional formatting for a more elegant design. <br><br> _Subjective Goblin graph scores_<br> 🟩🟩🟩🟩🟩 __Popularity Rating__ - Frequency I see it requested<br> 🟩🟩🟩🟩⬜ __Utility Rating__ - # Different use-cases it covers<br> ⬜⬜⬜⬜⬜ __MacGuyver Rating__ - Effort to build, test, maintain |
| <a href="bar-charts/column-chart/"><img src="bar-charts/column-chart/column-chart.png"/></a> | __Column chart (Vertical bar)__ | The standard vertical bar chart. Harder to read compared to the horizontal version, often because the labels are truncated or angled. Consider using the Bar chart (Horizontal bar), instead. <br><br> _Subjective Goblin graph scores_<br> 🟩🟩🟩🟩🟩 __Popularity Rating__ <br> 🟩🟩⬜⬜⬜ __Utility Rating__ <br> ⬜⬜⬜⬜⬜ __MacGuyver Rating__ |
| <a href="bar-charts/rounded-bar-chart/"><img src="bar-charts/rounded-bar-chart/rounded-bar-chart.png"/></a> | __Rounded bar chart__ | A standard horizontal bar chart, except the ends are rounded. Honestly, I personally don't see the appeal, but there's a lot of people who do. There's a risk that the curves make it harder to compare lengths. It's mainly used for infographics for the shape. <br><br> _Subjective Goblin graph scores_<br> 🟩🟩🟩⬜⬜ __Popularity Rating__ <br> ⬜⬜⬜⬜⬜ __Utility Rating__ <br> 🟩🟩🟩⬜⬜ __MacGuyver Rating__ |
| <a href="bar-charts/stacked-bar-chart/"><img src="bar-charts/stacked-bar-chart/stacked-bar-chart.png"/></a> | __Stacked bar chart__ | The standard horizontal stacked bar chart. Can be useful because it can display both the part-of-whole and total labels, but like many part-of-whole visuals, can be difficult to read and interpret with too many categories.<br><br> _Subjective Goblin graph scores_<br> 🟩🟩🟩🟩⬜ __Popularity Rating__ <br> 🟩🟩🟩⬜⬜ __Utility Rating__ <br> ⬜⬜⬜⬜⬜ __MacGuyver Rating__ |
| <a href="bar-charts/stacked-bar-chart-ii/"><img src="bar-charts/stacked-bar-chart-ii/stacked-bar-chart-ii.png"/></a> | __Stacked bar chart II__ | A horizontal stacked bar chart showing the percent of the total for each row (category along the Y-axis). Can be useful because it can display both the part-of-whole and total labels, but like many part-of-whole visuals, can be difficult to read and interpret with too many categories.<br><br> This is a useful chart type to analyze survey and sentiment analysis, for example. <br><br> _Subjective Goblin graph scores_<br> 🟩🟩🟩🟩⬜ __Popularity Rating__ <br> 🟩🟩🟩⬜⬜ __Utility Rating__ <br> ⬜⬜⬜⬜⬜ __MacGuyver Rating__ |
| <a href="bar-charts/divergent-bar-chart/"><img src="bar-charts/divergent-bar-chart/divergent-bar-chart.png"/></a> | __Divergent bar chart__ | A horizontal bar chart that plots the difference between two values being compared instead of showing the absolute values. This chart type is useful when you want to focus on high magnitudes of difference, or when the difference matters more than the absolute values. <br><br> _Subjective Goblin graph scores_<br> 🟩🟩🟩🟩⬜ __Popularity Rating__ <br> 🟩🟩🟩🟩⬜ __Utility Rating__ <br> ⬜⬜⬜⬜⬜ __MacGuyver Rating__ |
| <a href="bar-charts/lollipop/"><img src="bar-charts/lollipop/lollipop.png"/></a> | __Lollipop chart__ | An alternative to the standard horizontal bar chart that has a dingle shape on the end, making it look like a lollipop. Honestly, I personally don't see the appeal, but it's especially popular if you have the data labels appear in the circle. The main use-case is if the shape of the chart needs to resemble something like a thermometer or something else. <br><br> _Subjective Goblin graph scores_<br> 🟩🟩🟩⬜⬜ __Popularity Rating__ <br> ⬜⬜⬜⬜⬜ __Utility Rating__ <br> 🟩🟩🟩⬜⬜ __MacGuyver Rating__ |
| <a href="bar-charts/butterfly/"><img src="bar-charts/butterfly/butterfly.png"/></a> | __Butterfly chart__ | A type of bar chart where two series are plotted, but one is inversed. Useful for pairwise comparisons mainly of the magnitude and distribution for the values, for example when comparing two categories like sex or this year vs. last year. <br><br> _Subjective Goblin graph scores_<br> 🟩🟩🟩⬜⬜ __Popularity Rating__ <br> 🟩🟩🟩⬜⬜ __Utility Rating__ <br> 🟩🟩⬜⬜⬜ __MacGuyver Rating__ |
| <a href="bar-charts/bar-chart-with-line-end/"><img src="bar-charts/bar-chart-with-line-end/bar-chart-with-line-end.png"/></a> | __Bar chart with line end__ | A bar chart where the end has a longer line to make it easier to compare between the categories. Honestly, I wouldn't recommend doing this in Power BI because it's not worth the effort to MacGuyver and maintain it for the return you get. <br><br> _Subjective Goblin graph scores_<br> 🟩⬜⬜⬜⬜ __Popularity Rating__ <br> 🟩🟩⬜⬜⬜ __Utility Rating__ <br> 🟩🟩🟩⬜⬜ __MacGuyver Rating__ |
| <a href="bar-charts/bullet-chart/"><img src="bar-charts/bullet-chart/bullet-chart.png"/></a> | __Bullet chart__ | Bullet charts are great. I love them. They are excellent chart types for comparing to a target, or between two series. In my opinion, they are the most efficient chart type for this, other than perhaps a horizontal dumbbell / connected dot plot, which sadly is not possible in Power BI right now. <br><br> _Subjective Goblin graph scores_<br> 🟩🟩🟩🟩⬜ __Popularity Rating__ <br> 🟩🟩🟩🟩🟩 __Utility Rating__ <br> 🟩⬜⬜⬜⬜ __MacGuyver Rating__ |
| <a href="bar-charts/progress-bar/"><img src="bar-charts/progress-bar/progress-bar.png"/></a> | __Progress bar__ | A horizontal bar chart that shows a percentage completion or achievement. Note that this specific template doesn't account for overachievement (values going over 100%), which is something you should consider in addition. <br><br> _Subjective Goblin graph scores_<br> 🟩🟩⬜⬜⬜ __Popularity Rating__ <br> 🟩🟩🟩⬜⬜ __Utility Rating__ <br> 🟩⬜⬜⬜⬜ __MacGuyver Rating__ |
| <a href="bar-charts/progress-bar-ii/"><img src="bar-charts/progress-bar-ii/progress-bar-ii.png"/></a> | __Progress bar II__ | A version of the progress bar chart that breaks the progress into discrete chunks, like 10%, 20% or 25%. This can be good if those chunks have a functional meaning, like something happens at 75-100% that wouldn't happen at 50-75%. <br><br> _Subjective Goblin graph scores_<br> 🟩🟩🟩⬜⬜ __Popularity Rating__ <br> 🟩🟩🟩⬜⬜ __Utility Rating__ <br> 🟩🟩⬜⬜⬜ __MacGuyver Rating__ |
| <a href="bar-charts/progress-bar-iii/"><img src="bar-charts/progress-bar-iii/progress-bar-iii.png"/></a> | __Progress bar III__ | A version of the progress bar chart that has the progress tracked as a triangle along a vertical axis. More subtle than the original and requires more MacGuyvering, as it's actually a scatterplot. <br><br> _Subjective Goblin graph scores_<br> 🟩⬜⬜⬜⬜ __Popularity Rating__ <br> 🟩🟩⬜⬜⬜ __Utility Rating__ <br> 🟩🟩🟩🟩⬜ __MacGuyver Rating__ |
| <a href="bar-charts/progress-thin-bar/"><img src="bar-charts/progress-thin-bar/progress-thin-bar.png"/></a> | __Progress thin bar__ | A version of the progress bar chart that has the progress tracked as a dot along a vertical axis; more subtle and less ink than the original. Mainly for visual appeal. <br><br> _Subjective Goblin graph scores_<br> 🟩🟩⬜⬜⬜ __Popularity Rating__ <br> 🟩🟩⬜⬜⬜ __Utility Rating__ <br> 🟩🟩⬜⬜⬜ __MacGuyver Rating__ |
| <a href="bar-charts/bar-in-bar/"><img src="bar-charts/bar-in-bar/bar-in-bar.png"/></a> | __Bar-in-bar__ | Comparing two series where they are directly overlaid and one series has thinner bars than the other. This can be a nice alternative to the bullet chart and more efficient with the real estate than side-by-side bars. <br><br> _Subjective Goblin graph scores_<br> 🟩🟩🟩⬜⬜ __Popularity Rating__ <br> 🟩🟩🟩🟩⬜ __Utility Rating__ <br> 🟩🟩⬜⬜⬜ __MacGuyver Rating__ |
| <a href="bar-charts/side-by-side-bars/"><img src="bar-charts/side-by-side-bars/side-by-side-bars.png"/></a> | __Side-by-side bars__ | Two adjacent series to compare the absolute values. In this version, the series are designed to look more like a Tableau side-by-side chart, which is sub-optimal because it's not as flexible as the core visual from Power BI. <br><br> _Subjective Goblin graph scores_<br> 🟩🟩⬜⬜⬜ __Popularity Rating__ <br> 🟩🟩⬜⬜⬜ __Utility Rating__ <br> 🟩🟩🟩⬜⬜ __MacGuyver Rating__ |
| <a href="bar-charts/side-by-side-bars-ii/"><img src="bar-charts/side-by-side-bars-ii/side-by-side-bars-ii.png"/></a> | __Side-by-side bars II__ | Side-by-side bars to compare two or more series. A nice, simple core visual to compare absolute values. Ensure that the minimum width is set that you can have the data labels showing. <br><br> _Subjective Goblin graph scores_<br> 🟩🟩🟩🟩🟩 __Popularity Rating__ <br> 🟩🟩🟩⬜⬜ __Utility Rating__ <br> ⬜⬜⬜⬜⬜ __MacGuyver Rating__ |
| <a href="bar-charts/bar-chart-candlestick/"><img src="bar-charts/bar-chart-candlestick/bar-chart-candlestick.png"/></a> | __Bar chart and candlestick__ | Side-by-side bars where a candlestick shows the percentage difference. Honestly, this is a great chart type that's an alternative to connected dot plot or dumbbell charts, but in Power BI it's simply too much effort to MacGuyver with the core visuals. Just make a dumbbell / connected dot plot in Deneb or use a bullet chart; don't waste time with this. <br><br> _Subjective Goblin graph scores_<br> ⬜⬜⬜⬜⬜ __Popularity Rating__ <br> 🟩🟩🟩🟩⬜ __Utility Rating__ <br> 🟩🟩🟩🟩🟩 __MacGuyver Rating__ |

<br><br>

![Image header "Line chart templates"](line-chart-templates.png)

## Line chart templates
You can download these templates either as standalone or combined files. Click the below image for the combined file:

<a href="line-charts/all-line-chart-templates/"><img src="line-charts/all-line-chart-templates/Line Charts in Power BI.png"/></a>

The following line chart templates are available:

| Image | Name | Description |
|:-----:|:----:|:------------|
| <a href="line-charts/line-chart/"><img src="line-charts/line-chart/line-chart.png"/></a> |__Line chart__ | The standard line chart of Power BI. Useful for plotting trends, but needs specific handling of the axes and labels to be most usable and efficient. *Beware that the Y-axis won't start at 0 by default in Power BI. Additionally, be aware that Power BI will interpolate values such that it will connect data points over blanks, which can create false trends.  <br><br> _Subjective Goblin graph scores_<br> 🟩🟩🟩🟩🟩 __Popularity Rating__ - Frequency I see it requested <br> 🟩🟩🟩⬜⬜ __Utility Rating__ - # Different use-cases that it covers <br> ⬜⬜⬜⬜⬜ __MacGuyver Rating__ - Effort to make it with core visuals |
| <a href="line-charts/area-chart/"><img src="line-charts/area-chart/area-chart.png"/></a> |__Area chart__ | The standard line chart, but with area fill beneath the line. The shaded area can help illustrate the magnitude of difference, and also improve trend readability when the chart is small. <br><br> _Subjective Goblin graph scores_<br> 🟩🟩🟩⬜⬜ __Popularity Rating__ <br> 🟩🟩🟩⬜⬜ __Utility Rating__ <br> ⬜⬜⬜⬜⬜ __MacGuyver Rating__ |
| <a href="line-charts/line-with-labels-and-markers/"><img src="line-charts/line-with-labels-and-markers/label-markers.png"/></a> |__Labels and markers__ | The standard line or area chart with markers and labels. The markers should be subtle and small, and labels should be sufficiently configured to all be readable. Can sometimes provide too much context and reduce the time it takes users to read the graph. <br><br> _Subjective Goblin graph scores_<br> 🟩🟩🟩🟩🟩 __Popularity Rating__ <br> 🟩🟩🟩⬜⬜ __Utility Rating__ <br> ⬜⬜⬜⬜⬜ __MacGuyver Rating__ |
| <a href="line-charts/spline-chart/"><img src="line-charts/spline-chart/spline.png"/></a> |__Spline line chart__ | The standard line chart but where the lines are smoothened instead of linear. While this can be aesthetically pleasing or interesting, it can create misleading trends, so be certain that you are not just using "smooth lines" for aesthetic reasons, alone. <br><br> _Subjective Goblin graph scores_<br> 🟩🟩🟩🟩⬜ __Popularity Rating__ <br> 🟩🟩⬜⬜⬜ __Utility Rating__ <br> ⬜⬜⬜⬜⬜ __MacGuyver Rating__ |
| <a href="line-charts/stepped-line-chart/"><img src="line-charts/stepped-line-chart/stepped.png"/></a> |__Stepped line chart__ | Shows the connections as steps instead of linear or smoothened connections. Stepped line charts help emphasize that the data is not continuous, which can be helpful. <br><br> _Subjective Goblin graph scores_<br> 🟩⬜⬜⬜⬜ __Popularity Rating__ <br> 🟩🟩🟩⬜⬜ __Utility Rating__ <br> ⬜⬜⬜⬜⬜ __MacGuyver Rating__ |
| <a href="line-charts/label-latest-data-point/"><img src="line-charts/label-latest-data-point/label-latest-data-point.png"/></a> |__Label latest data point__ | The standard line or area chart where the latest data point is labelled. You can use this same approach to label other points-of-interest, like earliest, highest, lowest, or other points (like yesterday, last week, etc.) This helps provide additional context to the user. <br><br> _Subjective Goblin graph scores_<br> 🟩🟩🟩🟩🟩 __Popularity Rating__ <br> 🟩🟩🟩🟩🟩 __Utility Rating__ <br> 🟩⬜⬜⬜⬜ __MacGuyver Rating__ |
| <a href="line-charts/line-with-improved-labels-and-axis-ranges/"><img src="line-charts/line-with-improved-labels-and-axis-ranges/improved-axis-ranges.png"/></a> |__Improved axis ranges__ | The standard line or area chart where conditional formatting is used to control axis ranges to give more room for labels to render and to ensure that the axis starts at 0. This is generally recommended for most time series data, unless the emphasis is on the change (like stock market data). <br><br> _Subjective Goblin graph scores_<br> 🟩🟩🟩🟩⬜ __Popularity Rating__ <br> 🟩🟩🟩🟩🟩 __Utility Rating__ <br> 🟩⬜⬜⬜⬜ __MacGuyver Rating__ |
| <a href="line-charts/area-of-interest-vertical/"><img src="line-charts/area-of-interest-vertical/vertical-area-of-interest.png"/></a> |__Vertical area-of-interest__ | Highlighting a specific area-of-interest on the X-axis. This can be a period or a category, depending on how the chart is set up. Requires some MacGuyvering, but is relatively stable, and useful for drawing attention. <br><br> _Subjective Goblin graph scores_<br> 🟩🟩⬜⬜⬜ __Popularity Rating__ <br> 🟩🟩🟩🟩⬜ __Utility Rating__ <br> 🟩⬜⬜⬜⬜ __MacGuyver Rating__ |
| <a href="line-charts/error-bands/"><img src="line-charts/error-bands/error-bands.png"/></a> |__Error bands__ | Adding error bands to the line chart to visualize data variance about a measure of central tendency like an average. Also useful for visualizing uncertainty, like for forecasting. These concepts can be advanced for many users and require data literacy training and tutorials. <br><br> _Subjective Goblin graph scores_<br> 🟩⬜⬜⬜⬜ __Popularity Rating__ <br> 🟩🟩⬜⬜⬜ __Utility Rating__ (Situational)<br> ⬜⬜⬜⬜⬜ __MacGuyver Rating__ |
| <a href="line-charts/thresholds/"><img src="line-charts/thresholds/thresholds.png"/></a> |__Thresholds__ | Showing a specific target or threshold and shading or marking the area above (or below) it. Useful when there is a static target or when you want to compare to a global average. <br><br> _Subjective Goblin graph scores_<br> 🟩🟩🟩⬜⬜ __Popularity Rating__ <br> 🟩🟩🟩🟩⬜ __Utility Rating__ <br> 🟩🟩⬜⬜⬜ __MacGuyver Rating__ |
| <a href="line-charts/area-of-interest-horizontal/"><img src="line-charts/area-of-interest-horizontal/horizontal-area-of-interest.png"/></a> |__Horizontal area-of-interest__ | Highlighting a vertical area of interest, like a threshold area instead of threshold line. Also useful when you want to highlight multiple areas, like temperature ranges for machines. <br><br> _Subjective Goblin graph scores_<br> 🟩🟩🟩⬜⬜ __Popularity Rating__ <br> 🟩🟩🟩⬜⬜ __Utility Rating__ <br> 🟩⬜⬜⬜⬜ __MacGuyver Rating__ |
| <a href="line-charts/multiple-lines/"><img src="line-charts/multiple-lines/multiple-lines.png"/></a> |__Multiple lines__ | Comparing multiple series, with or without showing variation and uncertainty. <br><br> _Subjective Goblin graph scores_<br> 🟩🟩🟩🟩🟩 __Popularity Rating__ <br> 🟩🟩🟩🟩⬜ __Utility Rating__ <br> ⬜⬜⬜⬜⬜ __MacGuyver Rating__ |
| <a href="line-charts/hills-and-valleys/"><img src="line-charts/hills-and-valleys/hills-and-valleys.png"/></a> |__Hills and valleys__ | Comparing multiple series and highlighting the difference between them by using conditional formatting. Requires some MacGuyvering, but is quite stable. Note that the area fill cannot interpolate the area between data points, unlike the lines in the line chart. <br><br> _Subjective Goblin graph scores_<br> 🟩🟩⬜⬜⬜ __Popularity Rating__ <br> 🟩🟩🟩🟩⬜ __Utility Rating__ <br> 🟩🟩⬜⬜⬜ __MacGuyver Rating__ |
| <a href="line-charts/multiple-area/"><img src="line-charts/multiple-area/multiple-area.png"/></a> |__Multiple area__ | Comparing multiple series where there are overlapping area fills between the lines. Can be useful circumstantially but can also pollute the canvas with additional ink that doesn't need to be there. <br><br> _Subjective Goblin graph scores_<br> 🟩🟩🟩🟩⬜ __Popularity Rating__ <br> 🟩🟩🟩⬜⬜ __Utility Rating__ <br> ⬜⬜⬜⬜⬜ __MacGuyver Rating__ |
| <a href="line-charts/stacked-area/"><img src="line-charts/stacked-area/stacked-area.png"/></a> |__Stacked area__ | Parts-of-whole for trend analysis. Useful when you want to break up a trend to see how different parts contribute to a total. Need to be careful that it isn't mis-interpreted by users. <br><br> _Subjective Goblin graph scores_<br> 🟩🟩🟩⬜⬜ __Popularity Rating__ <br> 🟩🟩🟩⬜⬜ __Utility Rating__ <br> ⬜⬜⬜⬜⬜ __MacGuyver Rating__ |

<br><br>

![Image header "KPI & card templates"](kpi-cards-templates.png)

## KPI & card templates
You can download these templates either as standalone or combined files. Click the below images for the combined file:

### Core visuals - no SVG measures
These use the formatting options of the core visuals like cards, tables, etc. to achieve a KPI or callout-like effect.


<a href="kpi-cards/all-kpi-card-templates/"><img src="kpi-cards/all-kpi-card-templates/KPIs and Cards in Power BI (No SVGs).png"/></a>

The following templates are available:

| Image | Name | Description |
|:-----:|:----:|:------------|
| <a href="kpi-cards/basic-card/"><img src="kpi-cards/basic-card/basic-card.png"/></a> |__Basic Card__ | The standard card visual of Power BI. Typically, you should try to use conditional formatting and format strings to better give context to the number callout. However, there are cases where this context might not be required (particularly if calling out text). <br><br> _Subjective Goblin graph scores_<br> 🟩🟩🟩🟩🟩 __Popularity Rating__ - Frequency I see it requested <br> 🟩🟩⬜⬜⬜ __Utility Rating__ - # Different use-cases that it covers <br> ⬜⬜⬜⬜⬜ __MacGuyver Rating__ - Effort to make it with core visuals |
| <a href="kpi-cards/basic-card-ii/"><img src="kpi-cards/basic-card-ii/basic-card-ii.png"/></a> |__Basic card II__ | The standard card visual, but using conditional formatting and format strings to better provide context. Implicit information from colours and symbols helps the user understand how they should interpret the number. <br><br> _Subjective Goblin graph scores_<br> 🟩🟩🟩🟩🟩 __Popularity Rating__ <br> 🟩🟩🟩🟩⬜ __Utility Rating__ <br> ⬜⬜⬜⬜⬜ __MacGuyver Rating__ |
| <a href="kpi-cards/basic-card-iii/"><img src="kpi-cards/basic-card-iii/basic-card-iii.png"/></a> |__Basic card III__ | The standard card visual, but using dynamic format strings, typically also together with conditional formatting. This is similar to _Basic card II_. Note that dynamic format strings for measures don't work in all client tools, like Analyze in Excel's MDX queries. <br><br> _Subjective Goblin graph scores_<br> 🟩🟩🟩🟩🟩 __Popularity Rating__ <br> 🟩🟩🟩🟩⬜ __Utility Rating__ <br> 🟩⬜⬜⬜⬜ __MacGuyver Rating__ |
| <a href="kpi-cards/basic-kpi-card/"><img src="kpi-cards/basic-kpi-card/basic-kpi-card.png"/></a> |__Basic KPI__ | The standard KPI visual from Power BI that lets you compare to one or more targets. This visual is best used when the 'trend' is ignored, replaced with a disconnected dimension like "All", for example. That's because the 'trend' is regularly misunderstood, leading to misleading trends and difficulties of report creators to implement this visual, properly. Some effort is required to set the (conditional) formatting properly. <br><br> _Subjective Goblin graph scores_<br> 🟩🟩🟩🟩🟩 __Popularity Rating__ <br> 🟩🟩🟩🟩⬜ __Utility Rating__ <br> 🟩⬜⬜⬜⬜ __MacGuyver Rating__ |
| <a href="kpi-cards/boolean-conditional-text/"><img src="kpi-cards/boolean-conditional-text/boolean-conditional-text.png"/></a> |__Boolean conditional text__ | The standard card, where it displays a single boolean value (Yes/No; True/False; ✔️/✖️). This can be a nice way to call out answers to simple, highly aggregate questions. <br><br> _Subjective Goblin graph scores_<br> 🟩🟩⬜⬜⬜ __Popularity Rating__ <br> 🟩🟩⬜⬜⬜ __Utility Rating__ <br> ⬜⬜⬜⬜⬜ __MacGuyver Rating__ |
| <a href="kpi-cards/dynamic-titles/"><img src="kpi-cards/dynamic-titles/dynamic-titles.png"/></a> |__Dynamic titles__ | Making use of conditional DAX logic and conditional formatting of visual titles can provide a lot of flexibility to provide context. In many cases, the dynamic titles _are_ in fact the KPIs, allowing any visual to become a _de facto_ KPI card with a bit of MacGuyvering. However, this does result in a lot of DAX objects, as you typically need one or more measures for each dynamic (sub)title. <br><br> _Subjective Goblin graph scores_<br> 🟩🟩🟩🟩🟩 __Popularity Rating__ <br> 🟩🟩🟩🟩🟩 __Utility Rating__ <br> 🟩🟩⬜⬜⬜ __MacGuyver Rating__ |
| <a href="kpi-cards/dynamic-subtitles/"><img src="kpi-cards/dynamic-subtitles/dynamic-subtitles.png"/></a> |__Dynamic subtitles__ | Similar to dynamic titles, dynamic subtitles simply allow you to provide an extra line of text. You should be wary that you don't over-use these, making your visuals busy and increasing the time it takes for a user to read and interpret the card. The example in the image is too busy to be an effective KPI card, for example. <br><br> _Subjective Goblin graph scores_<br> 🟩🟩🟩🟩🟩 __Popularity Rating__ <br> 🟩🟩🟩🟩🟩 __Utility Rating__ <br> 🟩🟩⬜⬜⬜ __MacGuyver Rating__ |
| <a href="kpi-cards/kpi-bar/"><img src="kpi-cards/kpi-bar/kpi-bar.png"/></a> |__KPI bar__ | The standard bar chart, using dynamic (sub)titles to turn it into a KPI card. <br><br> _Subjective Goblin graph scores_<br> 🟩🟩🟩⬜⬜ __Popularity Rating__ <br> 🟩🟩🟩⬜⬜ __Utility Rating__ <br> 🟩⬜⬜⬜⬜ __MacGuyver Rating__ |
| <a href="kpi-cards/kpi-bullet/"><img src="kpi-cards/kpi-bullet/kpi-bullet.png"/></a> |__KPI bullet__ | Horizontal bar chart turned into a simple bullet chart by using error bars. Bullet charts are typically more effective than adjacent bar charts for target comparisons. <br><br> _Subjective Goblin graph scores_<br> 🟩🟩🟩⬜⬜ __Popularity Rating__ <br> 🟩🟩🟩⬜⬜ __Utility Rating__ <br> 🟩🟩⬜⬜⬜ __MacGuyver Rating__ |
| <a href="kpi-cards/kpi-doughnut/"><img src="kpi-cards/kpi-doughnut/kpi-doughnut.png"/></a> |__KPI doughnut__ | The standard doughnut chart, using dynamic (sub)titles to turn it into a KPI card. Doughnuts and pies are often dismissed without consideration, but can still be effective with 3 or fewer categories, depending on your use-case. <br><br> _Subjective Goblin graph scores_<br> 🟩🟩⬜⬜⬜ __Popularity Rating__ <br> 🟩🟩🟩⬜⬜ __Utility Rating__ <br> 🟩⬜⬜⬜⬜ __MacGuyver Rating__ |
| <a href="kpi-cards/kpi-gauge/"><img src="kpi-cards/kpi-gauge/kpi-gauge.png"/></a> |__KPI gauge__ | The standard gauge chart, using dynamic (sub)titles to turn it into a KPI card. Gauges are often dismissed as bad practice, but can still be an effective alternative to a bullet chart, depending on your use-case. <br><br> _Subjective Goblin graph scores_<br> 🟩🟩⬜⬜⬜ __Popularity Rating__ <br> 🟩🟩🟩⬜⬜ __Utility Rating__ <br> 🟩⬜⬜⬜⬜ __MacGuyver Rating__ |
| <a href="kpi-cards/kpi-sparkline-trend/"><img src="kpi-cards/kpi-sparkline-trend/kpi-sparkline-trend.png"/></a> |__KPI sparkline trend__ | The table visual, using the 'Insert' tab to add a Sparkline. Note that sparklines can create heavier visual DAX queries in some reports, having a high performance cost. Furthermore, they can be misleading, as they don't share a Y-axis range, and can't have labels. A good alternative can be creating your own custom SVG sparkline microvisualization; however, this requires additional effort and complexity. Sparklines can be very valuable. <br><br> _Subjective Goblin graph scores_<br> 🟩🟩⬜⬜⬜ __Popularity Rating__ <br> 🟩🟩🟩⬜⬜ __Utility Rating__ <br> ⬜⬜⬜⬜⬜ __MacGuyver Rating__ |
| <a href="kpi-cards/kpi-trend-bar/"><img src="kpi-cards/kpi-trend-bar/kpi-trend-bar.png"/></a> |__KPI trend bar__ | A bar chart for a (typically) non-continuous trend. Typically, this should also highlight a specific data point, like the latest month, or an anomolous value (highest/lowest). Consider using dynamic subtitles to provide effective context about the trend, but ensure that this isn't misleading. Define clearly what "trending down" or "up" means for users. You can also use this approach to show the magnitude difference between select TopN categories. <br><br> _Subjective Goblin graph scores_<br> 🟩🟩🟩⬜⬜ __Popularity Rating__ <br> 🟩🟩🟩⬜⬜ __Utility Rating__ <br> 🟩🟩⬜⬜⬜ __MacGuyver Rating__ |
| <a href="kpi-cards/kpi-trend-comparison/"><img src="kpi-cards/kpi-trend-comparison/kpi-trend-comparison.png"/></a> |__KPI trend comparison__ | Standard line chart comparing 2-3 series. Ensure that you take means to make the comparison easy to read and interpret, so that it doesn't become less effective than a full line-chart with axis labeling. <br><br> _Subjective Goblin graph scores_<br> 🟩🟩🟩⬜⬜ __Popularity Rating__ <br> 🟩🟩🟩⬜⬜ __Utility Rating__ <br> 🟩🟩⬜⬜⬜ __MacGuyver Rating__ |
| <a href="kpi-cards/kpi-trend-line/"><img src="kpi-cards/kpi-trend-line/kpi-trend-line.png"/></a> |__KPI trend line__ | The standard line or area chart, but using dynamic (sub)titles to turn it into a KPI. This can be a very effective way to call out a number, but still show the trend, beneath it. This is a very popular and effective approach. Consider using methods to label the latest data point, or whichever data point is being called out in the (sub)title. <br><br> _Subjective Goblin graph scores_<br> 🟩🟩🟩🟩🟩 __Popularity Rating__ <br> 🟩🟩🟩🟩⬜ __Utility Rating__ <br> 🟩⬜⬜⬜⬜ __MacGuyver Rating__ |
| <a href="kpi-cards/repeated-text/"><img src="kpi-cards/repeated-text/repeated-text.png"/></a> |__Repeated text__ | Using DAX methods to dynamically repeat text, showing the value as the count of characters. This can be an effective alternative to show numbers that are typically low and you want to visually draw attention to in a unique way. An example could be "issues" or "bugs" when doing testing, or "critical incidents in the last 24h" in a service desk report. This isn't so popular, but it's worth considering. <br><br> _Subjective Goblin graph scores_<br> 🟩⬜⬜⬜⬜ __Popularity Rating__ <br> 🟩🟩🟩⬜⬜ __Utility Rating__ <br> 🟩⬜⬜⬜⬜ __MacGuyver Rating__ |
| <a href="kpi-cards/star-rating-text/"><img src="kpi-cards/star-rating-text/star-rating-text.png"/></a> |__Star rating text__ | Using DAX approaches to create a star rating with unicode characters. This is best done when you have literal ratings, like from customers for products or stores. The DAX can be complex, but it's a pattern that's easy to re-use. <br><br> _Subjective Goblin graph scores_<br> 🟩🟩⬜⬜⬜ __Popularity Rating__ <br> 🟩🟩⬜⬜⬜ __Utility Rating__ <br> 🟩⬜⬜⬜⬜ __MacGuyver Rating__ |
| <a href="kpi-cards/waffle-text/"><img src="kpi-cards/waffle-text/waffle-text.png"/></a> |__Waffle text__ | Using line breaks and unicode characters to dynamically display a waffle chart out of text characters. This goes a bit beyond what is tolerable in a production solution, but can be a creative alternative to other waffle chart approaches. Consider using a waffle chart like this when you want to visualize progress or achievement, but not where overachievement is possible. <br><br> _Subjective Goblin graph scores_<br> 🟩🟩⬜⬜⬜ __Popularity Rating__ <br> 🟩🟩⬜⬜⬜ __Utility Rating__ <br> 🟩🟩🟩⬜⬜ __MacGuyver Rating__ |

<br><br>

### Core visuals - SVG measures
These use a combination of formatting options as well as SVG custom microvisualizations rendered as image URLs in the core visuals. 

**These SVG measure templates were created by Štěpán Rešl.**

<a href="kpi-cards/all-kpi-card-templates/"><img src="kpi-cards/all-kpi-card-templates/KPIs and Cards in Power BI (SVGs).png"/></a>

<br><br>

## Remark
I don't consider myself a "dataviz person"; these comments are my subjective opinions and experience. I'm just sharing these templates because they might be helpful to others.