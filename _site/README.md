# The Official Site of cheminfIBB Organisation

## Table of Contents

[Contributing](#contributing)

[Local preview](#local-preview)

## Contibuting

Only the members of the cheminfIBB are allowed to contribute. Please follow the instructions from the [contributing guidelines](CONTRIBUTING.md).

## Local Preview

1. Install ruby.

1. Add following lines to your ```~/.bashrc``` file so that you can install gems locally:

> ```.gems``` directory name is just a convention.

```bash
export GEM_HOME=$HOME/.gems

export PATH="$GEM_HOME/bin:$PATH"
```

1. Install ```bundler``` with ```gem install bundler```.

> You might need to

1. Go to the repository and run ```bundle install```.

1. Run ```bundle exec jekyll serve --incremental```.

1. Go to ```localhost:4000``` in your browser.
