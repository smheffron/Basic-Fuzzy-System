Part1 (Implementation):

Understanding the code:
	1.) FuzzyLogic.ipynb is where all the generalized code for fuzzy operations,
	cylindrical closure for combining antecedents, implication operators, fuzzy
	implications, compositional rule of inference, defuzzification, real valued
	operations (chopping consequents, get min firing strength, etc), aggregations, and
	trapezoidal membership function creators is located.
	
	2.) TestFuzzyLogic.ipynb is where I have run my code against a few of the examples
	in the book for a sanity check, it provides a few example inputs/outputs for
	certain operations on/using fuzzy sets.


How to run the code:
	1.) Ensure that all ipynb files are in the same directory. TestFuzzyLogic.ipynb
	requires usage from FuzzyLogic.ipynb. Upload these files to Jupyter for usage.
	
	2.) To run the tests on the generalized implementation, open TestFuzzyLogic.ipynb 	in Jupyter
	
	3.) Click on Cell->run all


Understanding the output:
	1.) The code will output examples 7.1, 7.2, and 7.3 from the textbook using the	
	generalized system in FuzzyLogic.ipynb