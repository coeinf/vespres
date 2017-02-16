# Vespres al Col·legi

## Setup

Requires ruby and [bundler](http://bundler.io/).

Clone the repository:

```bash
$ git clone ...
```

Enter to the directory and install dependencies:

```bash
$ cd vespres
$ bundle install
```


## Preview

Use bundler to execute jekyll:

```bash
$ bundle exec jekyll s -H 0.0.0.0 --incremental  --baseurl '' -P 4002
```

Open the browser in [localhost:4002](http://localhost:4002) to see the result.
