# Evaluating FiveThirtyEight's Pulitzer Circulation Data with scikit-learn

### Background

The accompanying Jupyter Notebook links to Nate Silver's dataset from the 2014 report, 'Pulitzer Prizes Don't Lure Readers.' Silver's article evaluates whether the number of Pulitzer prizes won by journalists from given newspapers is related to the change in circulation of these newspapers between 2004 and 2013. The author finds a weak correlation supported only by the corresponding growth of the New York Times.

### Methodology

My approach, with linear regression provided by scikit-learn, examines instead the competition between different newspapers within the same years: if awards reflect popularity or vice versa, one would expect correlations within the industry to occur at the same time as well. This correlation is even <i>weaker</i> than the already-weak correlation Silver found, with a completely insignificant R^2 score for the 1990-2003 data and a barely salient one for 2004-2014.

### Conclusions

It is probably safe to conclude that chasing such awards is not a particularly useful business strategy for publishers.
