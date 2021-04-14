# Dynamic Config using `circleci config pack`

Boilerplate code to build a config file for a continuation workflow.

The .circleci directory contains subdirectories that are the building blocks for pipelines that can be used depending on conditions. 

Intended usage is to specify which you'd like to build, build and validate the config, and then to filter that pipeline further at the worfklow and step level based on parameters that are passed in.

Ways to filter further:
* parameterized resource sizes based on branch (see primary/executors/default.yml)
* conditional workflows (see primary/workflows/*)
