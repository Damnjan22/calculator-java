LOC - 235 (ukupno za sva tri fajla)

EvaluateExpression - cyclomatic complexity: 12;

Calculate - cyclomatic complexity: 12;

Calculator.java - cognitive complexity: 29.


Statička analiza:

	- calculator.java:

		- Ln 4 - The public type Calculator must be defined in its own file
		- Ln 4 - Add a private constructor to hide the implicit public one.	
		- Ln 18 - Rename method "ToString" to prevent any misunderstanding/clash with method "toString" defined in superclass "java.lang.Object".
		- Ln 1 - Move this file to a named package.
		- Ln 18 - Rename this method name to match the regular expression '^[a-z][a-zA-Z0-9]*$'.
		- Ln 24 - Rename this method name to match the regular expression '^[a-z][a-zA-Z0-9]*$'.
		- Ln 70 - Immediately return this expression instead of assigning it to the temporary variable "textResult".
		- Ln 74 - Rename this method name to match the regular expression '^[a-z][a-zA-Z0-9]*$'.
		- Ln 183 - Remove this redundant jump.

	-Start.java:

		- Ln 8 - Replace this use of System.out or System.err by a logger.
		- Ln 19 - Replace this use of System.out or System.err by a logger.
		- Ln 1 - Move this file to a named package.
		- Ln 6 - Rename this local variable to match the regular expression '^[a-z][a-zA-Z0-9]*$'.

	-LICENSE:

		- Ln 3 - "dresevic": Unknown word.
