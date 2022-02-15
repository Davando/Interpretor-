Name: David Wang
Partner: None
Date: 10/15/21


USE GUIDE:
    1) The input would be written in calculator language.
        A test input can be in the form:
            let program = "write 3*(2+1)";;
    2) Program Execution (in the OCaml interpretor):
        - For AST:
            ast_ize_prog (parse ecg_parse_table program);;
        - For interpretation
            interpret (ast_ize_prog (parse ecg_parse_table program)) "";;
    3) Error handling:
        - Handles divide_by_zero errors
      	- Non-numeric input
	    - Use of inintialized variables
	    - Unexpected end of input
       
