# A Basis for Playing with Bootstrap and SCSS

To use this, I suggest something like:

```
# If you don't already have Bundler installed:
gem install bundle
git clone https://github.com/dsedivec/bootstrap-sass-playground playground
cd playground
bundle install --path=vendor/bundle
# If you're using rbenv:
rbenv rehash
compass init -r bootstrap-sass --using bootstrap
```

Then run `guard` and hit http://localhost:3000.

Use [the instructions for customizing Bootstrap][customize] if you want to control what parts of Bootstrap will be included.

[customize]: https://github.com/twbs/bootstrap-sass#sass
