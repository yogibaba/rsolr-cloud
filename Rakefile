require 'bundler/gem_tasks'

begin
  require 'rspec/core/rake_task'
  RSpec::Core::RakeTask.new(:spec)
  require 'rubocop/rake_task'
  RuboCop::RakeTask.new
  task default: [:rubocop, :spec]
rescue LoadError # rubocop:disable HandleExceptions
end
