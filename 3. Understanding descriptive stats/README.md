# Objective

The objective of this practical is to analyze and interpret a Student Rating dataset using Pandas and Matplotlib. The practical focuses on understanding relationships between professor tenure, minority status, age, gender, and evaluation scores.

# What I Did

In this practical, I worked with the Student Rating dataset containing information about professors, including their age, gender, minority status, tenure status, and evaluation scores. The dataset was loaded into a Pandas DataFrame for analysis.

First, I calculated the percentage of visible minority professors who were tenured and compared it with the tenure percentage of non-minority professors. The analysis showed that 84.375% of visible minority professors were tenured, compared to 76.94% of non-minority professors.

Next, I grouped the professors according to their tenure status and calculated the mean age and standard deviation for both groups. The mean age of untenured professors was 50.19 years with a standard deviation of 6.95, while the mean age of tenured professors was 47.85 years with a standard deviation of 10.42.

I then visualized the age variable using a histogram because age is a numerical variable and a histogram is suitable for showing its distribution.

For the categorical gender variable, I used bar graphs to visualize the number of professors in each gender category. I also compared `pyplot.bar()` and `pyplot.barh()`, where `bar()` creates vertical bars and `barh()` creates horizontal bars.

Finally, I filtered the dataset to include only tenured professors and calculated their median evaluation score. The median evaluation score was found to be 4.0.

# Conclusion

Through this practical, I applied Pandas and Matplotlib to perform basic statistical analysis and data visualization on the Student Rating dataset. I revised concepts such as filtering, grouping, mean, standard deviation, median, cross-tabulation, histograms, and bar charts. The practical also helped me understand how different types of variables require different methods of visualization and analysis.
