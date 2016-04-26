Trans-Code.github.io
====================

## Developer usage

This site is compiled with Jekyll.

Ensure you have Ruby installed, and the repo cloned locally.

```sh
cd /path/to/trans-code.github.io

# Install the dependancies
gem install bundler
bundle install

# Run the site compiler
bundle exec jekyll server --watch

# Now go to localhost:4000
```


## Adding a new project idea

To add a new idea to the Hackday Ideas page edit the `_data/ideas.yml` file
with your idea, and then send us a pull request.

If you don't feel comfortable using git and making pull requests open a
[Github issue][new-issue] with your idea, and we'll add it to the list.

[new-issue]: https://github.com/Trans-Code/Trans-Code.github.io/issues/new
