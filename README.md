<p align="center">
  <img src="docs/res/github-graph.png">
</p>

Fork of the https://github.com/actions/runner none of this is mine. Just experimenting setting up this runner here. Works the same as the original (hopefully). 

# GitHub Actions Runner

[![Code Scanning - Action](https://github.com/devicemanager/runner/actions/workflows/codeql.yml/badge.svg)](https://github.com/devicemanager/runner/actions/workflows/codeql.yml)

[![Runner CI](https://github.com/devicemanager/runner/actions/workflows/build.yml/badge.svg)](https://github.com/devicemanager/runner/actions/workflows/build.yml)

The runner is the application that runs a job from a GitHub Actions workflow. It is used by GitHub Actions in the [hosted virtual environments](https://github.com/actions/virtual-environments), or you can [self-host the runner](https://help.github.com/en/actions/automating-your-workflow-with-github-actions/about-self-hosted-runners) in your own environment.

## Get Started

For more information about installing and using self-hosted runners, see [Adding self-hosted runners](https://help.github.com/en/actions/automating-your-workflow-with-github-actions/adding-self-hosted-runners) and [Using self-hosted runners in a workflow](https://help.github.com/en/actions/automating-your-workflow-with-github-actions/using-self-hosted-runners-in-a-workflow)

Runner releases:

(these are the orignal links from the actions project, I would have to replace these with mine if I get my head wrapped around the actions scripts. Then this comment wille be different and download links point my runs. But if I find out something that would be smart to use for others as well I would probably create a PR and submit to the origin of this fork. So far nothing happening here.)

![win](docs/res/win_sm.png) [Pre-reqs](docs/start/envwin.md) | [Download](https://github.com/actions/runner/releases)  

![macOS](docs/res/apple_sm.png)  [Pre-reqs](docs/start/envosx.md) | [Download](https://github.com/actions/runner/releases)  

![linux](docs/res/linux_sm.png)  [Pre-reqs](docs/start/envlinux.md) | [Download](https://github.com/actions/runner/releases)

## Contribute

We accept contributions in the form of issues and pull requests. The runner typically requires changes across the entire system and we aim for issues in the runner to be entirely self contained and fixable here. Therefore, we will primarily handle bug issues opened in this repo and we kindly request you to create all feature and enhancement requests on the [GitHub Feedback](https://github.com/community/community/discussions/categories/actions-and-packages) page. [Read more about our guidelines here](docs/contribute.md) before contributing.
