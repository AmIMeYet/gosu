Build for `ruby 2.2.1p85` on linux:
```bash
bundle install
rm Gemfile.lock
export GOSU_RELEASE_VERSION=0.7.45
export LANG=en_US.UTF-8
rake linux:gem
gem install pkg/gosu-0.7.45.gem --no-doc
# Maybe:
# gem install gosu --platform=ruby
```
Then, for a bundler project:
```bash
# bundle install --local
```
