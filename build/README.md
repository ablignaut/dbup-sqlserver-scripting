
# Setup

- cd `/build`
- Run 'nuget SetApiKey' to add NuGet API Key to NuGet config
- Install Ruby
- Install Bundler: `gem install bundler`
- Run `bundle install`

# Build

- cd `/build`
- Run `rake build`

# Release to NuGet

- cd `/build`
- Prepend new line to `version.txt` with new version number and release notes
- Run `rake release`
