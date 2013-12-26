Initial command: 
  rails new babytime  --database=postgresql --skip-test-unit  (1) pq database, 2) rspec instead of test unit testing )

Shoulda, add rspec-rails and shoulda-matchers to the project's Gemfile
  group :test do
  gem 'rspec-rails'
  gem 'shoulda-matchers'
  end  

Initialize Rspec
  rails generate rspec:install  (creates the spec folder)  