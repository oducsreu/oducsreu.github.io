source "https://rubygems.org"

gem "github-pages", "~> 225", group: :jekyll_plugins

group :jekyll_plugins do
end

install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 2.0.4"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?
gem "kramdown-parser-gfm"