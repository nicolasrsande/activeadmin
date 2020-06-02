source "https://rubygems.org"

group :development, :test do
  gem 'rake'
  gem 'pry' # Easily debug from your console with `binding.pry`
  gem 'pry-byebug', platform: :mri # Step-by-step debugging

  gem 'arbre', github: 'activeadmin/arbre', ref: 'b546d7a10b95001cb7bd1273bbaa55172de77e98'

  gem 'cancancan'
  gem 'pundit'
  gem 'jruby-openssl', '~> 0.10.1', platform: :jruby

  gem 'draper', '~> 4.0'
  gem "devise", github: "heartcombo/devise", ref: "a451b98cf2311b6bb73b3762083294db131a4603"

  gem "rails", "~> 6.0.0"
  gem "activerecord-jdbcsqlite3-adapter", "~> 60.0", platform: :jruby

  gem "sprockets-rails", github: "rails/sprockets-rails", ref: "c269f5e01fdffa5c41350e855183d94ff33d318a"
  gem "sprockets", github: "rails/sprockets", ref: "2d6b1a8bde0cf870c14a2d193fa9a9be09ef99fc"

  gem "formtastic", github: "deivid-rodriguez/formtastic", ref: "0109c66329da7fb7bf7cdc23c6d59dceefeb13ee"
end

group :test do
  gem 'apparition'
  gem 'capybara', '~> 3.14'
  gem 'db-query-matchers', '0.10.0'

  gem 'simplecov', '0.17.1', require: false # Test coverage generator. Go to /coverage/ after running tests
  gem 'cucumber-rails', '~> 2.0', github: 'cucumber/cucumber-rails', ref: '050b01f852d07f8c5bd88541cb2a67e59290ad25', require: false
  gem 'cucumber'
  gem 'database_cleaner'
  gem 'jasmine'
  gem 'jasmine-core', '2.99.2' # last release with Ruby 2.2 support.
  gem 'launchy'
  gem 'parallel_tests', '~> 2.26'
  gem 'rails-i18n' # Provides default i18n for many languages
  gem 'rspec-rails'
  gem 'rspec', github: 'rspec/rspec', ref: '3e6c0fb9c9ec68eddd409cfe7b3eb077b390b302'
  gem 'rspec-core', github: 'rspec/rspec-core', ref: '119282ec3dde5295b337322fc53301c32d0bf7ec'
  gem 'rspec-mocks', github: 'rspec/rspec-mocks', ref: '1728885f65b25a9676c5ce54133ef8a1283e2e0d'
  gem 'rspec-support', github: 'rspec/rspec-support', ref: '6553911974ee93855008f8ff41c26cea6652d74d'
  gem 'rspec-expectations', github: 'rspec/rspec-expectations', ref: 'eb1787f0e1a5ec2c2650048ee60a45d4c9738d78'
  gem "sqlite3", "~> 1.4", platform: :mri
end

group :release do
  gem 'chandler', '0.9.0' # Github releases from changelog
end

group :lint do
  # Code style
  gem 'rubocop', '0.85.1'
  gem 'rubocop-rspec', '~> 1.30'
  gem 'rubocop-rails', '~> 2.3'
  gem 'mdl', '0.6.0'

  # Translations
  gem 'i18n-tasks'
  gem 'i18n-spec'
end

group :docs do
  gem 'yard' # Documentation generator
  gem 'kramdown' # Markdown implementation (for yard)
end

gemspec path: "."
