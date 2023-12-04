source "https://rubygems.org"

gem "github-pages", group: :jekyll_plugins
gem "jekyll-include-cache", group: :jekyll_plugins

# V = original from forked min-mistakes, now adding-in Gemfile that I created when I ran a `bundle` command locally, as described in/at https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/
#source "https://rubygems.org"
#gemspec

# Having said that! Why shouldn't I have the Gemfile stuff that https://github.com/mmistakes/mm-github-pages-starter/blob/master/Gemfile has?!

gem "tzinfo-data"
#gem "wdm", "~> 0.1.0" if Gem.win_platform? #<- Pretty sure the Github Pages environment is Linux, so commenting out this.

group :jekyll_plugins do
  gem "jekyll-paginate"
  gem "jekyll-sitemap"
  gem "jekyll-gist"
  gem "jekyll-feed"
  gem "jemoji"
  #gem "jekyll-include-cache" # <- Unnecess repetition, but is non-fatal. Notwithstanding, have commented out for that reason.
  #gem "jekyll-algolia" # <- Commented-out because I don't want to use algolia, and it's not on Github Pages' whitelist. Plus, maybe an error since it's not in plugins settings of https://github.com/mmistakes/mm-github-pages-starter/blob/master/_config.yml
end
