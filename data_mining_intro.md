# Data Mining

## CRISP-DM

The CRoss Industry Standard Process for Data Mining (CRISP-DM) is a process model with six phases that describes the data science life cycle.

![CRISP-DM](https://www.datascience-pm.com/wp-content/uploads/2021/02/CRISP-DM.png)

| **Phase**               | **Tasks**                                      |
|------------------------|-----------------------------------------------|
| **Business Understanding** | Business objectives, Assessment, Data mining goals, Project plan |
| **Data Understanding**     | Collect, Describe, Visualize, Verify quality |
| **Data Preparation**       | Select, Clean, Integrate, Format, Standardize/Discretize/Transform, Create new fields |
| **Modeling**               | Select techniques, Test design, Build model, Assess model |
| **Evaluation**             | Evaluate results, Review process, Decide next step |
| **Data Mining**            | Learn from data, Find common patterns, Predict future results |

Common problems: Data quality may be poor, data may be missing or noisy and patterns found may not be exact, not useful or simply not interesting

### Common data mining tasks
- Predictive
  - **Classification** Predict the class
  - **Regression** Predict a number
  - **Time Series Analysis** Predict next value in the series
- Descriptive
  - **Clustering** Grouping by similarities
  - **Summarization** Summarize and generalize data
  - **Association Rules** Discover connection between items
  - **Sequence Discovery** Find patterns in sequential data

## Data Cleaning
1. Import data
2. Merge datasets
3. Handle missing data
4. Standardization
5. Normalization
6. Remove duplicates

## Data Transformation
- **Transforming** Applying a function to an attribute
- **Summarizing** Grouping
- **Discretization**
  - Transform numeric values into categorical ones
  - Binarizing
  - Binning
- **Handle missing values**
  - Remove records
  - Imputation
    - Replace by a value
    - Use median/mean
    - Predict using kNN
- **Standardization** Substitute values by the *Z score*
- **Normalization** Rescale values to the **[0; 1]** interval