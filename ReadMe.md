## Simple site: Easy websites with GitHub pages

### Setup on Ubuntu Linux to test

sudo apt-get install ruby-bundler
sudo gem install github-pages

jekyll build
jekyll serve --watch (This allows incremental auto-build)
View on http://localhost:4000 

In case of build issues, use gem uninstall on duplicate installations of gems.

---

This website has been derived from the design provided by [Karl Broman](http://github.com/kbroman)
