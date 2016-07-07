# Collaboration tutorial

It's a project for a timed list experiment.  Participants have to list as many items from a semantic domain as possible.  The responses are written to a file, one line per response.

The raw files can be found in the folder [data/rawData/animals](https://github.com/seannyD/SeansGitHubTutorial-Collaboration/tree/master/data/rawData/animals).

The name of the file is the participant name/id followed by an underscore, then either 'm' or 'b', indicating if the participant was brought up monolingually or bilingually.

There is an R script for collating and analysing the data in `analysis/R/analyseData.Rmd`, and this writes the results to `results/MainResults.html`.
