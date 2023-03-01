task :environment do
  require_relative './config/environment'
end

task :hello do
  puts "hello from Rake!"
end
desc 'outputs hello to the terminal'
task :hello do
  puts "hello from Rake!"
end
namespace :greeting do
  desc 'outputs hello to the terminal'
    task :hello do
      puts "hello from Rake!"
    end
  
    desc 'outputs hola to the terminal'
    task :hola do
      puts "hola de Rake!"
    end


  desc 'drop into the Pry console'
task console: :environment do
  Pry.start
  end
end


