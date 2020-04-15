# Usage

See [action.yml](action.yml)

Basic:
```yaml
steps:
- uses: actions/checkout@v2
- uses: actions/setup-ruby@v1
  with:
    ruby-version: '2.6' # Version range or exact version of a Ruby version to use, using semvers version range syntax.
- run: ruby hello.rb
```
