# Matplotlib-interview-questions

1. What is Matplotlib?

Definition:
Matplotlib is a Python library used for data visualization, allowing creation of line plots, bar charts, scatter plots, histograms, etc.

🔵 2. What is pyplot?

Definition:
matplotlib.pyplot is a module that provides easy-to-use plotting functions, similar to MATLAB.

Example:

import matplotlib.pyplot as plt

🔵 3. What is a figure and axes in Matplotlib?

Figure: The entire canvas (overall window).

Axes: The individual plot area (graph inside the figure).

🔵 4. Difference between figure and subplot?

figure → full window

subplot → multiple plots inside a figure arranged in rows/columns

🔵 5. How to create a simple plot?
plt.plot(x, y)

🔵 6. How to label axes and title?
plt.xlabel("X-axis")
plt.ylabel("Y-axis")
plt.title("My Plot")

🔵 7. What is plt.show()?

Definition:
Displays the plot window.

🔵 8. How to change the figure size?
plt.figure(figsize=(6,4))

🔵 9. What is a line plot?

Definition:
A plot that shows trend of continuous data using lines.

plt.plot(x, y)

🔵 10. What is a scatter plot?

Definition:
A plot showing relationship between two variables using dots.

plt.scatter(x, y)

🔵 11. What is a bar plot?



Definition:
Plot representing categorical values using bars.

plt.bar(categories, values)

🔵 12. What is a histogram?

Definition:
Plot showing distribution of continuous data.

plt.hist(data, bins=10)

🔵 13. What is a box plot?

Definition:
Shows distribution, median, and outliers.

plt.boxplot(data)

🔵 14. What is a heatmap?

Definition:
Color-coded representation of values in a matrix.

🔵 15. What is a pie chart?

Definition:
Displays parts of a whole in circular format.

plt.pie(values)

🔵 16. How to add a legend?
plt.legend()

🔵 17. How to customize color, line style, marker?
plt.plot(x, y, color='red', linestyle='--', marker='o')

🔵 18. What is plt.subplots()?

Definition:
Creates multiple plots in one figure.

fig, ax = plt.subplots(2, 2)

🔵 19. What is tight_layout()?

Definition:
Automatically adjusts spacing between subplots.

plt.tight_layout()

🔵 20. How to save a plot?
plt.savefig("plot.png")

🔵 21. What is the difference between plt.plot() and ax.plot()?

plt.plot() → functional API

ax.plot() → Object-oriented API

🔵 22. What is rcParams?

Definition:
Global Matplotlib configuration settings (font size, color, style).

🔵 23. What is style use in Matplotlib?

Definition:
Predefined themes for plots.

plt.style.use("ggplot")

🔵 24. What are ticks in Matplotlib?

Definition:
Values shown on x-axis and y-axis.

plt.xticks()
plt.yticks()

🔵 25. What is annotate()?

Definition:
Add text notes on plot.

plt.annotate("Point", (x,y))

##################################
1. What is Matplotlib?

A Python library used for creating static, animated, and interactive visualizations.

2. What is pyplot in Matplotlib?

A module offering a simple interface for creating plots, similar to MATLAB.

3. What is a Figure?

The entire visual area or canvas that holds one or more plots.

4. What is an Axes?

The actual plotting area inside a figure where data is drawn.

5. What are subplots?

Multiple individual plotting areas arranged inside a single figure.

6. What is a line plot?

A chart that represents data trends using continuous lines.

7. What is a scatter plot?

A visualization that displays the relationship between two variables using dots.

8. What is a bar plot?

A chart representing categorical data with rectangular bars.

9. What is a histogram?

A chart showing the distribution of numerical data across bins.

10. What is a box plot?

A summary chart showing median, quartiles, and outliers of a dataset.

11. What is a heatmap?

A visualization that uses color to represent values within a matrix.

12. What is a pie chart?

A circular chart showing parts of a whole as slices.

13. What is a legend?

A descriptive guide that identifies the plotted elements by name or color.

14. What is labeling in Matplotlib?

Adding text to axes, titles, and plots to explain data.

15. What is figure size?

The dimensions of the plotting area measured in inches.

16. What are markers in plots?

Symbols used to represent individual data points.

17. What is line style?

The pattern of the plotted line, such as solid, dashed, or dotted.

18. What is plt.subplots()?

A function that creates a figure with one or more axes arranged in a grid.

19. What is tight_layout()?

A function that adjusts spacing so subplots do not overlap.

20. What is savefig()?

A function to save a figure to an external file.

21. What are ticks (xticks/yticks)?

Location markers on the x-axis and y-axis.

22. What is annotation?

Adding explanatory text or labels to specific plot points.

23. What are rcParams?

Global configuration settings that control Matplotlib’s default styles.

24. What are styles in Matplotlib?

Predefined themes that change the overall appearance of plots.

25. What is the difference between Figure and Axes?

Figure is the entire canvas; Axes is the individual plotting area within the figure.
