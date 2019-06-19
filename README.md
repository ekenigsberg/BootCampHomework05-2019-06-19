# BootCampHomework05-2019-06-19

[Jupyter Notebook Solution](https://github.com/ekenigsberg/BootCampHomework05-2019-06-19/blob/master/Pymaceuticals.ipynb)<br/>
to<br/>
[Data Analytics Boot Camp Homework #5](https://github.com/the-Coding-Boot-Camp-at-UT/UTAMCB201904DATA3/tree/master/05-Matplotlib/Homework/Instructions)

# Pymaceuticals Analysis

* **Capomulin and Ramicane showed strong results well outside the boundaries of standard error in all three dimensions studied** over the 45-day study:
  * Tumor Volume
  * Metastatic Sites
  * Survival Rate
* Other drugs showed weak positive results:
  * Infubinol and Stelasyn had a lower number of Metastatic Sites than the mean
  * Zoniferol slightly bettered the mean Survival Rate
* The unmistakable 60-percentage-point reduction in Tumor Volumes produced by Capomulin and Ramicane compared to all other protocols (including the placebo) **strongly suggest a causal relationship between (1) administering Capomulin and Ramicane and (2) reducing the size, and limiting the number of sites, of squamous cell carcinomas.**
![Tumor Volume](https://github.com/ekenigsberg/BootCampHomework05-2019-06-19/blob/master/Pymaceuticals01-Tumor%20Volume.png)
![Metastatic Sites](https://github.com/ekenigsberg/BootCampHomework05-2019-06-19/blob/master/Pymaceuticals02-Metastatic%20Sites.png)
![Survival Rate](https://github.com/ekenigsberg/BootCampHomework05-2019-06-19/blob/master/Pymaceuticals03-Survival%20Rate.png)
![Percent Change in Tumor Volume](https://github.com/ekenigsberg/BootCampHomework05-2019-06-19/blob/master/Pymaceuticals04-Percent%20Change.png)

Two observations:
* Following the [Better Way to Add Labels to Bar Charts](http://composition.al/blog/2015/11/29/a-better-way-to-add-labels-to-bar-charts-with-matplotlib/) caused my bars to disappear and leave data labels floating in space.
  * I worked around the problem by adding my data values to the X-axis labels.
  * I think my graph behaved strangely because I drew the bars individually (so that Python logic could selectively make the bars red or green).
  * I think the graph might have supported the data labels if I'd stored the negative values in one list, the positive values in a separate list, and then shown the data as a stacked bar graph.
* The graphs appear somewhat differently in the Jupyter Notebook than they appear when saved as images. sigh
