# Takes in input from the user and outputs a madlib story
# Bad style example
# susan evans
# Last edited 11/25/2016

print "Welcome to my MadLib program. Please enter in some information below.\n\n"
print "Pick a name?"
name = gets.chomp
print "Add an adjective"
adj= gets.chomp
print "Pick an noun"
noun = gets.chomp
print "Add an adjective"
adj_2 = gets.chomp
print " Pick a food (plural)"
food_p = gets.chomp
print "Pick a noun (plural)"
noun_2 = gets.chomp
print "Pick a verb ending in -ed"
verb = gets.chomp
print "Pick a noun"
noun_3 = gets.chomp
print "HERE'S YOUR MADLIB......."
puts "Come on over to #{name}’s Pizza Parlor where you can enjoy your favorite #{adj}-dish pizza`s."
puts "You can try our famous #{noun}-lovers pizza,\nor select from our list of #{adj_2} toppings, including delicious 
#{food_p}, #{noun_2}, and many more. Our crusts are hand #{verb} and basted in #{noun_3} to make them seem more hand-made."
