## Exercise 1 - ForEach, Map Exercises (~20 mins):

After a bitter turf war with Hostess, your dearest friend Betty Crocker came out victorious and quickly took over her rival's pastry factory.  As with any hostile pastry takeover, there are some kinks.  Use the data below to help address Betty's grievances. 


```
var yeOldeCakeShoppe = {
	name: 'Hostess',
	product: 'baked goods',
	established: 1930,
	pastries: [
		'ding dongs',
		'vanilla zingers',
		'blueberry muffin minis',
		'twinkies',
		'ring dings'
	]
}

var bettyCakes = [
	'strawberry',
	'banana',
	'sparkle berry',
	'chocolate',
	'confetti',
	'angel cake',
	'vanilla'
]

var yourPayments = [
	220,
	350,
	300,
	280,
	500
]


```

1. Betty needs to tell the local kids that hostess products are no longer around.  Create a function using forEach that console logs "<pastry name> are no longer being produced" for each Hostess pastry.

2. Betty is making exciting cakes.  Really really EXCITING CAKES.  For her labels, she wants a new array called 'excitingBettyCakes' that are all the original flavors but in all caps and with an exclamation mark at the end.  (i.e. "STRAWBERRY!"

3. Betty is impressed.  She wants to double your pay. Create a new array called "payRaise" that doubles all the payments from the "yourPayments" array.  Do this using a function that doubles a payment that is called within the map function.

4. Bonus exploration: Alright now we're ready to elevate Betty Crocker to the next level.  She wants to create a new neopolitan cake.  Using map, create a new array that contains only the ingredients for neopolitan icecream.  You should have __some__ success here but will definitely have some problems too.  What problems did you encounter and why?
