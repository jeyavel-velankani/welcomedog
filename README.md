# welcomedog

this gem will tell you the Good Morning ,Good evening, Good afternoon, good night message if you pass the hour value

# example: 

require 'welcomedog'

md = Welcomedog::Greeting.new

puts md.process(Time.now.hour)
