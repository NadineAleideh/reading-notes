# Readings Class 01: Exception Handling

1. Name one major benefit of being able to trace the call stack?

   - One major benefit of being able to trace the call stack during debugging, is that it helps in understanding the sequence of function calls in their program and how the program flow reaches a particular point in the code and identify which functions or methods were called leading up to an error or unexpected behavior.

2. If you could use try/catch in your day to day life, name an exception you’d like to ‘catch’ and handle?

   - If I could use try/catch in my day-to-day life, I'd like to use it when I book a flight for vacation , there's a possibility that the airline might cancel or reschedule the flight at the last minute or I be late. To handle this situation, I can use try/catch exception handling and do some altrnative solutions.

3. From an efficiency standpoint, are there downsides to try/catch blocks?

   - From an efficiency standpoint, downsides of try/catch blocks include potential performance impact due to overhead and disruption of control flow. Debugging can also be more complex, and excessive use can harm code readability.

4. Describe how you explain the .Net approach to exception handling to a non technical friend.

   - I'd like to say imagine you're cooking a recipe. While following the steps, you accidentally add too much sugar instead of salt. Now, you have a problem because your cake won't taste good. In software development, similar unexpected problems can occur, called exceptions. And just like a chef would taste the recipe better and decide whether to fix it or start over, in the .NET framework developers use a special mechanism called exception handling to deal with these unexpected issues in their code. It's like having a backup plan in case something goes wrong while the program is running.

5. Case Studies Therac-25 and Ariane 5: Name glaring mistakes that were made during the production of these systems.

   - Therac-25: The Therac-25 was a medical radiation therapy machine that caused several accidents in the 1980s. The following glaring mistakes were made during its production: Software Design Flaw, Lack of Adequate Safety Interlocks, Insufficient Testing.

   - Ariane 5: The Ariane 5 is a European space launch vehicle that encountered a catastrophic failure during its inaugural flight in 1996. The following glaring mistakes were made during its production: Incompatible Software, Lack of Error Handling, Insufficient Testing and Verification.
