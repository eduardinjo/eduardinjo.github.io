# Preview the blog locally
## Install prerequisites
On Linux Ubuntu
```
sudo apt-get install ruby ruby-dev make gcc
sudo gem install jekyll bundler
```

## Build and serve the blog
```
cd /path/to/eduardinjo.github.io
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000 in a browser.

## Preview drafts
```
bundle exec jekyll serve --drafts
```

# Push changes to github
```
cd /path/to/eduardinjo.github.io
git add --all
git commit -m "Blog_changes"
git push -u origin master
```
