source 'https://rubygems.org'

gem 'dotenv-rails', require: 'dotenv/rails-now'
gem 'rails', '~> 4.2.6'
gem 'pg', '~> 0.18.4'
gem 'rails_config', '~> 0.4.2'
gem 'devise', '~> 3.4.1'
gem 'devise-i18n', '~> 0.9.0'
gem 'paperclip', '~> 4.3.0'
gem 'kangal', '~> 1.2.3'
gem 'annotate', '~> 2.6.0'
gem 'recipient_interceptor', '~> 0.1.2' #deneme amaclı sahte email alısverişleri için
gem 'rails-i18n', '~> 4.0.4'
gem 'ransack', '~> 1.6.6'    #aramalarda kullanınır
gem 'polyamorous', '~> 1.2.0'

# Deployment gems
gem 'capistrano', '~> 3.4.0'
group :development do
  gem 'capistrano-rails',   '~> 1.1', require: false
  gem 'capistrano-bundler', '~> 1.1', require: false
  gem 'sshkit-sudo', require: false
  gem 'capistrano-maintenance', '~> 1.0', require: false
  gem 'recipes_matic', '~> 1.3.0'
end

gem 'exception_notification', '~> 4.1.1' 
gem 'responders', '~> 2.1.0'     #simple notifier in app

gem 'will_paginate', '~> 3.0.4'
gem 'will_paginate-bootstrap', '~> 0.2.3'
gem 'will-paginate-i18n', '~> 0.1.13'
gem 'rails_best_practices', '~> 1.15.1' 
gem 'simple_form', '~> 3.2.0'     
gem 'client_side_validations', '~> 4.2', '>= 4.2.1'       
gem 'client_side_validations-simple_form', '~> 3.2', '>= 3.2.1' 
gem 'show_for', '~> 0.4.0'    # veri goaterirknen kullanlır ..arastır
gem 'uglifier', '~> 2.7.1'    # verşlne js kodlrını anlasılkmack sekilde yazar ve küçültür
gem 'coffee-rails', '~> 4.1.0'
gem 'jquery-rails', '~> 4.0.4'
gem 'turbolinks', '~> 2.5.3'  
gem 'haml', '~> 4.0.2'       
gem 'haml-rails', '0.9.0'
gem 'breadcrumbs_on_rails', '~> 2.3.1' 
gem 'blankable', '~> 0.2.0'      # veriye uygun yontemle gostermye yarar.
gem 'hierapolis-rails', '~> 1.1.3' 
gem 'sass-rails', '~> 5.0.3'     # sass
gem 'compass-rails', '~> 2.0.5'  
gem 'bootstrap-sass', '~> 3.3.4'  #bottstrap ta değişiklşkler yapmak için
gem 'enum_help', '~> 0.0.14'      #arama helper
gem 'chosen-rails', '1.4.1'        
gem 'bootstrap-chosen-rails', '0.0.4'
gem 'model_to_locale'            
gem 'link_to_active_state'      #css classları ile değişiklikler
gem 'jbuilder', '~> 2.4'

group :doc do  
  gem 'sdoc', require: false
end

group :development, :test do #sadece dev ve test ortamlarında kullanılır
  gem 'better_errors'  
  gem 'letter_opener'
  gem 'rspec-rails'
  gem 'binding_of_caller'
  gem 'katip'
  gem 'capybara'
  gem 'bullet'
  gem 'sinatra', require: nil
  gem 'quiet_assets'
end

# For heroku
group :production, :staging do
  gem 'rails_12factor'
end

# Notifications
gem 'rollbar', '~> 2.12'   # hata loglama ve listeleme için

# App server
# gem 'unicorn', '~> 4.9.0'
gem 'puma', '~> 3.4.0'    #http request 

# Backgorund jobs
# Sidekiq
gem 'sidekiq', '~> 4.1'         
gem 'devise-async', '~> 0.10.1'     #devise arklplan işlemleri için(sifre unumta mesajı)
gem 'sidekiq-cron', '~> 0.4.2'      

# Comand line execution
gem 'cocaine', '~> 0.5.8'           

# AWS
gem 'aws-sdk', '~> 1.6'       #amazon webservis için

# Phony Rails
gem 'phony_rails', '~> 0.12.11'  # telefovn farkıl formatlardan validasyon

# Excell export
gem 'to_xls', '~> 1.5', '>= 1.5.3'   #excell cıktı almak

# Keep user activities
gem 'audited-activerecord', '~> 4.2' #kullanıcıların sistem uzerndeki aktivetelerini kaydeder..

# GSM service
# gem 'bulutfon_sdk', '~> 1.1', '>= 1.1.3'        #telefonlara bildirim gondermek için kullanılr.