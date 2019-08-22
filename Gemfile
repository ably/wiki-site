source "https://rubygems.org"

ruby File.read(File.expand_path("../.ruby-version", __FILE__)).strip

gem "jekyll", "~> 3.7.3"

gem "nokogiri", ">= 1.10.4"

# This is the default theme for new Jekyll sites. You may change this to anything you like.
gem "minima", "~> 2.0"

#This tests for broken links/images
gem "html-proofer"

# Needed for static site building in Heroku
gem "rake", "~> 12.3"

gem "sinatra", "~> 2.0.2"
gem "thin", "~> 1.7"

gem "omniauth-auth0", "~> 2.0"
gem "dotenv", "~> 2.2"

gem "redcarpet", "~> 3.4"

# If you have any plugins, put them here!
group :jekyll_plugins do
  # none
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.0" if Gem.win_platform?

