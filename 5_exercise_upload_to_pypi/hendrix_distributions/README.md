## Package Name: `distributions`

### Description:
`distributions` is a Python package that provides functionalities for working with both binomial and Gaussian distributions. This package includes classes for calculating, visualizing, and performing operations on these distributions.

### Installation:
You can install `distributions` via pip:

```
pip install distributions
```

### Usage:
Once installed, you can import and use the functionalities provided by `distributions` in your Python scripts or interactive sessions:

```python
from distributions import Binomial, Gaussian

# Create a binomial distribution
binom_dist = Binomial(prob=0.7, size=30)

# Print the characteristics of the distribution
print(binom_dist)  

# Plot the probability mass function
binom_dist.plot_bar_pdf()

# Create a Gaussian distribution
gaussian_dist = Gaussian(mean=0, stdev=1)

# Print the characteristics of the distribution
print(gaussian_dist)

# Plot the probability density function
gaussian_dist.plot_histogram_pdf()
```

### Contributing:
Contributions to `distributions` are welcome! If you'd like to contribute new features, fix bugs, or improve documentation, please feel free to submit a pull request on GitHub.

### License:
`distributions` is licensed under the MIT License. See the LICENSE file for details.

### Contact:
For any inquiries or feedback, you can contact the maintainers at hendrixobuks@gmail.com.