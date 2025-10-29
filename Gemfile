source "https://rubygems.org"

ruby "3.3.5"

# Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
gem "rails", "~> 7.1.5", ">= 7.1.5.2"

# The original asset pipeline for Rails [https://github.com/rails/sprockets-rails]
gem "sprockets-rails"

# Use postgresql as the database for Active Record
gem "pg", "~> 1.1"

# Use the Puma web server [https://github.com/puma/puma]
gem "puma", ">= 5.0"

# Use JavaScript with ESM import maps [https://github.com/rails/importmap-rails]
gem "importmap-rails"

# Hotwire's SPA-like page accelerator [https://turbo.hotwired.dev]
gem "turbo-rails"

# Hotwire's modest JavaScript framework [https://stimulus.hotwired.dev]
gem "stimulus-rails"

# Build JSON APIs with ease [https://github.com/rails/jbuilder]
gem "jbuilder"

# Use Redis adapter to run Action Cable in production
# gem "redis", ">= 4.0.1"

# Use Kredis to get higher-level data types in Redis [https://github.com/rails/kredis]
# gem "kredis"

# Use Active Model has_secure_password [https://guides.rubyonrails.org/active_model_basics.html#securepassword]
# gem "bcrypt", "~> 3.1.7"

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: %i[ windows jruby ]

# Reduces boot times through caching; required in config/boot.rb
gem "bootsnap", require: false

# Use Active Storage variants [https://guides.rubyonrails.org/active_storage_overview.html#transforming-images]
# gem "image_processing", "~> 1.2"

group :development, :test do
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem "debug", platforms: %i[ mri windows ]
end

group :development do
  # Use console on exceptions pages [https://github.com/rails/web-console]
  gem "web-console"

  # Add speed badges [https://github.com/MiniProfiler/rack-mini-profiler]
  # gem "rack-mini-profiler"

  # Speed up commands on slow machines / big apps [https://github.com/rails/spring]
  # gem "spring"
end

group :test do
  # Use system testing [https://guides.rubyonrails.org/testing.html#system-testing]
  gem "capybara"
  gem "selenium-webdriver"
end

#Gema para estilos css
gem 'tailwindcss-rails', '~> 4.4'

#gema simple form
gem 'simple_form', '~> 5.4'

#gema simple form tailwind
gem 'simple_form-tailwind', '~> 0.2.0'

# Autenticación / Acceso
gem "devise"
gem "devise-jwt"
gem "omniauth"                  # base OAuth
gem "omniauth-steam"            # ejemplo de integración social PC (inicio de sesión)
# Para PSN/Xbox/Nintendo, se implementa con omniauth-oauth2 personalizado:
gem "omniauth-oauth2"

# IA / LLM / RAG / Embeddings
gem 'ruby_llm', '~> 1.8', '>= 1.8.2'
gem "ruby-openai"

# Búsqueda y vectores
gem 'pgvector', '~> 0.3.2'
gem "pg_search"

# Notificaciones y tiempo real
gem "noticed"
# (Rails ya trae ActionCable. Para escalar: anycable-rails)

# Jobs / Scheduler
gem "sidekiq"
gem "sidekiq-cron"
gem "sidekiq-unique-jobs"

# Integraciones / scraping / APIs
gem "httparty"
gem "faraday"
gem "nokogiri"
gem "money-rails"
gem "countries"

# Observabilidad / calidad
gem "lograge"
gem "oj"
gem "dotenv-rails", groups: [:development, :test]
gem "rspec-rails", groups: [:development, :test]
gem "factory_bot_rails", groups: [:development, :test]
gem "faker", groups: [:development, :test]
gem "rack-attack"
gem "brakeman", group: :development
gem "bundler-audit", group: :development

# i18n
gem "rails-i18n"
