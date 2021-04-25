Github badges
![Build-github](https://github.com/buq2/minimal_ci_badges/actions/workflows/main.yml/badge.svg)
![License-github](https://img.shields.io/github/license/buq2/minimal_ci_badges)

GitLab badges
![Gitlab pipeline status](https://img.shields.io/gitlab/pipeline/buq2/minimal_ci_badges/master)

Kinda minimal CI demonstration for getting badges on your project page.

# Usage

1) Clone the repo 
2) Create new Github/GitLab repo page
3) Change padge urls in readme.md to refer to your repo
4) push the modified repo to Github
5) When you go to the project page, you will have a badge. Cool points achieved.

# Github

See it in its full glory [at Github](https://github.com/buq2/minimal_ci_badges).

## What/where?

Check `.github/workflows/main.yml` file which contains workflow definition 
for workflow that is run every time new push is made to the repo.

In the case of this repo, docker image is build and the image is run.
If the container does not return error code, build badge is green, otherwise
red (fail).

You can see actions which have been run in the [actions tab of your repo page](https://github.com/buq2/minimal_ci_badges/actions).

See [Github documentation](https://docs.github.com/en/actions/learn-github-actions)
for more information about GitHub actions.

# Gitlab

See it in its full glory [at GitLab](https://gitlab.com/buq2/minimal_ci_badges).

## What/where?

Check `.gitlab-ci.yml`.

You can see pipelines which have been run in the [pipelines tab/row of your repo page](https://gitlab.com/buq2/minimal_ci_badges/-/pipelines).

See [GitLab documentation about pipelines](https://docs.gitlab.com/ee/ci/pipelines/).

Also check out [GitLabs docs about Docker](https://docs.gitlab.com/ee/ci/docker/using_docker_images.html).


# Shields.io

You might be interested in checking [shields.io](https://shields.io). You can 
search for different badges and then click them to get preview of that
badge of your repo.
