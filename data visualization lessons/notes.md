Course Structure
As this course covers a broad range of ways that data visualizations can be used in the data analysis process, there will also be a large number of topics that will be touched upon. Below is a summary of topics that will be covered in the remaining lessons in this course.

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





## codes


# Lessons 3-5: Exploration of Data
These lessons systematically present core visualizations in exploratory data analysis. Exploration starts with univariate visualizations to identify trends in distribution and outliers in single variables. Bivariate visualizations follow, to show relationships between variables in the data. Finally, multivariate visualization techniques are presented to identify complex relationships between three or more variables at the same time.

# Lesson 6: Explanatory Visualizations
This lesson describes considerations that should be made when moving from exploratory data analysis to explanatory analysis. When polishing visualizations to present to others, you will need to consider what findings you want to focus on and how to use visualization techniques to highlight your main story. This lesson also provides tips for presentation of results and how to iterate on your presentations.

# Lesson 7: Visualization Case Study
In this lesson, you will bring together everything from the previous lessons in an example case study. You will be presented with a dataset and perform an exploratory analysis. You will then take findings from that analysis and polish them up for presentation as explanatory visualizations.
