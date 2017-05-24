# RailsAdminMagicNav
The Magic Nav generator, replaces Rails Admin's default navigation with a navigation that can be customized by the developer.

## Usage

### Disable Magic Nav

Set `magicNav.active = false` in `app/assets/javascripts/rails_admin/custom/ui.js`
 
## Installation
Add this line to your application's Gemfile:

```ruby
gem 'rails_admin_magic_nav', :git => 'https://github.com/hardhat/rails-admin-magic-nav.git'
```

And then execute:
```bash
$ bundle
```

Run the generator command:
```ruby
rails g rails_admin_magic_nav
````

Add the following to your routes file:
```ruby
get 'magic_nav' => 'rails_admin/magic_nav#index'
``


## Contributing
Contribution directions go here.

## License
The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
