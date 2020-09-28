Course Structure
As this course covers a broad range of ways that data visualizations can be used in the data analysis process, there will also be a large number of topics that will be touched upon. Below is a summary of topics that will be covered in the remaining lessons in this course.

---

# Lesson 2: Design of Visualizations
Before getting into the actual creation of visualizations later in the course, this lesson introduces design principles that will be useful both in exploratory and explanatory analysis. You will learn about different data types and ways of encoding data. You will also learn about properties of visualizations that can impact both the clarity of messaging as well as their accuracy.
## Notes

### Visuals can be bad if they:
- Don't convey the desired message.
- Are misleading.

This seems straightforward, but often visuals are created that do one or both of these unintentionally. There is an entire book that was published aimed at misleading visuals: How to Lie with Statistics.

### The Four Levels of Measurement
In order to choose an appropriate plot type or method of analysis for your data, you need to understand the types of data you have. One common method divides the data into four levels of measurement:

1. **Qualitative or categorica**l types (non-numeric types)
   1. **Nominal** data: pure labels without inherent order (no label is intrinsically greater or less than any other)
   2. **Ordinal** data: labels with an intrinsic order or ranking (comparison operations can be made between values, but the magnitude of differences are not be well-defined)
2. **Quantitative or numeric types**
   1. **Interval** data: numeric values where absolute differences are meaningful (addition and subtraction operations can be made)
   2. **Ratio** data: numeric values where relative differences are meaningful (multiplication and division operations can be made)


All **quantitative**-type variables also come in one of two varieties: **discrete and continuous.**

- **Discrete** quantitative variables can only take on a **specific set value**s at some maximum level of precision.
- **Continuous** quantitative variables can (hypothetically) take on values to **any level of precision.**

Distinguishing between continuous and discrete can be a little tricky – a rule of thumb is if there are few levels, and values can't be subdivided into further units, then it's discrete. Otherwise, it's continuous. If you have a scale that can only take natural number values between 1 and 5, that's discrete. A quantity that can be measured to two digits, e.g. 2.72, is best characterized as continuous, since we might hypothetically be able to measure to even more digits, e.g. 2.718. A tricky case like test scores measured between 0 and 100 can only be divided down to single integers, making it initially seem discrete. But since there are so many values, such a feature is usually considered as continuous.

When exploring your data, the most important thing to consider first is whether your data is qualitative or quantitative. In later lessons, you will see how this distinction impacts your choice of plots.

###Visual Encodings

### Examples of chart junk you saw in this video include:
1. Heavy grid lines
2. Unnecessary text
3. Pictures surrounding the visual
4. Shading or 3d components
5. Ornamented chart axes

[More on wiki](https://video.udacity-data.com/topher/2019/November/5dcc693a_chartjunk-wikipedia/chartjunk-wikipedia.pdf)

###data-ink ratio
the higher the bettter

###Design Integrity Notes
One of the main ways discussed here for looking at data integrity was with the lie factor. Lie factor depicts the degree to which a visualization distorts or misrepresents the data values being plotted. It is calculated in the following way:

Flowing Data: [How to Spot Visualization Lies](https://flowingdata.com/2017/02/09/how-to-spot-visualization-lies/)
[More PDFs](https://video.udacity-data.com/topher/2019/November/5dc4a59c_how-to-spot-visualization-lies-flowingdata/how-to-spot-visualization-lies-flowingdata.pdf)

###Using Color

Color can both help and hurt a data visualization. Three tips for using color effectively.

1. Before adding color to a visualization, start with black and white.
2. When using color, use** less intense** colors - not all the colors of the rainbow, which is the default in many software applications.
3. Color for communication. Use color to **highlight** your message and separate groups of interest. Don't add color just to have color in your visualization.
4. Try to use Blue and orange instead of Red and green colors

###Shape, Size, & Other Tools
In general, **color** and **shape** are best for categorical variables, while the **size** of marker can assist in adding additional **quantitative** **data**, as we demonstrated here.

Instead, it might be better to **break the information** into multiple **individual messages**, so the audience can understand every aspect of your message.

---

# Lessons 3-5: Exploration of Data
These lessons systematically present core visualizations in exploratory data analysis. Exploration starts with univariate visualizations to identify trends in distribution and outliers in single variables. Bivariate visualizations follow, to show relationships between variables in the data. Finally, multivariate visualization techniques are presented to identify complex relationships between three or more variables at the same time.

#03.Univariate Exploration of Data Videos
we look here how each variable is distributed before moving on new complex drawing

## barchart and Histogram



# Lesson 6: Explanatory Visualizations
This lesson describes considerations that should be made when moving from exploratory data analysis to explanatory analysis. When polishing visualizations to present to others, you will need to consider what findings you want to focus on and how to use visualization techniques to highlight your main story. This lesson also provides tips for presentation of results and how to iterate on your presentations.

# Lesson 7: Visualization Case Study
In this lesson, you will bring together everything from the previous lessons in an example case study. You will be presented with a dataset and perform an exploratory analysis. You will then take findings from that analysis and polish them up for presentation as explanatory visualizations.
