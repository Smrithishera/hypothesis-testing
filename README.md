# Hypothesis Testing
Hypothesis Testing is a statistical technique used to draw conclusions about a population based on a sample. It begins with a null hypothesis (H0), which assumes no effect or no difference, and an alternative hypothesis (H1 or Ha), which suggests the presence of an effect or a difference. The process involves analyzing the sample data to decide whether to reject the null hypothesis in favor of the alternative, depending on the probability of obtaining the observed data if the null hypothesis were true.

The dataset is based on the performance of two themes on a website. Our task is to find which theme performs better using Hypothesis Testing.

The dataset consists of 1,000 records with 10 columns, all of which are complete with no missing values. Here's a summary of the numerical columns:

Click Through Rate:

- Range: 0.01 to 0.50
- Mean: ~0.26

Conversion Rate:

- Range: 0.01 to 0.50
- Mean: ~0.25

Bounce Rate:

- Range: 0.20 to 0.80
- Mean: ~0.51

Scroll Depth:

- Range: 20.01 to nearly 80
- Mean: ~50.32

Age:

- Range: 18 to 65 years
- Mean: ~41.5 years

Session Duration:

- Range: 38 seconds to nearly 1800 seconds (30 minutes)
- Mean: ~925 seconds (about 15 minutes)

  Here's a table summarizing the performance comparison between the Light Theme and Dark Theme across various metrics based on hypothesis testing:

| **Metric**             | **Result**                                                                                                      | **P-Value** |
|------------------------|-----------------------------------------------------------------------------------------------------------------|-------------|
| **Click Through Rate** | Statistically significant difference, with the Dark Theme likely performing better.                             | 0.048       |
| **Conversion Rate**    | No statistically significant difference.                                                                        | 0.635       |
| **Bounce Rate**        | No statistically significant difference in Bounce Rates between the themes.                                     | 0.230       |
| **Scroll Depth**       | No statistically significant difference observed in Scroll Depths.                                              | 0.450       |

**Summary**: The Dark Theme shows a slight advantage in engaging users to click through, as indicated by the statistically significant difference in Click Through Rate. However, for other key performance indicators like Conversion Rate, Bounce Rate, and Scroll Depth, the choice between a Light Theme and a Dark Theme does not significantly influence user behavior according to the data.
