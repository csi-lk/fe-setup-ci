# Setup CI

A [action.yml file]('./action.yml') that creates a [Github composite run](https://docs.github.com/en/free-pro-team@latest/actions/creating-actions/metadata-syntax-for-github-actions#runs-for-composite-run-steps-actions) so we can simplify all Github Actions pipelines for front end repos.

It has to be in it's own repo due to [Github's convoluted way you have to set it up for usage](https://docs.github.com/en/free-pro-team@latest/actions/creating-actions/creating-a-composite-run-steps-action#creating-an-action-metadata-file)
