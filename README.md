# Project 2 - Ames Housing Data and Kaggle Challenge

## The Modeling Process

1. The train dataset has all of the columns that you will need to generate and refine your models. The test dataset has all of those columns except for the target that you are trying to predict in your Regression model.
2. Generate your regression model using the training data. We expect that within this process, you'll be making use of:
    - train-test split
    - cross-validation / grid searching for hyperparameters
    - strong exploratory data analysis to question correlation and relationship across predictive variables
    - code that reproducibly and consistently applies feature transformation (such as the preprocessing library)
3. Predict the values for your target column in the test dataset and submit your predictions to Kaggle to see how your model does against unknown data.
    - **Note**: Kaggle expects to see your submissions in a specific format. Check the challenge's page to make sure you are formatting your CSVs correctly!
    - **You are limited to models you've learned in class**. In other words, you cannot use XGBoost, Neural Networks or any other more advanced model for this project.
4. Evaluate your models!
    - consider your evaluation metrics
    - consider your baseline score
    - how can your model be used for inference?
    - why do you believe your model will generalize to new data?

## Submission

- Presentation will be delivered starting at 0900 on **Friday 16 April**. 
- Your technical report must be submitted in your submission repository by 23:59 on **Friday 16 April**.
- The Kaggle competition will close by midnight **Friday 16 April**.

Your technical report must include:

- A README.md (that isn't this file)
- Jupyter notebook(s) with your analysis and models (renamed to describe your project)
- Data files
- Presentation slides
- Any other necessary files (images, etc.)


---

## Presentation Structure

- **Must be within time limit established by local instructor.**
- Use Google Slides or some other presentation system (Keynote, Powerpoint, etc).
- Consider your audience. 
- Start with the **problem** you are solving.
- Use visuals that are appropriately scaled and interpretable.
- Talk about your procedure/methodology (high level).
- Talk about your primary findings.
- Make sure you provide **clear recommendations** that follow logically from your analyses and narrative and answer your data science problem.

Be sure to rehearse and time your presentation before class.

---

## Rubric
Your local instructor will evaluate your project (for the most part) using the following criteria.  You should make sure that you consider and/or follow most if not all of the considerations/recommendations outlined below **while** working through your project.

**Scores will be out of 27 points based on the 9 items in the rubric.** <br>
*3 points per section*<br>

| Score | Interpretation |
| --- | --- |
| **0** | *Project fails to meet the minimum requirements for this item.* |
| **1** | *Project meets the minimum requirements for this item, but falls significantly short of portfolio-ready expectations.* |
| **2** | *Project exceeds the minimum requirements for this item, but falls short of portfolio-ready expectations.* |
| **3** | *Project meets or exceeds portfolio-ready expectations; demonstrates a thorough understanding of every outlined consideration.* |

### The Data Science Process

**Problem Statement**

I have clients who want to invest in houses either by selling or buying.  They want to know what features are going to most influence the price of the house.  The information I am presenting should help them to make an informed decision.
The goal of this project is to help my clients find a desired house for a decent price by building a regression model that will best predict the sale price.  The data I use is from Ames Housing Spreadsheet


**Data Cleaning and EDA**
- Are missing values dealt with?
- Are important distributions examined and described?
- Are outliers identified and addressed?
- Are appropriate summary statistics provided?
- Are possible modeling insights to investigate discussed?

**Preprocessing and Modeling**
- Are categorical variables one-hot encoded or encoded in another logical way?
- Are features engineered?
- Have the data been scaled appropriately?
- Does the student properly split the data for validation/training purposes?
- Does the student use feature selection to remove noisy or multi-collinear features?
- Does the student test and evaluate a variety of model types (**AT MINIMUM:** linear regression, lasso, and ridge)?
- Does the student defend their choice of the best model for this data and problem statement?
- Does the student explain how the model works and evaluate its performance successes/downfalls?

**Evaluation and Conceptual Understanding**
- Does the student accurately identify and explain the baseline score?
- Does the student select and use metrics relevant to the problem statement?
- Is more than one metric uses to better assess performance?
- Does the student correctly interpret the results of their model for purposes of inference?

**Conclusion and Recommendations**

I have identified what features are the best predictors of housing price.  I have addressed missing data and outliers and improved my model by Ridge and Lasso.  I finally have created a regression model and was able to generate new data to predict sale price.  Now I can recommend the following to my clients:

- Invest in a house with a large living area  
- Invest in a house that has good overall quality
- Invest in a house that was built recently
- Invest in a house that has more full bath rooms
- Invest in a house with higher basement square footage 


### Organization and Professionalism

**Project Organization**
- Are modules imported correctly (using appropriate aliases)?
- Are data imported/saved using relative paths (so someone can replicate your analysis)?
- Does the README provide a good executive summary of the project?
- Is Markdown formatting and comments used appropriately to communicate in the notebooks?
- Are files & directories organized?
- Are unnecessary files included?
- Do files and directories have well-structured, appropriate, consistent names?

