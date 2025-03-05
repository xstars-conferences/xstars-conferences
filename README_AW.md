brew install ruby
export PATH="/usr/local/opt/ruby/bin:$PATH"
gem install jekyll bundler
gem install jekyll-sitemap jekyll-seo-tag
bundle exec /usr/local/lib/ruby/gems/3.4.0/bin/jekyll serve -w
