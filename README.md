# Ml Mathemetics Basics

Before understanding any machine learning model, it is essential to understand some basic mathematical concepts.

Two of the most important topics are inferential statistics and hypothesis testing

## Inferential Statistics 

When we talk about mean and variance, we usually refer to the sample rather than the entire population. But have we ever wondered why we rely on a sample instead of the full population?

Calculating population parameters is often impractical because it requires a large amount of memory, extensive computation, and significant time. However, by analyzing sample data, we can estimate population parameters with a certain level of confidence—which is often sufficient in practice.

Example:
Let’s say a food inspection team visits a food production factory for a surprise inspection. They want to verify whether the factory is following the ingredient quantities or nutritional values mentioned on the product packaging. Since the factory produces a large number of items, it’s not feasible to test every single product. Instead, the team selects a random sample of products and tests them.
If the sample meets the required standards, the factory is considered compliant. Otherwise, it may be flagged for violating regulations.

This raises another important question: What do we mean by "confidence"? And how can we be sure that a sample actually provides accurate insights about the population?

we will address all those questions here.

Here are the forumals for both populations and sample

#### **Population Statistics**

| Term                | Notation     | Formula                                                                 |
|---------------------|--------------|-------------------------------------------------------------------------|
| Population Size     | $$ N  $$ | Number of items                                                         |
| Population Mean     | $$ \mu    $$| $$ \frac{1}{N} \sum_{i=1}^{N} X_i $$                              |
| Population Variance | $$ \sigma^2 $$ | $$ \frac{1}{N} \sum_{i=1}^{N} (x_i - \mu)^2 $$               |


#### **Sample Statistics**

| Term              | Notation        | Formula                                                                      |
|-------------------|------------------|-------------------------------------------------------------------------------|
| Sample Size       | $$ n  $$     | Number of sampled items                                                       |
| Sample Mean       | $$ \bar{X}   $$ | $ \frac{1}{n} \sum_{i=1}^{n} X_i $                                  |
| Sample Variance   |$$ S^2    $$ | $$ \frac{1}{n - 1} \sum_{i=1}^{n} (X_i - \bar{X})^2 $$                  |


