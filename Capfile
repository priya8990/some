# Load DSL and Setup Up Stages
require 'capistrano/setup'
require 'capistrano/deploy'

require 'capistrano/rails'
require 'capistrano/bundler'
require 'capistrano/rvm'
require 'capistrano/puma'

# If you are using rbenv add these lines:
require 'capistrano/rbenv'
 set :rbenv_type, :user # or :system, depends on your rbenv setup
 set :rbenv_ruby, '2.2.1-p85'


# Loads custom tasks from `lib/capistrano/tasks' if you have any defined.
Dir.glob('lib/capistrano/tasks/*.rake').each { |r| import r }

