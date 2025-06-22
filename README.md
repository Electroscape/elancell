# elancell-com

Prerequisits:

Make sure gem is installed and added to the path:
`Bash
export GEM_HOME="$HOME/.gem"
export PATH="$HOME/.gem/bin:$PATH"
`

Upgrade Ruby to 3.4.4 and gem to 3.6.9 `gem update --system`
run `gem install jekyll bundler`

If no Gemfile in the folder, create one with `bundle init` and add `gem "jekyll"` in it
run `bundle` to create `Gemfile.lock`

## With Jeykll

- `jekyll build` - Builds the site and outputs a static site to a directory called _site.
- `jekyll serve` - Does jekyll build and runs it on a local web server at <http://localhost:4000>, rebuilding the site any time you make a change.

When you’re developing a site, use jekyll serve. To force the browser to refresh with every change, use jekyll serve --livereload. If there’s a conflict or you’d like Jekyll to serve your development site at a different URL, use the --host and --port arguments, as described in the [serve command options](https://jekyllrb.com/docs/configuration/options/#serve-command-options).
