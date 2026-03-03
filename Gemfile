source "https://rubygems.org"

# 强制指定兼容 Ruby 2.7 的旧版本
gem "github-pages", "228", group: :jekyll_plugins

# 解决之前遇到的 ffi 不兼容问题
gem "ffi", "~> 1.15.5"

gem "wdm", "~> 0.1.0" if Gem.win_platform?

group :jekyll_plugins do
  gem "jekyll-feed"
  gem 'jekyll-sitemap'
  gem 'hawkins'
end