# CI/CD Playground

this is a playground for me to test ci/cd related items.
If I bother too I will make mention of them here.

# renovate

anything related to testing out renovate configurations and
related resources will go into the renovate/ directory with
`/.github/renovate.json5` being the configuration.

# workflow-trigger

* `/workflow-trigger`
* `/.github/workflows/build.yaml`
* `/.github/workflows/trigger.yaml`

this is testing _gitops in actions_ using actions to trigger
workflows in _other_ repositories, alter repository, commit
and/or create a pull request for changes.

# path-filter

`dorny/path-filter` testing for running matrix jobs only on
changed paths.
