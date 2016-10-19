# pie-project
Central project planning for the PIE Framework using Zenhub

# Set Up

Install the Zenhub extension for Chrome or Firefox: https://www.zenhub.com/

Once installed, see the [Boards](https://github.com/PieLabs/pie-project#boards) tab above to view the PIE Project boards.

# Adding Issues

Any issues that are cross-cutting concerns across repositories should be added to the `pie-project` repository.
If they only relate to one code-base they should be added to that repository.

# Labels & Milestones

Common cross-repository labels and milestones are set using `github-sync-labels-milestones`.

`GITHUB_TOKEN` must be set as an env with a github token that has write permissions to the repositories.

```shell
> npm run sync-github
```

Labels and milestones are defined in milestones-labels.json

# Milestones 

Repository-specific milestones should include their repository name, e.g. `pie-cli-1.0`

