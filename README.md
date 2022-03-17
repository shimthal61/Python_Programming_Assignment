# Python_Programming_Assignment

The data in the file python_assignment_1.csv are from a 2 x 2 repeated measures design.
The first factor is ‘prime’ which can be either ‘positive’ or ‘negative’, and the second factor is
‘target’ which can be either ‘positive’ or ‘negative’. The columns in the data file are labelled
‘participant’, ‘prime’, ‘target’, and ‘rt’ (which is our dependent variable and measured in
milliseconds).

148 participants responded to a target image that was either positive or negative in valence. The
target was preceded by a prime that was either also positive or negative in valence. We want to
determine whether people responded faster to positive images following a positive prime (relative
to following a negative prime), and faster to negative images following a negative prime (relative to
following a positive prime).

Your main Python script should be as follows:

my_data = read_my_data("python_assignment_1.csv")
run_my_anova(my_data)
pairwise_comparisons(my_data)

You need to write three Python functions: read_my_data(), run_my_anova(), and
pairwise_comparisons(). The first function should read in the .csv data file. The second
function should print the descriptive statistics, produce a visualisation of the data, and perform (and
report the results of) the appropriate repeated measures ANOVA to determine whether there is a
priming effect in our dataset. The third function should perform and report the appropriate pairwise
comparisons to allow you to interpret the ANOVA.

Write your functions and the script above in a Jupyter Notebook, execute it, download it as HTML
and submit this HTML file to Blackboard. In addition to your code and output, be sure to include
narrative explaining your code and interpreting the output produced. 