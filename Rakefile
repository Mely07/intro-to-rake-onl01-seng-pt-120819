<<<<<<< HEAD
namespace :greeting do 
  desc 'outputs hello to the terminal'
  task :hello do
    puts "hello from Rake!"
  end

  desc 'outputs hola to the terminal'
  task :hola do
    puts "hola de Rake!"
  end
=======
# desc 'outputs hello to the terminal'
# task :greeting do
#   puts "hello from Rake!"
# end

namespace :db do
  desc 'outputs hello to the terminal'
task :greeting do
  puts "hello from Rake!"
>>>>>>> b1ab880d00323f349bcd876e0cb5f3cb0c3ec784
end

  task :environment do
    require_relative './config/environment'
  end 

  desc 'migrate changes to your database'
  task :migrate => :environment do
    Student.create_table
  end
  
  desc 'seed the database with some dummy data'
  task :seed do
    require_relative './db/seeds.rb'
  end
end

desc 'drop into the Pry console'
task :console => :environment do
  Pry.start
end