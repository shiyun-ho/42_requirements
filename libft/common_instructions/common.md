# Common Instructions

- Must follow norms and norminette.
- Functions should not quit unexpectedly apart from undefined behaviours.  
- Handle any potential segmentation fault, bus error, double free, etc.
- All heap allocated memory must be properly freed. 
- No leaks. 
- Submit Makefile:
	- Compiled your source files with the flags -Wall -Wextra -Werror and cc 	- Must not relink 
	- Contins rules $(NAME), all, clean, fclean and re
	- Bonus: 
		a) Include a rule `bonus` to your Makefile
		b) Bonus adds all various headers, lib, functions that are forbidden on the main part of the project
		c) Must be in diff file _bonus.{c/h} if subj does not specify
	- Mandatory and bonus part eval is done separately
- Test programs are encouraged 

