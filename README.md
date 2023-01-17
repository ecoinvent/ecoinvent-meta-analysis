# Ecoinvent meta-analysis

A repository for analyzing various aspects of ecoinvent, primarily using Brightway. Has the following structure:

* Analysis and notebooks are in `Notebooks`
* Intermediate data files should be stored in `Cache` - make sure you don't commit these files
* Outputs are in `Outputs`

Currently has the following analyses:

## Characterized cumulative elementary flows

This notebook does metaanalysis of the respective importance cumulative, characterized elementary flows.

For each elementary (biosphere) flow, each activity in `ecoinvent-3.9.1-cutoff`, and and each impact category implemented in 3.9.1, we calculate:

* The average normalized score across all activities per flow and impact category
* The median normalized score across all activities per flow and impact category
* The average and median ranks across all activities per flow and impact category

# Authors

* [Chris Mutel](https://github.com/cmutel/)
