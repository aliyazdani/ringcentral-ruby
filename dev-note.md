## Update all dependencies

```
bundle update
```


## Test

```
bundle exec rspec
```


## Deploy

Update version number in `ringcentral-sdk.gemspec`.

```
gem build ringcentral-sdk.gemspec
gem push ringcentral-sdk-<version>.gem
```
