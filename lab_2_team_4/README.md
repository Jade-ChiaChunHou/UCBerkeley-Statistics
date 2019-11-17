# lab_2

Exploring election and political data. 

This is a reduced project structure from Driven Data's cookiecutter
data science. If you don't have a reason *not* to use this structure,
give it a try for the project. 

You can read about the ideas behind this project structure,
[here](https://drivendata.github.io/cookiecutter-data-science/). 

# Project Organization

    ├── README.md          <- The top-level README for developers using this project.
	├── data
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── notebooks          <-  Notebooks. These are exploratory. 
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    ├── src                <- Source code for use in this project.
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.R
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.R
  
# Expectations 

## The report 

If you do work that is shown in the `./reports/` section there are two
rules that must be followed. 

1. Have a point
2. Don't suck. 

This is a general mantra that you can try out at other points in your
life too, if you like. 

What does this mean? In the deliverable that you're putting together,
everything that is included needs to be there for a reason and that
reason should be made clear to Alex (your reader). And, if you include
something, it needs to be done right. 

What does *right* look like? Well, that depends on what you're
doing. If you're trying to communicate through a plot or table, that
plot has to be titled, labeled, and *maximally* expressive of the
point that you want to make. If you're trying to communicate through a
model, you should make that model a clear to understand as
possible. If you're trying to communicate through *words* those words
should be carefully chosen! 

## The contribution model 

As a team, this is a good chance for you to start practicing working
within the GitHub workflow. Yes, I understand that this is going to
create additional work in the short-run; but, this is work that if you
do now when the stakes are relatively low, will be paid back later in
the program when the stakes are relatively less low. 

I would like the `master` branch to be the final branch that you, as a
team, issue a PR to show that you are done with the assignment. This
probably means that you should have a `dev` branch that you think of
as the destination for all work that you're doing as you produce your
lab. 

You will then likely want to have additional branches for work that
you are doing, while you are doing it. There are two general ways that
you can organize this: either creating a branch for each task that
you're undertaking, or creating a branch for each person to work on. 

I would recommend that, for this lab, you work with a branch for each
person to work on. That is, if I were working as a part of your team
we would set up the following structure: 

1. We would create a branch for the deveopment of work. `git checkout
   -b dev` 
2. When I was working, I would be working on my own branch. `git
   checkout -b alex` 
3. When I'm done with my work, I would commit this up to the remote
   `git push origin alex` and then issue a pull request to merge the
   `alex` and `dev` branches. 
4. Once the whole team is done with their work, the team would then
   issue a pull request for the entire cleaned and managed `dev`
   branch onto the `master` branch. As the instructor, I will then
   review this pull request. 
