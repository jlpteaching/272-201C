# Material for EEC 272 / ECE 201C

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

See <http://jlpteaching.github.io/272-201C> for a prettier version of this site.

## Adding a link to the header

Update the `_data/links.yml` file with two new lines:

```yaml
- title: <the title to appear in the link>
  link: <the relative path (Remove the .md from the md file)>
```

## Development of website

To render the website run the following:

```sh
> bundle exec jekyll serve
```

If you don't have the jekyll stuff installed already, you can run the following (assuming you have Ruby gems installed).

```sh
> gem install jekyll bundler
```
