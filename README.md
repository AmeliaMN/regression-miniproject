Regression mini-project
================
Professor McNamara

Last mini-project, I gave you a separate README.md file, which explained
what types of files I wanted. This time, I would like the README to
**be** your mini-project, so that your analysis shows on the front page
of your GitHub repo.

My suggestion is to leave this text in this document until you are
finished with your work, then remove it and commit as your final commit.
(In other words, I don’t want the instructions to appear in your final
submission.)

Like last time, I would like the GitHub repo to eventually contain

  - an RMarkdown document (this document, but with content\!)
  - a knitted document in GitHub-flavored-markdown (README.md)
  - the image file(s) for any visualizations you produce

## 1\. Reading in data

Find and import a dataset for this mini project. I don’t care what data
you use, but here are a few suggestions:

  - use the Pew data from the last mini project, or find another Pew
    survey that interests you
  - use data from the General Social Survey (not my little sample, go
    get your own)
  - search on Google dataset search for “survey” + some word that
    interests you

## 2\. Data wrangling

Do whatever data wrangling is necessary to prepare your data for
modeling. No matter which type of model you will be using, I would like
you to make sure that the reference level makes sense. This may require
a `fct_relevel`. If your data includes ordinal categorical variables,
you will need to ensure the ordering for those variables is correct.

## 3\. Visualization

Produce at least one visualization that shows the relationship between
your response variable and at least one of your explanatory variables.
You may end up fitting a model with multiple explanatory variables, but
you do not need to attempt to visualize all the relationships. Pick the
one or two that are most interesting.

Explain in words what the visualization shows.

## 4\. Modeling

Fit and explain your best model. I would prefer that your model beat the
mean or null model, but if you try many models and can’t find one that
is better than the null, that’s okay.

I do not want to see the entire process of trying many models. It’s fine
to include multiple code chunks with multiple models as you work, but
for your final commit please make sure it’s just the best one.

Display the output of your model, and interpret at least one (ideally
more than one) coefficient in words.

Show how well your model does, and compare it to a null model.
