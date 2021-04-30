ENV["SINATRA_ENV"] ||= "development"

require_relative './config/environment'

namespace :testing do
  desc "Trigger pry startup"
  task :console do
    Pry.start
  end
end