# Suitable test data
- **No data:** You should always check the special case of no data being entered - this isn't strictly invalid or erroneous data, but it certainly isn't what you want the user to do.
- **Erroneous/invalid data:** Data should be rejected by the program
- **Normal/Typical/Valid data:** Data that should be accepted by the program without causing errors.
- **Boundary/extreme/edge data:** Data of the correct type that is on either edge of the accepted validation limits.

# Trace tables and dry runs
- A vital skill for understanding program flow and testing accuracy of an algorithm for logic is called tracing execution.
- It involves examining a printed extract of program code running through the program.
- Take each line at a time and write out the current state of each variable in a trace table, noting any output the program produces.
- Each variable in the program should have its own column in the table.
- A new row should be added if the state of a variable changes.
- Trace tables are an excellent way to track down logic errors in a program. 

# The importance of user feedback
- Gaining user feedback at regular points throughout software development is essential
- A user should not simply be someone who you consult and then never speak to again until the product is complete.
- Regular feedback with the user:
	- Keeps a project focused.
	- Makes sure you develop the actual system they need.
	- Provides opportunities for discussion.
	- Makes the user feel part of the finished solution.