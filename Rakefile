desc 'outputs hello to the terminal'
task :hello do
  puts "hello from Rake!"
end

desc 'outputs hola to the terminal'
task :hola do
  put 'hola de Rake!'
end

namespace :greeting do
  desc "outputs hello to the terminal"
  task :hello do
    puts "hello from Rake!"
  end

  desc "outputs hola to the terminal"
  task :hola do
    puts "hola de Rake!"
  end
end

=begin
  - In the terminal
      $ rake greeting:hello
      $ rake greeting:hola

  - If there's an error add 'bundle exec' **
      $ bundle exec rake greeting:hello
    
=end