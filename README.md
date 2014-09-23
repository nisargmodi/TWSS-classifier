# What?!

A Naive Bayes model built for That's What She Said classification.

	require 'rubygems'
	require 'twss-classifier'		
	
	if TWSSClassifier.is_twss?("that was longer than i expected")
		puts "That's what she said!"
	end
	
	if TWSSClassifier.is_twss?("oh, this is good", 0.9) # Use a lower threshold of 0.9.
		puts "That's what she said!"
	end	
	
Read more about the algorithm [here](http://www.quora.com/Natural-Language-Processing/How-would-you-programmatically-parse-a-sentence-and-decide-whether-to-answer-thats-what-she-said), and see a demo [here](http://twss-classifier.heroku.com/).
