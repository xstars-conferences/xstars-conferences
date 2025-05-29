brew install ruby
export PATH="/usr/local/opt/ruby/bin:$PATH"
gem install jekyll bundler
gem install jekyll-sitemap jekyll-seo-tag
bundle install#?

bundle exec /usr/local/lib/ruby/gems/3.4.0/bin/jekyll serve -w

convert $f -resize 200x200 -gravity center -crop 200x200+0+0 ${f%.jpeg}_thumb.jpeg

