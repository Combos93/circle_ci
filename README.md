# Circle CI example

## This config include:

### Two endpoints
#### Building of container with ruby and database (and bundling of whole project)

* ruby & rails
* postgres
* RSpec

#### Linters and Securities features (standrd-rb, fasterer etc..)

* Scan for Rails code vulnerabilities by Bundler-audit
* Analyze Ruby code quality by Rubycritic
* Scan for Rails code vulnerabilities by Fasterer
* Scan for Rails code vulnerabilities by Brakeman
* Scan for Ruby and RubyGems system vulnerabilities
* Standardrb linter

Each part includes save cache and restore cache.