# Load DSL and Setup Up Stages
require 'capistrano/setup'
require 'capistrano/deploy'

# require 'capistrano/rails'
require 'capistrano/bundler'
# require 'capistrano/rails/migrations'
require 'capistrano/rvm'

require "capistrano/scm/git"
install_plugin Capistrano::SCM::Git

require 'capistrano/puma'
install_plugin Capistrano::Puma

# Loads custom tasks from `lib/capistrano/tasks' if you have any defined.
Dir.glob('lib/capistrano/tasks/*.rake').each { |r| import r }