## Installation

1. Add this extension to your Gemfile with this line:
  ```ruby
  gem 'spree_quotes_management', github: 'rubyonrailsdeveloper/spree_quotes_management'
  ```

  #### Spree < 3.2

  ```ruby
  gem 'spree_quotes_management', github: 'vinsol-spree-contrib/spree-quotes-management', branch: 'X-X-stable'
  ```

  The `branch` option is important: it must match the version of Spree you're using.
  For example, use `3-0-stable` if you're using Spree `3-0-stable` or any `3.0.x` version.


2. Bundle your dependencies and run the installation generator:

  ```shell
    bundle
    bundle exec rails g spree_quotes_management:install
  ```
