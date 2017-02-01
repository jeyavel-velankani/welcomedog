# welcomedog

this gem will tell you the Good Morning ,Good evening, Good afternoon, good night message if you pass the hour value

# steps to follow to add this gem in your code

## add the gem in the gemfile
gem 'welcomedog', git: 'git@github.com:jeyavel-velankani/welcomedog.git'


## add the below code in the your application or ruby file and run application

require 'welcomedog'

md = Welcomedog::Greeting.new

puts md.process(Time.now.hour)
